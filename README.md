# Networking-Basics-Zero-to-Hero
In this Respo we are going to learn the basic networking knowlegde require for Technical Support &amp; DevOps Role
# Network
In simple words it is a group of two or more computers
# Components Of Network
* Two or More Computers
* Cables as link's between Computers
* A Network Interfacing Card [NIC] on each computer
* Switches - which perform's the switching process
* Routers - that connects two or more Pocket- Switched Network's
* Software called Operating System [OS].
# Operating System
It act's as gateway between Hardware and Software application for effective communication. Windows & Linux are the famous OS

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
IP Address Format and Table
IP address is a short form of "Internet Protocol Address." It is a unique number provided to every device connected to the internet network, such as Android phone, laptop, Mac, etc. An IP address is represented in an integer number separated by a dot (.), for example, 192.167.12.46.
Types of IP Address
An IP address is categorized into two different types based on the number of IP address it contains. These are:
         IPv4 (Internet Protocol version 4)
o	IPv6 (Internet Protocol version 6)
What is IPv4?
IPv4 is version 4 of IP. It is a current version and the most commonly used IP address. It is a 32-bit address written in four numbers separated by a dot (.), i.e., periods. This address is unique for each device. For example, 66.94.29.13
What is IPv6?
IPv4 produces 4 billion addresses, and the developers think that these addresses are enough, but they were wrong. IPv6 is the next generation of IP addresses. The main difference between IPv4 and IPv6 is the address size of IP addresses. The IPv4 is a 32-bit address, whereas IPv6 is a 128-bit hexadecimal address. IPv6 provides a large address space, and it contains a simple header as compared to IPv4.
IP Address Format
Originally IP addresses were divided into five different categories called classes. These divided IP classes are class A, class B, class C, class D, and class E. Out of these, classes A, B, and C are most important. Each address class defines a different number of bits for its network prefix (network address) and host number (host address). The starting address bits decide from which class an address belongs.
 
Network Address: The network address specifies the unique number which is assigned to your network. In the above figure, the network address takes two bytes of IP address.
Host Address: A host address is a specific address number assigned to each host machine. With the help of the host address, each machine is identified in your network. The network address will be the same for each host in a network, but they must vary in host address.
Address Format IPv4
The address format of IPv4 is represented into 4-octets (32-bit), which is divided into three different classes, namely class A, class B, and class C.
 
The above diagram shows the address format of IPv4. An IPv4 is a 32-bit decimal address. It contains four octets or fields separated by 'dot,' and each field is 8-bit in size. The number that each field contains should be in the range of 0-255.
ADVERTISEMENT
Class A
Class A address uses only first higher order octet (byte) to identify the network prefix, and remaining three octets (bytes) are used to define the individual host addresses. The class A address ranges between 0.0.0.0 to 127.255.255.255. The first bit of the first octet is always set to 0 (zero), and next 7 bits determine network address, and the remaining 24 bits determine host address. So the first octet ranges from 0 to 127 (00000000 to 01111111).
Class B
Class B addresses use the initial two octets (two bytes) to identify the network prefix, and the remaining two octets (two bytes) define host addresses. The class B addresses are range between 128.0.0.0 to 191.255.255.255. The first two bits of the first higher octet is always set to 10 (one and zero bit), and next 14 bits determines the network address and remaining 16 bits determines the host address. So the first octet ranges from 128 to 191 (10000000 to 10111111).
Class C
Class C addresses use the first three octets (three bytes) to identify the network prefix, and the remaining last octet (one byte) defines the host address. The class C address ranges between 192.0.0.0 to 223.255.255.255. The first three bit of the first octet is always set to 110, and next 21 bits specify network address and remaining 8 bits specify the host address. Its first octet ranges from 192 to 223 (11000000 to 11011111).
Class D
Class D IP address is reserved for multicast addresses. Its first four bits of the first octet are always set to 1110, and the remaining bits determine the host address in any IP address. The first higher octet bits are always set to 1110, and the remaining bits specify the host address. The class D address ranges between 224.0.0.0 to 239.255.255.255. In multicasting, data is not assigned to any particular host machine, so it is not require to find the host address from the IP address, and also, there is no subnet mask present in class D.
Class E
Class E IP address is reserved for experimental purposes and future use. It does not contain any subnet mask in it. The first higher octet bits are always set to 1111, and next remaining bits specify the host address. Class E address ranges between 240.0.0.0 to 255.255.255.255.

TCP vs UDP: Differences between the protocols
The main difference between TCP (transmission control protocol) and UDP (user datagram protocol) is that TCP is a connection-based protocol and UDP is connectionless. While TCP is more reliable, it transfers data more slowly. UDP is less reliable but works more quickly. This makes each protocol suited to different types of data transfers.
Protocols are rules that govern how data is formatted and sent over a network. TCP and UDP are two different methods for doing the same job: transferring data via the internet. They enable servers and devices to communicate so you can send emails, watch Netflix, play games, and browse web pages.
TCP creates a secure communication line to ensure the reliable transmission of all data. Once a message is sent, the receipt is verified to make sure all the data was transferred.
UDP does not establish a connection when sending data. It sends data without confirming receipt or checking for errors. That means some or all of the data may be lost during transmission.
Here are the main differences between TCP and UDP:
Factor	TCP	UDP
Connection type	Requires an established connection before transmitting data	No connection is needed to start and end a data transfer
Data sequence	Can sequence data (send in a specific order)	Cannot sequence or arrange data
Data retransmission	Can retransmit data if packets fail to arrive	No data retransmitting. Lost data can’t be retrieved
 Delivery	Delivery is guaranteed	Delivery is not guaranteed
Check for errors	Thorough error-checking guarantees data arrives in its intended state	Minimal error-checking covers the basics but may not prevent all errors
Broadcasting	Not supported	Supported
Speed	Slow, but complete data delivery	Fast, but at risk of incomplete data delivery
Which protocol is better: TCP or UDP?
It depends on what you’re doing online and the type of data being transferred. UDP is better if you’re gaming online, because its speedy data transfer allows for mostly lag-free gaming. TCP is better if you’re transferring files, like family photos, because it ensures the data arrives exactly as it was sent.
Overall, TCP and UDP are both useful protocols, so to think in terms of TCP vs UDP is a bit misleading. But depending on the type of data transfer, TCP or UDP might be better for the job. Here are some examples:
TCP is best for:
•	 Email or texting
•	 File transfers
•	 Web browsing
UDP is best for:
•	 Live streaming
•	 Online gaming
•	 Video chat
Here’s a detailed breakdown of the advantages and disadvantages of TCP and UDP:
 Advantages of TCP
Transmission control protocol (TCP) is the protocol to choose for maximum reliability and quality. It may not be the fastest, but it gets the job done right. Here are a few advantages of the TCP protocol:
•	It sets up and maintains a connection between sender and receiver.
•	It operates independently of the operating system.
•	It supports many routing protocols.
•	It checks for errors, guaranteeing data arrives at its destination unaltered.
•	It confirms data arrival after delivery, or attempts to retransfer.
•	It’s able to send data in a particular sequence.
•	It optimizes the pace of data transmission based on the receiver.
 Disadvantages of TCP
TCP isn’t suited for some types of data transfers, especially ones that require faster speeds. These are the drawbacks of TCP packet transmission:
•	It uses more bandwidth and is slower than UDP.
•	It’s especially slow at the beginning of a file transfer.
•	It can prevent data from loading if some data is lost. For example, it won’t load images on a web page until all of the page data has been delivered.
•	It reduces its transfer rate if the network is congested, resulting in even slower speeds.
•	It’s not suited for LAN and PAN networks.
•	It can’t multicast or broadcast.
Despite its slower speeds, TCP is the only protocol that can retransmit lost data packets. When reliability is critical, TCP is the best option.
 Applications of TCP
When should you enable TCP data transfer? Most data transfers automatically use the best protocol option. But in certain circumstances — such as when using a VPN — you may need to choose a protocol to optimize your browsing experience. Enable TCP for the following activities:
•	Email and text messaging
•	Streaming pre-recorded content on sites like Netflix, Hulu, or HBO Max
•	Transferring files between apps and devices
•	General web browsing
•	Remote device or network administration
 Advantages of UDP
UDP delivers data rapidly, and it doesn’t slow down or turn back to recollect lost data. This makes it an ideal protocol for delivering continuous data or broadcasting, such as for live streaming, video calling, and matching servers with IP addresses. Here are some of the advantages of UDP:
•	No connection is needed to send or receive data, so apps and operating systems work faster.
•	Broadcast and multicast transmission is available, meaning one UDP transmission can send data to multiple recipients.
•	It endures packet loss, delivering data even if it's incomplete.
•	Smaller packet size and less overhead reduce end-to-end delay.
•	Operates over a larger range of network conditions than TCP.
•	UDP communication is more efficient.
•	It can transmit live and real-time data.
 Disadvantages of UDP
While UDP provides the speed you need to live a comfortable digital life, UDP isn’t as reliable as TCP. This is something to be aware of when setting up a VPN, because most VPNs run on UDP protocols to keep connection speeds high. Here are some disadvantages of using UDP:
•	It’s connectionless, which makes data transfer unreliable.
•	There’s no system in place to acknowledge a successful data transfer.
•	There’s no way to know if data is delivered in its original state, or at all.
•	It has no error control, so it drops packets when errors are detected.
•	In case of a data collision, routers will often drop UDP packets and favor TCP packets.
•	Multiple users accepting UDP data can cause congestion, and there’s no way to mitigate this.
•	It cannot sequence data, so data can arrive in any order or out of order.
 Applications of UDP
UDP is best suited for transferring a steady flow of live data. This allows many users to access data easily and quickly, if not in perfect condition. A good example is playing an online game. UDP can keep the action moving in spite of potential errors or data loss. Here are a few applications of UDP in real life.
•	Online gaming
•	Multicasting
•	Video chatting/conferencing
•	VoIP (in-app voice calling)
•	Domain Name Systems (which translates domain names into IP addresses)

Four Layers of TCP/IP model
In this TCP/IP tutorial, we will explain different layers and their functionalities in TCP/IP model:

![image](https://github.com/6288mani/Networking-Basics-Zero-to-Hero/assets/89063645/27cc025e-a4da-4f9a-932b-109a2ede3471)

 TCP/IP Conceptual Layers
The functionality of the TCP IP model is divided into four layers, and each includes specific protocols.
TCP/IP is a layered server architecture system in which each layer is defined according to a specific function to perform. All these four TCP IP layers work collaboratively to transmit the data from one layer to another.
•	Application Layer
•	Transport Layer
•	Internet Layer
•	Network Interface

MAC ID
A MAC (Media Access Control) address, sometimes referred to as a hardware or physical address, is a unique, 12-character alphanumeric attribute that is used to identify individual electronic devices on a network
