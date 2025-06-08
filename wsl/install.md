Got it! 😎 Here’s the Kali Linux on WSL installation guide and clear steps: 🐧💻


---

🐧 Installing Kali Linux on WSL

<a name="objectives"></a> 🎯 Objectives

> Install Kali Linux on Windows using WSL 2 smoothly and efficiently ✅




---

⚙️ Prerequisites:

Make sure you have:

Windows 10 or 11 with the latest updates installed 📥

WSL 2 feature enabled

A stable internet connection 🌐



---

🧰 Step 1: Enable WSL and Virtual Machine Platform

Open PowerShell as Administrator and run:

dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart

dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart

Then, restart your PC 🔄


---

💻 Step 2: Update WSL to version 2

Install WSL with this command:

wsl --install

Or install Kali Linux directly:

wsl --install -d kali-linux

> [!TIP]
If you face issues, set WSL 2 as default version with:



wsl --set-default-version 2


---

🐉 Step 3: Install Kali Linux

If not installed via command line, install Kali from the Microsoft Store:

1. Open Microsoft Store 🏬


2. Search for Kali Linux


3. Click Install and wait for it to finish




---

⚡ Step 4: Initial Kali Linux setup

Open Kali Linux for the first time, it will ask you to create:

A username

A password


> [!IMPORTANT]
Remember your password! 🔐




---

🧪 Step 5: Update Kali Linux

Run the update commands:

sudo apt update && sudo apt upgrade -y

To install full Kali tools package:

sudo apt install -y kali-linux-default


---

🛠️ Step 6: Running Kali Linux

Start Kali anytime with:

wsl -d kali-linux

Or simply:

kali


---

> [!WARNING]
Make sure your PC BIOS/UEFI virtualization settings are enabled. Otherwise, WSL 2 won’t work 🚫




---

</p>
<h3 align="center">© Copyright 2025 - Kali Linux WSL Guide</h3>
<p align="center">
</p>
---

> 📩 For questions or support contact:
tknohamzacontact@gmail.com



🔗 Follow us on:
Facebook | Instagram | Twitter | Telegram