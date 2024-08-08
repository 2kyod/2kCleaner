# DeepClean2kyoo

DeepClean2kyoo is a powerful batch script designed to automate the cleaning and maintenance of various system directories and services on a Windows machine. This script aims to improve system performance and security by removing unnecessary files, disabling unwanted services, and cleaning up logs and caches.

## Features

- **Automated Cleanup**: The script performs a thorough cleanup of various system directories and services.
  - Deletes Windows Defender scans.
  - Cleans Xbox services and disables related tasks.
  - Updates the hosts file to block specific domains.
  - Removes various registry keys and directories.
  - Disables Windows Defender real-time protection.
  - Cleans Discord cache and other application logs.
  - Cleans event logs and system root history.

- **Administrator Permissions**: The script requests and ensures administrator permissions to perform the necessary cleanup tasks.

- **Logging**: All actions performed by the script are logged in a `cleanup_log.txt` file for review.

- **IObit Unlocker Integration**: The script uses IObit Unlocker to handle and delete files that are locked or in use.

## Usage

1. **Run as Administrator**: Ensure the script is executed with administrator privileges.
2. **Follow Prompts**: Follow the on-screen prompts and click OK for any IObit Unlocker notifications.
3. **Review Logs**: Check the `cleanup_log.txt` file for a detailed log of the actions performed.

## Credits

This script leverages the powerful tool **IObit Unlocker** to manage and delete locked files. Credit goes to IObit for providing this essential utility.

## Disclaimer

Use this script at your own risk. It is designed for advanced users who understand the implications of removing system files and registry keys. Ensure you have backups of important data before running the script.
