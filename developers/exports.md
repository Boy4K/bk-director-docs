# Exports and events

## Client export

```lua
-- true while the editor is open
local open = exports.bk_director:IsOpen()
```

Use it to hide your own HUD, phone or notifications while a player is editing.

## Client events

| Event | When |
| --- | --- |
| `bk_director:restoreWorld` | right after the editor resets weather, time and filters on close. Re-apply your weather/time sync here |
| `bk_director:closed` | the editor is fully closed |

```lua
AddEventHandler('bk_director:restoreWorld', function()
    -- ask your weather/time script to sync this player again
end)
```
