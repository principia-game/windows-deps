# windows-deps
This repository contains custom buildscripts for building various dependencies for the Windows version of Principia with unnecessary components disabled, in order to reduce the final size.

To build, run this command in the respective directory:

```bash
makepkg-mingw -Csf --noconfirm
```
