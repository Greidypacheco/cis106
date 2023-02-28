---
Name: Greidy Pacheco
Semester: Spring 23
Course: cis106
---

# Week Report 3

## Summary of presentations 

### Introduction to LInux
**What is an operating system?**
An operating system provide the basics tools to be able to use the computer's hardware. A operating system allows to have all the fundamentals software functionalities of a computer. 

**Aside from a kernel, what other parts make an operating system?**
Command-LInes shell,  Graphical users interfaces, utility and productivity programs, libraries. 

**What is a Linux distribution?**
Linux is a Unix-like operating system popular in academic and business environment. In addition, some of its characteristics are that it is a open source software, available free charge, it can be installed on almost any system as it supports almost every processor architecture. 

**What is Ubuntu?**
Ubuntu is  a LInux distribution, free and with community and profession support. It includes pieces of software such as, LibreOffice, Web browser Firefox, Email client and AppStore. 

**Define the following terms: Open Source, Closed source, free software**
Open source: It is a development method for software that harnesses the power of distributed peer review and transparency of process. It means that the software may be distributed for a fee or free. The source code is distributed with the software. 
Closed source: The software is not distributed with the source code. The user is not permitted to modify the code. 
Free software: The software is provided with the code . It can be free of charge or can have a fee. 

**What are the 4 freedoms defined by the free software foundation?**
Freedom 0: Use the software for any purpose. 
Freedom 1: Examine the source for any purpose. 
Freedom 2: Redistribute the software.
Freedom 3: Redistribute your modified software. 


### The basics of Virtualization 
**What is virtualization?**
Virtualization is defined as creating virtual versions of something. It is often used to let multiple OSs run on one physical machine at the same time. 

**List 3 benefits of virtualization**
1- Allow application to be tested before installing them on a host machine. 
2- Offers the ability to save the state of  machine at given time and roll it back or forward. 
3- Allows running multiple OSs on one machine without dual booting. 

**What is a hypervisor?**
Hypervisor/ VIrtual Machine Manager (VMM), is a software  or hardware in charge of creating, managing, and running virtual machines. There are two types of hypervisor:
Type 1, which run directly on the hardware and type 2 which is an application that runs on top of an operating system. 

**What is virtualbox**
VirtualBox is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use. 


### Exploring Desktop Environment 
**What is a desktop environment? (Provide 3 examples)**
A desktop environment (DE) is an implementation of the desktop metaphor made for a bundle of programs running on top of a computer operating system, which shares a common GUI, sometimes described as a graphical shell. Some examples of desktop environment are KDE, GNOME and Cinnamon.

**List 4 common elements of desktop environments**
1- Panels
2- Menus
3- Launcher
4- File Manager

**What is Ubuntu’s default desktop environments?**
GNOME 3 is the defaulted Ubuntu DE. 

**What are the official flavors of Ubuntu?**
Canonical offers an official flavor of Ubuntu with the xfce DE called Xunbuntu. 

### What is a Shell?
**What is Bash?**
Bash shell is a program that provides interactive access to the LInux system. It runs as a regular program and is normally started whenever a user logs in into a terminal. 

**How do you access the Linux CLI?**
A command-line interface is a means of interacting with a computer program where the user issues commands to the program in the form of successive lines of text. To access the CLI can be via terminal emulator or Linux console. 

**What is a console terminal?**
It text the Linux system out of graphical desktop mode and place it in text mode. A virtual console is a terminal session that runs in Linux system memory. 

**What is a terminal emulator?**
A terminal emulator is a program that allows you to access the command line interface. Some of the terminal emulator are Konsole, Terminology and GNOME terminal. 

**Provide 3 examples of Linux commands**
1- Ctrl + R, search the history backwards. 
2- Ctrl + L, clear the screen.
3- Ctrl + Z, suspend/stop the command. 


### Managing Software
**Which command is used for updating ubuntu**
``` sudo apt update; sudo apt upgrade -y```

**Which command is used for installing software. Provide an example.**
```sudo apt install spotify```

**Which command is used for removing software. Provide an example**
```sudo apt remove spotify```

**Which command is used for searching for software. Provide an example.**
```apt search "google chrome"```

**Definition of the following terms:**

    * Package: It archives that contain binaries of software, configuration files and information about dependencies. A box containing all the necessary stuff to install the program you want. 
    * Library: Reusable code that can be used by more than one functions oor program. 
    * Repository: A large collection of software available for download. 

