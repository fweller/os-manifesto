Kernels

Kernel Types:

- [Monolithic](https://en.wikipedia.org/wiki/Monolithic_kernel)
    - Entire OS runs in kernel space (privileged level)
    - Easier to debug issues than a microkernel
    - Are often faster than a microkernel
- [Hybrid](https://en.wikipedia.org/wiki/Hybrid_kernel)
    - Attempts to combine the best features of monolithic and microkernels
- [Microkernel](https://en.wikipedia.org/wiki/Microkernel)
    - Only the tiny microkernel operates at a privileged level
    - Everything else (drivers, protocol stacks, file systems) run in user space
    - Are often smaller than monolithic kernels
    - May be more inherently secure than monolithic

Loadable modules allow a monolithic kernel to load and unload execuatable modules during runtime, avoiding the need to reboot the system.

Noteworthy kernels listed in chronologic order

- BSD Kernel - 1978 Monolithic
- [Procto](https://www.qnx.com/developers/docs/8.0/com.qnx.doc.neutrino.sys_arch/topic/kernel.html) - 1982 Microkernel
    - QNX RTOS
- [Mach](https://en.wikipedia.org/wiki/Mach_%28kernel%29) - 1985 Microkernel
    - Carnegie Mellon University
    - Used today by Apple, and no one else
- [MINIX](https://en.wikipedia.org/wiki/Minix) - 1987 Microkernel
    - For educational use
- [GNU Hurd](https://en.wikipedia.org/wiki/GNU_Hurd) - 1990 Microkernel
    - Has never been fully operational
- [Linux](https://kernel.org/)  - 1991 Monolithic
    - Used in Linux, ChromeOS, and Android operating systems
- [L4 Microkernel](https://en.wikipedia.org/wiki/L4_microkernel_family) - 1993 Microkernel
    - For the L4 family of operating systems
- [XNU](https://en.wikipedia.org/wiki/XNU) - 1996 Microkernel
    - Apple MacOS (originally from NeXT)
    - Derived from CMU Mach
    - Is a mostly-monolithic executive built on top of the Mach microkernel
- [GNU Mach](https://en.wikipedia.org/wiki/GNU_Mach) - 1997 Microkernel
    - Continuation of CMU Mach
    - 2016 first year it was stable
- [DragonflyBSD Kernel](https://en.wikipedia.org/wiki/DragonFly_BSD) - 2004 Hybrid
    - Less complicated than the GNU Mach kernel
- [Illumos](https://illumos.org/) - 2010 Monolithic
    - Solaris Kernel modernized to be completely FOSS
- [Zircon](https://en.wikipedia.org/wiki/Fuchsia_%28operating_system%29#Kernel) - 2021 Microkernel
    - Google project for Fuchsia OS
- [Maestro](https://github.com/llenotre/maestro) - 2023 Monolithic
    -  Unix-like (Linux-compatible) kernel written in Rust     