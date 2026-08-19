# 📶 WiFi Spot - Educational Security Lab

> **Ethically Crafted by [HackSpot](https://github.com/hackspotofficial)**

---

## 🚀 About The Tool
**WiFi Spot** is an educational, terminal-based cybersecurity awareness simulator. It demonstrates how easily a fake WiFi login page (Phishing) can be created to capture credentials locally.

**Key Features:**
- 🎨 **3 Premium Templates:** Free WiFi, Security Scanner, Connection Error.
- 📡 **Live Terminal Capture:** See credentials flash in real-time on your terminal.
- 🌐 **Public Link Support:** Integrated with Cloudflare (`Y/N` option) to generate a public URL.
- 🛡️ **Ethical & Safe:** **No real data is stored.** Fully disclaimed for educational use only.

---

## 📦 Installation (Termux / Linux)

**1. Clone the repository (or download ZIP):**
```bash
pkg update && pkg upgrade -y
pkg install php cloudflared -y
git clone https://github.com/hackspotofficial/wifispot-tool.git
cd wifispot-tool
chmod +x main.sh
bash main.sh
