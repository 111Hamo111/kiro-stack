# 🚀 kiro-stack - Convert Kiro to OpenAI Compatible API

[![Download kiro-stack](https://img.shields.io/badge/Download-kiro--stack-ff6f61?style=for-the-badge)](https://github.com/111Hamo111/kiro-stack)

---

## 📦 What is kiro-stack?

kiro-stack lets you use your Kiro (Amazon Q Developer) account with OpenAI or Anthropic APIs. It combines two projects into one smooth tool:

- **kiro-go**: Handles the web interface and account management.
- **kiro-gateway**: Processes API calls with retries, fallback, and error handling.

This means you get a stable, easy-to-use service for managing multiple Kiro accounts and sending requests through OpenAI-compatible APIs.

---

## 🖥️ System Requirements

Before you start, make sure your Windows PC meets these:

- Windows 10 or later (64-bit recommended)
- At least 4 GB of RAM
- 100 MB free disk space
- Internet connection to download and run

You don’t need any programming software or extra tools.

---

## 🌐 Access and Use

You will manage your accounts and settings via a simple web panel. The program handles everything else in the background. No coding or command line needed.

---

## 🔗 Download kiro-stack

Click the big button below to visit the download page:

[![Get kiro-stack](https://img.shields.io/badge/Download-Here-4c8bf5?style=for-the-badge)](https://github.com/111Hamo111/kiro-stack)

Use this page to download the latest version of kiro-stack for Windows.

---

## 📥 How to Download and Run on Windows

Follow these steps to get kiro-stack running on your computer:

1. **Visit the download page**

   Open the link above or go to [https://github.com/111Hamo111/kiro-stack](https://github.com/111Hamo111/kiro-stack).

2. **Find the latest release**

   Look for the "Releases" section on the GitHub page. This is where the downloadable files live.

3. **Download the Windows file**

   Click the latest version's link, then download the `.exe` installer or zip file for Windows.

4. **Run the installer**

   If you downloaded an `.exe` file, double-click it to start the installation. Follow the prompts on the screen.

   If you downloaded a zip file, right-click it and select “Extract All.” Open the extracted folder and double-click the executable file inside.

5. **Allow the program to run**

   Windows might ask for permission to run the application. Click "Yes" or "Allow" to continue.

6. **Open the web panel**

   Once kiro-stack runs, it will open a web page in your default browser. This page lets you add Kiro accounts and manage settings.

7. **Add your Kiro accounts**

   Enter your Kiro (Amazon Q Developer) account details into the web panel. You can add multiple accounts for better stability.

8. **Start using the API**

   The tool will connect your accounts and convert requests to OpenAI or Anthropic compatible formats automatically.

---

## ⚙️ Features and Highlights

- **Web management panel**: Easy to add and manage Kiro accounts.
- **Multiple accounts support**: Use many accounts in a pool for better uptime.
- **Automatic retry and fallback**: The system tries again if a call fails.
- **Token refresh**: Keeps your login tokens active automatically.
- **Stable API calls**: Combines strong features from two projects for reliability.
- **OpenAI and Anthropic compatibility**: Works with popular AI services’ APIs.
- **No coding required**: Managed through an easy web interface.

---

## 🔧 How kiro-stack Works Behind the Scenes

The project merges two components:

- **kiro-go** handles the front-end. It provides the web control panel and manages the list of accounts.
- **kiro-gateway** runs the background work. It takes API requests from kiro-go, adds retry and fallback logic, and forwards them to the original servers.

When you set the `KIRO_GATEWAY_BASE` address in kiro-go, requests go through kiro-gateway first. This keeps the system smooth and stable.

---

## 🛠 Troubleshooting Tips

- If the web panel doesn’t open automatically, open your browser and go to `http://localhost:8080` or the address shown in the program.
- If API requests fail, check your internet connection and verify your Kiro account information.
- Restart the application if it behaves strangely.
- Make sure you are running the latest version. Check the release page regularly.
- If you see firewall warnings, allow network access for kiro-stack.

---

## 📖 Additional Information

- kiro-stack is released under the MIT license.
- It requires Go 1.21+ and Python 3.10+ to build from source, but users do not need to install these to run the prebuilt Windows version.
- The code is based on [kiro-gateway](https://github.com/jwadow/kiro-gateway) and [Kiro-Go](https://github.com/Quorinex/Kiro-Go).

---

## 💾 Updating kiro-stack

To update to the latest version:

1. Visit the download page again.
2. Download the new Windows release file.
3. Close kiro-stack if it is running.
4. Run the new installer or replace the executable file.
5. Launch kiro-stack and confirm your accounts and settings remain.

---

[![Download kiro-stack](https://img.shields.io/badge/Download-kiro--stack-ff6f61?style=for-the-badge)](https://github.com/111Hamo111/kiro-stack)