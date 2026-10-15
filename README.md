# Static SSH client untuk ARM jadul

Build otomatis via GitHub Actions:

- `dbclient` (Dropbear) dan `ssh` (OpenSSH, tanpa OpenSSL)
- Target: armv5 (soft-float), armv6 (hard-float), armv7 (hard-float)
- Static penuh (musl), tanpa dependensi library

## Cara pakai
1. Tab **Actions -> Build static SSH client (ARM) -> Run workflow** (hasil di Artifacts), atau
2. Push tag, misalnya `git tag v1.0 && git push origin v1.0`, hasil muncul di **Releases**.
