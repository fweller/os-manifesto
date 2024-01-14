# Init Systems

Init is the first process that is executed once the Kernel loads.

- Until the 2010's, Linux was using the BSD-style SysVinit
- There is a religious war of people who hate systemd and the inventor of it, and prefer either OpenRC or [SysVinit over systemd](https://nosystemd.org/)

## List of Inity Systems

- [systemd](https://en.wikipedia.org/wiki/Systemd)
  - A modern SysV-style init and rc replacement for Linux systems
  - Solves many issues with the original SysVinit
  - I am a big fan of systemd and I never want to return to sysVinit
  - History
    - Development was lead by Red Hat and was the idea of Lennart Poettering
    - 2010 first release
    - 2019 fully adopted by most distributions
  - [Documentation](https://www.freedesktop.org/wiki/Software/systemd/)
  - Good article: [The Biggest Myths](http://0pointer.de/blog/projects/the-biggest-myths.html)
- [SysVinit](https://en.wikipedia.org/wiki/Init#SYSV)
  - [init](https://en.wikipedia.org/wiki/Init) as per AT&T UNIX System V
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
- Upstart
  - Abandoned by Canonical in 2014 in lieu of systemd
