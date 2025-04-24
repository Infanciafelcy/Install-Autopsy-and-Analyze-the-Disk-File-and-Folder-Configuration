# Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration
## AIM:
To install Autopsy on Kali Linux and analyze disk images, files, and folder configurations for digital forensic purposes.

## DESIGN STEPS:
### Step 1:
Install Autopsy using the terminal with the command:

### Step 2:
Launch Autopsy from the terminal or application menu and create a new case.

### Step 3:
Add a disk image or file to the case and analyze the contents such as deleted files, metadata, and folder structure.

## PROGRAM:
## Autopsy Installation and Analysis Steps
Install Autopsy (GUI-based Forensic Tool)
🔗 Download Autopsy: Click Here

## Installation Steps:
Download the Autopsy Windows Installer from the official website.
Extract the ZIP file and open the bin folder.
Run autopsy.exe and set up a new forensic case for analysis.
## Install Sleuth Kit (CLI-based Forensic Tools)
🔗 Download Sleuth Kit: Click Here

## Installation Steps:
Download the Windows ZIP package from the official website.
Extract the ZIP folder and move it to a suitable directory (e.g., C:\sleuthkit).
Add the bin folder to Windows PATH:
Open Control Panel → System → Advanced System Settings.
Click Environment Variables → Edit Path.
Add the Sleuth Kit bin folder path and save changes.
Verify installation by running:
fls -version
## Create & Configure a Virtual Hard Disk (VHD) in Windows
Press Win + X, Select Disk Management.
Click Action > Create VHD.
Choose a location and set a disk size (e.g., 10GB+).
Select Fixed Size or Dynamically Expanding and click OK.
In Disk Management, find your new disk (marked as "Not Initialized") -> Right-click the new disk → Initialize Disk → Select MBR.
Right-click Unallocated Space → New Simple Volume → Format the disk -> Click next → Finish.


## OUTPUT:
File and Folder Configuration Analysis Results
![Screenshot 2025-04-06 220942](https://github.com/user-attachments/assets/a306bd6e-f928-4fe5-bf5b-5c33ed6144b2)

## Creation of Virutual Hard disk:
![Screenshot 2025-03-30 214803](https://github.com/user-attachments/assets/f0142075-e27f-4c31-bf0f-0d3340d8c5a9)

![Screenshot 2025-04-07 030042](https://github.com/user-attachments/assets/5798eb1c-3208-4f49-a938-1cf847625efb)

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
