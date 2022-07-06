## Overview

This repository does not contain any code since it would be impractical to store an entire Linux operating system on GitHub, but will be a demonstration video to show progress I have made, along with documentation. This repository is being used to document my progress.


**Linux From Scratch** is a manual started by Gerard Beekmans that guides you through the creation of your own Linux os. The main reason I decided to make a **LFS** system was to understand Linux better. Linux is used across the entire software industry for its stability and versatility.

<!-- [My progress in LFS](PROGRESS.md) -->
> My LFS system is not currently finished.

[Software Demonstration](https://youtu.be/hTKsMmkf8HI)

### Development Environment
For this project, I used:
- Linux From Scratch version 11.1
- Kali-Linux 2022.2
- Oracle VM VirtualBox 6.1.34

**Kali-Linux**: This distribution of Linux is primarily used for penetration testing and security. LFS is built within a Linux os to access the tools needed. The manual specifies that most modern versions of Linux will work, so Kali was a personal preference.

**VirtualBox**: this allows you to run any os in a virtual environment that is isolated from your computer. Although you are able to build LFS on your computer, virtual environments have some advantages:
- You do not have to change over to Linux if you use Windows or Mac
- Some mistakes or errors that can occur while building LFS that can break the host Linux environment, and using a virtual environment protects you since it is separate from the host.

**Links to resources:**
* [Linux From Scratch](http://linuxfromscratch.org)
* [Oracle VM VirtualBox](https://www.virtualbox.org)
* [Kali Linux](https://www.kali.org/)

#### Tips
Linux From Scratch assumes the user is already familiar with basic functions in Linux, so certain questions are not answered in the book.
If you follow the book and get to a part where you don't know what they are asking you to do, it helps to change it into a question.

**The task:**
> Using the `tar` program, extract the package to be built.

**What you lookup:**

> "How to extract a package using `tar` in terminal"

I won't include a specific website because there are many problems you can run into if it's your first LFS system. Troubleshooting here is more about asking good questions and carefully reading the book.
### Future Work
I don't intend to maintain my LFS system since this is more of a learning experience. However, I may build on it:
* **Beyond Linux From Scratch** guides you through customizing and extending what you make in LFS.
* After **BLFS**, I want to look into building a smaller system that I can use in a VR headset instead of a traditional mobile os like Android.