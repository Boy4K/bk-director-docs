# FAQ and troubleshooting

<details>
<summary>The camera is very zoomed in</summary>

Press **Z** while flying to go back to zoom 50, or set **Zoom** on the keyframe. Lower values zoom in, higher values are wide angle.
</details>

<details>
<summary>Another script moves my camera</summary>

BK Director takes the camera back on its own. If a HUD or phone shows up during the video, use `exports.bk_director:IsOpen()` to hide it. See [Exports and events](exports.md).
</details>

<details>
<summary>Weather or time stays wrong after closing</summary>

Your weather script must sync again. Listen to `bk_director:restoreWorld`. See [Exports and events](exports.md).
</details>

<details>
<summary>Ped photos don't load</summary>

They come from the FiveM documentation site. Without internet access you see a **?**, but the ped works.
</details>

<details>
<summary>Photo mode doesn't work</summary>

Start `screenshot-basic` before `bk_director`.
</details>

<details>
<summary>The editor doesn't open</summary>

Check the cooldown and whether the player is dead or cuffed (both in the settings). The command name changes only after a restart.
</details>

<details>
<summary>Do I need to restart after changing a setting?</summary>

No, except for the command name and the default key.
</details>
