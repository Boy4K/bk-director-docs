# Installation

{% stepper %}
{% step %}
### Copy the resource

Put the `bk_director` folder in your `resources` folder.
{% endstep %}

{% step %}
### Start it

In `server.cfg`, after your framework:

```
ensure bk_director
```

ESX, QBCore and QBox are detected on their own. Without a framework it runs standalone.
{% endstep %}

{% step %}
### Give admins access to the settings

Admins see the **Settings** button. Use the ACE permission:

```
add_ace group.admin bk_director.admin allow
```

On ESX and QBCore the groups listed in the settings also count (by default `admin`, `superadmin`, `god`).
{% endstep %}

{% step %}
### Photo mode (optional)

Start `screenshot-basic` before `bk_director` to use photo mode.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
The `data/projects` folder must exist inside the resource. Some zip tools drop empty folders: if it's missing, create it.
{% endhint %}

## Where things are saved

| File | What |
| --- | --- |
| `data/settings.json` | the settings changed from the panel |
| `data/index.json` | the list of saved projects per player |
| `data/projects/<license>_<id>.json` | one project |

All of them are written by the resource. You never need to edit them by hand.
