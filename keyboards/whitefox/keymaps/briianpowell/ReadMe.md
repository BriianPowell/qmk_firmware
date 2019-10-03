# WhiteFox Compilation

Compiling for QMK on Manjaro, ARM core being used is too new, need to revert to older version.
Use below for stability and compiling.

```
pacman -U https://archive.archlinux.org/packages/a/arm-none-eabi-gcc/arm-none-eabi-gcc-8.3.0-1-x86_64.pkg.tar.xz 
```

Compile with:

```
make whitefox:briianpowell:dfu-util -l
```
