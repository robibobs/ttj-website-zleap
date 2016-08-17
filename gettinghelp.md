### Getting help

When doing any tasks,  asking for requirng help is inevitable.  While there are a wide range of forums to ask for help there are a few things YOU can do in order to help your self and help the community or person you're asking.


Firstly know your system, by this I mean what OS are you running,  It may not be a simple case of 

* Linux, OSX, Windows

Forums need to know what you are running so in the case of Linux, peraps what distribution you are running, for OSX which version and for windows again what version and release e.g Windows 7 home, starter, professional.

Being able to identify this is really important.

The same goes for the actual software you are having problems, with what version are you running.


Listed below is how to possible determnine what you are running

* GNU / Linux

GNU / Linux has a built in documentation system in the form of man (manual) pages,  these can be accessed with man command for example 
>man ls


Commands such as 

>uname -a
>Linux CoreDuo 3.19.0-32-generic #37~14.04.1-Ubuntu SMP Thu Oct 22 09:41:40 UTC 2015 x86_64 x86_64 x86_64 GNU/Linux

Along with

lsb_release -a

Can help determine specific version being run

>Distributor ID:	LinuxMint
>Description:	Linux Mint 17.3 Rosa
>Release:	17.3
>Codename:	rosa


Once you have determined the OS version on a Linux system, it may help to know what hardware you have

lsusb - list usb
lshw - list hardware
lspci - list pci devices

inxi (on Ubuntu derived distributions)

inxi can access a large amount of information, from network devices to graphics devices

With Linux, to determine the version of a particular package you can usually use a command line switch such as :

>ls --version
>ls (GNU coreutils) 8.21
>Copyright (C) 2013 Free Software Foundation, Inc.
>License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>.
>This is free software: you are free to change and redistribute it.
>There is NO WARRANTY, to the extent permitted by law.



* OSX

* Windows

