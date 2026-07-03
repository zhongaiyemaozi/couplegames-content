# Clover Couple Games — Remote Content

Encrypted content & animation packs for **Clover Couple Games**, served globally via **jsDelivr**.

- `manifest.json` — plaintext catalog the app reads to decide what to download.
- `packs/*.bin` — AES-256-GCM encrypted content fragments (data only, **no executable code**).

Content is decrypted on-device by the app. This repo contains **data only** and complies with App Store Review Guideline 2.5.2.

Served via: `https://cdn.jsdelivr.net/gh/zhongaiyemaozi/couplegames-content@main/manifest.json`
