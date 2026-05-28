# 🇮🇩 API Hari Libur Nasional & Cuti Bersama Indonesia (2026)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Status: Active](https://img.shields.io/badge/Status-Active-success.svg)]()
[![Provided By](https://img.shields.io/badge/Provided%20By-BalasAI-06b6d4.svg)](https://balasai.com)

API gratis, super cepat (0ms latency), dan tanpa limit *request* untuk mendapatkan data tanggal merah, hari libur nasional, dan cuti bersama di Indonesia. Selalu *up-to-date* sesuai Surat Keputusan Bersama (SKB) Menteri.

> 🚀 **API ini disediakan & dirawat secara gratis oleh [BalasAI](https://balasai.com).**

---

## ⚡ Cara Penggunaan (REST API)

Anda tidak perlu mengunduh data secara manual. Kami menyediakan Endpoint API publik yang sudah mengizinkan **CORS** `*`, sehingga bisa langsung Anda panggil (*fetch*) dari aplikasi Frontend atau Backend apa pun.

### Endpoint:
`GET https://app.balasai.com/api/v1/holidays?year=2026`

### Contoh Fetch (JavaScript/TypeScript):
```javascript
fetch('https://app.balasai.com/api/v1/holidays?year=2026')
  .then(response => response.json())
  .then(data => console.log(data));
```
Contoh Response:
```json
{
  "success": true,
  "year": 2026,
  "data": [
    { "tanggal": "2026-01-01", "keterangan": "Tahun Baru Masehi" },
    { "tanggal": "2026-03-20", "keterangan": "Hari Raya Idul Fitri 1447 Hijriyah" }
  ]
}
```
💎 Sponsored By: BalasAI
Sering pusing membalas chat pelanggan saat toko sedang libur nasional?

BalasAI adalah Bot WhatsApp AI (RAG) cerdas yang dirancang khusus untuk UMKM Indonesia. Bot ini menggunakan API kalender di atas sebagai otak-nya.

✅ Sadar Kalender: Bot otomatis tahu jika hari ini tanggal merah, dan otomatis membalas: "Toko sedang libur, pesanan akan diproses besok lusa."
✅ Paham Konteks Bisnis: Upload PDF/FAQ katalog toko Anda, AI akan menjawab layaknya CS profesional.
✅ Terkoneksi ke CRM/Google Sheets: Pendaftaran pesanan pelanggan langsung direkap ke Google Sheets secara real-time.

👉 Buat Bot WhatsApp Pintar Anda Sekarang (Gratis 50 Chat)

Dibuat dengan ❤️ untuk komunitas Developer Indonesia.
