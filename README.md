# nova-browser
macOS browser in SwiftUI: Nova Shield (ad-block), Nova Security (passwords), proxy, themes, widgets. Preview 1.0.7. My own ru project 
//////////////////////////////////////////////////////////
macOS 13+, today last version of Nova Browser 1.0.7-b5

🤝 Contributing
PRs are welcome! Please:
discuss significant changes in an Issue first;
keep PRs focused and small;
follow Swift API Design Guidelines.
Dev notes
Web engine: WebKit (WKWebView) with content‑blocking rules.
Passwords live in macOS Keychain; no export of secrets.
Strict Shield may break sites; toggle off if something misbehaves.
