# Linux_cheat_sheet
Commands to operate with linux
# 🐧 Linux Cheat Sheet

A quick reference guide for common Linux commands.

## Table of Contents
- [File Operations](#file-operations)
- [Directory Operations](#directory-operations)
- [Permissions](#permissions)
- [System Information](#system-information)
- [Process Management](#process-management)
- [Networking](#networking)
- [Package Management](#package-management)

---

## File Operations

| Description                     | Command                    |
|---------------------------------|----------------------------|
| List files in a directory       | `ls`                       |
| List all files including hidden | `ls -a`                    |
| Display file content            | `cat filename`             |
| Copy a file                     | `cp source destination`    |
| Move a file                     | `mv source destination`    |
| Remove a file                   | `rm filename`              |
| Create a new file               | `touch filename`           |

---

## Directory Operations

| Description                           | Command                     |
|---------------------------------------|-----------------------------|
| Create a new directory                | `mkdir directoryname`       |
| Remove an empty directory             | `rmdir directoryname`       |
| Remove a directory and its contents   | `rm -r directoryname`       |
| Change current directory              | `cd directoryname`          |
| Go up one directory level             | `cd ..`                     |
| Go to the home directory              | `cd ~`                      |
| List current directory's path         | `pwd`                       |

---

## Permissions

| Description                               | Command                         |
|-------------------------------------------|---------------------------------|
| Change file permissions                   | `chmod permissions filename`    |
| Change file owner                         | `chown owner filename`          |
| Add execute permission to a file          | `chmod +x filename`             |
| Make a file readable and writable by all  | `chmod 666 filename`            |
| Make a file executable by the owner       | `chmod 700 filename`            |

---

## System Information

| Description                      | Command                    |
|----------------------------------|----------------------------|
| Display system information       | `uname -a`                 |
| Show current disk usage          | `df -h`                    |
| Show memory usage                | `free -h`                  |
| Display CPU information          | `lscpu`                    |
| Show all active processes        | `ps aux`                   |
| Display running processes tree   | `pstree`                   |

---

## Process Management

| Description                        | Command                     |
|------------------------------------|-----------------------------|
| List running processes             | `ps`                        |
| Kill a process by PID              | `kill PID`                  |
| Kill all processes named `name`    | `killall name`              |
| Show real-time process activity    | `top`                       |
| Stop a process by PID              | `kill -STOP PID`            |
| Resume a stopped process by PID    | `kill -CONT PID`            |

---

## Networking

| Description                                | Command                       |
|--------------------------------------------|-------------------------------|
| Display all network interfaces             | `ifconfig`                    |
| Display active network connections         | `netstat -tuln`               |
| Ping a host                                | `ping hostname`               |
| Display routing table                      | `route -n`                    |
| Download a file from the web               | `wget url`                    |
| SSH into a remote server                   | `ssh user@hostname`           |

---

## Package Management

### **Debian/Ubuntu**

| Description                                 | Command                            |
|---------------------------------------------|------------------------------------|
| Update package lists                        | `sudo apt update`                  |
| Upgrade installed packages                  | `sudo apt upgrade`                 |
| Install a package                           | `sudo apt install packagename`     |
| Remove a package                            | `sudo apt remove packagename`      |
| Search for a package                        | `apt search packagename`           |

### **Red Hat/CentOS**

| Description                                 | Command                            |
|---------------------------------------------|------------------------------------|
| Install a package                           | `sudo yum install packagename`     |
| Remove a package                            | `sudo yum remove packagename`      |
| Update all packages                         | `sudo yum update`                  |
| Search for a package                        | `yum search packagename`           |
| List all installed packages                 | `yum list installed`               |

---

Feel free to extend or customize this cheat sheet based on your needs. You can add more sections or commands as necessary.
