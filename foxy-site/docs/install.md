

# **Foxy Video Scraping: Real-Time Web Scraping, OCR, Data Labeling & Modeling with Export to Databases and Spreadsheets**

**Foxy** is a versatile tool compatible with **Linux**, **Windows**, and **macOS**. It allows real-time web scraping, OCR (Optical Character Recognition), data labeling, and modeling, with export capabilities to databases and spreadsheets.

### **Tested on:**

- **Linux:** Ubuntu 24.04 LTS
- **Windows:** Windows 11 Professional


## Installation:
    1. Download from this link and unzip the Foxy.zip file.
    2. These are the system folders.
[Foxy Apps Download](https://github.com/FoxySoftware/Foxy/releases/tag/beta_b)

![](https://raw.githubusercontent.com/FoxySoftware/FoxySoftware.github.io/main/resource/file_foxy_win_linux_mac.png)


### In Windows:
Files starting with w correspond to PowerShell commands for Windows.
Run w-foxy-install.ps1 using Windows PowerShell.

### In Linux/macOS:
Use foxy-install.sh. Make sure to set executable permissions for the script before running it.

![](https://raw.githubusercontent.com/FoxySoftware/FoxySoftware.github.io/main/resource/execute_as_program.png)


### Execute the Install Script.
![](https://raw.githubusercontent.com/FoxySoftware/FoxySoftware.github.io/main/resource/install_linux.png)

---

### **Requirements**

Foxy runs inside Docker containers, ensuring that your main operating system remains untouched while keeping your data and other applications secure.

- **Docker:** Ensure that Docker Engine is running.  
  For more information, visit the [Docker Website](https://www.docker.com/).

---

### **Installation Guides**

#### **Windows**

To install Docker on Windows, follow these steps:

1. **Download Docker Desktop:**
   - Visit the [Docker Desktop for Windows](https://docs.docker.com/desktop/install/windows-install/) page and download the installer.
   
2. **Install Docker Desktop:**
   - Run the installer and follow the instructions. This will enable **Hyper-V** and **WSL 2** (Windows Subsystem for Linux) if they are not already enabled.
   
3. **Enable Hyper-V and WSL 2:**
   - Open **Control Panel** → **Programs** → **Turn Windows features on or off**.
   - Check the boxes for **Hyper-V** and **Virtual Machine Platform**.
   - Restart your computer.

4. **Install WSL 2:**
   - Open **PowerShell** as an administrator.
   - Run `wsl --install` to install WSL and set version 2 as the default.
   - Restart your computer if necessary.

5. **Configure Docker Desktop to Use WSL 2:**
   - Open **Docker Desktop**.
   - Go to **Settings** → **General** and ensure "Use the WSL 2 based engine" is enabled.
   - Under **Resources** → **WSL Integration**, enable integration with your Linux distributions.

6. **Verify the Installation:**
   - Open a terminal (cmd, PowerShell, or WSL).
   - Run `docker --version` to confirm Docker is installed correctly.
   - Run `docker run hello-world` to test Docker. You should see a welcome message.

---

#### **Mac OS**

To install Docker on macOS, follow these steps:

1. **Download Docker Desktop for Mac:**
   - Visit [Docker Desktop for Mac](https://docs.docker.com/desktop/install/mac-install/) and download the installer.

2. **Install Docker Desktop:**
   - Open the downloaded `.dmg` file and drag the Docker icon to the **Applications** folder.

3. **Open Docker Desktop:**
   - Go to the **Applications** folder and double-click Docker to start it.

4. **Verify Installation:**
   - Open a terminal and run `docker --version`.
   - Run `docker run hello-world` to verify the installation.

---

#### **Linux**

To install Docker on Linux, refer to the [Docker Linux Install Guide](https://docs.docker.com/desktop/install/linux/).

---

### **Additional Software Requirements**

- **VLC Media Player:**  
  Required for video processing. Download it from [VLC Official Site](https://www.videolan.org/).

- **Image Editors:**
  - **Windows:** Paint
  - **Linux:** Pinta
  - **macOS:** Paintbrush

---

