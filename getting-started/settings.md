# Settings panel

Click **Settings** in the top bar (admins only). Every change is saved immediately to `data/settings.json` and applies to every player.

<figure><img src="https://raw.githubusercontent.com/Boy4K/bk-director-docs/main/assets/settings.jpg" alt="Server settings"><figcaption><p>Server settings</p></figcaption></figure>

## Access and security

| Setting | What it does |
| --- | --- |
| **Command** | name of the command that opens the editor (restart needed) |
| **Default key** | key that opens the editor, empty = none (restart needed) |
| **Private scene** | each player edits in their own routing bucket, nobody sees them |
| **Traffic and peds in the private scene** | turn ambient traffic back on in the private scene |
| **Return the player on close** | puts the player back where they opened the editor |
| **Block when dead or cuffed** | the editor won't open |
| **Open cooldown** | seconds between two openings |
| **Max camera distance** | how far the camera can fly from the player (0 = no limit) |

## Limits

| Setting | Default |
| --- | --- |
| Max project duration | 180 s |
| Max take duration | 120 s |
| Samples per second | 20 |
| Takes per project | 12 |
| Actors per project | 20 |
| Texts per project | 20 |
| Saved projects per player | 15 |

## Vehicles

**Allow vehicle spawning** lets players spawn a vehicle for their takes. **Blacklisted vehicles** blocks models such as `rhino` or `hydra`.

## Language and photos

| Setting | What it does |
| --- | --- |
| **Language** | English or Italiano, for the panel and the in-game messages |
| **Discord webhook for photos** | photos taken in photo mode are also sent here. Type `off` to remove it |

{% hint style="info" %}
The webhook stays on the server. Players never receive it.
{% endhint %}

## Admin

**Admin ACE permission** (default `bk_director.admin`) and **Admin groups** for ESX and QBCore decide who sees this panel.
