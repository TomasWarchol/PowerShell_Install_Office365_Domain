# Office Removal and Microsoft 365 Installation Script

## Overview

This script automates the process of removing the old Office installation and installing the Microsoft 365 suite on domain computers. It simplifies the entire process, saving valuable time and effort for system administrators.

## Features

- **Removes the old Office installation:** This script ensures the complete uninstallation of any existing Office software before proceeding with the installation of Microsoft 365. This prevents conflicts and compatibility issues.

- **Installs Microsoft 365 suite:** After removing the old Office software, the script initiates the installation of the Microsoft 365 suite from the specified path. This facilitates a seamless transition to the latest version of Office applications.

- **Designed for domain computers:** The script is specifically designed for domain computers, making it ideal for system administrators managing a network of computers within an organization.

## Prerequisites

Before using this script, please ensure that the following prerequisites are met:

- **Access to domain computers:** Execute the script on domain computers where the old Office installation needs to be removed and the Microsoft 365 suite needs to be installed.

- **Microsoft 365 installation files:** Obtain the Microsoft 365 installation files and specify the correct path in the script. Ensure that the installation files are accessible to the script during execution.

## Usage

To use this script with Active Directory policies, follow these steps:

1. **Load the script into the Group Policy Management Console in Active Directory.**

2. **Configure the policy to run the script at user logon.**

3. **Ensure that the Microsoft 365 installation files are available at the specified path mentioned in the script.**

4. **When domain users log in, the script will automatically execute, removing the old Office installation and installing the Microsoft 365 suite.**

## Disclaimer

This script is provided as-is without any warranty. Use it at your own risk. Make sure to thoroughly test it in a non-production environment before deploying it in a live environment.

## Contributions

Contributions to this script are welcome. If you have any improvements or suggestions, feel free to open an issue or submit a pull request.
