# Networking-Basics-Zero-to-Hero
In this Respo we are going to learn the basic networking knowlegde required for Technical Support &amp; DevOps Role.
# Network
In simple words it is an Interconnection of two or more devices

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/876ab814-29cd-4080-9094-fc2d2de36c39)

# Networking
The communication between the interconnected devices is called Networking
# Network Architecture

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/8877eee9-6c22-4149-9495-331e834dec72)

# Types of Network

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/b4c7bf4c-0ef5-46f7-8d21-3a626fb4f0ce)

* LAN - Local Area Network
* MAN - Metropolitian Area Network
* CAN - Controller Area Network
* WAN - Wide Area Network
* PAN - Personal Area Network
* SAN - Storage Area Network [Cloud]
# Components Of Network
* Two or More Computers
* Cables as link's between Computers
* A Network Interfacing Card [NIC or CAN or Ethernet(10 MBPS), Fast Ethernet (100 MBPS), Giga Byte Ethernet (1000 MBPS/1 GBPS)] on each computer
* A Network Devices [HUB, Routers, Switches, Firewalls]
* Logical Address - IP Address
* Protocol - TCP/UDP
* Topology - Bus, Mesh, Ring, Star
* Software called Operating System [OS].
# HUB -
It is a centralized device which contains multiple ports used to connect multiple systems to create a group or network. It performs Broad Casting Method which also called as Non- Secured Device or Non- Intelligent Device. It doesn't maintain MAC (Media Access Control).
# Switch -
It is a networking device which contains multiple ports used to connect multiple systems to create a group or network. It performs Multi- Casting [One to Many or Many to Many Communication] for the first time and Uni- Casting method [ 1 to 1 communication it is called as Intelligent Device] from second time onwards. It also maintains MAC list.

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/4534639c-3b52-4e46-be08-47be713e6a93)
![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/c272b770-e8d1-48ca-90d7-d85850a02e45)

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/934c5d81-f655-40bc-b77f-7d1172436129)

# Router -
It is a networking device which is used to communicate between two or more different networks from different geographical areas. It performs only Uni- Casting method. It also maintains MAC list. It is called as Intelligent device. Encryption, Decryption, Segmentation [8 bits] & Encapsulation [Invisible]
# Operating System
It act's as Interface between Hardware and Software application for effective communication. Windows & Linux are the famous OS.
# Types of OS
* Server - Servers are used to maintain Domain Centrally & Securely contains different kinds of services[AD, User Management, Profiles, Home Folder's, Permissions, Group policy Management Console, DFS (Distributed File System), DHCP (Dynamic Host Configuration protocol), DNS (Domain Name System), WDS (Windows Deployment Services), Software Deployment, Hyper -V, Storage Management, RRAS (Routing & Remote Access Service), RAS (Remote Access System), RDS (Remote Desktop System), Backup & Recovery, OU (Organisation Unit), IIS (Internet Information Service) are used in many computers.
* Client - It runs on computer only,it doesn't maintain services.
# Classification Of Network -
* Topology - Topology specifies the geometric arrangement of the network. Common topologies are a Bus, Ring, Tree, Mesh, Hybrid and Star.

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/eb616269-2b63-47fe-b42e-4b4a47e78325)

* Protocol - Protocol specifies a common set of rules and signals the computers on the network use to communicate. Most networks use Ethernet, but some networks may use IBM's Token Ring protocol. We recommend Ethernet for both home and office networking.

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/42fb8ac0-32a9-4da1-82cc-4c363117237f)

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/46727eae-5878-49c1-b968-d1ac878ba0cf)

* Architecture - It is a Logical Topology. Architecture refers to one of the two major types of network architecture:

<img width="522" alt="image" src="https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/c858b688-15af-4904-b346-d5fec7001eac">

  
         * Peer to Peer [WorkGroup Model] - In a Peer-to-Peer networking configuration, there is no server, and computers simply connect with each other in a workgroup.
  
         * Client & Server [Domain Model] - It refers to a system server that hosts, delivers, and manages most of the resources and services that the client requests.

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/37e4df09-2ff6-4e1f-815e-fd9ef5339578)

# IP Address Format and Table

IP address is a short form of "Internet Protocol Address".It is a Logical address assigned by a unique number provided to every device connected to the internet network, such as Android phone, laptop, Mac, etc. It is a Network Layer address [Layer-3]. An IP address is represented in an integer number separated by a dot (.), for example, 192.167.12.46.

# Types of IP Address

An IP address is categorized into two different types based on the number of IP address it contains.

These are:

         * IPv4 (Internet Protocol version 4)
         * IPv6 (Internet Protocol version 6)

# What is IPv4?

IPv4 is version 4 of IP. It is a current version and the most commonly used IP address. It is a 32-bit address written in four numbers separated by a dot (.), i.e., periods. This address is unique for each device. For example, 66.94.29.13

# What is IPv6?

IPv4 produces 4 billion addresses, and the developers think that these addresses are enough, but they were wrong. IPv6 is the next generation of IP addresses. The main difference between IPv4 and IPv6 is the address size of IP addresses. The IPv4 is a 32-bit address, whereas IPv6 is a 128-bit hexadecimal address. IPv6 provides a large address space, and it contains a simple header as compared to IPv4.

# IP Address Assignment

  * Static IP Address - Address that are manually assigned and do not change over time.
  * Dynamic IP Address - Addresses that are automatically assigned for a specific period of time & can change after this period is over.

# IP Address Format

Originally IP addresses were divided into five different categories called classes. These divided IP classes are class A, class B, class C, class D, and class E. Out of these, classes A, B, and C are most important. Each address class defines a different number of bits for its network prefix (network address) and host number (host address). The starting address bits decide from which class an address belongs.

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/ea76d34a-7ae3-4fd4-aa35-32656c3d4fe3)

* Network Address: The network address specifies the unique number which is assigned to your network. In the above figure, the network address takes two bytes of IP address.
* Host Address: A host address is a specific address number assigned to each host machine. With the help of the host address, each machine is identified in your network. The network address will be the same for each host in a network, but they must vary in host address.
Address Format IPv4

The address format of IPv4 is represented into 4-octets (32-bit), which is divided into three different classes, namely class A, class B, and class C.

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/e150812d-cbab-49c4-a6ec-f60912a5d6a8)

The above diagram shows the address format of IPv4. An IPv4 is a 32-bit decimal address. It contains four octets or fields separated by 'dot,' and each field is 8-bit in size. The number that each field contains should be in the range of 0-255.
# Network Classes

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/b72e3e6d-0ad4-4579-9474-9c625a913c65)

# Sub-Netting :

It is basically Splitting Network into smaller Networks which provides Security, Privacy & Isolation.

 *  Private subnet – The subnet does not have a direct route to an internet gateway. Resources in a private subnet require a NAT device to access the public internet.
 *  Public subnet – The subnet has a direct route to an internet gateway. Resources in a public subnet can access the public internet.

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/fe899698-6be2-4731-84d2-5615995a6f76)

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/abd60566-53a0-423c-bfc3-0d0c93ceb380)

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/662b9c6b-a46f-4fa3-803c-5ef4af4aac1a)

From the above Diagram we have elobarated the Classes below : -
# Class A -
Class A address uses only first higher order octet (byte) to identify the network prefix, and remaining three octets (bytes) are used to define the individual host addresses. The class A address ranges between 0.0.0.0 to 127.255.255.255. The first bit of the first octet is always set to 0 (zero), and next 7 bits determine network address, and the remaining 24 bits determine host address. So the first octet ranges from 0 to 127 (00000000 to 01111111).
# Class B -
Class B addresses use the initial two octets (two bytes) to identify the network prefix, and the remaining two octets (two bytes) define host addresses. The class B addresses are range between 128.0.0.0 to 191.255.255.255. The first two bits of the first higher octet is always set to 10 (one and zero bit), and next 14 bits determines the network address and remaining 16 bits determines the host address. So the first octet ranges from 128 to 191 (10000000 to 10111111).
# Class C -
Class C addresses use the first three octets (three bytes) to identify the network prefix, and the remaining last octet (one byte) defines the host address. The class C address ranges between 192.0.0.0 to 223.255.255.255. The first three bit of the first octet is always set to 110, and next 21 bits specify network address and remaining 8 bits specify the host address. Its first octet ranges from 192 to 223 (11000000 to 11011111).
# Class D -
Class D IP address is reserved for multicast addresses. Its first four bits of the first octet are always set to 1110, and the remaining bits determine the host address in any IP address. The first higher octet bits are always set to 1110, and the remaining bits specify the host address. The class D address ranges between 224.0.0.0 to 239.255.255.255. In multicasting, data is not assigned to any particular host machine, so it is not require to find the host address from the IP address, and also, there is no subnet mask present in class D.
# Class E -
Class E IP address is reserved for experimental purposes and future use. It does not contain any subnet mask in it. The first higher octet bits are always set to 1111, and next remaining bits specify the host address. Class E address ranges between 240.0.0.0 to 255.255.255.255.

# Differences between the protocols TCP vs UDP: 

Here are the main differences between TCP and UDP:

![TCP   UDP](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/540de19c-a7fe-41f6-abc7-26324e9044ed)

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/b9a6ec76-322c-4e53-b659-fdb5346048d4)

# Which protocol is better: TCP or UDP?

It depends on what you’re doing online and the type of data being transferred. UDP is better if you’re gaming online, because its speedy data transfer allows for mostly lag-free gaming. TCP is better if you’re transferring files, like family photos, because it ensures the data arrives exactly as it was sent.
Overall, TCP and UDP are both useful protocols, so to think in terms of TCP vs UDP is a bit misleading. But depending on the type of data transfer, TCP or UDP might be better for the job. Here are some examples:

         * TCP is best for:
                  * Email or texting
                  * File transfers
                  * Web browsing

         * UDP is best for:
                  * Live streaming
                  * Online gaming
                  * Video chat

# Here’s a detailed breakdown of the advantages and disadvantages of TCP and UDP:

# Advantages of TCP

Transmission control protocol (TCP) is the protocol to choose for maximum reliability and quality. It may not be the fastest, but it gets the job done right. Here are a few advantages of the TCP protocol:

* It sets up and maintains a connection between sender and receiver.
* It operates independently of the operating system.
* It supports many routing protocols.
* It checks for errors, guaranteeing data arrives at its destination unaltered.
* It confirms data arrival after delivery, or attempts to retransfer.
* It’s able to send data in a particular sequence.
* It optimizes the pace of data transmission based on the receiver.

# Disadvantages of TCP protocol:

TCP isn’t suited for some types of data transfers, especially ones that require faster speeds. These are the drawbacks of TCP packet transmission:

* It uses more bandwidth and is slower than UDP.
* It’s especially slow at the beginning of a file transfer.
* It can prevent data from loading if some data is lost. For example, it won’t load images on a web page until all of the page data has been delivered.
* It reduces its transfer rate if the network is congested, resulting in even slower speeds.
* It’s not suited for LAN and PAN networks.
* It can’t multicast or broadcast.

# Applications of TCP

Despite its slower speeds, TCP is the only protocol that can retransmit lost data packets. When reliability is critical, TCP is the best option. Applications of TCP When should you enable TCP data transfer? Most data transfers automatically use the best protocol option. But in certain circumstances — such as when using a VPN — you may need to choose a protocol to optimize your browsing experience.

Enable TCP for the following activities:

* Email and text messaging
* Streaming pre-recorded content on sites like Netflix, Hulu, or HBO Max
* Transferring files between apps and devices
* General web browsing
* Remote device or network administration

# Advantages of UDP

UDP delivers data rapidly, and it doesn’t slow down or turn back to recollect lost data. This makes it an ideal protocol for delivering continuous data or broadcasting, such as for live streaming, video calling, and matching servers with IP addresses. Here are some of the advantages of UDP:

* No connection is needed to send or receive data, so apps and operating systems work faster.
* Broadcast and multicast transmission is available, meaning one UDP transmission can send data to multiple recipients.
* It endures packet loss, delivering data even if it's incomplete.
* Smaller packet size and less overhead reduce end-to-end delay.
* Operates over a larger range of network conditions than TCP.
* UDP communication is more efficient.
* It can transmit live and real-time data.

# Disadvantages of UDP

While UDP provides the speed you need to live a comfortable digital life, UDP isn’t as reliable as TCP. This is something to be aware of when setting up a VPN, because most VPNs run on UDP protocols to keep connection speeds high. Here are some disadvantages of using UDP:

* It’s connectionless, which makes data transfer unreliable.
* There’s no system in place to acknowledge a successful data transfer.
* There’s no way to know if data is delivered in its original state, or at all.
* It has no error control, so it drops packets when errors are detected.
* In case of a data collision, routers will often drop UDP packets and favor TCP packets.
* Multiple users accepting UDP data can cause congestion, and there’s no way to mitigate this.
* It cannot sequence data, so data can arrive in any order or out of order.

# Applications of UDP

UDP is best suited for transferring a steady flow of live data. This allows many users to access data easily and quickly, if not in perfect condition. A good example is playing an online game. UDP can keep the action moving in spite of potential errors or data loss. Here are a few applications of UDP in real life.

* Online gaming
* Multicasting
* Video chatting/conferencing
* VoIP (in-app voice calling)
* Domain Name Systems (which translates domain names into IP addresses)

# Four Layers of TCP/IP model

In this TCP/IP tutorial, we will explain different layers and their functionalities in TCP/IP model:

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/27cc025e-a4da-4f9a-932b-109a2ede3471)

# TCP/IP Conceptual Layers

The functionality of the TCP IP model is divided into four layers, and each includes specific protocols.
TCP/IP is a layered server architecture system in which each layer is defined according to a specific function to perform. All these four TCP IP layers work collaboratively to transmit the data from one layer to another.

* Application Layer
* Transport Layer
* Internet Layer
* Network Interface

# MAC ID
A MAC (Media Access Control) address, sometimes referred to as a hardware or physical address, is a unique, 12-character alphanumeric attribute that is used to identify individual electronic devices on a network.

# DHCP
Dynamic Host Configuration Protocol (DHCP) is a client/server protocol that automatically provides an Internet Protocol (IP) host with its IP address and other related configuration information such as the subnet mask and default gateway.

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/a7dbd036-b464-4b06-ad5c-03d1dd3c1dbf)

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/9185672c-0676-42c2-839a-99653c7f108d)

# DNS
A Domain Name System (DNS) turns domain names into IP addresses, which allow browsers to get to websites and other internet resources.

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/7291c7eb-11bc-47f1-a72d-441ad5d80839)

![DNS](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/1af7858a-0c22-40c9-85ac-9ce80ea2397f)

# OSI Model [Open Systems Interconnection]

The Open Systems Interconnection (OSI) model is a conceptual framework that divides network communications functions into seven layers. Sending data over a network is complex because various hardware and software technologies must work cohesively across geographical and political boundaries.

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/50b14cfe-2003-4cd6-898f-44da2c450f3d)

# Virtual Machine

It is a computer file typically called an image, that behaves like an actual computer. Where the physical server is logically isolated through hydervisor is known as Virtual Machine.

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/819d7ab1-43cd-4f6e-a84e-3d9c8927a558)

# Linux 
Linux is one of popular version of UNIX operating System. It is open source as its source code is freely available. It is free to use. Linux was designed considering UNIX compatibility. Its functionality list is quite similar to that of UNIX. It is Secure, Free, Fast & Heavily Customizable.

# Components of Linux System
Linux Operating System has primarily three components

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/262877b5-85f1-4ea0-b92c-128460da826d)

* Kernel − Kernel is the core part of Linux. It is responsible for all major activities of this operating system. It consists of various modules and it interacts directly with the underlying hardware. Kernel provides the required abstraction to hide low level hardware details to system or application programs.

* System Library − System libraries are special functions or programs using which application programs or system utilities accesses Kernel's features. These libraries implement most of the functionalities of the operating system and do not requires kernel module's code access rights.

* System Utility − System Utility programs are responsible to do specialized, individual level tasks.

# Kernel Mode vs User Mode
* Kernel component code executes in a special privileged mode called kernel mode with full access to all resources of the computer. This code represents a single process, executes in single address space and do not require any context switch and hence is very efficient and fast. Kernel runs each processes and provides system services to processes, provides protected access to hardware to processes.

* Support code which is not required to run in kernel mode is in System Library. User programs and other system programs works in User Mode which has no access to system hardware and kernel code. User programs/ utilities use System libraries to access Kernel functions to get system's low level tasks.


# Basic Features
Following are some of the important features of Linux Operating System.

* Portable − Portability means software can works on different types of hardware in same way. Linux kernel and application programs supports their installation on any kind of hardware platform.

* Open Source − Linux source code is freely available and it is community based development project. Multiple teams work in collaboration to enhance the capability of Linux operating system and it is continuously evolving.

* Multi-User − Linux is a multiuser system means multiple users can access system resources like memory/ ram/ application programs at same time.

* Multiprogramming − Linux is a multiprogramming system means multiple applications can run at same time.

* Hierarchical File System − Linux provides a standard file structure in which system files/ user files are arranged.

* Shell − Linux provides a special interpreter program which can be used to execute commands of the operating system. It can be used to do various types of operations, call application programs. etc.

* Security − Linux provides user security using authentication features like password protection/ controlled access to specific files/ encryption of data.

# Architecture

The following illustration shows the architecture of a Linux system −

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/d317bfe1-4716-44dd-8ab7-5ae1aa9c4bf1)


# The architecture of a Linux System consists of the following layers −

* Hardware layer − Hardware consists of all peripheral devices (RAM/ HDD/ CPU etc).

* Kernel − It is the core component of Operating System, interacts directly with hardware, provides low level services to upper layer components.

* Shell − An interface to kernel, hiding complexity of kernel's functions from users. The shell takes commands from the user and executes kernel's functions.

* Utilities − Utility programs that provide the user most of the functionalities of an operating systems.

# Types of Operating System:
* Single User - Single Tasking Operating System - In this type only one user can log into system and can perform only one task at a time Eg: MS-DOS
* Single User - Multitasking Operating System - In this type OS supports only one user to log into the system but a user can perform multiple tasks at a time, browsing internet while playing songs etc. Eg: Windows -98,Xp,vista,7 etc.
* Multi User - Multitasking Operating System - In this type OS provide multiple users to log into system and also each user can perform various tasks at a time. In a broader term multiple users can logged into system and share the resources of the system at the same time Eg: UNIX,LIUNX etc.

# Some important File System Hierarchy

![Root Hierarchy](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/d650a489-7d17-4870-b9ef-55f33f13e68b)

# Diffrent Linux distros

➔ Popular Desktop Linux OS

* Ubuntu Linux
* Linux Mint
* Arch Linux
* Fedora
* Debian
* OpenSuse

➔ Popular Server Linux OS

* Red Hat Enterprise Linux [RHEL]
* Ubuntu Server
* Centos
* SUSE Enterprise Linux

# Most used Linux distros currently in IT industry.

* RPM based:- RHEL & Centos
* Debian based :- Ubuntu Server

# Diffrence between RPM based and Debian based.

From user’s point of view, there isn’t much difference in these tools. The RPM and DEB formats are both just archive files, with some metadata attached to them. They are both equally arcane, have hardcoded install paths and only differ in subtle details. DEB files are installation files for Debian based distributions. RPM files are installation files for Red Hat based distributions. Ubuntu is based on Debian’s package manage based on APT and DPKG. Red Hat, CentOS and Fedora are based on the old Red Hat Linux package management system, RPM.

* DEB or .deb (Debian based softwares)

DEB is the extension of the Debian software package format and the most often used name for such binary packages. DEB was developed by Bedian.

    *  Example: Google chrome software
    *  Package name: google-chrome-stable_current_amd64.deb
    *  Installation: dpkg -i google-chrome-stable_current_amd64.deb

* RPM or .rpm (Red Hat based softwares)

It is a package management system. The name RPM variously refers to the .rpm file format, files in this format, software packaged in such files, and the package manager itself. RPM was intended primarily for Linux distributions; the file format is the baseline package format of the Linux Standard Base. RPM was developed by Community & Red Hat.

    *  Example: Google chrome software
    *  Package Name: google-chrome-stable-57.0.2987.133-1.x86_64.rpm
    *  Installation: rpm -ivh google-chrome-stable-57.0.2987.133-1.x86_64.rpm

# Linux Commands A-Z

![Linux-A-Z](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/4de57985-33c7-4ab4-9a6c-fce698d70eaa)

# We use only some of the following commands while working on Linux
# 1) System Information Commands :-
* arch: used to print the computer architecture (shows the architecture of the machine 1).
* uname -m: command is used to print the machine hardware name (shows the machine 2 architecture).
* uname -a: This Linux command is used to show all the system information in the following order: Kernal name, network node hostname, kernel release date, kernel version, machine hardware name, platform, and OS.
* uname -s: shows the kernel name.
* uname -n: shows the hostname of the network node.
* uname -v: shows the current version of the kernel.
* uname -p: shows the type of processor.
* uname -i: shows the platform of hardware (i.e., x86_64)
* uname -o: shows the name of the operating system.
* uname -r: shows the kernel release date.
* dmidecode -q: shows the components (hardware) of the system.
* hdparm -i /dev/hda: command is used to show a hard disk’s characteristics.
* hdparm -tT /dev/sda: Linux command is used to perform read test on a hard drive.
* cat /proc/cpuinfo: shows CPU information.
* cat /proc/interrupts: shows interrupts.
* cat /proc/meminfo: checks memory usage.
* cat /proc/swaps: shows the total and used swap size.
* cat /proc/version: shows the kernel version.
* cat /proc/net/dev: shows network adapters and statistics.
* cat /proc/mounts: shows mounted filesystem.
* lspci -tv: shows PCI devices.
* lsusb -tv: shows USB devices.
* date: shows the system date.
* cal 2020: shows the almanac for 2020.
* cal 07 2020: shows the almanac for July 2020.
* date 041217002020.00: sets (declare, set) date and time.
* clock -w: saves date changes in BIOS.
# 2) Shutdown (Reboot System or Log Out) Commands :-
* shutdown -h now: shutdowns the system (1).
* init 0: shutdowns system (2).
* telinit 0: shutdowns the system (3).
* halt: shutdowns the system (4).
* shutdown -h hours: minutes &: scheduled system shutdown.
* shutdown -c: cancels a scheduled system shutdown.
* shutdown -r now: restart (1).
* reboot: reboot (2).
* logout: log out.
# 3) Files and Directories Commands :-
* cd /home: enters the “home” directory.
* cd ..: used for going back one level.
* cd ../ ..: used for going back 2 levels.
* cd: used for going to the root directory.
* cd ~ user1: used for going to the user1 directory.
* cd –: used for going (return) to the previous directory.
* pwd: shows the path of the working directory.
* ls: is used to view the files in a directory.
* ls -F: is used to view files in a directory.
* ls -l: shows the details of files and folders in a directory.
* ls -a: shows hidden files.
* ls * [0-9] *: shows files and folders that contain numbers.
* tree: shows files and folders in tree form starting from the root. (1)
* lstree: shows files and folders as a tree starting from the root. (2)
* mkdir dir1: creates a folder or directory named ‘dir1’.
* mkdir dir1 dir2: creates two folders or directories simultaneously (Create two directories at the same time).
* mkdir -p /tmp/dir1/dir2: creates a directory tree.
* rm -f file1: is used to delete the file named ‘file1’.
* rmdir dir1: is used to delete the folder named ‘dir1’.
* rm -rf dir1: is used to delete a folder named ‘dir1’ with its contents recursively. (If I delete it recursively, I am saying that it is with its content).
* rm -rf dir1 dir2: is used to delete two folders (directories) with their content recursively.
* mv dir1 new_dir: is used to rename or move a file or folder (directory).
* cp file1: is used to copy a file.
* cp file1 file2: is used to copy two files in unison.
* cp dir / *.: is used to copy all files from a directory into the current working directory.
* cp -a /tmp/dir1.: is used to copy a directory within the current working directory.
* cp -a dir1: is used to copy a directory.
* cp -a dir1 dir2: is used to copy two directories in unison.
* ln -s file1 lnk1: creates a symbolic link to the file or directory.
* ln file1 lnk1: creates a hard link to the file or directory.
* touch -t 0712250000 file1: is used to modify the real time (creation time) of a file or directory.
* file file1: is used to output (dump on screen) of the mime type of a text file.
* iconv -l: used to show the lists of known ciphers.
* iconv -f fromEncoding -t toEncoding inputFile> outputFile: the given command creates a new form of the input file suppose it is encoded in fromEncoding and converting it to ToEncoding.
* find. -maxdepth 1 -name * .jpg -print -exec convert “{}” -resize 80 × 60 “thumbs / {}” \;: group resized files in the current directory and send them to directories in thumbnail views (requires converting from ImagemagicK).
# 4) Find files Commands :-
* find / -name file1: find file and directory starting from system root.
* find / -user user1: this command is used to find files and directories belonging to user’ user1′.
* find/home/user1 -name\*.bin: find files with extension ‘. bin ‘inside the directory’ / home / user1 ‘.
* find /usr/bin -type f -atime +100: find binary files not used in the last 100 days.
* find /usr/bin -type f -mtime -10: find files created or changed within the last 10 days.
* find / -name \ *. rpm -exec chmod 755 ‘{}’ \;: search for files with ‘.rpm’ extension and modify permissions.
* find / -xdev -name \ *. rpm: Search for files with ‘.rpm’ extension ignoring removable devices like cdrom, pen-drive, etc.
* locate \ *. ps: find files with the ‘.ps’ extension first executed with the ‘updatedb’ command.
* whereis halt: show the location of a binary, help, or source file. In this case, it asks where the ‘halt’ command is.
* which halt: show the full path (the full path) to a binary/executable.
# 5) Mounting a Filesystem Commands :-
* mount /dev/hda2/mnt/hda2: Using this command, you can mount a disk named hda2. Check first the existence of the directory ‘/ mnt / hda2’; if it is not, you must create it.
* umount /dev/hda2: Using this command, you can unmount a disk named hda2. First exit from point ‘/ mnt / hda2.
* fuser -km/mnt/hda2: Using this command, you can force unmount when a a device is busy.
* umount -n /mnt/hda2: Using this command, you can run the unmount without reading the / etc / mtab. However, it is used when the file is read-only, or the hard drive is full.
* mount /dev/fd0/mnt/floppy: You can mount a floppy disk.
* mount /dev/cdrom/mnt/cdrom: run this command and mount a cdrom / dvdrom.
* mount /dev/hdc/mnt/cdrecorder: Using this command, you can easily mount a rewritable cd or dvdrom.
* mount /dev/hdb/mnt/cdrecorder: with the help of this command, you can mount a rewritable cd / dvdrom (a dvd).
* mount -o loop file.iso /mnt/cdrom: If you want to mount an iso file or image, then run the given command.
* mount -t vfat /dev/hda5/mnt/hda5: using this command, you can mount a FAT32 filesystem.
* mount / dev/sda1/mnt/usbdisk: using this command, you can mount a USB pen-drive or a memory (without specifying the type of filesystem).
# 6) Disk Space Commands :-
* df -h: displays a list of mounted partitions.
* ls -lSr | more: shows the size of the files and directories ordered by size.
* du -sh dir1: Using this command, you can easily estimate the space used by the directory ‘dir1’.
* du -sk * | sort -rn: shows the size of the files and directories ordered by size.
* rpm -q -a –qf ‘% 10 {SIZE} t% {NAME} n’ | sort -k1,1n: shows the space used by the installed rpm packages organized by size (Fedora, Redhat and others).
* dpkg-query -W -f = ‘$ {Installed-Size; 10} t $ {Package} n’ | sort -k1,1n: shows the space used by installed packages, organized by size (Ubuntu, Debian and others).
# 7) Users and Groups Commands :-
* groupadd group_name – It is used to create a new group.
* groupdel group_name: It is used to delete a group.
* groupmod -n new_group_name old_group_name: It is used to rename a group.
* useradd -c “Name Surname” -g admin -d /home/user1 -s /bin/bash user1: It is used to create a new user belonging to the group “admin”.
* useradd user1: With the help of this command, you can create a new user.
* userdel -r user1: to delete a user, you can use this command (‘-r’ removes the Home directory).
* usermod -c “User FTP ” -g system -d /ftp/user1 -s/bin/nologin user1: You can change the user attributes using the given command.
* passwd: This command is used to change the password.
* passwd user1: If you want to change a user’s password (only by root), you can proceed with this command.
* chage -E 2020-12-31 user1: if you want to put a term for the user’s password, then use the given Linux command, and the key will expire on December 31, 2020.
* pwck: is used to verify the integrity of the system authentication information, including correct syntax, the file format of ‘/ etc / passwd’, and the existence of users.
* grpck: command is used to check the correct syntax and format of the file ‘/ etc / group’ and groups’ existence.
* newgrp group_name: Run the given command to register a new group to change the newly created files’ default group.
# 8) Permissions in Files (Use “+” to place permissions and “-” to remove) Commands :-
* ls -lh: Shows permissions.
* ls /tmp | pr -T5 -W $ COLUMNS: divides the terminal into five columns.
* chmod ugo + rwx directory1: It will set read (r), write (w) and execute (x) permissions to owner (u), group (g) and others (o) on directory ‘directory1’.
* chmod go-rwx directory1: removes read permission (r), write (w) and (x) execute to group (g) and others (o) on directory ‘directory1’.
* chown user1 file1: changes the owner of a file.
* chown -R user1 directory1: changes the directory owner and all files and directories contained within.
* chgrp group1 file1: changes group of files.
* chown user1: group1 file1: changes user and group that owns a file.
* find / -perm -u + s: use this command to view all files on the system with SUID configured.
* chmod u + s /bin/file1: put the SUID (Set User ID) bit in a binary file. The user running that file acquires the same privileges as the owner.
* chmod us /bin/file1: disable the SUID (Set User ID) bit in a binary file. 100
* chmod g + s /home/public: put an SGID (Set User ID) bit in a directory –similar to SUID but per directory.
* chmod gs /home/public: disable an SGID (Set User ID) bit in a directory.
* chmod o + t /home/public: put a STICKY bit in a directory. Allows file deletion only to legitimate owners.
* chmod ot /home/public: disable a STICKY bit in a directory.
# 9) Special attributes in files (Use “+” to set permissions and “-” to remove) Commands :-
* chattr + a file1: allows writing by opening a file only append mode.
* chattr + c file1: enable a file to be automatically compressed/decompressed.
* chattr + d file1: ensure that the program ignores deleting files during backup.
* chattr + i file1: makes the file invariable, so it cannot be deleted, altered, renamed, or linked.
* chattr + s file1: allows a file to be safely deleted.
* chattr + S file1: this Linux command ensures that a file is modified and changes are written synchronously with sync.
* chattr + u file1: allows you to retrieve a file’s content even if it is canceled.
* lsattr: show special attributes.
# 10) Archives and compressed files Commands :-
* bunzip2 file1.bz2: linux command is used to unzip a file named ‘file1.bz2’.
* bzip2 file1: It will compress a file named ‘file1’.
* gunzip file1.gz: using the given command, you can unzip a file called ‘file1.gz’.
* gzip file1: It will compress a file named ‘file1’.
* gzip -9 file1: the command is used to compress with maximum compression.
* rar to file1.rar test_file: will create a rar file called ‘file1.rar’.
* rar to file1.rar file1 file2 dir1: It will compress ‘file1’, ‘file2’ and ‘dir1’ simultaneously.
* unrar x file1.rar: is used to unzip or extract the rar files in the full path.
* tar -cvf archive.tar file1: with the help of this command, you can create an unzipped tarball.
* tar -cvf archive.tar file1 file2 dir1: creates an archive containing ‘file1’, ‘file2 ′ and’dir1’.
* tar -tf archive.tar: it is used to display the contents of an archive.
* tar -xvf archive.tar: to extract a tarball.
* tar -xvf archive.tar -C / tmp: extract a tarball in / tmp.
* tar -cvfj archive.tar.bz2 dir1: create a compressed tarball inside bzip2.
* tar -xvfj archive.tar.bz2: decompress a tar archive compressed in bzip2
* tar -cvfz archive.tar.gz dir1: This command is used to create a gzipped tarball.
* tar -xvfz archive.tar.gz: Unzip a gzipped tar archive.
* zip file1.zip file1 – You can create a compressed zip file.
* zip -r file1.zip file1 file2 dir1: zip multiple files and directories simultaneously.
* unzip file1.zip: unzip a zip file.
# 11) RPM packages (Red Hat, Fedora, and the similar) Commands :-
* rpm -ivh package.rpm: install an rpm package.
* rpm -ivh –nodeeps package.rpm: install an rpm package ignoring dependency requests.
* rpm -U package.rpm: update a rpm package without changing the configuration of the files.
* rpm -F package.rpm: update an rpm package only if it is installed.
* rpm -e package_name.rpm: remove a rpm package.
* rpm -qa: show all rpm packages installed on the system.
* rpm -qa | grep httpd: show all rpm packages with the name “httpd”.
* rpm -qi package_name: get information on a specific installed package.
* rpm -qg “System Environment/Daemons”: show the rpm packages of a software group.
* rpm -ql package_name: show the list of files given by an installed rpm package.
* rpm -qc package_name: show configuration list of files given by an installed rpm package.
* rpm -q package_name –whatrequires: show requested a list of dependencies for an rpm package.
* rpm -q package_name –whatprovides: show the capacity given by a rpm package.
* rpm -q package_name –scripts: show scripts started during installation / removal.
* rpm -q package_name –changelog: show the revision history of a rpm package.
* rpm -qf /etc/httpd/conf/httpd.conf: check which rpm package belongs to a given file.
* rpm -qp package.rpm -l: show a list of files given by an rpm package that has not yet been installed.
* rpm –import/media/cdrom/RPM-GPG-KEY: import the digital signature of the public key.
* rpm –checksig package.rpm: check the integrity of an rpm package.
* rpm -qa gpg-pubkey: verify the integrity of all installed rpm packages.
* rpm -V package_name: check file size, licenses, types, owner, group, MD5 summary check and last modification.
* rpm -Va: check all rpm packages installed on the system. Use with care.
* rpm -Vp package.rpm: check an rpm package not installed yet.
* rpm2cpio package.rpm | cpio –extract –make-directories * bin *: extract executable file from rpm package.
* rpm -ivh /usr/src/redhat/RPMS/`arch`/package.rpm: install a package built from a rpm source.
* rpmbuild –rebuild package_name.src.rpm: build an rpm package from an rpm source.
# 12. YUM Package Updater (Red Hat, Fedora, and the similar) Commands :-
* yum install package_name: download and install an rpm package.
* yum localinstall package_name.rpm: this will install an RPM and try to resolve all dependencies for you, using your repositories.
* yum update package_name.rpm: update all rpm packages installed on the system.
* yum update package_name: update / update a rpm package.
* yum remove package_name: remove an rpm package.
* yum list: list all packages installed on the system.
* yum search package_name: Find a package in the rpm repository.
* yum clean packages: clean an rpm cache by deleting the downloaded packages.
* yum clean headers: remove all header files that the system uses to resolve the dependency.
* yum clean all: remove from cache packages and header files.
# 13) Deb packages (Debian, Ubuntu, and derivatives) Commands :-
* dpkg -i package.deb: install / update a deb package.
* dpkg -r package_name: remove a deb package from the system.
* dpkg -l: show all deb packages installed on the system.
* dpkg -l | grep httpd: show all deb packages with the name “httpd”
* dpkg -s package_name: get information on a specific package installed on the system.
* dpkg -L package_name: show list of files given by a package installed on the system.
* dpkg –contents package.deb: show list of files given by a package not installed yet.
* dpkg -S /bin/ping: check which package belongs to a given file.
# 14) APT Package Updater (Debian, Ubuntu and derivatives) Commands :-
* apt-get install package_name: install / update a deb package.
* apt-cdrom install package_name: install / update a deb package from a cdrom.
* apt-get update: update the package list.
* apt-get upgrade: upgrade all installed packages.
* apt-get remove package_name: remove a deb package from the system.
* apt-get check: verify the correct resolution of the dependencies.
* apt-get clean: clear cache from downloaded packages.
* apt-cache search searched-package: returns a list of packages that corresponds to the series “searched packages”.
# 15) View the content of a file Commands :-
* cat file1: view a file’s contents starting from the first row.
* tac file1: view the contents of a file starting from the last line.
* more file1: view the content throughout a file.
* less file1: similar to the ‘more’ command but allows saving the movement in the file and the movement backward.
* head -2 file1: see the first two lines of a file.
* tail -2 file1: see the last two lines of a file.
* tail -f /var/log/messages: see what has been added to the file in real time.
# 16) Text manipulation Commands :-
* cat file1 file2 .. | command <> file1_in.txt_or_file1_out.txt – General syntax for manipulating text using PIPE, STDIN, and STDOUT.
* cat file1 | command (sed, grep, awk, grep, etc …)> result.txt: general syntax to manipulate a text in a file and write the result in a new file.
* cat file1 | command (sed, grep, awk, grep, etc …) »result.txt: general syntax to manipulate a text from a file and add results to an existing file.
* grep Aug /var/log/messages: search for words “Aug” in the file ‘/ var / log / messages’.
* grep ^ Aug /var/log/messages: find words starting with “Aug” in file ‘/ var / log / messages’
* grep [0-9] /var/log/messages: select all lines in the file ‘/ var / log / messages’ that contain numbers.
* grep Aug -R /var/log / *: Find the string “Aug” in the directory ‘/ var / log’ and below.
* sed ‘s /stringa1/stringa2/g’ example.txt: relocate “string1” with “string2” in example.txt
* sed ‘/ ^ $ / d’ example.txt: remove all blank lines from example.txt
* sed ‘/ * # / d; / ^ $ / d ‘example.txt: remove comments and blank lines from example.txt
* echo ‘esempio’ | tr ‘[: lower:]’ ‘[: upper:]’: Convert lowercase to uppercase.
* sed -e ‘1d’ result.txt: remove the first line from the file example.txt
* sed -n ‘/stringa1/p’: display only the lines that contain the word “string1”.
# 17) Set character and file conversion Commands :-
* dos2unix filedos.txt fileunix.txt: convert a text file format from MSDOS to UNIX.
* unix2dos fileunix.txt filedos.txt: convert a text file format from UNIX to MSDOS.
* recode .. HTML <page.txt> page.html: convert a text file into html.
* recode -l | more: show all available format conversions.
# 18) File system analysis Commands :-
* badblocks -v /dev/hda1: Check for bad blocks on disk hda1.
* fsck /dev/hda1: repair / check the Linux system file’s integrity on disk hda1.
* fsck.ext2 /dev/hda1: repair / check the integrity of the ext 2 system file on disk hda1.
* e2fsck /dev/hda1: repair / check the integrity of the ext 2 system file on disk hda1.
* e2fsck -j /dev/hda1: repair / check the integrity of the ext 3 system file on disk hda1.
* fsck.ext3 /dev/hda1: repair / check integrity of system file ext 3 on disk hda1.
* fsck.vfat /dev/hda1: repair / check the integrity of the fat system file on disk hda1.
* fsck.msdos /dev/hda1: repair / check the integrity of a system dos file on disk hda1.
* dosfsck /dev/hda1: repair / check the integrity of a system dos file on disk hda1.
# 19) Format a filesystem Commands :-
* mkfs /dev/hda1: create a Linux-like system file on partition hda1.
* mke2fs /dev/hda1: create a Linux ext 2 system file on hda1.
* mke2fs -j /dev/hda1: create a Linux ext3 (periodic) system file on partition hda1.
* mkfs -t vfat32 -F /dev/hda1: create a FAT32 system file on hda1.
* fdformat -n /dev/fd0: format a flooply disk.
* mkswap /dev/hda3: create a swap system file.
# 20) Working with the SWAP Commands :-
* mkswap /dev/hda3: create swap system file.
* swapon /dev/hda3: activating a new swap partition.
* swapon /dev/hda2/dev/hdb3: activate two swap partitions.
# 21) Salvas (Backup) Commands :-
* dump -0aj -f /tmp/home0.bak home: make a full save of the ‘/ home’ directory.
* dump -1aj -f /tmp/home0.bak/home: make an incremental save of the ‘/ home’ directory.
* restore -if /tmp/home0.bak: restoring a salvo interactively.
* rsync -rogpav –delete /home/tmp: synchronization between directories.
* rsync -rogpav -e ssh –delete /home ip_address: /tmp: rsync through the SSH tunnel .
* rsync -az -e ssh –delete ip_addr: /home/public/home/local: synchronize a local directory with a remote directory via ssh and compression.
* rsync -az -e ssh –delete /home/local ip_addr: /home/public: synchronize a remote directory with a local directory via ssh and compression.
* dd bs = 1M if = /dev/hda | gzip | ssh user @ ip_addr ‘dd of = hda.gz’: save a hard drive on a remote host via ssh.
* dd if = /dev/sda of = /tmp/file1: save the contents of a hard disk to a file. (In this case the hard disk is “sda” and the file is “file1”).
* tar -Puf backup.tar / home/user: make an incremental save of the directory ‘/ home / user’.
* (cd /tmp/local/ && tar c.) | ssh -C user @ ip_addr ‘cd /home/share / && tar x -p’: copy the contents of a directory to a remote directory via ssh.
* (tar c / home) | ssh -C user @ ip_addr ‘cd /home/backup-home && tar x -p’: copy a local directory to a remote directory via ssh.
* tar cf -. | (cd / tmp / backup; tar xf -): local copy preserving licenses and links from one directory to another.
* find /home/user1 -name ‘* .txt’ | xargs cp -av –target-directory = / home/backup/ –parents: find and copy all files with extension ‘.txt’ from one directory to another.
* find /var/log -name ‘* .log’ | tar cv –files-from = – | bzip2> log.tar.bz2: find all files with the extension ‘.log’ and make a bzip archive.
* dd if = /dev/hda of = /dev/fd0 bs = 512 count = 1: make a copy of the MRB (Master Boot Record) to a floppy disk.
* dd if = /dev/fd0 of = /dev/hda bs = 512 count = 1: restore the copy of the MBR (Master Boot Record) saved on a floppy.
# 22) CD ROM Commands :-
* cdrecord -v gracetime = 2 dev = /dev/cdrom -eject blank = fast -force: clean or erase a rewritable cd.
* mkisofs /dev/cdrom> cd.iso: create an iso image of cdrom on disk.
* mkisofs /dev/cdrom | gzip> cd_iso.gz: create a compressed iso image of cdrom on disk.
* mkisofs -J -allow-leading-dots -R -V “Label CD” -iso-level 4 -o ./cd.iso data_cd: create an iso image of a directory.
* cdrecord -v dev = /dev/cdrom cd.iso: burn an iso image.
* gzip -dc cd_iso.gz | cdrecord dev = /dev/cdrom –: burn a compressed iso image.
* mount -o loop cd.iso /mnt/iso: mount an iso image.
* cd-paranoia -B: take songs from a cd to wav files.
* cd-paranoia -” -3″: transfer the first 3 songs from a cd to wav files.
* cdrecord –scanbus: scan bus to identify scsi channel.
* dd if = /dev/hdc | md5sum: run a md5sum on a device, such as a CD.
# 23) Work with the NETWORK ( LAN and Wi-Fi) Commands :-
* ifconfig eth0: show the configuration of an Ethernet network card.
* ifup eth0: activate an interface ‘eth0’.
* ifdown eth0: disable an interface ‘eth0’.
* ifconfig eth0 192.168.1.1 netmask 255.255.255.0: configure an IP address.
* ifconfig eth0 promisc: configure ‘eth0‘ in common mode to obtain packets (sniffing).
* dhclient eth0: activate interface ‘eth0’ in dhcp mode.
* route -n: show route table.
* route add -net 0/0 gw IP_Gateway: configure default entry.
* route add -net 192.168.0.0 netmask 255.255.0.0 gw 192.168.1.1: configure static route to search for network ‘192.168.0.0/16’.
* route del 0/0 gw IP_gateway: remove the static route.
* echo “1”> /proc/sys/net/ipv4/ip_forward: activate ip traversal.
* hostname: display the hostname of the system.
* host www.example.com: find the hostname to resolve the name to an ip address (1).
* nslookup www.example.com: look up the hostname to resolve the name to an IP address and vice versa (2).
* ip link show: show the link status of all interfaces.
* mii-tool eth0: show link status of ‘eth0’.
* ethtool eth0: show network card ‘eth0’ statistics.
* netstat -tup: show all active network connections and their PIDs.
* netstat -tupl: show all network listeners on the system and their PIDs.
* tcpdump tcp port 80: show all HTTP traffic.
* iwlist scan: show wireless networks.
* iwconfig eth1: show the configuration of a wireless network card.
* whois www.example.com: search the Whois database.
# 24) Microsoft Windows Networks (SAMBA) Commands :-
* nbtscan ip_addr: bios network name resolution.
* nmblookup -A ip_addr: bios network name resolution.
* smbclient -L ip_addr/hostname: show remote actions of a host in windows.
# 25) IP tables (FIREWALL) Commands :-
* iptables -t filter -L: show all strings from the filter table.
* iptables -t nat -L: show all strings from nat table.
* iptables -t filter -F: clean all the rules from the filter table.
* iptables -t nat -F: clear all rules from the nat table.
* iptables -t filter -X: delete any string created by the user.
* iptables -t filter -A INPUT -p tcp –dport telnet -j ACCEPT: allow telnet connections to enter.
* iptables -t filter -A OUTPUT -p tcp –dport http -j DROP: block HTTP connections to exit.
* iptables -t filter -A FORWARD -p tcp –dport pop3 -j ACCEPT: allow POP connections to a forward chain.
* iptables -t filter -A INPUT -j LOG –log-prefix “DROP INPUT”: logging an input string.
* iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE: configure a PAT (Address Translation Port) on eth0, hiding force-out packets.
* iptables -t nat -A PREROUTING -d 192.168.0.1 -p tcp -m tcp –dport 22 -j DNAT –to-destination 10.0.0.2:22: redirect addressed packets from one host to another.
# 26) Monitoring and debugging Commands :-
* top: show Linux tasks using the most CPU.
* ps -eafw: show Linux tasks.
* ps -e -o pid, args –forest: Show Linux tasks in hierarchical mode.
* pstree: show a process system tree.
* kill -9 Process_ID: force a process to close and kill it.
* kill -1 Process_ID: force a process to reload the configuration.
* lsof -p $$: show a list of files opened by processes.
* lsof / home/user1: shows a list of files open in a given system path.
* strace -c ls> /dev/null: show the system calls made and received by a process.
* strace -f -e open ls> /dev/null: show library calls.
* watch -n1 ‘cat/proc/interrupts’: show interrupts in real-time.
* last reboot: show reboot history.
* lsmod: show the loaded kernel.
* free -m: shows RAM status in megabytes.
* smartctl -A /dev/hda: monitor the reliability of a hard disk through SMART.
* smartctl -i /dev/hda: check if SMART is enabled on a hard disk.
* tail /var/log/dmesg: show events inherent to the kernel loading process.
* tail /var/log/messages: show system events.
