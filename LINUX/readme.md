# Linux Basics

## Operating System:
- An operating system (OS) is a system software that manages computer hardware and software resources 
- and acts as an intermediary between the user and the hardware.


## Linux vs Windows

| Feature               | Linux                                | Windows                              |
|-----------------------|---------------------------------------|---------------------------------------|
| Interface             | CLI (Command Line Interface)         | GUI (Graphical User Interface)        |
| Usability             | Difficult to use                     | Easy to use                           |
| Source Code           | Open Source                          | Closed Source                         |
| Licensing             | No Licensing Required                | Licensing Required                    |
| Cost                  | Free                                 | Paid                                  |
| Resource Usage        | Lightweight (Consumes Less Resources)| Heavy (Consumes More Resources)       |
| Security              | More Secure                          | Less Secure                           |



## 🧩 Different Types of Operating Systems

- **Batch OS** – Executes batches of jobs with minimal or no user interaction.
- **Time-Sharing OS** – Allows multiple users to share system resources simultaneously.
- **Distributed OS** – Manages a group of independent computers as a single system.
- **Embedded OS** – Designed to run on embedded systems like smartwatches or appliances.
- **Real-Time OS** – Provides immediate response and is used in time-critical environments.
- **Network OS** – Enables communication and resource sharing across a network.
- **Mobile OS** – Optimized for mobile devices like smartphones and tablets.

## 🖧 What is a Server?

A **server** is a powerful computer or system that provides data, services, or resources to other computers (clients) over a network. Examples include web servers, file servers, and database servers.

---

## 🖥️ Desktop OS vs Server OS

| Feature             | Desktop OS                          | Server OS                            |
|---------------------|--------------------------------------|---------------------------------------|
| **Purpose**         | Designed for personal daily use     | Designed to manage network resources  |
| **Users**           | Typically one user at a time        | Supports multiple users simultaneously|
| **Performance**     | Optimized for user interface & apps | Optimized for stability & performance |
| **Uptime**          | Can afford restarts or downtime     | Requires high uptime (24/7)           |
| **GUI**             | GUI-focused for easy use            | Often CLI-based for efficiency        |
| **Examples**        | Windows 10/11, Ubuntu Desktop       | Windows Server, Ubuntu Server, CentOS |
| **Security**        | Basic security                      | Advanced security and access control  |
| **Price**           | Usually cheaper                     | Can be more expensive (licensed)      |


## Linux Architecture

**Linux architecture has four main components hardware,kernel,shell and user/application**



**Hardware:** it consists of motherboard ,CPU,HDD etc

**Kernel:** kernel is the heart/core of the OS, kernel communicates with Hardware

**Shell:** provides interface to user to communicate with kernel 

**Application/user:** Users interact with the system through varies applications such as office, games, etc. 

<img width="1258" height="642" alt="image" src="https://github.com/user-attachments/assets/2bb7d4f9-6df7-489c-a2c7-89d80974f974" />


## Distributions of Linux
- redhat
- dabian
- fedora
- ubuntu
- amazon linux
- kali linux
- mint
- suse

    
---



## Linux Basic Commands:

**shows username**
````
whoami
````
**shows hostname**
````
hostname
````
**shows present working dir**
````
pwd
````
**display os informaton**
````
cat /etc/os-release
````
**display kernel information**
````
uname -a
````
**display memory information**
````
free -h
````
**display disk information**
````
df -h
````

**list files and dir's**
````
ls
````

**change directory**
````
cd <dirname>
````
**back to previous dir**
````
cd ..
````
- check current shell
````
echo $SHELL
````
- exit the terminal
```bash
exit
```
- check live processes
````
top
````
- check CPU information
```bash
lscpu
```
- check disk/storage information
````
df -h
````
- list block devices
```bash
lsblk
```
- check size of file/dir
````
du -sh file/dirname
````
---

## Directory  Structure in  Linux:

-In Linux directory structure   “/”  (slash) is main directory
- All other directories comes under “/” directory.




1. / - The main folder.


2. /bin - Basic commands everyone uses (e.g., ls, cp).


3. /sbin - Commands for system admins (e.g., reboot).


4. /usr - Programs and tools for users.


5. /var - Stores changing files like logs.


6. /tmp - Temporary files that auto-delete.


7. /etc - System settings and configuration files.


8. /dev - Files that connect to hardware (e.g., USB).


9. /proc - Info about running programs and the system.


10. /sys - Details about hardware and devices.


11. /lib - Helper files for programs to run.


12. /boot - Files needed to start the computer.


13. /home - home dir of local user.


14. /opt - Extra programs you install.


15. /root - home dir of root user


16. /media - Automatically mounted drives (e.g., USB).


17. /mnt - Manually mounted drives.


18. /srv - Files for server programs (e.g., websites).


19. /run - Temporary system files from this boot.


