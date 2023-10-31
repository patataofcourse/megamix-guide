# Getting started

In order to run Megamix mods you'll need the following:

- Rhythm Heaven Megamix (the US version)[^1]
- A Nintendo 3DS family console (with Luma3DS installed and an SD card)
    - or Citra (a relatively recent version)
- [RHMPatch](https://github.com/rhmodding/RHMPatch/releases/latest)

The rest of the steps depend on what platform you're modding on:
    - [Hardware (Nintendo 3DS console)](#hardware-nintendo-3ds-console)
    - [Citra](#citra)

[^1]: If you're on a non-US 3DS, you still have to use the North American version of Megamix.

## Hardware (Nintendo 3DS console)

1. Make sure Luma3DS is installed: hold SELECT when turning on your console.

```admonish success
If you see a Luma version of **13.0.2**, you can continue without problems!
```

```admonish warning
If you see a Luma version of **11.0** or higher, you can continue, but it's recommended you [update your CFW](https://3ds.hacks.guide/restoring-updating-cfw).
```

```admonish failure
If you see the regular HOME menu, or a Luma version of **10.3 or lower**, see [3ds.hacks.guide](https://3ds.hacks.guide/key-information) to mod your console or update Luma.
```

2. Insert your 3DS' SD card into your computer

3. Create a folder named `rhmm` on the root of your SD card

4. Copy `C00.bin` from the RHMPatch `RHMM_patch.zip` to `rhmm`

```admonish warning
If there's no `C00.bin` here, your game will crash!
```

5. Navigate to `SD:/luma/titles`

```admonish note
If the `luma` or `titles` folders don't exist, create the folder(s) and continue.

```
6. Create a folder named `000400000018A400` in the `titles` folder

```admonish tip title="Preinstalled mods?"
If you already have a `000400000018A400` folder, there's a chance you already have mods set up. It's recommended you clear the contents of the folder (with prior backup if preferred) to avoid conflicts with other mods.

If you're running US Megamix on a non-US console, and you see a `locale.txt` file inside `000400000018A400`, rest assured, you can delete it, since RHMPatch takes care of allowing Megamix to run on your console.
```

7. Copy `code.ips` from `RHMM_patch.zip` into `000400000018A400`

8. Eject the card from your PC and insert it into your 3DS

9. Power on your 3DS while holding SELECT

10. Turn on "Enable patching" in the Luma configuration menu

```admonish success title="All done!"
RHMPatch is set up for you to load mods! You can now continue to [Running mods](./running_mods.md)
```

## Citra

1. Open Citra

2. Right-click on Rhythm Heaven Megamix and then select "Open Mods Location"

```admonish note
Make sure you can see Megamix from the Citra menu. Otherwise, you can add the folder where your Megamix ROM is by double-clicking on "Add new game directory", or installing the CIA into Citra.
```

3. Copy the `code.ips` from the RHMPatch `RHMM_patch.zip` into the folder that was opened

4. On Citra, click on `File > Open Citra Folder` and go to the `sdmc` folder

5. Create a folder named `rhmm`

6. Copy `C00.bin` from `RHMM_patch.zip` into `rhmm`

```admonish warning
If there's no `C00.bin` here, your game will crash!
```

```admonish success title="All done!"
RHMPatch is set up for you to load mods! You can now continue to [Running mods](./running_mods.md)
```