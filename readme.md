Forked version of Simple Heels aimed at those with scaling characters. Tired of having your heels dig into the ground whenever you change your racial height or have a plugin adjust for you? Not anymore!

The copies of Simple Heels on Sea of Stars and https://repo.caraxian.com do not include this option. In the plugin installer, add this custom repository:

```
https://raw.githubusercontent.com/Vipersden01/SimpleHeelsAutoAdjust/master/repo.json
```

Open `/xlplugins`, go to Settings, and add that URL under Custom Plugin Repositories. The installer label is **Auto Adjusting Simple Heels**. It updates the existing Simple Heels install and shares its config, so do not keep the official copy enabled beside it.

## What changes?

**Scale with character size** matches your heel offsets to your height and custom scale, including offsets that come from a mod. **Character Baseline Size** is the size those offsets were made for. **Racial height (Penumbra)** and **Custom scale (Plugin / SizeChange)** can be typed in, or **Apply From Current Scale** can fill them from the body on screen.

Other players receive the height correction. Custom scale is applied only on a client that can see it. Temporary offsets are left alone. With the option off, offsets behave as they do in upstream Simple Heels.
