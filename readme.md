# Quake Package Utility

I wrote and used this utility constantly in the past to build `.pak` files for Half-Life to make the games and mods run faster on a spinning hard drive, keep the assets safe and less cluttered. It is of little use nowadays but here for reference.

## Usage
```
QPAK e [pak] [file1[file2[...]]]
     l [list] [pak] [file1[file2[...]]]
     p [list] [pak]
     v [pak] [file1[file2[...]]]
```

### Commands:
* `e[xtract]`       Extract the specified `[file]`('s) from `[pak]`.
* `l[ist]`          Write a list to `[list]` containing filenames in `[pak]`.
* `p[ack]`          Read the specified `[list]` and pack files into `[pak]`.
* `v[iew]`          View files in `[pak]` matching specified `[file]`('s).

### Optional:
* `[list]`          If not specified the default of `qpak.txt` is used.
* `[pak]`           If not specified the default of `qpak.pak` is used.
* `[file]`          If not specified the default of `[*.*]` (all) is used.
* `* and ?`         Minimal REGEX is supported for the `[file]` parameter.
