# Running mods

Once you have RHMPatch set up, loading mods into your game is very easy!

When you download a mod, from, say, GameBanana or Google Drive, you'll usually download it in one of two formats:

- A C00.bin file
- A .zip file containing multiple files and folders

Both of these formats are pretty much the same, except the .zip will include things like custom textures, music, or text.

```admonish note
If you see mod downloads for SpiceRack / Saltwater, those won't work for you. Download RHMPatch / C00 versions of the mods you want to run!
```

To install those mods, simply drag-and-drop the C00.bin (and additional folders if applicable) into the `rhmm` folder in your SD card or Citra folder!

```admonish tip
Most of the time, modders will include tickflow sources or additional region variations. If you want to save space, you can pick and choose what folders you want to copy over. Folders that the game will look for are:

- Commonly present: `cellanim`, `layout`, `message`, `sound`
- Sometimes present: `treasure`, `model`, `effect`
- Rarely present: `common`, `icon`, `__test`

Also include the folders with "US" at the beginning: `UScellanim`, `USmessage`, etc. Exclude any other variations (EU, JP, KR, etc.)
```

```admonish warning
You can't run multiple mods at the same time without some extra work, see [Loading multiple mods at once](./multi_mod.md) for more information.
```