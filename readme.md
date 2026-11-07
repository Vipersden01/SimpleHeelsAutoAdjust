Use this fork until racial height and custom draw scale are merged upstream.

The copies of Simple Heels on Sea of Stars and https://repo.caraxian.com do not include this option yet. In the plugin installer, add this custom repository:

```
https://raw.githubusercontent.com/Vipersden01/SimpleHeelsAutoAdjust/master/repo.json
```

Open `/xlplugins`, go to Settings, and add that URL under Custom Plugin Repositories. This build uses the same plugin name as Simple Heels and is a newer version, so install or update it from this repository and do not keep the official copy enabled beside it.

## Character scaling

**Scale offsets with racial height** is a checkbox in the plugin options.

When it is on, heel entries, emote offsets, and model `heels_offset` attributes are multiplied by the character's racial model height and by the draw object's custom scale. Racial height is the value Penumbra racial scaling and Special Snowflakes change. Custom scale is the draw scale Special Snowflakes reports as current custom scale, so feet stay planted when either value changes the body size.

The synced value stays the saved offset. Other players receive that number rather than the scaled result, so someone without the size change does not inherit the extra lift. A client running this build multiplies the saved offset by the scales on the character it is drawing.

Temporary offsets are left alone. With the option off, offsets behave as they do in upstream Simple Heels.
