
# 🌌 Nova Browser

A modern macOS browser built with **SwiftUI** — lightweight, customizable and privacy-focused.

Includes **Nova Shield** (ad & tracker blocking), **Nova Security** (password manager), proxy support, themes and widgets.

> 🖥 macOS 13+ • Universal (Apple Silicon & Intel)  
> 📦 Latest build: **1.0.8-b2**

---

## ✨ Features

- 🛡 **Nova Shield** — ad & tracker blocking (normal + strict mode)  
- 🔑 **Nova Security** — secure password manager with macOS Keychain, generator & autofill  
- 🎨 **Customization** — themes, accent colors, dynamic wallpapers (Aurora, Cosmos, Sakura…)  
- 📖 **Reading mode** with per-site zoom control  
- 🧩 **Widgets** — clock, notes, weather (demo), Pomodoro timer, daily quotes  
- 🌐 **Proxy support** — HTTP / HTTPS / SOCKS (experimental)  
- 🧭 **Nova Home** — customizable start page with smart widgets

---

## 🚀 Installation

1. Download the latest `.dmg` from [Releases](../../releases/latest).  
2. Drag **Nova Browser.app** into your **Applications** folder.  
3. If macOS shows the *“unverified developer”* warning:

Right-click on the app → **Open** → Confirm launch.

---

## ⚠️ Known Issues

- App is not signed with a Developer ID yet (Gatekeeper warning possible).  
- English localization is ~70% complete.  
- `nova://store` is still under development (only one extension available).  
- Strict Nova Shield mode may break some websites.

---

## 🤝 Contributing

Contributions are welcome!

- Please open an **Issue** before making large changes.  
- Keep pull requests small and focused.  
- Follow the official [Swift API Design Guidelines](https://swift.org/documentation/api-design-guidelines/).

---

## 🛠 Developer Notes

- Web engine: **WebKit (WKWebView)** with custom content-blocking rules.  
- All passwords are stored securely in **macOS Keychain** (no export of secrets).  
- Strict Shield uses private WebKit APIs → may break in future macOS versions and is not App Store-safe.

---

ё

Если хочешь, могу сделать версию покороче, более техничную или наоборот — более маркетинговую 😼
