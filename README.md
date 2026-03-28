# Open Source Audit Project

## Student Details

Name: Aiswarya Rajesh
Roll Number: 24MEI10014

## Chosen Software

Python

## Project Description

The project includes the analysis of open-source software such as Python, its origin, use of Linux with Python, the ecosystem of open-source software, and comparison with proprietary software. Shell scripts are also included for practical knowledge of Linux operating systems.

---
## Scripts Description

### Script 1 – System Identity Report

The purpose of this script is to offer a basic system report, essentially a welcome screen. This information may include, but not be limited to, the Linux distribution, kernel, currently logged-in user, home directory, system up time, and system date.

### Script 2 – FOSS Package Inspector

This script checks for the availability of Python on the system by running package management commands. If Python is installed, it displays vital information such as version and description of the package. It also uses a case statement to provide a short description of the package.

### Script 3 – Disk and Permission Auditor

This script checks various essential system directories such as /etc/, /var/log/, and /home/. It uses a loop to go through each of these directories and show essential information such as the directory’s size, permissions, and ownership.

### Script 4 – Log File Analyzer

This script reads the file line by line, counting the number of times the keyword repeats. It does this using a while loop and if statement. It also makes use of the counter variable to keep track of the repetition of the keyword.

### Script 5 – Open Source Manifesto Generator

This script requires the user to input values for three different variables, then it generates the manifesto based on the input values. It stores the output in a file, appending the current date.

---

## How to Run the Scripts

### Step 1: Open Terminal

We need to open a terminal and go to the directory where our scripts are located.
cd path/to/your/scripts

### Step 2: Give Permission
We need to make your scripts executable by giving execute permission.

chmod +x script1.sh
chmod +x script2.sh
chmod +x script3.sh
chmod +x script4.sh
chmod +x script5.sh

### Step 3: Execute Scripts

We need to execute our scripts.
./script1.sh
./script2.sh
./script3.sh
./script4.sh
./script5.sh

---
## Dependencies

* Linux OS – Kali Linux or Ubuntu
* Bash Shell
* Basic Linux commands – uname, whoami, dpkg, grep, ls, etc.



---
