Filesystems

The following filesystems must run on top of a volume manager such as

- [LVM (Logical Volume Manager)](https://en.wikipedia.org/wiki/Logical_Volume_Manager_%28Linux%29)

Filesystems without integrated volume managers

- [Ext4](https://en.wikipedia.org/wiki/Ext4) - This is the default Linux journaling filesystem.  
    - It has reliability and fault tolerance.
- [XFS](https://en.wikipedia.org/wiki/XFS)  - This is originally form SGI (Silicon Graphics) 
    - It is robust and fast and competes with Ext4.
- [JFS](https://en.wikipedia.org/wiki/JFS_%28file_system%29) - This is originally from IBM.  
    - Not as good as Ext4.
- [F2FS](https://en.wikipedia.org/wiki/F2FS) (Flash-Friendly File System) 

Filesystems with integrated volume managers (do not require LVM) - These are the best modern filesystems

- [ZFS](https://en.wikipedia.org/wiki/ZFS) (Zettabyte file system) 
    - Originally from SunOS
    - Two code bases
        - [Oracle ZFS](https://en.wikipedia.org/wiki/Oracle_ZFS) - proprietary - not free
        - [OpenZFS](https://en.wikipedia.org/wiki/OpenZFS) ([OpenZFS](https://openzfs.org/wiki/Main_Page)) - what everyone else uses, ZoL.  
            - Licencing is CDDL (Common Development and Distribution License)
    - Linus Torvalds [will not merge OpenZFS into the kernel](https://www.realworldtech.com/forum/?curpostid=189841&threadid=189711&utm_source=pocket_reader)
        - because he fears Oracle’s litigious nature coming after the linux community.
        - Because CDDL is incompatible with the GNU General Public License used by Linux
    - The only distros that use OpenZFS are Ubuntu and Mint
        - Ubuntu seems to be hiding this feature recently
- [BtrFS](https://en.wikipedia.org/wiki/Btrfs) (Better File System)
    - Btrfs is not as good as ZFS, but Btrfs is baked into the Linux kernel while ZFS is not.
    - This is the highest quality file system that we can find in most Linux distro installers
    - Synology uses this filesystem for their NAS
- [Bcachefs](https://en.wikipedia.org/wiki/Bcachefs)  - Not ready for prime time yet
- [Stratis](https://stratis-storage.github.io/) [filesystem](https://en.wikipedia.org/wiki/Stratis_%28configuration_daemon%29) - not ready for prime time yet
    - Written in rust for reliability
    - Sponsored by Red Hat

Encryption - all of the above can be run on top of:

- [LUKS](https://en.wikipedia.org/wiki/Linux_Unified_Key_Setup) (Linux Unified Key Setup) - I use this for every install (except for VMs)
