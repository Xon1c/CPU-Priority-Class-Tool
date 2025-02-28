# Registry Folder and Value Creator Script

This batch script creates a registry folder inside `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\`, named after the user-defined input. The script also creates a subfolder called `PerfOptions` and adds a `DWORD` value called `CpuPriorityClass` with a value of `3`.

## Features

- Prompts the user for an executable name (example :  `FortniteClient-Win64-Shipping.exe`).
- Creates a folder named after the input executable in the registry path:
  `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\`.
- Creates a subkey `PerfOptions`.
- Adds a `DWORD` value `CpuPriorityClass` with the value `3` inside the `PerfOptions` key.

## Prerequisites

- **Administrator Privileges:** The script modifies the registry, which requires elevated permissions.
- **Windows OS:** This script is designed for use on Windows operating systems.

## Usage

1. Download or clone the repository.
2. Open a text editor and paste the script into a new `.bat` file (e.g., `create_reg_key.bat`).
3. Right-click the `.bat` file and select **Run as Administrator**.
4. When prompted, enter the name of the executable 
5. The script will create the registry folder and set the appropriate value.

This Script Was Made For Gaming Mostly To Set Programs That Might Not Want To Let You Set Their Priority Class to high, like an anticheat thing or idk

Made By Xon1c

