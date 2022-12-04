# `axyriah/dwm`

Concise patch collection for [suckless' dwm].

[suckless' dwm]: https://dwm.suckless.org/

-   Window "swallowing" - Child processes are drawn over the parent process to free up screen
    space
-   Auto start - Alternative shell script-based auto start support
-   Gaps - Support for outer window gaps
-   XRDB - X.org xrdb/xresources color support
-   Fake Fullscreen - Fullscreen windows only take the space given to them unless forced with `Super+F`

The main target platform for this fork is FreeBSD. You may need to tweak `config.mk` to
make it work on other operating systems.
