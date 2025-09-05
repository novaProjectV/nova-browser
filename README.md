# 🌌 Nova Browser

macOS browser in **SwiftUI** — lightweight, customizable and privacy-friendly.  
Includes **Nova Shield** (ad-block & tracker protection), **Nova Security** (password manager), proxy support, themes, widgets.  

> 🖥 macOS 13+ • Universal (Apple Silicon & Intel)  
> 📦 Latest build: **1.0.8-b1**  

---

## ✨ Features
- 🛡 **Nova Shield** — ad & tracker blocking (normal + strict mode)  
- 🔑 **Nova Security** — passwords stored in macOS Keychain, password generator, autofill  
- 🎨 **Customization** — themes, accent colors, wallpapers (Aurora, Cosmos, Sakura…)  
- 📖 **Reading mode** and per-site zoom  
- 🧩 **Widgets** — clock, notes, weather _demo_, pomodoro timer, quote of the day  
- 🌐 **Proxy** (HTTP/HTTPS/SOCKS, experimental)  

---

## 🚀 Installation
1. Download the `.dmg` from [Releases](../../releases/latest).  
2. Drag **Nova Browser.app** into **Applications**.  
3. If macOS shows *“unverified developer”* warning:  
   - Right click → **Open** → confirm.  

---

## ⚠️ Known issues
- Not yet signed with Developer ID (Gatekeeper warning possible).  
- English UI ~70% complete.  
- `nova://store` unfinished, currently only one extension available.  
- Strict Nova Shield mode may break some websites.  

---

## 🤝 Contributing
Pull requests are welcome!  
- Please open an **Issue** before making large changes.  
- Keep PRs small and focused.  
- Follow [Swift API Design Guidelines](https://swift.org/documentation/api-design-guidelines/).  

---

## 🛠 Dev notes
- Web engine: **WebKit (WKWebView)** with content-blocking rules.  
- Passwords live in **macOS Keychain** (no export of secrets).  
- Strict Shield uses private WebKit APIs → may break in future macOS versions, not App Store-ready.  

---

## 📸 Screenshots (v1.0.7-build5)
![Nova Home](https://github.com/user-attachments/assets/7bcbaa6f-fcc5-4418-9b60-8d718ad065b4)

---
