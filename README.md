# Linux Task 01 - Linux Environment Setup & Essential Commands

## White Band Associates Summer Internship 2026 - Cyber Security

**Name:** Bhakti Parhad
**Task:** Linux Task 01
**Domain:** Cyber Security
**Operating System Used:** Kali Linux
**Environment:** Virtual Machine

---

## Objective

The objective of this task was to gain hands-on experience with the Linux operating system, terminal navigation, directory management, file management, and system information commands.

Linux is one of the most important operating systems used in Cyber Security, Ethical Hacking, System Administration, Cloud Computing, and Server Management.

---

## Tasks Performed

### Part A: Linux Installation & Verification

* Installed Kali Linux in a Virtual Machine.
* Verified successful installation.
* Explored the Linux desktop environment.
* Opened and used the terminal.
* Collected system information.

#### Screenshots

##### Desktop Environment

![Desktop Environment](Screenshots_linux_01/Desktop_Environment.png)

##### Terminal Window

![Terminal Window](Screenshots_linux_01/Terminal_Window.png)

##### System Information

![System Information](Screenshots_linux_01/System_Information.png)

---

### Part B: Basic Navigation Commands

The following Linux commands were executed and studied:

| Command  | Description                           |
| -------- | ------------------------------------- |
| pwd      | Display current working directory     |
| ls       | List files and directories            |
| ls -la   | List all files including hidden files |
| cd       | Change directory                      |
| clear    | Clear terminal screen                 |
| history  | Show command history                  |
| whoami   | Display current username              |
| hostname | Display system hostname               |

#### Screenshots

##### pwd

![pwd](Screenshots_linux_01/pwd.png)

##### ls

![ls](Screenshots_linux_01/ls.png)

##### ls -la

![ls -la](Screenshots_linux_01/ls_la.png)

##### cd

![cd](Screenshots_linux_01/cd.png)

##### clear

![clear](Screenshots_linux_01/clear.png)

##### history

![history](Screenshots_linux_01/history.png)

##### whoami

![whoami](Screenshots_linux_01/whoami.png)

##### hostname

![hostname](Screenshots_linux_01/hostname.png)

---

### Part C: Directory Management

Created the following directory structure:

```text
CyberSecurity_Lab
├── Networking
├── Linux
├── CyberSecurity
├── EthicalHacking
└── Reports
```

Commands used:

```bash
mkdir -p CyberSecurity_Lab/{Networking,Linux,CyberSecurity,EthicalHacking,Reports}
tree CyberSecurity_Lab
```

#### Screenshots

##### mkdir Command

![mkdir](Screenshots_linux_01/mkdir.png)

##### tree Command

![tree](Screenshots_linux_01/tree.png)

---

### Part D: File Management

Performed the following operations:

* Created files
* Copied files
* Renamed files
* Moved files
* Deleted files

Commands used:

```bash
touch
cp
mv
rm
```

#### Screenshot

![File Operations](Screenshots_linux_01/file_operations.png)

---

### Part E: System Information Collection

Executed the following commands:

```bash
uname -a
hostname
whoami
date
uptime
pwd
```

Information collected:

* Kernel Version
* Username
* Current Directory
* Current Date and Time
* System Uptime

#### Screenshots

##### uname -a

![uname -a](Screenshots_linux_01/uname_a.png)

##### date

![date](Screenshots_linux_01/date.png)

##### uptime

![uptime](Screenshots_linux_01/uptime.png)

---

### Part F: Linux Research Activity

Topics researched:

1. What is Linux?
2. Why is Linux important in Cyber Security?
3. Difference between Linux and Windows
4. What is a Linux Distribution?
5. Why Ethical Hackers prefer Linux-based Operating Systems

The detailed answers are available in:

```text
Research_Answers.txt
```

---

## Repository Structure

```text
Linux_Task_01_Bhakti_Parhad
│
├── Screenshots_linux_01
│   ├── Desktop_Environment.png
│   ├── Terminal_Window.png
│   ├── System_Information.png
│   ├── pwd.png
│   ├── ls.png
│   ├── ls_la.png
│   ├── cd.png
│   ├── clear.png
│   ├── history.png
│   ├── whoami.png
│   ├── hostname.png
│   ├── date.png
│   ├── file_operations.png
│   ├── mkdir.png
│   ├── tree.png
│   ├── uname_a.png
│   └── uptime.png
│
├── Command_Outputs.txt
├── Linux_Notes_Task_01.txt
├── Research_Answers.txt
└── README.md
```

---

## Learning Outcomes

Through this task, I learned:

* Linux installation and setup
* Linux terminal basics
* Navigation commands
* Directory management
* File management operations
* System information commands
* Linux file system fundamentals
* Importance of Linux in Cyber Security

---

## Author

**Bhakti Parhad**
Cyber Security Intern
