# hl_c11_a3_anti_troll
This disables the map restart caused by the tripmine explosions. As requested by Blizzard Fox, it also modifies the tripmines so that they don't explode and instead respawn players who touch the beams.

If you want the tripmines to explode normally but still not restart the level, set the cvar in hl_c11_a3.cfg:
```
as_command tmantitroll_respawn_mode 1
```
You can increase this value to override the player respawn delay.

In an effort to preserve the puzzle aspect of the map, the tripmines will respawn after exploding so that it's slightly harder to cheese your way through.

The included .cfg will override (not overwrite) the default one if you place it in svencoop_addon, so just extract the contents there and you're good to go.
