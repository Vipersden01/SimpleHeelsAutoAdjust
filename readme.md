Use this fork until racial height and custom draw scale are merged upstream.

The copies of Simple Heels on Sea of Stars and https://repo.caraxian.com do not include this option yet. In the plugin installer, add this custom repository:

```
https://raw.githubusercontent.com/Vipersden01/SimpleHeelsAutoAdjust/master/repo.json
```

Open `/xlplugins`, go to Settings, and add that URL under Custom Plugin Repositories. This build uses the same plugin name as Simple Heels and is a newer version, so install or update it from this repository and do not keep the official copy enabled beside it.

## Character size

**Scale with character size** is a checkbox in the plugin options. It matches heel offsets to height and custom scale. **Made at size** is the size those offsets were made for. **Use current size** fills it from the body on screen.

Other players receive the height correction. Custom scale applies only on a client that can see it. Temporary offsets are left alone. With the option off, offsets behave as they do in upstream Simple Heels.
