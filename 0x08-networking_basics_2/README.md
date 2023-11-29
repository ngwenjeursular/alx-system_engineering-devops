# Networking Basics Project - 0x08

## Overview
This project, part of the DevOps curriculum, extends the knowledge gained in Networking Basics #0.
The focus is on understanding localhost, 0.0.0.0, the hosts file, and practical network operations using Bash scripts.

## Timeline
- **Project Start:** Nov 29, 2023 6:00 AM
- **Project End:** Dec 1, 2023 6:00 AM
- **Checker Release:** Dec 1, 2023 6:00 AM
- **Auto Review:** A review will be launched automatically at the deadline.

## Resources
Read or watch materials related to the following topics:

- What is localhost
- What is 0.0.0.0
- What is the hosts file
- Netcat examples

Refer to the `man` or `help` commands for:
- ifconfig
- telnet
- nc
- cut

## Learning Objectives
By the end of this project, you are expected to:

1. Explain the concepts of localhost (127.0.0.1) and 0.0.0.0.
2. Understand the purpose and content of the `/etc/hosts` file.
3. Display active network interfaces on a machine using `ifconfig`.
4. Develop Bash scripts to configure IP resolutions and show attached IPv4 addresses.
5. Create a Bash script to listen on a specified port using netcat.


## Requirements
- **Allowed Editors:** vi, vim, emacs
- **Interpreted On:** Ubuntu 20.04 LTS
- **File Endings:** All files should end with a new line
- **Executable Scripts:** All Bash script files must be executable
- **Shellcheck:** Scripts must pass shellcheck (version 0.7.0 via apt-get) without any errors
- **Shebang:** The first line of all Bash scripts should be exactly `#!/usr/bin/env bash`
- **Comments:** The second line of all Bash scripts should be a comment explaining the script's purpose

## Tasks

### 0. Change your home IP
[0. Change your home IP](0-change_your_home_IP)
Configure an Ubuntu server to change IP resolutions for localhost and facebook.com.

#### Requirements:
- localhost resolves to 127.0.0.2
- facebook.com resolves to 8.8.8.8

### 1. Show attached IPs
[Show attached IPs](1-show_attached_IPs)
Write a Bash script that displays all active IPv4 IPs on the machine it’s executed on.

### 2. Port listening on localhost (Advanced)
[Port listening on localhost](100-port_listening_on_localhost)
Write a Bash script that listens on port 98 on localhost.
