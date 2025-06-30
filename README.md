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

**2.



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

**Types of Shell:**

Command-line shell (e.g., Bash, CMD)

Graphical shell (e.g., Windows desktop, GNOME in Ubuntu)


⭐️ It acts like a translator between the user and the kernel.

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

This repository contains a table-based documentation of the standard Linux/Unix file system structure.

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

## ✅ Summary

- 🧑‍💻 **Choose VMware** if you're a professional user looking for **better performance** and enterprise-grade features.
- 🎓 **Choose VirtualBox** if you're a student or hobbyist wanting a **free and flexible solution**.

---

## 📌 License

This content is provided under the [MIT License](LICENSE).





