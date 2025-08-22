# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## DESIGN STEPS:

### INSTALLING VMware:
Install VMware Workstation Player on your system and download the Kali Linux ISO from its official website.

INSTALLING VMWARE:

Step 1. Download VirtualBox

• Go to: https://www.virtualbox.org/

• Click on the “Downloads” link in the left menu

• Under VirtualBox x.x.x platform packages, click Windows hosts

<img width="1920" height="1080" alt="Screenshot 2025-08-13 090008" src="https://github.com/user-attachments/assets/740c401e-6489-49ff-a3c8-db261d674952" />

Step 2. Run the Installer

• Locate the downloaded .exe file (usually in your Downloads folder)

<img width="1919" height="400" alt="Screenshot 2025-08-13 090303" src="https://github.com/user-attachments/assets/2b476fed-e2c1-4e10-be36-4943295c20c3" />

• Double-click it to run the installer

Step 3. Installer Wizard

• Click Next
<img width="1920" height="1080" alt="Screenshot 2025-08-13 135716" src="https://github.com/user-attachments/assets/39b5b995-3d74-43af-90f0-2832d259a3ad" />


• Keep default settings unless you want to change install location or features

• Click Next

Step 4. Network Interface Warning

• Click Yes to proceed (this may temporarily disconnect your internet)
<img width="1917" height="1079" alt="Screenshot 2025-08-13 090847" src="https://github.com/user-attachments/assets/00de90ee-3e56-488f-b26e-a23223572cf9" />


Step 5. Begin Installation

• Click Install

• If asked for permission by User Account Control (UAC), click Yes
<img width="1919" height="1078" alt="Screenshot 2025-08-13 092450" src="https://github.com/user-attachments/assets/5537a649-14c9-4fe4-98e0-19dc5952ebbc" />


Step 6. Finish Setup

• Click Finish

• VirtualBox will launch (if the checkbox is ticked)
<img width="1920" height="1080" alt="Screenshot 2025-08-13 092610" src="https://github.com/user-attachments/assets/c44f9468-be86-4f8a-a750-a67195270a8e" />


### INSTALLING KALI LINUX:

Create a new virtual machine in VMware using the Kali Linux ISO, configure the hardware settings, and complete the installation of Kali Linux.

Step 1: Open Oracle VirtualBox

• After installing VirtualBox, open it.

• The main screen of VirtualBox should appear.

Step 2: Download Kali Linux VirtualBox Image

• Go to:

https://cdimage.kali.org/kali-2024.4/kali-linux-2024.4-virtualbox-amd64.7z

• Download the .7z file (Kali Linux VirtualBox image)
<img width="569" height="229" alt="Screenshot 2025-08-13 093527" src="https://github.com/user-attachments/assets/c4af96e1-f93f-417c-80f0-b6a4945e1d6f" />


Step 3: Extract the File

• Use 7-Zip or WinRAR to extract the .7z file:

o Right-click on the downloaded file

o Select "Extract Here" or "Extract to Folder"

• You’ll get a folder containing a .vbox file (VirtualBox Machine Definition File)

Step 4: Import Kali Linux into VirtualBox

• Open VirtualBox

• Click on File → Import Appliance



• Click Choose, then browse to the extracted .vbox file

• Select the .vbox file and click Next

• Keep the default settings as they are

• Click Import Wait for the import process to complete

Step 5: Start Kali Linux

• Once imported, you will see "Kali Linux" in the left panel

• Select it and click Start and the Kali Linux will boot up
<img width="640" height="480" alt="VirtualBox_kalilinux_13_08_2025_13_52_06" src="https://github.com/user-attachments/assets/00a578ff-6ed7-430c-88fa-a2b94846dd7a" />

<img width="1280" height="800" alt="VirtualBox_kalilinux_13_08_2025_09_32_45" src="https://github.com/user-attachments/assets/5a90d8db-7bc7-4414-8d02-f85b815bafc3" />

<img width="1920" height="936" alt="VirtualBox_kalilinux_13_08_2025_13_02_08" src="https://github.com/user-attachments/assets/39ddbcde-f9e4-454a-8c46-cb20872004d0" />
Step 6: Use the Terminal in Kali Linux

• After login (default username: kali, password: kali)

• Open the Terminal (black monitor icon)

• Try the basic Linux commands:
<img width="1920" height="936" alt="VirtualBox_kalilinux_13_08_2025_09_34_43" src="https://github.com/user-attachments/assets/8bb312e4-3a59-42d7-b96e-c1ee73e98698" />



### INSTALLING SLEUTH KIT:

Open the terminal in Kali Linux and run the command sudo apt install sleuthkit to install Sleuth Kit.

• Download Sleuth Kit from www.sleuthkit.org/sleuthkit/download.php
<img width="1920" height="1080" alt="Screenshot 2025-08-13 132851" src="https://github.com/user-attachments/assets/9a7d2d72-a20d-4e8e-8252-608a4f42320b" />


● Move the downloaded folder to the program files.

● Go to the system environment variables.
<img width="1920" height="1080" alt="Screenshot 2025-08-13 133017" src="https://github.com/user-attachments/assets/0f1df15b-3844-43f6-9150-8b2eff8a4e0e" />

<img width="1920" height="1080" alt="Screenshot 2025-08-13 133252" src="https://github.com/user-attachments/assets/f83cddcb-55a9-4c21-bab9-ec48b8d16e3c" />

● Click environment variables.
<img width="1920" height="1080" alt="Screenshot 2025-08-13 133308" src="https://github.com/user-attachments/assets/6c84bc5c-036b-4a49-a3cf-2272d964cbdb" />


● Click the path
● Now add the sleuth kit folder address.
● And the click ok. USING OF SLEUTH KIT:

<img width="1478" height="747" alt="Screenshot 2025-08-13 081112" src="https://github.com/user-attachments/assets/1601c5c2-01c2-4ac5-b211-05b8b04e43d7" />

● Open command prompt and type fls -V to check sleuth kit is installed or
not.
● Lists partition layout
<img width="1920" height="1080" alt="Screenshot 2025-08-13 134030" src="https://github.com/user-attachments/assets/a37171a7-6324-4c35-a9b2-4d1f93ae3969" />



● Lists files and directories
<img width="1920" height="1080" alt="Screenshot 2025-08-13 134409" src="https://github.com/user-attachments/assets/63dabb80-af58-4fad-a754-58e6746a202d" />


These are the some of the commands used in the Sleuth kit.


## OUTPUT:
```
## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.

