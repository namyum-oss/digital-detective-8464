# Mission 3 – Understand the Operating System

### Task 3.1 – Explore Your Operating System

I used Terminal commands to explore my system, account, storage and activity.

| Information explored | What it tells you | Your observation (privacy-safe) |
|---|---|---|
| Operating system / system details | Shows OS, kernel and hardware details. | macOS, Darwin kernel and ARM64 architecture. |
| Current account identity | Shows the logged-in username. | Username displayed: [redacted] |
| Available and used storage | Shows total, used and available space. | 926 GiB total, 13 GiB used and 758 GiB available. |
| System activity snapshot | Shows running processes and system activity. | Viewed using the `top` command. |

**Commands used:** `uname -a`, `whoami`, `df -h`, `top -l 1`

### Task 3.2 – Understand Processes

**1. What is a process?**

A process is a program that is currently running on a computer.

**2. What does the PID column represent?**

PID stands for Process ID. It is a unique number used to identify each running process.

**3. Give two examples of processes that may be running on your computer.**

- Safari
- Visual Studio Code

**Command used:** `ps aux` – Displays running processes and their details.

### Task 3.3 – Understand Paths and Permissions

An **absolute path** gives the complete location starting from the root directory (`/`), while a **relative path** gives the location in relation to the current directory.

**Examples:**
- Absolute path: `/Users/[redacted]/digital-detective-8464/mission-03-operating-system`
- Relative path: `mission-03-operating-system`

**File permissions observed:** `-rw-r--r--`

The owner has read and write permissions but cannot execute the file. Group and others have read-only permission.

**Commands used:** `pwd`, `cd`, `ls -l`

### Task 3.4 – Explain Operating-System Responsibilities

| OS responsibility | Your explanation | Example |
|---|---|---|
| Process management | Manages running programs and CPU time. | Running Safari and VS Code. |
| Memory management | Allocates and manages RAM. | Giving memory to Safari. |
| Device management | Manages connected hardware. | Keyboard and mouse. |
| File management | Organises and manages files and folders. | Creating and renaming files. |
| User interface / shell | Allows users to interact with the computer. | Finder and Terminal. |
| Security and permissions | Controls access to files and resources. | Read and write permissions. |
