# ZygnalBot-Launcher
The launcher for my Discord bot, ZygnalBot — which is highly customizable — essentially serves as a framework to load other cogs and Extensions

### Showcase: https://www.youtube.com/watch?v=_1UChwgQuzw

# ZygnalBot Launcher

**ZygnalBot Launcher** is a powerful desktop application for managing, configuring, and extending your ZygnalBot Discord bot. It provides a user-friendly interface for setup, updates, environment configuration, extension management, and more.

---

## Main Tabs & Features (Based on Actual Code)

### 1. **ZygnalBot Tab (Home)**
- **Latest Version Indicator:** Shows if you have the latest ZygnalBot version.
- **Download Button:** Download ZygnalBot to your specified location.
- **Integrity Check:**
  - Button opens a modal with options:
    - Check integrity only (shows changes, asks before replacing)
    - Instantly replace old/outdated files
    - Skip `.env` files, skip `data` folder, skip `extensions` folder
- **Update Management:** Notifies if an update is available and allows updating.

### 2. **Launcher Tab**
- **Quick Start:**
  - Instantly launch any detected ZygnalBot installation in a new terminal window (runs in background, launcher can be closed).
  - Rename, delete, or open the folder of any Quick Start entry.
- **Step-by-Step Setup:**
  - **Python Setup:** Install Python 3.12.7, add to PATH, check installation.
  - **Select ZygnalBot Folder:** Choose the folder containing your bot.
  - **Virtual Environment:** Optionally set up a venv and install requirements.
  - **Configure .env:** Use the Env Creator or edit manually.
  - **Launch Bot:** Start with venv or global Python.
  - **Status Tracking:** See if each step is ready, warning, or error.

### 3. **Discord Tab**
- **Discord Integration:**
  - Set up your own Discord application (Client ID/Secret), log in, and see your profile and servers.
- **Bot Invite Generator:**
  - Select a Quick Start installation, generate invite links (simple or advanced), select permissions and scopes.
- **Server List:**
  - View your servers, filter, and invite the bot directly if you have permissions.
- **Session Info:**
  - See your Discord token/session, expiration, and scopes.
- **Config Management:**
  - Save, rename, delete Discord integration configs.

### 4. **Env Creator Tab**
- **Step-by-Step Wizard:**
  - Enter all required and optional settings for your `.env` file (Discord Token, Bot Owner ID, Command Prefix, Trusted Guilds, Whitelisted Bots, Logging, API Keys, etc).
  - Each field has help buttons and validation.
- **Save Options:**
  - Download the `.env` file
  - Copy to clipboard
  - Save directly to your bot directory (if selected)
- **Review:**
  - Preview your `.env` before saving, with sensitive data masked.
- **Progress Bar:**
  - Visual stepper shows your progress.
- **Help Content:**
  - Inline help for each field (how to get Discord token, user ID, etc).

### 5. **Extensions Tab**
- **Browse Extensions:** Loads from the ZygnalBot API, shows all available extensions.
- **Search:** Filter extensions by name.
- **Set Download Path:** Choose where to save extensions.
- **Install All:** One-click install for all extensions to the selected path.
- **Manual Download:** Download individual extensions.
- **View Details:** See version, file type, release date, status, and markdown-formatted details for each extension.
- **Progress Modal:** Shows download progress for each extension.

### 6. **Notes Tab**
- **System Notes:**
  - Shows important info and troubleshooting tips.
  - Main command: `!panel` (access all bot features)
  - Update/export/import config instructions
  - Ticket system troubleshooting
  - Requirements for server images, bot images, etc.
- **Fallback Notes:**
  - If notes can't be loaded, fallback HTML is shown with the above info.

### 7. **Settings Tab**
- **Theme:** Choose from Dark, Light, Midnight, Forest, Ocean, or set custom colors.
- **Language:** English, German, French, Spanish.
- **Download Settings:** Set download location, auto-extract after download.
- **Startup:** Start with Windows, start minimized.
- **Notifications:** Enable/disable update/download/extraction notifications, play sound, use native notifications.
- **Cache:** Clear download cache, auto-clear, keep previous versions.
- **Shortcut:** Create/recreate desktop shortcut.
- **Save/Reset:** Save or reset all settings to default.

### 8. **Credits Tab**
- **Development Team:** Lists owner, lead dev, coding, design.
- **Support:** Info on how to support ZygnalBot (donate, etc).
- **Version and Copyright**

---

## Getting Started
1. Download and run the launcher.
2. Use the Guide tab for first-time setup.
3. Configure your bot with the Env Creator.
4. Download extensions as needed.
5. Launch ZygnalBot from the ZygnalBot tab or Quick Start.

---

## Support
For help, see the Guide or Notes tab, or consult the ZygnalBot community. 
