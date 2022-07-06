### Getting Started

1. [VirtualBox and Linux](#virtualbox-and-linux)
2. [Package Versions](#package-versions)

#### VirtualBox and Linux
Using VirtualBox slowed progress, but it was worth it.
The main problem I encountered was choosing how much RAM and how many CPU cores it would need. I failed to install Linux several times because it would freeze or fail.
**Problems:**
1. I first tried to install Ubuntu, but the current version has a bug when you try to install it without an internet connection.
2. When I installed Kali Linux, it would freeze on the login screen or the desktop.

The second problem took a while to solve. I tried to use what Kali recommended for virtual machines, which got it too boot sometimes. I tried giving it different combinations of RAM and cores as well. I later I found out that it may run slower if you give it an unbalanced amount, so 3 cores with 8GB of RAM sometimes runs slower than 2 cores and 4GB.

In the end it seems like it has more to do with the video controller settings in virtual box than the resources, assuming you have enough resources. I couldn't fix it, but I was able to work around it. I kept trying to boot it until loaded in. Once it is on the desktop it gets faster because the startup takes more resources than just running it. To "shut it down" between sessions I used VirtualBox to save it's state so I wouldn't have to go through the startup process again.

#### Package Versions

