# Linux Software Installation Lab

## Introduction
In this lab, you’ll learn how to install and uninstall applications in Linux Ubuntu and the Advanced Package Tool (APT) package manager. You'll specifically work with the Suricata and tcpdump applications, essential for network security analysis.

## Activity Overview
This lab guides you through installing and uninstalling applications in Ubuntu using APT and sudo. It highlights the convenience of the APT package manager in managing software complexities, especially in a Linux environment. The lab focuses on network security applications like Suricata and tcpdump, crucial for analyzing and capturing network traffic.

## Scenario
As a security analyst, you need to have Suricata and tcpdump installed on your system. The scenario involves installing, uninstalling, and reinstalling these applications in your Linux Bash shell. You'll also confirm their correct installation.

## Tasks
### Task 1: Ensure APT Installation
Check if the APT package manager is installed in your Linux environment by running the `apt` command in the Bash shell.

### Task 2: Install and Uninstall Suricata
- Install Suricata using the APT package manager (`sudo apt install suricata`).
- Verify the installation by running the `suricata` command.
- Uninstall Suricata using `sudo apt remove suricata`.

### Task 3: Install the tcpdump Application
Install tcpdump, a network traffic capturing tool, using the APT package manager (`sudo apt install tcpdump`).

### Task 4: List Installed Applications
Confirm the installation of required applications by listing all installed applications using the APT package manager (`apt list --installed`).

## Conclusion
This lab underscores the significance of efficient software management in a Linux environment, particularly for security analysts requiring essential network monitoring tools like Suricata and tcpdump.

