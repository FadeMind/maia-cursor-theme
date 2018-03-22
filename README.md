# Maia Cursor Theme for Manjaro Linux KDE Plasma Desktop

<p align="center">
  <img src="https://i.imgur.com/rvxrqXT.png" alt="maia-cursor-theme"/>
</p>

# DEPENDENCIES

- `bash` <br/>
- `cmake` <br/>
- `inkscape` <br/>
- `libcanberra` <br/>
- `xorg-xcursorgen` <br/>

# BUILD AND INSTALL PACKAGE

**Install dependencies**<br/>

> `sudo pacman -S --needed --noconfirm cmake inkscape libcanberra xorg-xcursorgen gtk-engine-murrine`<br/>

**Download PKGBUILD**<br/>

> `mkdir -p maia-cursor-theme;cd maia-cursor-theme;wget "https://pastebin.com/raw/9p5JwGsS" -O PKGBUILD`<br/>

**Build and install package**<br/>

> `mkdir -p /tmp/makepkg; BUILDDIR=/tmp/makepkg makepkg -srci`<br/>
