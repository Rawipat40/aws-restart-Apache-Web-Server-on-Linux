# Setting Up Apache Web Server on Linux

This guide provides a concise overview of setting up an Apache Web Server on a Linux system.

## Prerequisites

- Access to a Linux system (e.g., Ubuntu, CentOS)
- Sudo privileges or root access to install packages
- Basic familiarity with the Linux command line

## Installation

1. **Update Package Repository:**

    Update the package repository.

    ```bash
    sudo apt update
    ```

    or

    ```bash
    sudo yum update
    ```

2. **Install Apache:**

    Install Apache using the appropriate package manager.

    For Ubuntu/Debian:

    ```bash
    sudo apt install apache2
    ```

    For CentOS/RHEL:

    ```bash
    sudo yum install httpd
    ```

3. **Start and Enable Apache Service:**

    Start and enable the Apache service.

    For Ubuntu/Debian:

    ```bash
    sudo systemctl start apache2
    sudo systemctl enable apache2
    ```

    For CentOS/RHEL:

    ```bash
    sudo systemctl start httpd
    sudo systemctl enable httpd
    ```

4. **Verify Installation:**

    Access the default landing page to verify the installation.

## Configuration

- **Basic Configuration:**

    Edit Apache's main configuration file.

- **Virtual Hosts:**

    Create and enable virtual host configuration files.

- **Firewall Configuration:**

    Allow HTTP traffic through the firewall.

## Usage

1. **Manage Apache Service:**

    Use systemctl commands to manage the Apache service.

2. **Place Web Content:**

    Place web content in the default web root directory.

3. **Monitor Logs:**

    Monitor access and error logs for troubleshooting and monitoring purposes.

## What I Have Learned

Through this task, I have gained the following knowledge:

- Understanding of how to install and configure the Apache Web Server on a Linux system.
- Familiarity with basic Apache configuration options such as virtual hosts and firewall settings.
- Ability to manage the Apache service using systemctl commands.
- Experience in monitoring Apache logs for troubleshooting and monitoring purposes.

## 

![Apache-Web-Server-on-Linux1](https://github.com/Rawipat40/aws_restart-Apache-Web-Server-on-Linux/assets/141838218/35212b91-521e-4228-b85a-d4af62338eb9)

![Apache-Web-Server-on-Linux2](https://github.com/Rawipat40/aws_restart-Apache-Web-Server-on-Linux/assets/141838218/bf0ca87e-d3d9-49bb-ac1b-c731d10efed4)
