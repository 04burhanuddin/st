# Burhan Build of ST (simple terminal)
--------------------
st is a simple terminal emulator for X which sucks less. from [suckless.org](https://suckless.org/)


## Requirements

In order to build st you need the Xlib header files.

## Installation

Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

```shell
git clone https://github.com/04burhanuddin/st.git
cd st
sudo make clean install
```

## Patch & Features

- [Alpha](https://st.suckless.org/patches/alpha/) - This patch allows users to change the opacity of the background
- [Anysize](https://st.suckless.org/patches/anysize/) - By default, st's window size always snaps to the nearest multiple of the character size plus a fixed inner border (set with borderpx in config.h)...
- [Blinking Cursor](https://st.suckless.org/patches/blinking_cursor/) - This patch allows the use of a blinking cursor.
- [Boxdraw](https://st.suckless.org/patches/boxdraw/) - Custom rendering of lines/blocks/braille characters for gapless alignment.
- [Colorscheme](https://st.suckless.org/patches/colorschemes/) - This patch adds multiple color schemes and lets you change them without having to restart st.
- [Font2](https://st.suckless.org/patches/font2/) - This patch allows to add spare font besides default....
- [Glphy Wide Support](https://st.suckless.org/patches/glyph_wide_support/) - This patch fixes wide glyphs truncation
- [Scrollback](https://st.suckless.org/patches/scrollback/) - Scroll back through terminal output using Shift+{PageUp, PageDown}.

## Credits

Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

