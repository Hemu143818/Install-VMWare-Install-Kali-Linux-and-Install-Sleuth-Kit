# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
## name:- k hemanth yadav
## reg no:- 212224100033
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## **Design Steps:**

### **Step 1: Install  VirtualBox**

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualBox website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VirtualBox to verify the installation.


### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version
   
## PROGRAM:

## OUTPUT:
**VIRTUAL BOX:**
<img width="1918" height="1088" alt="Screenshot 2025-09-10 084911" src="https://github.com/user-attachments/assets/2c7518d0-2703-4f26-bb37-346af66cbbdd" />


**KALI LINUX:**
<img width="1919" height="1088" alt="Screenshot 2025-09-10 084928" src="https://github.com/user-attachments/assets/e95e6d14-8019-43fa-b7f4-40e9327ef852" />



**SLEUTH-KIT:**
<img width="1835" height="933" alt="Screenshot 2025-09-10 084945" src="https://github.com/user-attachments/assets/d1935417-e009-4630-a945-5c892aea3cc8" />



## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
