# 🦊 KITSUNE v1.0 - Firepower Edition

**KITSUNE** is a high-performance, modular Layer 4 and Layer 7 **DDoS testing tool** developed for educational and research purposes. Designed with speed, stealth, and flexibility in mind, KITSUNE empowers cybersecurity researchers, red teamers, and ethical hackers to simulate and study the impact of various denial-of-service strategies in controlled environments.

---

## 🚀 Features

- ✅ **Layer 4 & Layer 7 DDoS Modules**
- 🌐 **Cloudflare Bypass** via `cloudscraper`
- 🧠 **Dynamic Attack Mode Suggestion System**
- 🦾 **Multiple Attack Modes**, including:
  - Random URI Flood
  - Slowloris
  - User-Agent Swarm
  - Cache Bypass Flood
  - POST Data Flood
  - Cookie Bomb
  - Random Method Flood
  - Referer Spam
  - HEAD Flood
  - Headless Browser Flood (Planned)
- 📊 **Real-Time Stats Dashboard**
- 🌍 **Rotating Proxies** & **User-Agent Spoofing**
- 🔐 **Botnets & OSINT Scraping (Coming Soon)**

---

## 📦 Requirements

- Python 3.8+
- `requests`, `cloudscraper`, `colorama`, `aiohttp`, `beautifulsoup4`, etc.
- Linux or Termux recommended (Windows partially supported)

```bash
pip install -r requirements.txt
