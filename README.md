# NAME:ROGITH GANESH R
# REGISTER NO: 212223100046
# Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration
## AIM:
To install Autopsy on Kali Linux and analyze disk images, files, and folder configurations for digital forensic purposes.


# DESIGN STEPS:
# Step 1: Install VirtualBox
🔗
Installation Steps:
1.Download the Windows hosts .exe file from the official VirtualBox website.
2.Run the installer and follow the on-screen instructions.
3.Once installed, launch VirtualBox to verify the installation.

# Step 2: Install Kali Linux on VirtualBox
🔗 Download Kali Linux VM: Click Here

Installation Steps:
1.Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).
2.Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM.
3.Go to Settings > Storage, click Empty under Controller: IDE.
4.Select Graphical Install, follow the prompts to set language, location, username, and password.
5.Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.

# Step 3: Install Autopsy (GUI-based Forensic Tool)
🔗 Download Autopsy: Click Here

Installation Steps:
Download the Autopsy Windows Installer from the official website.
Extract the ZIP file and open the bin folder.
Run autopsy.exe and set up a new forensic case for analysis.

# Step 4: Install Sleuth Kit (CLI-based Forensic Tools)
🔗 Download Sleuth Kit: Click Here

Installation Steps:
1.Download the Windows ZIP package from the official website.
2.Extract the ZIP folder and move it to a suitable directory (e.g., C:\sleuthkit).
3.Add the bin folder to Windows PATH:
4.Open Control Panel → System → Advanced System Settings.
5.Click Environment Variables → Edit Path.
6.Add the Sleuth Kit bin folder path and save changes.
7.Verify installation by running:
```
fls -version
```
# Step 5: Create & Configure a Virtual Hard Disk (VHD) in Windows
1.Press Win + X, Select Disk Management.
2.Click Action > Create VHD.
3.Choose a location and set a disk size (e.g., 10GB+).
4.Select Fixed Size or Dynamically Expanding and click OK.
5.In Disk Management, find your new disk (marked as "Not Initialized") -> Right-click the new disk → Initialize Disk → Select MBR.
6.Right-click Unallocated Space → New Simple Volume → Format the disk -> Click next → Finish.

# OUTPUT:
# VIRTUAL BOX:
![image](https://github.com/user-attachments/assets/2668afca-d2e4-44cb-987f-52f1101fde32)

# VIRTUAL Machine(Kali Linux)
![image](https://github.com/user-attachments/assets/7cd5bb13-b5ed-4a4a-9cb8-b90b0dd1de54)

# AUTOPSY
![WhatsApp Image 2025-04-25 at 03 39 59_26c7ccbb](https://github.com/user-attachments/assets/30066df7-3f3f-4ea4-b7fd-9b6b7e5f9a2b)

# Sleuth kit
![WhatsApp Image 2025-04-25 at 03 44 29_788b2086](https://github.com/user-attachments/assets/3b1a068c-aa6b-41a8-9d1f-766e135da179)

# creation of virtual hard disk:
![image](https://github.com/user-attachments/assets/fa31f693-4cb1-45e4-8bf6-722de0cfa95c)



# analysis of images:
![image](https://github.com/user-attachments/assets/9b0b3d1a-9f2c-44d2-8c9c-bb843d0c3ac7)

# click on os account:
![image](https://github.com/user-attachments/assets/f5cf71ae-1c5a-461b-861b-7619c71e3ee6)

# GENERATE REPORTS:
![image](https://github.com/user-attachments/assets/6ad1367c-fe5a-4dfa-8e18-e885391eb47d)
![image](https://github.com/user-attachments/assets/188b8ab6-645a-45c6-9bef-75bc77c71330)
![image](https://github.com/user-attachments/assets/eb229c6c-3883-498c-9297-9a9e8d87255d)






## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
