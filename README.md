# discord-custom-modaration-bot-open-source-code-by-project-proxi

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Disnake](https://img.shields.io/badge/Disnake-2.9+-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**A fast, customizable, Python Discord moderation bot by Project Proxi**

</div>

---

### **About Project Proxi Mod Bot**
This is a custom Discord moderation bot written 100% in **Python** using the `Disnake` library.
Built to be lightweight, self-hosted, and fully open-source. Think Carl-Bot but you control the code.

Designed to run easily on PC or GitHub Codespaces in 1 click.

### **Features**
- **Slash Commands**: `/timeout`, `/kick`, `/warn`, `/warnings`
- **Permission System**: Only mods/admins can use moderation commands
- **Warning System**: SQLite database to track warns per server
- **Mod Logging**: Logs deleted messages
- **Cog Structure**: Easy to add new features/modules
- **Codespaces Ready**: No install hassle

### **Tech Stack**
| Tech | Purpose |
| --- | --- |
| **Python 3.10+** | Main Language |
| **Disnake** | Discord API Wrapper |
| **aiosqlite** | Async SQLite Database |
| **python-dotenv** | Secure Token Management |

### **Installation & Setup**
1. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
