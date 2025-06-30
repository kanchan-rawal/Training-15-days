# Training-15-days
# Day 1 (25 june 2025)
## Introduction to linux
### What is linux?
Linux is a free, open-source operating system that works as a bridge between a computer's hardware and the software you use.

### Operating system
(an interface between the user and the computer hardware)

⭐️
Linux is based on Unix — it works like Unix but is built independently.

⭐️ 
**Linux distributions** are different versions of the Linux operating system.**e.g.ubuntu**

### Difference between linux and windows

| Feature           | **Linux**                              | **Windows**                          |
|------------------|----------------------------------------|--------------------------------------|
| **Type**          | Open-source OS                        | Closed-source (paid license)         |
| **Cost**          | Free to use                           | Paid (license required)              |
| **Customization** | Highly customizable                   | Limited customization                |
| **Security**      | More secure, fewer viruses            | More vulnerable to malware           |
| **Usage**         | Used by developers, servers, hackers  | Mostly used by general users         |         
| **Examples**      | Ubuntu, Fedora, Kali Linux            | Windows 10, Windows 11               |

### How to install linux on windows
**1.Virtual box:** It's like creating a computer inside your computer,VirtualBox lets you create a virtual machine.
(https://www.virtualbox.org/)

**2.Microsoft visual c++ redistributable:**

(https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist)

> This is required for features like USB support and VirtualBox Extension Pack.

**3.Ubuntu download:**
(https://tinyurl.com/csegndec)

**4.Start Ubuntu:**



1. Open VirtualBox


2. Click New → Name: "Ubuntu"


3. Set RAM (at least 2 GB) and create a virtual hard disk (20 GB or more)


4. Under "Storage", click the empty optical drive → choose your Ubuntu ISO


5. Start the VM → Ubuntu will boot and begin installation.


**Product-Based Company:**
Makes its own product (like Google makes Chrome, Microsoft makes Windows)
Earns by selling that product.
Makes and sells own product


**Service-Based Company:**
Works for other companies (like Infosys builds software for banks or hospitals)
Earns by providing services.
Works for clients and gets paid

**Startups:**
A startup is a new company started by one or more people to create a unique product or service, usually with limited resources and big ideas,trying to grow fast by solving a real-world problem in a different or better way.

**e.g.zomato,paytm**

### Uses of linux: ###

Linux is used in servers, computers, Android, and cloud systems.
It’s popular for programming, hacking, and high-security applications.

# Day 2 (26 june 2025) 
### Booting:

It loads the operating system (like Windows or Linux) into the computer’s memory (RAM) so you can start using it.

**Cold Booting:** Starting the computer from power off state (like turning it on),**hard booting**

**Warm Booting:** 	Restarting the computer when it is already on (like using Restart button),**soft booting**

### Kernel:

The core of an OS is called the kernel.
It directly controls the hardware like CPU, memory, disk, etc.


**Functions:**

Manages CPU, RAM, devices

Handles processes and files

Acts as a bridge between software and hardware

### Shell:

The shell is the outer part of the OS that interacts with the user.



It takes commands from the user and passes them to the kernel.


⭐️ It acts like a translator between the user and the kernel.

**Types of shells:**

bash: Enhanced sh with more features, widely used on Linux.

sh: Basic Unix shell, mainly for scripting and compatibility.

zsh: Feature-rich, highly customizable shell popular among power users.

fish: User-friendly shell with smart features and easy syntax.

**Categories of Shells:**


Command-Line Shell: You type text commands (like in Windows Command Prompt or Linux Terminal).

Graphical Shell: You use graphical elements like icons and menus (like Windows Explorer or macOS Finder).


### Commands:
**date:** Returns current date.

**whoami:** Returns the current domain and user name.

**ls (list):** Returns content of a specified Directory

**cd:** Changes directory.

**mkdir:** Creates a new directory.

**pwd:** Prints the current working directory.

**touch:** Creates empty file.

**cat:** Creates file with content.

**whereis:** Finds the location of specified file.

**mv:** To move or rename a file.

**cp:** To copy content of a file to the other.

**whatis:** Gives short description of a command.

# File System Structure


| Directory | Name                 | Description |
|-----------|----------------------|-------------|
| `/`       | Root Directory        | The top-level directory. All other directories are under it. |
| `/bin`    | Binary                | Essential user command binaries. |
| `/sbin`   | System Binary         | System administration binaries. |
| `/boot`   | Boot Loader Files     | Contains boot files like the kernel. |
| `/etc`    | Configuration Files   | System-wide configuration files. |
| `/dev`    | Device Files          | Device nodes for hardware. |
| `/home`   | Home Directories      | Personal directories for users. |
| `/lib`    | Shared Libraries      | Libraries required by system binaries. |
| `/media`  | Removable Media       | Mount point for USBs and CDs. |
| `/mnt`    | Temporary Mounts      | Used for mounting file systems temporarily. |
| `/opt`    | Optional Software     | Third-party applications. |
| `/proc`   | Process Info          | Virtual filesystem with runtime info. |
| `/root`   | Root Home             | Home directory of the root user. |
| `/run`    | Runtime Data          | Temporary runtime information. |
| `/srv`    | Service Data          | Data for services (e.g., HTTP, FTP). |
| `/tmp`    | Temporary Files       | Temp files, usually cleared on reboot. |
| `/usr`    | User Programs         | Secondary hierarchy for user data. |
| `/var`    | Variable Files        | Log files, spool files, etc. |
# Day 3(27 june 2025)
### iso file:

An ISO file contains all the contents of a disc — including the file system structure, boot files, and data — bundled into one file with the .iso extension.

### Bare metal installation

Bare metal installation refers to installing an operating system (OS), software, or virtualization environment directly on the physical hardware of a server or computer, without any pre-installed OS or virtualization layer.

### VMware and virtual box

| Feature               | VMware                                     | VirtualBox                                |
|-----------------------|--------------------------------------------|--------------------------------------------|
| **Developer**         | VMware Inc.                                | Oracle Corporation                         |
| **Main Products**     | VMware Workstation, VMware Player          | Oracle VM VirtualBox                       |
| **License**           | Mostly **paid** (some free tools)          | Completely **free and open-source**        |
| **Performance**       | Generally **faster and more stable**       | Slightly **slower**, but improving         |
| **OS Support**        | Supports most OSs (Windows, Linux, etc.)   | Also supports most OSs                     |
| **Snapshots**         | Yes (in all versions)                      | Yes (in all versions)                      |
| **USB Device Support**| Full support                               | Good support (extension pack needed)       |
| **Guest Tools**       | VMware Tools (very polished)               | Guest Additions (sometimes less smooth)    |
| **User Interface**    | More polished and professional             | Simpler, more beginner-friendly            |
| **3D Graphics Support**| Better 3D acceleration                    | Basic 3D support (limited gaming use)      |

---
### Dual booting

Dual booting means installing two operating systems on the same computer, so you can choose one at startup.

### Partitioning Scheme


A partitioning scheme is the way a hard drive is divided into sections (partitions) to store data or install operating systems.



Types of Partitioning Schemes


MBR (Master Boot Record)	Old system, supports up to 4 primary partitions, max 2 TB disk size	Older BIOS systems

GPT (GUID Partition Table)	Newer system, supports 128 partitions, disks larger than 2 TB, more secure	Modern UEFI systems

### file and directory permissions
control who can read, write, or execute a file or directory.


**There are three types of permissions:**

Permission	Symbol	Meaning on File	Meaning on Directory


**Read	r**	View the contents	List the files

**Write 	w** Modify the file	Add/delete files

**Execute	 x**	Run the file as program	Enter or access directory



---

**User Categories**


Category	Meaning


u	User (owner of the file)

g	Group (users in the file's group)

o	Others (all other users)

a	All (user + group + others)




---


**Changing Permissions**


Using **chmod (change mode)**


Symbolic mode:


chmod u+x file.txt     # Add execute for user

chmod g-w file.txt     # Remove write from group

chmod o=r file.txt     # Set others to read-only


**Numeric (octal) mode:**


Number	Permission


7	rwx

6	rw-

5	r-x

4	r--

0	





# Day 4 (30 june 2025)
## PC Hardware troubleshooting
**Hardware** refers to the physical parts of a computer system — the components you can touch and see. These parts work together to process data, perform tasks, and run software.

⭐️PC is like a human body.

**CPU:** brain

**RAM:** short term memory

**Hard drive:** long term memory
 
**Motherboard:** nervous system

**power supply:** heart

### Types of computer hardware:
**Input Devices:**	Keyboard, Mouse, Microphone, Webcam	Allow users to input data into the computer.

**Output Devices:**	Monitor, Printer, Speakers	Display or output information from the computer.

**Processing Unit	CPU** *(Processor)*, Motherboard	:The brain of the computer; processes data and controls operations.

**Storage Devices:**	Hard Disk (HDD), SSD, Pen Drive	Store data permanently or temporarily.

**Memory:**
*(RAM)*	RAM (Random Access Memory)	Temporary memory that holds data currently being used.

**Power Supply Unit (PSU):**	SMPS	Converts electricity to usable power for components.

**Expansion Components:** Graphics Card (GPU), Sound Card	Enhance performance or add features.

**Cooling System:**	Fans, Heat Sink, Liquid Coolers	Prevent components from overheating.

**Ports and Cables:**	USB, HDMI, Ethernet, SATA cables	Connect devices and transfer data/power.


# Motherboard 

The **motherboard** is the **main circuit board** of a computer. It connects and allows communication between all components, making it the backbone of your PC.

---

## Key Functions

- Connects the **CPU**, **RAM**, **storage**, **GPU**, and **peripherals**.
- Manages **power distribution** to hardware.
- Hosts the **BIOS/UEFI firmware**, which starts your computer.
- Provides **expansion slots** for additional cards (like WiFi, sound, or GPU).

---
![image](https://github.com/user-attachments/assets/582a9ee7-31ef-4f71-9626-d7d1e7b3f3d2)


##  Major Components on motherboard


| Component               | Description |
|-------------------------|-------------|
| **CPU Processor Socket**| Slot where the CPU (Central Processing Unit) is installed. |
| **RAM Memory Slots**    | Sockets for installing RAM modules (memory). |
| **24-pin Power Connector** | Supplies main power to the motherboard from the power supply unit (PSU). |
| **8-pin Power Connector** | Provides extra power specifically for the CPU. |
| **Case Fan Connector**  | Connects a fan to keep the system cool. |
| **Heat Sink**           | A metal piece that helps dissipate heat from chips like the CPU or chipset. |
| **IDE Connector**       | Legacy connector for older hard drives and CD/DVD drives. |
| **AGP Slots**           | Older slot used for video/graphics cards. |
| **SATA Ports**          | Connect modern storage devices like SSDs and HDDs. |
| **PCI Slots**           | Expansion slots for sound cards, network cards, and older GPUs. |
| **Jumper Port**         | Used for resetting BIOS or configuring hardware at low level. |
| **Floppy Port**         | Legacy connector for floppy disk drives. |
| **BIOS Chip**           | Contains the firmware to boot the system and control hardware settings. |
| **Modem Port**          | Used for dial-up internet (outdated). |
| **Audio Port**          | Connects audio devices like speakers and microphones. |
| **USB Port**            | Universal connection port for various peripherals. |
| **VGA Port**            | Analog video output for monitors (legacy). |
| **DVI Port**            | Digital video output, better than VGA. |
| **HDMI Port**           | Combines high-definition video and audio output. |
| **PS/2 Port**           | Legacy port for connecting keyboard and mouse. |

---

## BIOS vs UEFI

- **BIOS**: Basic firmware to start your PC (older systems).
- **UEFI**: Modern version with graphical interface, supports larger drives and secure boot.

### What is Cache Memory?

Cache memory is a small, high-speed memory located very close to or inside the CPU (Central Processing Unit). It stores frequently accessed data and instructions so the CPU can retrieve them faster than from main memory (RAM).

### Cache Memory Levels:

**L1 (Level 1):** Smallest and fastest, inside CPU core

**L2 (Level 2):** Larger, slightly slower

**L3 (Level 3):** Shared among cores, larger but slower than L1/L2



---

⭐️Let

**Cache =** Notebook on your desk (super quick to grab info)

**RAM =** Bookshelf nearby (still fast but not as instant)

**Hard Drive =** Library down the hall (big but slow)

### Difference between ram and cache memory:

| Feature             | Cache Memory                              | RAM (Random Access Memory)                 |
|---------------------|--------------------------------------------|---------------------------------------------|
| **Speed**           | Very fast                                  | Slower than cache                           |
| **Size**            | Small (in MBs)                             | Large (in GBs)                              |
| **Location**        | Inside or near CPU                         | On the motherboard                          |
| **Purpose**         | Stores frequently accessed CPU data        | Stores data and apps currently in use       |
| **Cost**            | More expensive per MB                      | Cheaper per GB                              |
| **Accessed By**     | Directly by CPU                            | Through system bus                          |
| **Volatile**        | Yes (data lost when power off)             | Yes (also volatile)                         |

---







