Open Source Software Audit Project
Project Overview

This repository showcases my Open Source Software audit project completed as part of the Open Source Software course at VIT Bhopal. The main goal of this project is to study how open-source software operates within a Linux environment and to gain insight into its philosophy, ecosystem, and internal structure.

For this audit, I choose Python as the primary software to analyze. Python is among the most popular programming languages globally, known for its clean syntax, ease of learning, and strong community-driven development.

Throughout this project, I explored how Python exists within a Linux system and developed a series of shell scripts to examine system details, installed software, file permissions, log data, and open-source principles.

Selected Open Source Software

Software Name: Python
Category: Programming Language
License: Python Software Foundation License (Open Source)

Python was developed by Guido van Rossum and released in 1991. It was created with a focus on simplicity and readability, making it highly accessible to developers.

Over time, Python has become widely used in various domains such as:

Software development
Data science
Artificial intelligence
Web development
Automation and scripting

Since Python is open-source, developers across the globe can contribute to its improvement and expansion.

Project Objectives

The primary goals of this project include:

Understanding the core principles of open-source software
Studying how an open-source application functions within a Linux system
Gaining practical experience with shell scripting
Exploring system information, installed packages, logs, and directories through scripts
Documenting findings to better understand open-source ecosystems
Repository Structure

This repository consists of multiple shell scripts, each designed to perform specific auditing tasks:

README.md
script1_system_identity.sh
script2_package_inspector.sh
script3_disk_auditor.sh
script4_log_analyzer.sh
script5_manifesto_generator.sh
Script Descriptions
Script 1 – System Identity Report

This script collects and displays essential information about the Linux system in an organized manner.

It retrieves details such as:

Current user
Linux distribution
Kernel version
System uptime
Current date and time

This script shows how basic shell commands can be combined to produce a quick system summary.

Script 2 – FOSS Package Inspector

This script verifies whether Python is installed on the system.

It performs the following tasks:

Detects Python installation
Displays the installed version
Provides a brief description of Python

This ensures that the selected open-source software is present and properly installed.

Script 3 – Disk and Permission Auditor

This script analyzes important Linux directories and reports details such as:

Directory permissions
Ownership (user and group)
Directory size

The directories inspected include:
/etc, /var/log, /home, /usr/bin, /tmp

Script 4 – Log File Analyzer

This script examines Linux log files to identify specific keywords such as “error”.

The script:

Reads log files line by line
Counts keyword occurrences
Displays the most recent matching entries

This demonstrates fundamental log analysis techniques used in system monitoring

Script 5 – Open Source Manifesto Generator

This is an interactive script that creates a personalized open-source philosophy statement.

It prompts the user with three questions:

An open-source tool they frequently use
Their interpretation of “freedom”
What they would like to build for the community

Based on the responses, the script generates a short manifesto and saves it as a text file.

This script emphasizes the collaborative and value-driven nature of open-source software.

Technologies Used
Linux (Ubuntu )
Bash Shell Scripting
Python (audited software)
Git & GitHub for version control

Key Learnings

This project helped me understand several important concepts, including:

1.The organization of Linux file systems
2.How open-source software is installed and maintained
3.The role of automation using shell scripts
4.Basic system auditing practices
5.The collaborative nature of open-source development

It also enhanced my understanding of GitHub and version control systems, which are essential in modern software workflows.

Conclusion

Open-source software is a crucial part of today’s technological landscape. Tools like Python demonstrate how community-driven development can produce powerful and widely adopted solutions.

This audit project provided hands-on experience with Linux environments, scripting, and open-source concepts. It also highlighted the transparency, flexibility, and collaboration that make open-source software highly valuable.
