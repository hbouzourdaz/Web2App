<h1 align="center">
  <img src="https://img.icons8.com/?size=100&id=64478&format=png&color=4ade80" alt="Logo" width="40" height="40" /> Web2App Converter PRO
</h1>

<p align="center">
  <strong>Transform Any Website or Web-App Into a Premium Windows Desktop Application in Seconds.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-blue" alt="Windows" />
  <img src="https://img.shields.io/badge/Python-3.11+-yellow" alt="Python" />
  <img src="https://img.shields.io/badge/Electron-Powered-47848f" alt="Electron" />
  <img src="https://img.shields.io/badge/License-Proprietary-red" alt="License" />
</p>

<p align="center">
  🌐 <strong>Official Website:</strong> <a href="https://web2-app-hakim.vercel.app/">https://web2-app-hakim.vercel.app/</a>
</p>

<hr>

## 🚀 Overview

**Web2App Converter** is a powerful, standalone desktop utility designed for developers, agencies, and entrepreneurs. It allows you to package any responsive website, CRM, or web application into a fully-fledged, installable Windows `.exe` file without writing a single line of code.

It automatically generates a professional **Setup Installer** powered by NSIS, complete with your custom branding, icons, and automated cache management.

## ✨ Key Features

- **🪄 1-Click Compilation:** Enter a URL, choose an icon, and hit build. The software handles Electron dependencies and compilation in the background.
- **🎨 White-Label Branding:** Customize the installer (`Setup.exe`) with your own `header.png` and `sidebar.png`. The end-user sees your brand, not ours.
- **🌍 Bilingual & RTL Support:** A fully dynamic UI that supports English and Arabic natively, including strict Right-to-Left (RTL) layout adjustments.
- **🌗 Smart Theming:** Built-in Light and Dark modes that automatically sync or can be manually toggled.
- **⚡ Native Performance:** Uses multi-threading and an intelligent local caching system (`cache_workspace`) to make compilation blazingly fast.
- **🔒 Built-in Licensing Engine:** Includes a robust `Free Trial` vs `PRO` licensing system with hidden system-level limits to help you monetize the software.

## 💼 Versions

| Feature | Free Version | PRO Version |
| :--- | :---: | :---: |
| **Max Builds** | 2 Applications | **Unlimited** |
| **Setup Installer** | Included | Included |
| **Custom Icons** | Supported | Supported |
| **White-Labeling** | Limited | **Full Control** |
| **Developer Support** | None | **24/7 Priority** |

## 🛠️ Installation & Usage (For Users)

1. Download the latest `Web2App_Converter_Free_Setup.exe` from the [Releases](#) page.
2. Run the installer and open the software from your Desktop.
3. Type the **Name** of your App and its **URL** (e.g., `https://example.com`).
4. Select your `.ico` or `.png` icon.
5. Click **Generate Setup File**. Within seconds, your new desktop app is ready for distribution!

## 💻 Building from Source (For Developers)

If you have purchased the source code or wish to compile it yourself:

1. Clone this repository.
2. Install the required Python dependencies:
   ```cmd
   pip install -r requirements.txt
   ```
3. Ensure you have Node.js installed (required for the Electron compiler).
4. Run the application:
   ```cmd
   python main.py
   ```
5. To compile the software into an executable, use PyInstaller:
   ```cmd
   pyinstaller --noconsole --onefile --name "Web2App_Converter" --icon="icon.ico" "main.py"
   ```

## 📞 Contact & Support

Developed by **Hakim BOUZOURDAZ**.
For business inquiries, purchasing the PRO version, or custom modifications, contact me via:

- **Website:** [https://web2-app-hakim.vercel.app/](https://web2-app-hakim.vercel.app/)
- **WhatsApp:** [Click Here to Chat](https://wa.me/213549523594)

---
*Built with ❤️ using Python, CustomTkinter, and Electron.*
