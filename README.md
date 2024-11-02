# Install software in a Linux distribution <br> - Software installation in Linux

## Objective

To gain hands-on experience with package management in Linux using the APT package manager. This project demonstrates the ability to install and uninstall applications, such as Suricata and tcpdump, on a Debian-based Linux distribution. By utilizing a virtual machine environment, the goal is to safely practice these skills and enhance understanding of Linux system administration and security.

## Skills Learned
1. Package Management:
    * **Understanding APT:** how to use the Advanced Package Tool (APT) to manage software packages on a Debian-based Linux system.
    * **Installing Packages:** practiced using the apt install command to install new packages, such as Suricata and tcpdump.
    * **Uninstalling Packages:** learned how to use the apt remove command to uninstall packages.
    * **Listing Installed Packages:** used the apt list --installed command to view a list of installed packages.

2. Command-Line Usage:
    * **Basic Command-Line Navigation:** gained experience in using the Linux terminal to navigate directories and execute commands.
    * **Using sudo:** learned how to use the sudo command to elevate privileges and run commands as root.
    * **Reading Command Output:** practiced interpreting the output of commands to understand the installation process and verify successful installation.

3. Security Tool Usage:
    * **Suricata:** learned about the capabilities of Suricata as a network security tool for intrusion detection and prevention.
    * **Tcpdump:** learned about the basic usage of tcpdump for capturing and analyzing network traffic.

4. Problem-Solving:
    * troubleshoot issues that may arise during package installation and uninstallation.
    * learned to verify the successful installation of packages by checking their presence in the package list.

## Tools Used

* **Advanced Package Tool (APT)**

* **sudo**

* **Linux Terminal**

* **Virtual Machine**

### Specific Tools Installed:
* **Suricata**

* **Tcpdump** 

## Steps

**1. Ensure that APT is installed**
* Confirm that the APT package manager is installed in your Linux environment.

![software install linux 1](https://github.com/user-attachments/assets/d98156ee-626f-4e40-a5a0-cb298e752028)
<br>

APT is already installed by default in the Linux Bash shell in this lab because this is a Debian-based system. APT is also the recommended package manager for Debian.

**2. Install and uninstall the Suricata application**

  1. install Suricata

![software install linux 2](https://github.com/user-attachments/assets/30d46c23-062a-4cb2-a091-b0c126492b26)
<br>

  2. verify that it is installed correctly

![software install linux 3](https://github.com/user-attachments/assets/bcfd22ad-367d-4a8c-808f-6d59c4949a3e)
<br>

  3. uninstall the application.

![software install linux 4](https://github.com/user-attachments/assets/060e1eac-8c06-469f-99d3-0fa713062cd7)
<br>

  4. verify that it is uninstalled correctly

<![software install linux 5](https://github.com/user-attachments/assets/1e652edd-c782-4816-ae16-dd749235a149)
br>

**3. Install the tcpdump application**

* Use the APT package manager to install tcpdump.

![software install linux 6](https://github.com/user-attachments/assets/b8c8b5b0-89f9-4c4e-9e47-c86c0274bb91)
<br>

**4. List the installed applications**

  1. Use the APT package manager to list all installed applications.

![software install linux 7](https://github.com/user-attachments/assets/0ebe298c-946b-4045-bcde-37dc708ba104)
<br>

  2. Search through the list to find the tcpdump application you installed.

![software install linux 8](https://github.com/user-attachments/assets/b886eb34-64a3-4e1a-8d35-d41cb5a4695a)
<br>

**5. Reinstall the Suricata application**

  1. Run the command to install the Suricata application.

![software install linux 9](https://github.com/user-attachments/assets/8a08865c-9b2d-41ec-b937-3edc59b7cd8d)
<br>

  2. Use the APT package manager to list the installed applications.

![software install linux 10](https://github.com/user-attachments/assets/f33e4e61-5941-4d49-870f-cf4ebf9a2fad)
<br>

### Summary

The lab primarily utilized the Advanced Package Tool (APT), a powerful package management system for Debian-based Linux distributions. APT streamlined the installation and removal of the Suricata intrusion detection system and tcpdump packet analyzer. These tools are essential for network security analysis and monitoring. The lab was conducted within a virtual machine environment, providing a safe and controlled space to practice these skills. By completing this lab, hands-on experience in managing software packages on a Linux system was gained; a crucial skill for any cybersecurity professional.
