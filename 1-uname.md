# uname

The uname command in Linux is a command-line utility used to display basic system information, including the kernel name, version, and hardware details. 

## options
- -s, --kernel-name: Prints the kernel name (default behavior).
- -n, --nodename: Prints the network node hostname.
- -r, --kernel-release: Prints the kernel release version (e.g., 5.15.0-78-generic).
- -v, --kernel-version: Prints detailed kernel version information, including the build date and compiler used.
- -m, --machine: Prints the machine hardware name (e.g., x86_64).
- -p, --processor: Prints the processor type, or "unknown" if the information is unavailable.
- -i, --hardware-platform: Prints the hardware platform, or "unknown" if the information is unavailable.
- -o, --operating-system: Prints the operating system name (e.g., GNU/Linux).
- -a, --all: Prints all available information in a specific order (omitting -p and -i if unknown). This is a very common option for troubleshooting and system identification.

## example
`uname -a`

Linux mymachine 2.6.18-194.el5PAE #1 SMP Fri Apr 2 15:37:44 EDT 2010 i686 i686 i386 GNU/Linux