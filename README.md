# 🔐 CipherLab

CipherLab is a browser-based cybersecurity project I built to experiment with cryptography and turn some of the concepts I've been learning into something interactive.

The idea is pretty simple: put a few different security tools into one place and make them fun to actually use.

## What it can do

* 🔎 **Data Detector** — Analyze hashes, Base64, Hex, Caesar shifts, and other types of input.
* 🔐 **File Vault** — Encrypt and decrypt local files using AES, with support for AES-128, AES-256, DES, and 3DES.
* 🔑 **RSA Encryption** — Generate RSA-2048 key pairs and use public/private key encryption for files.
* 📨 **One-Time Secrets** — Create encrypted messages with passphrases, expiration times, and one-time access.
* ⚡ **Browser-Based** — Most of the cryptographic processing happens directly in the browser using JavaScript and the Web Crypto API.

The project also has a cybersecurity-inspired interface with animated scanning effects, system logs, a Matrix-style background, and lock/unlock animations. I wanted it to feel more like a security tool rather than just another collection of HTML forms.

## 🛠️ Built With

* HTML
* CSS
* JavaScript
* Web Crypto API
* CryptoJS

The project currently uses AES-GCM, RSA-OAEP, PBKDF2, and SHA-based hashing for different features.

## 🚧 Current Status

CipherLab is **still a work in progress** and shouldn't be considered a finished or production-ready security product.

There are a lot of things I want to improve, including the UI, cryptographic features, error handling, key management, and overall architecture. Some functionality also relies on external libraries and dependencies, so there is plenty of room to expand the project with better tools and additional integrations.

For now, it's mainly a **learning project and a place to experiment with cybersecurity and cryptography concepts**.

## ⚠️ Disclaimer

CipherLab hasn't been professionally security-audited, so don't use it to protect genuinely sensitive or critical information.

**Built to learn. Built to experiment. Built to look cool. 🔐**
