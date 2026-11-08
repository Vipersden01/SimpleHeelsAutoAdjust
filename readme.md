Use this fork until racial height and custom draw scale are merged upstream.

The copies of Simple Heels on Sea of Stars and https://repo.caraxian.com do not include this option yet. In the plugin installer, add this custom repository:

```
https://raw.githubusercontent.com/Vipersden01/SimpleHeelsAutoAdjust/master/repo.json
```

Open `/xlplugins`, go to Settings, and add that URL under Custom Plugin Repositories. This build uses the same plugin name as Simple Heels and is a newer version, so install or update it from this repository and do not keep the official copy enabled beside it.

The normal install is `0.11.1.14`. Testing build `0.11.1.16` adds **Scale with character size**. Turn on **Get plugin testing builds** in `/xlsettings` under Experimental, then enable testing for Simple Heels in the plugin installer.

## Character scaling

**Scale offsets with racial height** is a checkbox in the plugin options.

On `0.11.1.14`, heel entries, emote offsets, and model `heels_offset` attributes are multiplied by the character's racial model height and by the draw object's custom scale. Racial height is the value Penumbra racial scaling and Special Snowflakes change. Custom scale is the draw scale Special Snowflakes reports as current custom scale.

The synced value stays the saved offset. Other players receive that number rather than the scaled result. Temporary offsets are left alone. With the option off, offsets behave as they do in upstream Simple Heels.

## Testing: character size

**Scale with character size** matches heel offsets to height and custom scale. **Made at size** is the size those offsets were made for. **Use current size** fills it from the body on screen.

Other players receive the height correction. Custom scale applies only on a client that can see it. Temporary offsets are left alone.
