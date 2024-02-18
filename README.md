# Linux-Basics
    Linux for beginners

<h2>📖A Brief History</h2>

- Created by Linus Torvalds
- Originally a personal project that turned into the Linux kernel
- Made to be open-source

<h2>⚙️Linux Components</h2>

Linux, just like any other operating system, is comprised of a few components.

- User
  - The Linux system is comprised of a user or multiple users.
  - Users are the individuals interacting with the computer itself

- Applications
  - Programs that perform specific tasks within Linux
  - Nano is a text-editor program, which most Linux users will utilize daily.

- Shell
  - Command-line interpreter
  - Allows users to directly communicate with Linux to control their systems

- Filesystem Hierarchy Standard
  - Organizes data within Linux

- Kernel
  - Manages processes and memory for Linux OS
  - Communicates with hardware from commands sent by the Shell
  - Utilizes drivers to enable applications to execute tasks
  - Helps allocate resources to help Linux operate more efficiently

- Hardware
  - Physical components of the computer
    - Central Processing Unit
    - Random Access Memory
    - Hard-Drive
    - Graphics Processing Unit
    - Motherboard
    - Network Card
    - Cooling mechanisms
    - Power Supply
    - Peripherals
   
<h2>💻Linux Distributions</h2>

Linux is an open-source operating system. This means anyone can view the source code and openly manipulate it to create their version of Linux. The following down below are some popular distributions (distros) for Linux.

- Kali Linux
  - Designed for digital forensics and penetration testing

- Ubuntu Linux
  - Widely used in cloud computing

- Parrot Linux
  - User-friendly Linux
  - Portable lab for cybersecurity testing

- Red Hat Enterprise Linux
  - Linux built for enterprise use
  - Subscription Based
  - Popular for a company-based cloud

- CentOS Linux
  - Enterprise based Linux system
  - Discontinued

<h2>Types of Shells</h2>

- Bourne-Again Shell (bash)
- C Shell (csh)
- Korn Shell (ksh)
- Enhanced c shell (tcsh)
- Z shell (zsh)

<h2>Basic Linux Commands</h2>

<h3>File Commands</h3>

- <code>pwd</code> - Prints working directory onto the screen
- <code>ls</code> - Displays all files and directories in current working directory
- <code>cd</code> - Changes the working directory
- <code>cat</code> - Displays contents of a file
- <code>head</code> - Displays the first 10 lines of a file (default)
- <code>tail</code> - Displays the last 10 lines of a file (default)
- <code>less</code> - Displays contents of a file one page at a time
- <code>grep</code> - Searches specified file and returns all lines in the file containing a specified string
- <code>find</code> - Searches for directories and files that meet specific criteria
- <code>-mtime</code> - Returns all files and directories that have been modified within a specific time frame (days)
- <code>-mmin</code> - Returns all files and directories that have been modified within a specific time frame (minutes)

<h3>File Changes Commands</h3>

- <code>mkdir</code> - Creates a new directory
- <code>rmdir</code> - Removes a directory
- <code>touch</code> - Creates a new file
- <code>rm</code> - Removes a file
- <code>mv</code> - Moves a file or directory to a new location
- <code>cp</code> - Copies a file or directory into a new location

<h3>File Permissions Commands</h3>

- <code>ls -l</code> - Displays permissions to files and directories
- <code>ls -la</code> - Displays permissions to files and directories including hidden files
- <code>chmod</code> - Changes permissions on files and directories
  - Example: <code>chmod u+r,g+w,o-x file1</code>
    - <code>chmod u+r</code> - Enables read permissions for user for file1
    - <code>chmod g+w</code> - Enables write permissions for group for file1
    - <code>chmod o-x</code> - Removes execute permissions for other for file1
- <code>chown</code> - Changes ownership of a file or directory

[Example](https://docs.google.com/document/d/1LoaR8h0OYzDMc0BUhDhH7RZgBG9Nz2N7KMabH7NpO8M/edit?usp=sharing&resourcekey=0-hvX9-80lSFVG6OWt5BB6wQ)

<h3>User Management Commands</h3>

- <code>sudo</code> - Allows user to have root privileges for a command
- <code>sudo su</code> - Allows user to have root privileges for multiple commands
- <code>sudo adduser</code> - Adds another user to the system
- <code>sudo deluser -r</code> - Deletes user and their files/directories
- <code>finger</code> - Displays all information of all users logged in
- <code>finger username</code> - Displays information on specific user
- <code>last</code> - Shows recent logins
