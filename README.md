# msys-pkgs
This repository contains custom buildscripts for building various dependencies for Principia with unnecessary components disabled, in order to reduce the final size.

To build, run this command in the respective directory:

```bash
MINGW_ARCH="mingw64 ucrt64" makepkg-mingw -Csf --noconfirm
```

To rebuild the repo in its entirety, do:

```bash
for d in */ ; do pushd $d; MINGW_ARCH="mingw64 ucrt64" makepkg-mingw -Csf --noconfirm; popd; done
