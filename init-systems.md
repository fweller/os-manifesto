Init Systems

init is the first process that is executed once the Kernel loads

There is a religious war of people who hate systemd and the inventor of it, and prefer either OpenRC or [SysVinit over systemd](https://nosystemd.org/)

- [systemd](https://en.wikipedia.org/wiki/Systemd) - THE ONLY ONE I WILL USE
    - A modern SysV-style init and rc replacement for Linux systems
    - 2010 first release
    - 2019 fully adopted by most distributions
    - Development was lead by Red Hat and was the idea of Lennart Poettering
    - Solves many issues with the original SysVinit
    - [documentation](https://www.freedesktop.org/wiki/Software/systemd/)
    - good article: [The Biggest Myths](http://0pointer.de/blog/projects/the-biggest-myths.html?utm_source=pocket_reader)
    - I am a big fan of systemd and I never want to return to sysVinit
- [SysVinit](https://en.wikipedia.org/wiki/Init#SYSV) ([init](https://en.wikipedia.org/wiki/Init) as per AT&T UNIX System V)
    - Is a collection of System V-style init programs
    - 1983 first release
- [OpenRC](https://en.wikipedia.org/wiki/OpenRC)
    - a dependency-based init system that is compatible with SysVinit
    - Gentoo and BSD usage mostly
    - 2015 first release
- [runit](http://smarden.org/runit/)
    - runit is a daemontools-inspired process supervision suite
- BSD init ([init](https://en.wikipedia.org/wiki/Init) as per BSD / Research UNIX)
    - Predates SysVinit
    - 1982 first release
- upstart
    - Abandoned by Canonical in 2014 in lieu of systemd
