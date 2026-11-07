Use this fork until racial height scaling is merged upstream.

The copies of Simple Heels on Sea of Stars and https://repo.caraxian.com do not include this option yet. Install this fork instead:

```
https://github.com/Vipersden01/SimpleHeelsAutoAdjust
```

Disable the official Simple Heels plugin while this build is loaded. Dalamud treats them as the same plugin.

## Racial height scaling

**Scale offsets with racial height** is a checkbox in the plugin options.

When it is on, heel entries, emote offsets, and model `heels_offset` attributes are multiplied by the character's racial model height. That height is the value Penumbra racial scaling and Special Snowflakes change, so feet stay planted when the body gets taller or shorter.

Temporary offsets are left alone. With the option off, offsets behave as they do in upstream Simple Heels.
