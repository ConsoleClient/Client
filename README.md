# Console Client

A modern desktop GUI for keeping your Minecraft AFK accounts online – with real Microsoft authentication, proxy support, and Discord webhook alerts.

<p align="center">
  <img src="https://cravatar.eu/helmhead/Console/256.png" alt="Console Client logo" width="96">
</p>

<p align="center">
  <strong>Windows AFK client for Minecraft alts, farms, queue bots, and utility accounts.</strong><br>
  <a href="https://consoleclient.com">Website</a> ·
  <a href="https://consoleclient.com/tos/">Terms of Service</a>
</p>

<p align="center">
  <a href="#-features">Features</a> ·
  <a href="#-download--install">Download</a> ·
  <a href="#-quickstart">Quickstart</a> ·
  <a href="#-requirements">Requirements</a> ·
  <a href="#-faq--best-practices">FAQ</a>
</p>

## ✨ Features

- **Multi-account dashboard**
  - Central view of all your AFK accounts
  - Per-account status badges (`Connected`, `Idle`, etc.)
  - One-click **Connect**, **Stop**, and **Connect All**

- **Real Microsoft authentication**
  - Uses proper Microsoft account login flow
  - Works with migrated Java accounts
  - Keeps your main game and launcher untouched

- **Proxy support**
  - Per-account SOCKS5 proxy host, port, username, and password
  - Grouped proxy view for quick overview
  - Helps spread traffic across different IPs

- **Discord webhook integration**
  - Events: join, disconnect, death, kicked, error
  - Optional `@everyone` on a per-event basis
  - Customizable message templates with placeholders (email, username, reason, time, proxy)

- **AFK-focused design**
  - Ideal for farms, spawners, queue bots, and utility alts
  - Built for long-running uptime
  - Console log window with live output and linkified URLs

- **Simple config**
  - JSON config and account files stored next to the executable
  - Easy to back up and move between machines

## 📦 Download & Install

1. **Go to the Releases tab**  
   Open the Releases page of this repository and download the latest Windows build  
   (for example: `ConsoleClient-win64.zip`).

2. **Extract the zip**  
   Right-click the zip → **Extract All…** and choose a folder, such as:
   - `C:\ConsoleClient`
   - or your Desktop

3. **Run `ConsoleClient.exe`**  
   Inside the extracted folder, double-click `ConsoleClient.exe`.

   If Windows SmartScreen shows a warning:
   - Click **More info**
   - Click **Run anyway**

4. **Pin it for quick access**  
   Right-click the running app in the taskbar → **Pin to taskbar**.

## 🚀 Quickstart

Get your first bot online in a couple of minutes.

### 1. Configure the server

1. Open the **Config** tab.
2. Set **Server Host** to your server address  
   e.g. `mc.consoleclient.com`
3. Set the **Port** to your server’s port (usually `25565`).
4. Set **Minecraft Version** to the server backend version  
   e.g. `1.21.10`
5. Set **Join Command**  
   e.g. `/afk`, `/spawn`, or any command you want to run after joining.
6. Click **Save** to write the config to disk.

### 2. Add an account

1. Go to the **Accounts** tab.
2. Click **Add Account**.
3. Enter your Microsoft email.
4. (Optional) Add SOCKS5 proxy details for that account:
   - Host
   - Port
   - Username / Password

### 3. Complete Microsoft login

When prompted, Console Client will show a link and a one-time code:

1. Open the link in your browser.
2. Paste the code.
3. Sign in with your Microsoft account.
4. Return to Console Client; the account will be ready to use.

### 4. Connect the bot

1. Open the **Dashboard** tab.
2. Click **Connect** next to an account  
   or **Connect All** to start every configured account.
3. Use the **Chat** tab to talk in-game as your bots.
4. Use the **Console** tab to monitor log output, disconnect reasons, and reconnect attempts.

---

## 🖥 Requirements

**Operating system**

- Windows 10 or Windows 11 (64-bit)

**Hardware**

- A few GB of free RAM if you plan to run multiple accounts
- Stable, low-packet-loss internet connection
- A few MB of disk space for logs and configs

**Minecraft**

- Java accounts migrated to Microsoft
- Server address (for example: `mc.consoleclient.com`)
- Server backend version (for example: `1.21.10`)

**Optional**

- SOCKS5 proxies for accounts
- Discord webhook URL for alerts
