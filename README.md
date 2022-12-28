# `aaxyi/dwm`

Concise patch collection for [suckless' dwm].

[suckless' dwm]: https://dwm.suckless.org/

> **Warning**! Since the window swallowing patch is broken on FreeBSD, consider applying it manually
> or sticking to [sw] instead

-   autostart - Alternative shell script-based auto start support
-   fullgaps - Support for outer window gaps
-   xrdb - X.org xrdb/xresources color support
-   fakefullscreen - Fullscreen windows only take the space given to them unless forced with `Super+M+B`
-   underlinetags - Underline active tags
-   nomonocleborders - No borders on monocle layout
-   alwayscenter - Floating windows are going to be centered by default

The main target platform for this fork is FreeBSD. You may need to tweak `config.mk` to
make it work on other operating systems.

[sw]: https://code.axyria.dev/sw
