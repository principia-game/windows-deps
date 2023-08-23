# msys-pkgs
This repository contains custom buildscripts for building various dependencies for Principia with unnecessary components disabled, in order to reduce the final size.

To build, run this command in the respective directory:

```bash
makepkg-mingw --cleanbuild --syncdeps --force --noconfirm
```
