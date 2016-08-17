### Getting help

When doing any tasks, requiring help is inevitable. While there are a wide range of forums to ask for help, there are a few things __you__ can do in order to help, not just yourself, but the community or person you're asking.

Firstly, know your system; what OS are you running?  It may not be a simple case of Linux, OSX or Windows - forums need to know exactly what you are running; for example with Linux, what distribution you are running, and for OSX or Windows what version and release - for example Windows 7 Professional, or OSX Yosemite. Being able to identify this is really important.

The same goes for the actual software you are having problems with; what version are you running?

Listed below are methods to determine what distribution and/or version of  your operating system you are running.

##### Linux

GNU / Linux has a built in documentation system in the form of man (manual) pages. These can be accessed with the `man` command, for example `man ls` 

You can use commands such as `uname -a`

Which, for example, may return

`Linux CoreDuo 3.19.0-32-generic #37~14.04.1-Ubuntu SMP Thu Oct 22 09:41:40 UTC 2015 x86_64 x86_64 x86_64 GNU/Linux`

You can also use `lsb_release -a` which can help determine similar information, but in a more user-friendly form, for example:
```
>Distributor ID:	LinuxMint
>Description:	Linux Mint 17.3 Rosa
>Release:	17.3
>Codename:	rosa
```

Once you have determined the OS version on a Linux system, it may help to know what hardware you have

`lsusb` - list usb
`lshw` - list hardware
`lspci` - list pci devices

On Ubuntu deried distributions, `inxi` can access a large amount of information, including network devices, graphics devices, and more.

To determine the version of a particular package on Linux you can usually use a command line switch such as `--version`, for example:

```
> ls --version
ls (GNU coreutils) 8.21
Copyright (C) 2013 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>.
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.
```

##### OSX


##### Windows

Hold the Windows modifier key and press R to open the Run dialog, and type `winver`. This will open a dialog showing your exact version and build of Windows.
