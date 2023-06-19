
Office Removal and Microsoft 365 Installation Script
Overview
This script is designed to simplify the process of removing the old Office installation and installing the Microsoft 365 suite on domain computers. It automates the entire process, saving time and effort for system administrators.

Features

Removes the old Office installation: The script ensures that any existing Office software is completely uninstalled before proceeding with the installation of Microsoft 365. This helps avoid conflicts and compatibility issues.

Installs Microsoft 365 suite: Once the old Office software has been removed, the script initiates the installation of the Microsoft 365 suite from the specified path. This ensures a seamless transition to the latest version of Office applications.

Designed for domain computers: The script is specifically tailored for use on domain computers, making it ideal for system administrators managing a network of computers within an organization.

Prerequisites
Before using this script, ensure that the following prerequisites are met:

Access to domain computers: The script should be executed on domain computers where the old Office installation needs to be removed and the Microsoft 365 suite needs to be installed.

Microsoft 365 installation files: Obtain the Microsoft 365 installation files and specify the correct path in the script. Ensure that the installation files are accessible to the script during execution.

Usage
To use this script with Active Directory policies, follow these steps:

Load the script into the Group Policy Management Console in Active Directory.

Configure the policy to run the script at user logon.

Ensure that the Microsoft 365 installation files are available at the specified path mentioned in the script.

When domain users log in, the script will automatically execute, removing the old Office installation and installing the Microsoft 365 suite.

Disclaimer
This script is provided as-is without any warranty. Use it at your own risk. Make sure to test it thoroughly in a non-production environment before deploying it in a live environment.

Contributions
