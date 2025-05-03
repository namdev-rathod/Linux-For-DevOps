# 🐧 **Linux for DevOps**


1. 🌍 Understand Real World Scenarios  
2. ❓ Why Linux?  
3. 🖥️ Where We Can Use Linux?  
4. 📚 Fundamentals of Linux  
5. ⚔️ Linux vs Windows  
6. 📂 Linux File System  
7. 📦 Package Management  
8. 🛠️ Core Components of Linux  
9. 🗂️ Directory Structure In Linux  
10. 👤 Linux User Management  
11. 📄 Linux File Management  
12. ✍️ VI Editor Shortcuts (commonly used)  
13. 🔐 File Permissions  
14. 🛡️ File Special Permissions  
15. ⚙️ Process Management  
16. 📈 Linux System Monitoring  
17. 🌐 Basic Networking in Linux  
18. 💾 Disk and Storage Management in Linux  
19. 🛠️ Troubleshooting Commands  
20. 🧰 General Commands  
21. 📝 Editors – VI, VIM, Nano  
22. 🐚 Shell Scripting  
23. 🕒 Cron Management
24. 🎯 Linux Interview Questions
25. 📚 From Where to Learn Linux?

---

## 🌍 **Understand Real World Scenarios For Linux**

Linux is the foundation of most tech companies today, from startups to giants like Google and Amazon. As a DevOps engineer, you’ll work with Linux servers to manage cloud infrastructure, deploy websites, and automate tasks. 🖥️
Most cloud platforms, including AWS and GCP, use Linux for its stability, flexibility, and cost-effectiveness. 🌐
Whether it’s running databases, hosting applications, or managing containers with Docker, Linux powers many key technologies. 🚀
👉 Bottom Line: Knowing Linux is critical for cloud computing, system administration, and DevOps roles in the real world.

Certainly! Here's the theory for **"Why Linux?"** in **5-7 lines**:

---

## ❓ **Why Linux?**

 Linux is the preferred choice for most tech companies because it is **open-source**, **secure**, and **highly customizable**. 🛠️  
 It’s free to use and offers **better performance** with low overhead, making it ideal for running servers, databases, and cloud applications. ☁️  
 Unlike Windows, Linux gives complete control over the system, allowing automation through scripts and commands. 📝  > It’s also **secure by design**, with frequent security patches and 
 a smaller attack surface compared to other OS. 🔒  
 **👉 Bottom Line:** Linux offers stability, security, and cost-efficiency, making it a top choice for DevOps, cloud computing, and system administration.

---

## 🐧 **Popular Linux Distributions**

- **Ubuntu**:  
  - User-friendly, great for beginners  
  - Popular for both personal use and servers  
  - Often used in cloud environments (AWS, GCP)

- **CentOS / RHEL**:  
  - Enterprise-grade, stable, and secure  
  - Widely used in server environments  
  - RHEL is commercial support; CentOS is community-driven

- **Debian**:  
  - Known for stability and reliability  
  - Often used as the base for other distributions (like Ubuntu)

- **Fedora**:  
  - Cutting-edge features, great for developers  
  - Supports new software and technologies  
  - Upstream source for Red Hat Enterprise Linux (RHEL)

- **Arch Linux**:  
  - Minimalistic, flexible, and customizable  
  - Ideal for advanced users who want full control

- **Linux Mint**:  
  - Beginner-friendly, based on Ubuntu  
  - Comes with a pre-configured desktop environment (Cinnamon)

- **Kali Linux**:  
  - Specialized for penetration testing and cybersecurity  
  - Pre-packed with security tools

- **OpenSUSE**:  
  - Known for its enterprise-grade tools and flexible configuration  
  - Good for both developers and system admins

- **Manjaro**:  
  - Based on Arch Linux but more user-friendly  
  - Great for users who want the Arch experience without the complexity
---

## 🖥️ **Where We Can Use Linux?**

 Linux is used in **many areas of technology**, especially in **servers** and **cloud computing**. 🌐  
 It powers **web servers** (Apache, Nginx), **databases** (MySQL, PostgreSQL), and is a go-to for **containerized applications** (Docker, Kubernetes). 🐳  
 In **cloud environments** (AWS, GCP, Azure), Linux is the OS of choice due to its **stability**, **performance**, and **low cost**. ☁️  
 It's also used in **IoT devices**, **smartphones** (Android uses Linux Kernel), **embedded systems**, and **cybersecurity** tools. 🔒  
 **👉 Bottom Line:** Linux is everywhere, from websites to mobile apps to cloud services — it's the backbone of modern tech.

---

## 📚 **Fundamentals of Linux**

At its core, **Linux** is an open-source operating system based on the **Unix model**. 🖥️  
Everything in Linux is treated as a **file** — including devices, processes, and directories. 📂  
The system is built around a **kernel**, which handles hardware interaction and system resource management. 🔧  
Linux uses a **command-line interface (CLI)** for interaction, though graphical interfaces (GUIs) are available. 🖱️
The system follows a **hierarchical file system**, and you use commands like `ls`, `cd`, and `cp` to navigate and manipulate files. 🗂️
**👉 Bottom Line:** Linux’s structure is simple yet powerful, providing full control over system resources and processes.

---

## ⚔️ **Linux vs Windows**

- **Cost**:  
  - **Linux** is **open-source** and free to use. 🆓  
  - **Windows** requires a **license**, which often involves recurring costs. 💰

- **Customization**:  
  - **Linux** is highly **customizable**, allowing users to modify the OS to meet specific needs. 🛠️  
  - **Windows** is more **restricted** in terms of customization options. ⚙️

- **User Interface**:  
  - **Windows** has a **graphical user interface (GUI)** that is more familiar to most users, making it **easier to use for beginners**. 🖱️  
  - **Linux** can be used with a **GUI** (e.g., Ubuntu, GNOME), but many advanced users prefer the **command-line interface (CLI)** for more control. 💻

- **Security**:  
  - **Linux** is considered more **secure** due to its open-source nature, allowing for quicker updates and fixes. It also has a smaller attack surface. 🔒  
  - **Windows** is a more common target for malware and viruses, though it has significantly improved its security features. 🦠

- **Performance**:  
  - **Linux** is lightweight, making it ideal for **servers** and systems with limited resources. ⚡  
  - **Windows** can be resource-heavy, especially in enterprise environments and with certain applications. 🖥️

- **Software Support**:  
  - **Windows** has better **native support** for popular commercial software like **Microsoft Office**, **Adobe**, and various games. 🎮  
  - **Linux** is more suited for **open-source software**, but tools like **Wine** or **virtual machines** can run Windows software on Linux. 📂

- **Use Cases**:  
  - **Linux** is widely used in **servers**, **cloud computing**, **IoT devices**, and **supercomputers**. 🚀  
  - **Windows** is commonly used for **personal desktop use**, **gaming**, and **business environments**. 🏢

- **System Administration**:  
  - **Linux** provides **full control** over the system, making it the preferred choice for **system administrators** and **DevOps engineers**. ⚙️  
  - **Windows** has a more automated system administration experience, but it lacks the granular control that Linux offers. 🔧

- **👉 Bottom Line**:  
  - **Choose Linux** for **servers**, **cloud environments**, **development**, and **customization**.  
  - **Choose Windows** for **desktop use**, **business software**, and **gaming**.

---

## 📂 Linux File System: Hierarchical Overview

```
/  (Root)
├─ bin       📦 Essential user binaries  
├─ boot      🚀 Static files for bootloader  
├─ dev       🖥️ Device files  
├─ etc       📝 Host & system configuration  
├─ home      🧑‍💻 User home directories  
│   └─ user/  
├─ lib       🔧 Essential shared libraries  
├─ mnt       📂 Mount point for temporary mounts  
├─ media     💾 Removable media (CDs, USB)  
├─ opt       📦 Optional add-on application software  
├─ proc      🌀 Virtual filesystem for processes  
├─ root      👑 Home for the root user  
├─ run       ⚡ Runtime variable data  
├─ sbin      🛠️ System binaries (admin commands)  
├─ srv       🌐 Data for services (e.g., web, FTP)  
├─ sys       🔄 Kernel & system information  
├─ tmp       🗑️ Temporary files  
├─ usr       📚 User utilities & applications  
│   ├─ bin/  
│   ├─ lib/  
│   └─ share/  
└─ var       📈 Variable data (logs, mail, spool)
```

---

### 🔑 Key Directory Descriptions

- **/** (Root)  
  The single entry point of the entire filesystem tree.  

- **/bin & /sbin**  
  Essential programs for all users (`/bin`) and system admin tasks (`/sbin`).  

- **/etc**  
  All global configuration files live here (network, user accounts, services).  

- **/home**  
  Personal data and settings for each user—your “workspace” on the system.  

- **/var**  
  Frequently changing data: logs (`/var/log`), mail (`/var/mail`), caches.  

- **/proc & /sys**  
  Virtual filesystems providing real-time info about kernel and processes.  

- **/usr**  
  Secondary hierarchy for read-only user data, apps, and libraries—think “big share.”  

---

## 📦 **Package Management in Linux**

Package management is essential for managing the software on a Linux system. It allows you to **install**, **update**, **remove**, and **manage software** packages efficiently.

---

### **1. What is a Package?**  
A **package** is a compressed file containing a program or software, along with its dependencies, configuration files, and documentation. These packages make it easy to install and maintain software on Linux systems.

---

### **2. Types of Package Management Systems**
- **Debian-based systems** (e.g., Ubuntu, Debian):  
  Use **APT (Advanced Package Tool)** for managing packages.  
  Example command:  
  ```bash
  sudo apt install <package_name>   # Install a package
  sudo apt update                   # Update package list
  sudo apt upgrade                  # Upgrade installed packages
  sudo apt remove <package_name>    # Remove a package
  ```
  
- **Red Hat-based systems** (e.g., CentOS, Fedora):  
  Use **YUM (Yellowdog Updater, Modified)** or **DNF (Dandified YUM)** for managing packages.  
  Example command:  
  ```bash
  sudo yum install <package_name>   # Install a package
  sudo yum update                   # Update packages
  sudo yum remove <package_name>    # Remove a package
  ```

- **Arch-based systems** (e.g., Arch Linux, Manjaro):  
  Use **Pacman** for managing packages.  
  Example command:  
  ```bash
  sudo pacman -S <package_name>      # Install a package
  sudo pacman -Sy                   # Synchronize package databases
  sudo pacman -R <package_name>      # Remove a package
  ```

---

### **3. Package Formats**
- **DEB**: Used by Debian-based distributions (e.g., Ubuntu).
- **RPM**: Used by Red Hat-based distributions (e.g., CentOS, Fedora).
- **PKGBUILD**: Used by Arch Linux for building packages.

---

### **4. How Package Management Works**
- **Repositories**:  
  Linux distributions maintain **repositories**, which are online servers storing packages. When you run the package manager (e.g., `apt`, `dnf`, `pacman`), it connects to these repositories to fetch packages.

- **Dependencies**:  
  When installing a program, the package manager automatically installs any required **dependencies** (other software packages needed for the program to work).

---

### **5. Advantages of Package Management**
- **Efficiency**: Automates the process of installing, updating, and removing software. 🔄  
- **Security**: Ensures software is up to date with security patches. 🔒  
- **Convenience**: Provides easy access to thousands of software packages in official repositories. 📦

---

## 🛠️ **Core Services to Learn in Linux**

- 📜 SSH (Secure Shell)  
- 📁 FTP / SFTP Services  
- 📬 Mail Services  
- 🖥️ Web Server Services (Apache, Nginx)  
- 📈 Database Services (MySQL, PostgreSQL)  
- 🛡️ Firewall Services (firewalld, iptables, ufw)  
- 🔄 Cron Jobs (Task Scheduling)  
- 🌀 Logging Services (rsyslog, journalctl)  
- 📦 Package Management Services (apt, yum, dnf)

---

## 👤 **Linux User Management**

In Linux, **user management** is crucial for controlling who can access the system and what actions they can perform. 🖥️  
You can **create users** (`useradd`, `adduser`) to allow new people to use the system, and **set passwords** (`passwd`) to secure their accounts. 🔒  
Using commands like `usermod`, you can **modify user details** (like changing their group or shell).  
With `groupadd` and `usermod -aG`, you can **create groups** and **add users to groups** for organized permission management. 👥  
**Permissions** are controlled by `chown` (change ownership) and `chmod` (change file access rights). 📂  
You can also **lock, unlock, or expire** user accounts (`passwd -l`, `chage`) to enhance security. 🔐  
This ensures that **only the right people** have the **right level of access** at all times! 🚀

---

### 👤 **1. Create a User**
```bash
sudo useradd devops_user
```
- **Explanation**: This creates a new user named `devops_user` without setting a password.

---

### 🔒 **2. Add Password for User**
```bash
sudo passwd devops_user
```
- **Explanation**: This sets a password for `devops_user`. You will be prompted to enter the password.

---

### 🔄 **3. Change Password for User**
```bash
sudo passwd devops_user
```
- **Explanation**: This allows you to **change** the password of `devops_user`. You will be asked to enter the new password.

---

### 🏷️ **4. Create a Group**
```bash
sudo groupadd devops_group
```
- **Explanation**: This creates a new group named `devops_group`.

---

### ➕ **5. Add User to a Group**
```bash
sudo usermod -aG devops_group devops_user
```
- **Explanation**: This command adds the user `devops_user` to the group `devops_group`.

---

### 🛠️ **6. Grant User Sudo Permission**
```bash
sudo usermod -aG sudo devops_user
```
- **Explanation**: This command gives `devops_user` **sudo** (administrative) privileges by adding them to the `sudo` group.

---

## 📢 **Quick Verification Commands**

- **Check if user belongs to a group**:
  ```bash
  groups devops_user
  ```

- **Verify if user has sudo permissions**:
  ```bash
  sudo -l -U devops_user
  ```

---

## 📄 **Linux File Management**

Linux provides a wide range of commands for managing files and directories efficiently. Here's what you need to know:

---

### 📂 **1. Creating Files**

- **Create an empty file**:
  ```bash
  touch filename.txt
  ```

- **Create a file with content**:
  ```bash
  echo "Hello, World!" > hello.txt
  ```

---

### 📝 **2. Viewing Files**

- **View the content of a file**:
  ```bash
  cat filename.txt
  ```

- **View the beginning of a file**:
  ```bash
  head filename.txt
  ```

- **View the end of a file**:
  ```bash
  tail filename.txt
  ```

- **Search for content within a file**:
  ```bash
  grep "search_term" filename.txt
  ```

---

### 🗂️ **3. Managing Directories**

- **Create a directory**:
  ```bash
  mkdir directory_name
  ```

- **Change to a directory**:
  ```bash
  cd directory_name
  ```

- **List the contents of a directory**:
  ```bash
  ls -l
  ```

- **Remove a directory**:
  ```bash
  rmdir directory_name
  ```

---

### ✂️ **4. Copying, Moving, and Renaming Files**

- **Copy a file**:
  ```bash
  cp source_file destination_file
  ```

- **Move or rename a file**:
  ```bash
  mv old_name new_name
  ```

- **Copy a directory and its contents**:
  ```bash
  cp -r source_directory destination_directory
  ```

---

### 🗑️ **5. Deleting Files**

- **Delete a file**:
  ```bash
  rm filename.txt
  ```

- **Delete a directory and its contents**:
  ```bash
  rm -r directory_name
  ```

---

### 📑 **6. Changing File Permissions**

- **Change file permissions** (read, write, execute):
  ```bash
  chmod 755 filename
  ```

- **Change file ownership** (user:group):
  ```bash
  chown user:group filename
  ```

---

### 🔍 **7. File Search**

- **Search for a file by name**:
  ```bash
  find /path/to/search -name filename.txt
  ```

---

### 🔐 **8. File Compression**

- **Create a .tar file**:
  ```bash
  tar -cvf archive_name.tar /path/to/directory
  ```

- **Extract a .tar file**:
  ```bash
  tar -xvf archive_name.tar
  ```

---

### 📚 **9. File Disk Usage**

- **Check the disk usage of files and directories**:
  ```bash
  du -sh /path/to/directory
  ```

- **Check free disk space**:
  ```bash
  df -h
  ```

---

## ✨ **Bonus Tips**:
- Use **wildcards** (`*`, `?`) to match multiple files.  
  Example: `ls *.txt` to list all `.txt` files.

---

### ✍️ **Vim Editor**

The **Vim editor** (Vi IMproved) is an advanced version of the **VI** editor, providing enhanced features for editing and creating text, especially useful for developers and system administrators. Vim offers a **more user-friendly experience** while still retaining the power of the original **VI** editor.

---

### 🔹 **Key Features of Vim**:
- **Syntax Highlighting**: Vim supports syntax highlighting for various programming languages, making code easier to read and debug.
- **Undo/Redo History**: Unlike VI, Vim allows you to undo and redo multiple changes.
- **Search and Replace**: Powerful search features, including regular expressions.
- **Plugins**: Vim supports many plugins to enhance its functionality, such as code completion, file navigation, etc.
- **Multiple Buffers**: Allows opening multiple files at once and easily switching between them.
- **Customizability**: Vim can be customized extensively with the `.vimrc` file.

---

### 📝 **How to Open Vim**:
- Open a file with **vim**:
  ```bash
  vim filename.txt
  ```

- If the file doesn’t exist, Vim will create it.

---

### 🔹 **Vim Modes**:
Just like **VI**, Vim operates in different modes:

#### 1. **Normal Mode**:
- This is the default mode where you can navigate, search, and manipulate text.
- **Common commands**:
  - `h`, `j`, `k`, `l`: Move the cursor left, down, up, and right.
  - `dd`: Delete a line.
  - `yy`: Copy a line.
  - `p`: Paste the copied content.
  - `u`: Undo changes.
  - `Ctrl + r`: Redo changes.
  - `/search_term`: Search for a term in the file.
  
#### 2. **Insert Mode**:
- This is the mode for **editing** and typing.
- To enter **Insert Mode**, press `i` (or `I` to start at the beginning of the line).
- To exit **Insert Mode**, press `Esc`.

#### 3. **Command Mode**:
- You can execute commands like saving, quitting, or searching in **Command Mode**.
- **Common commands**:
  - `:w`: Save the file.
  - `:q`: Quit Vim.
  - `:wq`: Save and quit.
  - `:q!`: Quit without saving changes.

---

### 🔹 **Working with Files in Vim**:

1. **Open a File**:
   ```bash
   vim myfile.txt
   ```

2. **Insert Text**:
   - Press `i` to enter Insert Mode and start typing.
   - Press `Esc` to return to Normal Mode.

3. **Save the File**:
   - Press `Esc` and type `:w` to save changes.
   - Press `Esc` and type `:wq` to save and quit.

4. **Quit Vim**:
   - Press `Esc` and type `:q` to quit if no changes were made.
   - Press `Esc` and type `:q!` to force quit without saving changes.

---

### 🔹 **Vim Search and Replace**:

1. **Search for a term**:
   - In Normal Mode, type `/term` and press Enter to search for the word "term".
   - Press `n` to find the next occurrence and `N` for the previous occurrence.

2. **Replace a word**:
   - To replace a word on the current line, use the `:s` command:
     ```bash
     :s/old_word/new_word/
     ```
   - To replace all occurrences of the word in the entire file:
     ```bash
     :%s/old_word/new_word/g
     ```

---

### ✍️ **VI Editor Shortcuts (Commonly Used)**

The **VI editor** is a powerful tool for text editing in Linux, but mastering it requires familiarity with its shortcuts and commands. Below are the **most commonly used VI shortcuts**, organized by mode, to help you become efficient in navigating and editing files.

---

### 🔹 **Navigation Shortcuts (Normal Mode)**

- **Move Cursor**:
  - `h` → Move left by one character
  - `j` → Move down by one line
  - `k` → Move up by one line
  - `l` → Move right by one character
  - `w` → Jump to the beginning of the next word
  - `b` → Jump to the beginning of the previous word
  - `0` → Jump to the beginning of the current line
  - `$` → Jump to the end of the current line
  - `gg` → Jump to the beginning of the file
  - `G` → Jump to the end of the file

---

### 🔹 **Editing Shortcuts (Normal Mode)**

- **Deleting Text**:
  - `x` → Delete the character under the cursor
  - `dw` → Delete a word from the cursor position
  - `dd` → Delete the current line
  - `d$` → Delete from the cursor to the end of the line
  - `d0` → Delete from the cursor to the beginning of the line
  - `dG` → Delete from the cursor to the end of the file

- **Copying/Pasting**:
  - `yy` → Copy (yank) the current line
  - `yw` → Copy the current word
  - `p` → Paste the copied text after the cursor
  - `P` → Paste the copied text before the cursor

- **Undo/Redo**:
  - `u` → Undo the last change
  - `Ctrl + r` → Redo the undone change

---

### 🔹 **Insertion Shortcuts (Insert Mode)**

- **Switch to Insert Mode**:
  - `i` → Start inserting before the cursor
  - `I` → Start inserting at the beginning of the line
  - `a` → Start inserting after the cursor
  - `A` → Start inserting at the end of the line
  - `o` → Open a new line below the current line and start inserting
  - `O` → Open a new line above the current line and start inserting

- **Exit Insert Mode**:
  - `Esc` → Exit Insert Mode and return to Normal Mode

---

### 🔹 **Search and Replace (Normal Mode)**

- **Search**:
  - `/search_term` → Search for a term forward
  - `?search_term` → Search for a term backward
  - `n` → Move to the next occurrence of the search term
  - `N` → Move to the previous occurrence of the search term

- **Replace**:
  - `:s/old/new/` → Replace the first occurrence of `old` with `new` in the current line
  - `:s/old/new/g` → Replace all occurrences of `old` with `new` in the current line
  - `:%s/old/new/g` → Replace all occurrences of `old` with `new` in the entire file

---

### 🔹 **File Operations (Command Mode)**

- **Save**:
  - `:w` → Save the current file
  - `:wq` → Save and quit the file
  - `ZZ` → Save and quit (shortcut for `:wq`)

- **Quit**:
  - `:q` → Quit if no changes have been made
  - `:q!` → Quit without saving changes
  - `:x` → Save and quit (alternative to `:wq`)

---

### 🔹 **Other Useful Shortcuts**

- **Move Between Words**:
  - `Ctrl + w` → Jump between words when editing
  - `Ctrl + f` → Move forward one page
  - `Ctrl + b` → Move backward one page

- **Case Changing**:
  - `~` → Toggle the case of the character under the cursor (uppercase <-> lowercase)
  - `gU` → Convert the selected text to uppercase
  - `gu` → Convert the selected text to lowercase

- **Line Operations**:
  - `C` → Change the rest of the current line
  - `D` → Delete from the cursor to the end of the line
  - `Y` → Copy the current line
  - `J` → Join the current line with the next line

---
### 🔐 **File Permissions in Linux**

In Linux, **file permissions** are a critical part of security and help control who can access and modify files. Each file or directory in Linux has associated **permissions** that determine what actions users can perform. Understanding these permissions is essential for managing security on your Linux system.

---

### 🔹 **Types of Permissions**
- **Read (r)**: Allows reading the file or listing the contents of a directory.
- **Write (w)**: Allows modifying the file or adding/removing files in a directory.
- **Execute (x)**: Allows executing a file (if it's a script or program) or accessing a directory's contents.

These permissions are applied to three types of users:
- **Owner (u)**: The user who owns the file.
- **Group (g)**: Users who belong to the file's group.
- **Others (o)**: Everyone else who is not the owner or in the group.

---

### 🔹 **Viewing File Permissions**
To view the permissions of a file, use the `ls -l` command:
```bash
ls -l filename
```
Output example:
```
-rw-r--r-- 1 user group 12345 Jan  1 12:34 file.txt
```
Explanation:
- The first character (`-`) indicates it's a regular file.
- The next three characters (`rw-`) represent the owner's permissions (read and write).
- The next three (`r--`) represent the group's permissions (read only).
- The final three (`r--`) represent others' permissions (read only).

---

### 🔹 **Changing File Permissions**
To change file permissions, the `chmod` command is used:
- **Syntax**: `chmod [options] mode file`
- **Mode** can be specified in **symbolic** or **numeric** form.

#### 🔹 **Symbolic Mode**
- **`r`**: Read
- **`w`**: Write
- **`x`**: Execute

- Example 1: Give execute permission to the owner of the file
  ```bash
  chmod u+x file.txt
  ```

- Example 2: Remove write permission for the group
  ```bash
  chmod g-w file.txt
  ```

- Example 3: Give read and write permissions to the owner, and read permission to others
  ```bash
  chmod u+rw, o+r file.txt
  ```

#### 🔹 **Numeric Mode**
Each permission is represented by a number:
- **Read (r) = 4**
- **Write (w) = 2**
- **Execute (x) = 1**

- The permissions are represented by three digits:
  - **First digit** for the **owner**
  - **Second digit** for the **group**
  - **Third digit** for **others**

- Example: Set permissions to `rw-r--r--`:
  ```bash
  chmod 644 file.txt
  ```

  Breakdown:
  - Owner (`rw-`): 6 (read + write = 4 + 2)
  - Group (`r--`): 4 (read)
  - Others (`r--`): 4 (read)

---

### 🔹 **Changing Ownership**
To change the ownership of a file, the `chown` command is used:
- **Syntax**: `chown [owner][:group] file`

- Example: Change the owner to `user1` and the group to `staff`:
  ```bash
  chown user1:staff file.txt
  ```

- Example: Change the owner to `user1` only:
  ```bash
  chown user1 file.txt
  ```

---

### 🔹 **Changing Group Ownership**
To change the group ownership of a file, the `chgrp` command is used:
- **Syntax**: `chgrp group file`

- Example: Change the group ownership to `admin`:
  ```bash
  chgrp admin file.txt
  ```

---
### 🔑 **Special Permissions: setfacl and getfacl**

In Linux, **Access Control Lists (ACLs)** provide a more flexible permission model than the traditional user/group/other file permissions. ACLs allow you to set permissions for individual users or groups on specific files or directories.

Here’s how you can use **`setfacl`** and **`getfacl`** to manage and view ACLs:

---

### **🔹 What is `setfacl`?**
The `setfacl` command is used to **set** ACLs on files and directories. It allows you to assign permissions to specific users or groups that are not part of the file’s owner, group, or other categories.

### **🔹 What is `getfacl`?**
The `getfacl` command is used to **view** the current ACLs on a file or directory. It provides detailed information about the permissions set on the file for each user or group.

---

### **💻 How to Use `setfacl` and `getfacl`**

#### **1. Setting ACL for a User**
To assign specific permissions to a user for a file, use the `setfacl` command. For example:

```bash
setfacl -m u:username:rwx /path/to/file
```
- **Explanation**:
  - `-m`: Modify (set) ACL.
  - `u:username:rwx`: Grant the user `username` **read (r)**, **write (w)**, and **execute (x)** permissions on the file.
  - `/path/to/file`: The file or directory where ACL is being set.

**Example:**
```bash
setfacl -m u:john:rw /home/user/file.txt
```
This command grants **read** and **write** permissions to the user `john` on the file `/home/user/file.txt`.

---

#### **2. Setting ACL for a Group**
Similarly, you can set permissions for a group. Use the `g:` flag to specify the group.

```bash
setfacl -m g:groupname:rx /path/to/directory
```
- **Explanation**:
  - `g:groupname:rx`: Grant the group `groupname` **read (r)** and **execute (x)** permissions.
  - `/path/to/directory`: The directory to set the ACL on.

**Example:**
```bash
setfacl -m g:devs:rx /projects/myproject
```
This command grants **read** and **execute** permissions to the group `devs` on the `/projects/myproject` directory.

---

#### **3. Setting Default ACL for Directories**
To set default ACLs for directories, which apply to newly created files and directories within it, use the `-d` option:

```bash
setfacl -d -m u:username:rw /path/to/directory
```
- **Explanation**:
  - `-d`: Set default ACLs for files created within the directory.
  - `-m`: Modify the ACL.
  - `u:username:rw`: Grant **read (r)** and **write (w)** permissions to `username` for newly created files in the directory.

**Example:**
```bash
setfacl -d -m u:alice:rw /projects/shared
```
This ensures that any new files created in `/projects/shared` will automatically grant **read** and **write** permissions to the user `alice`.

---

#### **4. Removing ACLs**
You can also remove ACLs for specific users or groups using the `-x` option:

```bash
setfacl -x u:username /path/to/file
```
- **Explanation**:
  - `-x`: Remove ACL entry.
  - `u:username`: Specifies the user whose ACL will be removed.

**Example:**
```bash
setfacl -x u:bob /home/user/file.txt
```
This command removes the ACL for the user `bob` on the file `/home/user/file.txt`.

---

### **👁️ Viewing ACLs with `getfacl`**
To view the current ACLs on a file or directory, use the `getfacl` command.

```bash
getfacl /path/to/file
```

**Example:**
```bash
getfacl /home/user/file.txt
```
This will display the ACLs set on the file `/home/user/file.txt`.

**Sample Output:**
```bash
# file: /home/user/file.txt
# owner: user
# group: users
user::rw-
user:john:rw-
group::r--
mask::rw-
other::r--
```

- The output shows:
  - **Owner** (`user`) has **read** and **write** permissions.
  - **User** `john` has **read** and **write** permissions.
  - **Group** has **read** permission.
  - **Mask** sets the maximum permissions for all users.
  - **Others** have **read** permission.

---

### **🚫 Remove All ACLs**
If you want to remove all ACLs from a file or directory and revert it to standard user/group/other permissions, you can use the `-b` option with `setfacl`:

```bash
setfacl -b /path/to/file
```

This command removes all ACL entries from the file or directory, leaving only the basic permissions.

---

### 🌐 **What is Networking in Linux?**

**Networking in Linux** refers to the configuration, management, and troubleshooting of network connections on Linux-based systems. It enables Linux machines to communicate with each other, access the internet, connect to servers, and share data securely and efficiently.

---

### 💡 **Key Concepts:**

* **IP Addressing**: Assigns a unique identity to each device.
* **Subnetting**: Divides networks for better organization and security.
* **Gateway**: Routes traffic from your network to other networks.
* **DNS (Domain Name System)**: Resolves human-readable domain names to IP addresses.
* **Interfaces**: Physical (e.g., `eth0`) or virtual (e.g., `lo`) network devices used to send/receive data.

---

### 📦 **Why It's Important in DevOps:**

* Managing connectivity between microservices and cloud infrastructure.
* Configuring CI/CD pipelines to access remote servers or APIs.
* Monitoring and securing network traffic in production environments.
* Debugging failed deployments due to DNS or port issues.

---

### 🛠️ **Common Commands:**

* `ip a` – Show IP address
* `ping` – Test connectivity
* `netstat` / `ss` – Check listening ports
* `dig` / `nslookup` – DNS troubleshooting
* `curl` – Test HTTP endpoints

---

### 🌐 **Basic Networking Examples for DevOps**

---

**0️⃣ IP Address - Private Class**
🔍 Private IP ranges help in internal communication within networks.

* Examples:

  * `10.0.0.0 – 10.255.255.255`
  * `172.16.0.0 – 172.31.255.255`
  * `192.168.0.0 – 192.168.255.255`
* Use the online subnet calculator: [https://www.davidc.net/sites/default/subnets/subnets.html](https://www.davidc.net/sites/default/subnets/subnets.html)

---

**1️⃣ `curl ifconfig.me`**
📡 Get your **public IP address** from a Linux terminal:

```bash
curl ifconfig.me
```

🧠 Useful when setting up cloud VMs or whitelisting IPs in firewalls.

---

**2️⃣ `netstat -tlupn`**
📊 View all **listening services and their ports**:

```bash
sudo netstat -tlupn
```

* `t` – TCP
* `u` – UDP
* `l` – Listening
* `p` – Show PID
* `n` – Show numeric addresses

📍 Example:

```bash
Proto Recv-Q Send-Q Local Address           Foreign Address         State       PID/Program name
tcp        0      0 0.0.0.0:80              0.0.0.0:*               LISTEN      1234/apache2
```

---

**3️⃣ `traceroute google.com`**
🛰️ Shows the **network path (hops)** to a destination:

```bash
traceroute google.com
```

🔎 Helps detect where latency or packet loss happens.

---

**4️⃣ `curl` and `wget`**
📥 Test endpoint and download files:

```bash
curl -I https://example.com     # Header only
curl -O https://example.com/app.tar.gz

wget https://example.com/app.tar.gz
```

📌 `curl` is good for APIs, `wget` is good for large file downloads.

---

**5️⃣ `nslookup google.com`**
🔎 Query DNS to find IP address of a domain:

```bash
nslookup google.com
```

🧠 Helps troubleshoot DNS resolution issues.

---

**6️⃣ `dig google.com`**
📖 More detailed DNS query than `nslookup`:

```bash
dig google.com
```

* Shows A record, TTL, authoritative info.

---

**7️⃣ `ifconfig` / `ip a` / `ip r`**
🛠️ Check network interfaces and routing table:

```bash
ifconfig      # Deprecated but still used
ip a          # Show all network interfaces and IPs
ip r          # Show routing table
```

---

### 🔐 **Private IP Address Classes (IPv4)**

Private IP addresses are reserved for internal network use and are not routable on the public internet. They are defined by [RFC 1918](https://datatracker.ietf.org/doc/html/rfc1918).([Network Lessons][1])

| **Class** | **IP Range**                  | **Subnet Mask** | **Total Addresses** | **Typical Use Cases**                                                                                                           |
| --------- | ----------------------------- | --------------- | ------------------- | ----------------------------------- 
| A         | 10.0.0.0 – 10.255.255.255     | 255.0.0.0       | 16,777,216          | Large enterprises, ISPs, cloud VPCs                                                                                            |
| B         | 172.16.0.0 – 172.31.255.255   | 255.240.0.0     | 1,048,576           | Medium-sized networks, universities                                                                                            |
| C         | 192.168.0.0 – 192.168.255.255 | 255.255.0.0     | 65,536              | Home networks, small businesses     

These ranges are commonly used in environments like home routers, corporate LANs, Docker containers, and cloud infrastructures.

---

### 🌐 **IPv4 vs. IPv6 Comparison**

| **Feature**              | **IPv4**                                   | **IPv6**                                                                                                                                                                                            
| ------------------------ | ------------------------------------------ | -------------------------------------------
| **Address Length**       | 32-bit                                     | 128-bit                                                                                                                                                                                            
| **Address Format**       | Decimal (e.g., 192.168.1.1)                | Hexadecimal (e.g., 2001:0db8::1)                                                                                                                                                                 
| **Total Addresses**      | \~4.3 billion                              | \~340 undecillion                                                                                                                                                                                
| **Header Size**          | 20–60 bytes (variable)                     | 40 bytes (fixed)                                                                                                                                                                                  
| **Configuration**        | Manual or DHCP                             | Stateless auto-configuration or DHCPv6                                                                                                                                                           
| **Security**             | Optional (IPSec)                           | Mandatory (IPSec)                                                                                                                                                                             
| **Broadcast Support**    | Yes                                        | No (uses multicast and anycast)                                                                                                                                                                  
| **NAT Required**         | Yes, due to limited address space          | No, ample address space                                                                                                                                                                          
| **Packet Fragmentation** | By sender and routers                      | By sender only                                                                                                                                                                                 
| **Adoption**             | Widely used, but address exhaustion issues | Growing adoption, especially in modern networks


---




