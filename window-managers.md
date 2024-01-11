Window Managers

A window manager is system software that controls the placement and appearance of windows within a windowing system in a graphical user interface.

- [What kinds of window managers are there?](https://askubuntu.com/questions/65083/what-kinds-of-desktop-environments-and-shells-are-available)
- [Comparison of tiling window managers](https://wiki.archlinux.org/title/Comparison_of_tiling_window_managers)

There are 3 types of window managers

- Compositing - standard
- Stacking - for low-end hardware
- Tiling - for people who demand fast window tiling on multiple monitors

Window Managers

- [Compositing](https://en.wikipedia.org/wiki/Compositing_window_manager) (Standard) - are stacking window managers that provide applications with an off-screen buffer for each window.  
    - [KWin](https://en.wikipedia.org/wiki/KWin) - used by KDE Plasma 5
    - [Mutter](https://en.wikipedia.org/wiki/Mutter_%28software%29) - used by Gnome 3, replaced Metacity
    - Xfwm
    - Enlightenment
    - [Compbiz](https://en.wikipedia.org/wiki/Compiz) - Not popular anymore?
    - Metacity
    - Muffin
    - Quartz - MacOS
    - Desktop Window Manager - Windows
    - SurfaceFlinger - Android
- [Stacking](https://en.wikipedia.org/wiki/Stacking_window_manager) AKA Floating - draws and allows windows to overlap, without using a compositing algorithm
    - [OpenBox](https://en.wikipedia.org/wiki/Openbox) (standard WM in LXDE and LXQt)
    - FluxBox
    - AfterStep
    - Motif
    - [IceWM](https://ice-wm.org/) - lightweight, customizable, text file configurable
- [Tiling](https://en.wikipedia.org/wiki/Tiling_window_manager) ([compared](https://wiki.archlinux.org/title/Comparison_of_tiling_window_managers), [compared](https://simpletools.info/doku.php/wm:tiling:comparison)) - "tile" the windows so that none are overlapping.
        - They usually make very extensive use of key-bindings and have less (or no) reliance on the mouse.
        - Tiling window managers may be manual, offer predefined layouts, or both.
    - Manual
        - [i3 improved tiling WM](https://i3wm.org/) - X11 only
            - can be installed preconfigured on ubuntu with [Regolith](https://regolith-desktop.com/)
            - [i3 userguide](https://i3wm.org/docs/userguide.html#:~:text=Floating%2C-Floating%2520mode%2520is&text=You%2520can%2520toggle%2520floating%2520mode%2Ccan%2520move%2520the%2520window%2520around.), configured with text file only
            - Most recommended for first time users to manual tiling WMs
            - tree data structure
        - [Sway](https://swaywm.org/) - i3 on Wayland
            - tiling wayland compositor
            - drop-in replacement for i3wm
            - Sway allows you to arrange your application windows logically, rather than spatially.
        - [i3-gaps](https://github.com/Airblader/i3)
            - fork of i3 with gaps and some other features
        - [herbstluftwm manual tiling WM](https://herbstluftwm.org/) - X11
            - [github](https://github.com/herbstluftwm/herbstluftwm), [tutorial](https://herbstluftwm.org/tutorial.html), configured with text file
        - [Ratpoison](https://www.nongnu.org/ratpoison/)
            - configured with text
    - [Dynamic](https://en.wikipedia.org/wiki/Dynamic_window_manager) - [info](https://wiki.archlinux.org/title/Window_manager) - can dynamically switch between tiling or floating window layout
        - [awesome](https://awesomewm.org/)
            - supports both tiling and stacking
            - dwm derivative
            - scripted in Lua 
        - [dwm](https://dwm.suckless.org/) (dynamic window manager)
            - tiled, monocle, and floating layouts
            - no Lua thankfully
            - customized by editing source code thus keeping userbase small and elitist
        - [qtile](http://www.qtile.org/) - X11 & Wayland
            - written and scripted in python - cool ([default config file](http://docs.qtile.org/en/stable/manual/config/default.html))
            - works with Wayland Display Server
        - [SpectrmWM](https://github.com/conformal/spectrwm) - X11
            - based on xmonad and dwm.
            - configured with text
        - [xmonad](https://xmonad.org/) - X11
            - haskel language
            - Forked by leftwm and spectrwm 
        - [wmii](https://github.com/0intro/wmii) - X11
        - [Hyprland](https://hyprland.org/) - Wayland
            - New and gaining in popularity
            - Written in C++ and based on the wlroots library
    - Hybrid
        - [bspwm](https://github.com/baskerville/bspwm) - X11
            - represents windows as the leaves of a full binary tree.
            - Most recommended for experienced users