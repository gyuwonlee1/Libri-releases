# Libri Releases

This repository hosts public release artifacts for Libri.

Source code is maintained in a private repository. This repository is used only for public installer downloads and Tauri updater metadata.

Each GitHub Release should include:

- The NSIS installer `.exe`
- The matching Tauri updater signature `.exe.sig`
- `latest.json`
- `THIRD_PARTY_NOTICES.md`

Third-party notices are included with each release.

Do not commit private source code, signing keys, signing passwords, `.env` files, build caches, or internal development documents to this repository.
