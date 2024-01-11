
[Desktop Environments](https://en.wikipedia.org/wiki/Comparison_of_X_Window_System_desktop_environments)

Info

- A desktop environment is a collection of software designed to give functionality and a certain look and feel to an operating system.
- Linux GUI software can usually run perfect fine on any of these desktop environments.
- The most popular desktop environments can be categorized by the amount of overhead required to run them: heavy, medium, and light-weight

An abridged list of only the most popular DE's

- The heavy-weight:  All of these look beautiful
    - Gnome 3
        - Beautiful but offers minimal customization
        - Is usually the default DE for big distros
        - A good choice for beginners
    - KDE Plasma 5
        - Beautiful and highly configurable (the most configurable)
        - A good choice for power users
    - Cinnamon
        - A good choice for those who just want something that works
- The light-weight: Just enough graphics to look good 
    - Xfce
        - Works the same for over 25 years
        - Very popular with experienced users, and with long-time users

The most popular desktop environments

- [Gnome](https://www.gnome.org/) [3](https://en.wikipedia.org/wiki/GNOME#GNOME_3) (GNU Network Object Model Environment)
    - #1 The most popular DE due to being the default DE for many of the most popular Linux distros and not because it's actually the best
    - Good examples: Fedora, Ubuntu, RHEL
    - 2011 initial release.  GTK+ Toolkit
    - Gnome is the flagship desktop environment for most of the big distributions because
        - Gnome is released on a six-month cadence, everything is released at the same time.
            - Ubuntu and Fedora six-month releases are tied to the Gnome releases
        - Gnome LTS is supported for a very long time.
        - Gnome offers such minimal user customization that it is difficult for the end-user to break
        - Gnome looks attractive and modern
    - Some people really hate gnome ([article](https://medium.com/%40fulalas/gnome-linux-a-complete-disaster-feb27b13a5c2), [reddit](https://www.reddit.com/r/linuxmasterrace/comments/pxstui/why_is_gnome_hated/), [article](https://www.theregister.com/2011/08/05/linus_slams_gnome_three/))
    - Linus Torvalds quotes about Gnome
        - “This ‘users are idiots, and are confused by functionality’ mentality of Gnome is a disease. If you think your users are idiots, only idiots will use it. I don’t use Gnome, because in striving to be simple, it has long since reached the point where it simply doesn’t do what I need it to do.”
        - I wish the gnome people had understood the real rules inside the kernel. Like “you never break external interfaces” – and “we need to do that to improve things” is not an excuse.
        - Gnome 3 is an unholy mess
    - My thoughts on Gnome
        - I  have used Gnome more than any other DE, it was the only desktop I actually used for over 15 years, but only because it was the default with Ubuntu.  
        - When using large monitors, I have had to rely on third party extensions to make windows tile into specific grids.  After Gnome API changing  broke my preferred extensions I decided to stop using this DE and began distro-hopping and desktop environment testing.
- [KDE](https://kde.org/) [Plasma 5](https://en.wikipedia.org/wiki/KDE_Plasma_5)
    - #2 Most popular worldwide and #1 Most popular in Europe especially Germany
    - 2014 initial release. Qt Toolkit
    - Good examples: OpenSUSE, Manjaro, Siduction, Kubuntu, KDE Neon
    - KDE Plasma is not the flagship desktop environment for most of the big distributions [because](https://www.reddit.com/r/linux/comments/x8m0bt/why_do_none_of_the_major_distros_have_kde_plasma/)
        - KDE Plasma does not have a homogeneous relase cadence and life cycle like Gnome does, there is no harmony across critical parts of the KDE Plasma stack.  
        - KDE Plasma LTS only covers Plasma and not the framework and gears (applications).  
        - KDE ecosystem has more than double the number of components of Gnome
        - Note: KDE Plasma 6 is [proposed to align releases](https://community.kde.org/Schedules/Plasma_6) in a more distro-friendly manner
    - My thoughts on Plasma
        - It takes longer to get comfortable with compared to cinnamon or gnome, but it is amazingly customizable.  
        - This is the best DE for users who want a modern and beautiful desktop and want to customize and tinker with their environment as it is way more customization than Gnome
- [Xfce](https://xfce.org/)
    - #3 Most popular worldwide
    - 1997 initial release.  GTK Toolkit.  Lightweight
    - Xfce was one of the original X11 desktop environments
    - Xfce was originally called XFCE (XForms Common Environment) but no longer uses XForms
    - This is a lightweight DE that is highly customizable
    - This DE more than any other DE adheres to the UNIX mentality of being backwards and forwards compatible
- [Cinnamon](https://en.wikipedia.org/wiki/Cinnamon_%28desktop_environment%29)
    - #4 most popular worldwide
    - 2011 initial release.  Gnome 3 fork by Linux Mint. GTK toolkit.
    - Attempts to be more traditional than Gnome 3
    - I like this a lot, its much more useful and enjoyable than gnome, also more consistent in usability and feel. 

The somewhat popular desktop environments

- [Deepin](https://www.deepin.org/en/) DDE
    - Might be more popular than the above DEs but I wouldn't know because its extremely unpopular in the west
    - Beautiful and heavy, similar to MacOS, uses Qt
    - DDE/LightDM (Uses KWin)
- [LXQt](https://lxqt-project.org/) (Lightweight Qt)
    - For very low end computers
    - Uses the Qt Toolkit instead of GTK
    - Is basically a rewrite of LXDE using QT instead of GTK3 (which the team considers unfavorable)
    - Is replacing LXDE in popularity
- [LXDE](http://www.lxde.org/) (Lightweight X11 Desktop Environment)
    - For very low end computers
    - GTK2 Toolkit
    - Many developers have abandoned LXDE for LXQt
- [Budgie](https://en.wikipedia.org/wiki/Budgie_%28desktop_environment%29) - by SolusOS
    - GTK3
- [Panthea](https://elementary.io/)
    - By Elementary OS
    - Beautiful.  Looks like MacOS.  Best for beginners.
- [Moksha](https://www.bodhilinux.com/moksha-desktop/)
    - by Bodhi Linux
    - Enlightenment 17 continuation
- [COSMIC](https://github.com/pop-os/cosmic) (Computer Operating System Main Interface Components)
    - System76 PopOS adopting this soon
    - Redox uses this by default
    - Written in rust, not based on gnome, using Iced toolkit
- [UKUI](https://www.ukui.org/) - Ultimate Kylin UI for Chinese

Losing popularity

- [MATE](https://mate-desktop.com/) (MATE Advanced Traditional Environment)
    - Gnome 2 continuation
- [Unity](https://en.wikipedia.org/wiki/Unity_%28user_interface%29) 
    - Gnome 2 fork by Canonical (Ubuntu 10-16)
- [Gnome 2](https://en.wikipedia.org/wiki/GNOME#GNOME_2) 
    - Was the most popular desktop for a long time
- [Trinity](https://www.trinitydesktop.org/)
    - KDE fork for low end equipment,  Not popular.
- [Lumina](https://lumina-desktop.org/)
- [Enlightenment](https://www.enlightenment.org/)
    - Project is officially dead
- [Weston](https://wayland.freedesktop.org/) 
    - For embedded desktops running on Wayland
- [FluxBox](http://fluxbox.org/) 
- [CDE](https://en.wikipedia.org/wiki/Common_Desktop_Environment) (Common Desktop Environment)
    - This is probably what I used on Sun workstations in the 90s. 
