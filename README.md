# Functa Trace — Release Channel

Repo ini hanya untuk distribusi update Functa Trace.

## Untuk pengguna

Download installer terbaru di tab **[Releases](../../releases)**.

Installer otomatis akan terdeteksi sebagai update oleh aplikasi yang sudah ter-install (banner notif muncul saat app dibuka).

## Mekanisme update

File `update.json` di root repo ini dibaca oleh aplikasi untuk mengecek versi terbaru. Format:

```json
{
  "version": "1.0.1",
  "released_at": "2026-05-06",
  "notes": "Catatan rilis...",
  "installer_url": "https://github.com/Functafx/Functa-trace/releases/download/v1.0.1/FunctaTrace-Setup-1.0.1.exe",
  "sha256": "..."
}
```
