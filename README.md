# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### Reg.No : 212222100035
### Name : Prakash M
# AIM:
To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.
# DESIGN STEPS:
## Step 1: Install VirtualBox
### Installation Steps:
  1.Download the Windows hosts .exe file from the official VirtualBox website.
  
  2.Run the installer and follow the on-screen instructions.
  
  3.Once installed, launch VirtualBox to verify the installation.

## Step 2: Install Kali Linux on VirtualBox

## Installation Steps:
   1.Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).
   
   2.Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM.
   
   3.Go to Settings > Storage, click Empty under Controller: IDE.
   
   4.Select Graphical Install, follow the prompts to set language, location, username, and password.
   
   5.Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.

## Step 3: Install Sleuth Kit (CLI-based Forensic Tools)
### Installation Steps:
   1.Download the Windows ZIP package from the official website.
   
   2.Extract the ZIP folder and move it to a suitable directory (e.g., C:\sleuthkit).
   
   3.Add the bin folder to Windows PATH:
```
    Open Control Panel → System → Advanced System Settings.
    Click Environment Variables → Edit Path.
    Add the Sleuth Kit bin folder path and save changes.
```
  4.Verify installation by running:
```
fls -version
```
# OUTPUT:
## VIRTUAL BOX :
![image](https://github.com/user-attachments/assets/53715640-9c87-45b5-bc44-1889d817cf53)

# KALI LINUX:
![435602628-9faca712-6391-4934-b1fe-d8bb631defec](https://github.com/user-attachments/assets/4748a22b-e0ba-47db-b5ee-43178b9b06dc)

# SLEUTH KIT:
![435605427-4faf010a-cc96-427d-89cf-ea036f01256d](https://github.com/user-attachments/assets/446519f5-ecc5-41a9-9c4b-a94833e13dcb)

# RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
