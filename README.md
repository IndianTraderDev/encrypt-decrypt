# 🔐 Secure Encrypt/Decrypt (AES-GCM + PWA)

A client-side, browser-based secure encryption and decryption tool using modern Web Crypto API (AES-GCM with PBKDF2). Fully offline capable thanks to PWA support.

## 🌟 Features

- AES-GCM authenticated encryption
- Password-based key derivation (PBKDF2 with 250,000 iterations)
- Random salt and IV per encryption
- Pure client-side (no server involved)
- Progressive Web App (PWA): installable and works offline
- Mobile- and GitHub Pages-friendly

## 🚀 How to Use

1. Clone or download this repository.
2. Open `index.html` in a browser **OR** deploy it via GitHub Pages.
3. Enter your text and password.
4. Choose to Encrypt or Decrypt.
5. Copy or save the result.

## 🧱 File Structure

```
.
├── index.html         # Main app
├── manifest.json      # PWA manifest
├── sw\.js              # Service worker for offline support
├── icon-192.png       # Optional icon
├── icon-512.png       # Optional icon
└── README.md

```

## 📦 Deployment

You can deploy it via GitHub Pages:

1. Push files to a GitHub repo.
2. Enable Pages in Settings → Pages → source: `main` branch, folder: `/root`.
3. Access it via: `https://your-username.github.io/repo-name`

---

## 🛡️ Security Notes

- All encryption is done **locally in the browser**.
- Your data never leaves your machine.
- Uses AES-GCM for integrity/authentication.

---

## 📋 License

MIT
```