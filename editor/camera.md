# Camera keyframes

It works like the Rockstar Editor: **place a keyframe, move the camera, the keyframe takes that shot.** Between two keyframes the camera moves on its own.

<figure><img src="https://raw.githubusercontent.com/Boy4K/bk-director-docs/main/assets/timeline.jpg" alt="Camera keyframes (cyan) and speed points (yellow) on the timeline"><figcaption><p>Camera keyframes (cyan) and speed points (yellow) on the timeline</p></figcaption></figure>

## Add and edit

| Action | How |
| --- | --- |
| Fly the camera | right click, then right or left click to stop |
| Add a keyframe | **K** or the **Keyframe (K)** button |
| Change a keyframe's shot | click it on the timeline (the playhead jumps to it) and fly: the keyframe follows |
| Move a keyframe | drag it on the timeline |
| Go to a keyframe's shot | **Go here** |
| Copy the current shot | **Use current shot** |

If the playhead is already on a keyframe, **K** places the new one a bit later (2 seconds by default, see [Scene](scene.md)).

## Keyframe settings

<figure><img src="https://raw.githubusercontent.com/Boy4K/bk-director-docs/main/assets/keyframe.jpg" alt="A camera keyframe"><figcaption><p>A camera keyframe</p></figcaption></figure>

| Setting | What it does |
| --- | --- |
| **Time** | when the keyframe is |
| **How it gets here** | the easing from the previous keyframe (below) |
| **Zoom** | 50 is normal, lower is closer, higher is wide angle (20–100) |
| **Roll** | tilts the camera |

### Easing

| Easing | Use it for |
| --- | --- |
| **Smooth continuous** (recommended) | one fluid move through every keyframe, no bounce |
| **Slow down and stop here** | the camera stops on this keyframe |
| **Linear** | constant speed |
| **Ease in / Ease out** | starts slow / ends slow |
| **Hard cut** | jumps straight to this shot, like a cut in editing |

## Shot type

A keyframe can work on its own or with a subject (a take).

| Type | What the camera does |
| --- | --- |
| **Free** | stays where you put it |
| **Fixed, looking at subject** | stays put and turns to follow the subject |
| **Follows the subject** | rides attached to the subject and looks where it looks (hood, wheel, interior view) |
| **Car rig** | rides attached to the subject and always looks at it |

With a subject selected you get **quick shots**: Behind, Front, Drone, Left side, Right side, Low, Hood, Wheel. One click and the keyframe is placed on the car.

## Depth of field and shake

**Enable blur** turns on depth of field: focus distance, blur range and strength. On a subject shot you can let it focus on the subject automatically.

**Camera shake** adds a handheld, road vibration, jolt, explosion, drunk or skydiving shake, with its own strength.
