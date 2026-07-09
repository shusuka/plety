# Yusuf — Dashboard proyek Vercel

Dashboard modern untuk mengorganisir semua proyek Vercel — tema gelap, animasi candy, papan **drag & drop** 5 kategori (Pribadi · Umum · Kantor · Jualan · Games) yang tersimpan otomatis di browser.

## Fitur

- **`index.html`** — single-file (React + Tailwind via CDN, tanpa build). Berisi hero, papan 20 proyek Vercel, dan footer.
- Tiap kategori = baris horizontal berisi kartu proyek (thumbnail screenshot situs asli + badge framework + status live).
- Kartu bisa diseret antar-kategori, dihapus (dengan opsi pulihkan), dan dibuka di tab baru. Susunan tersimpan di `localStorage`.
- Kategori **Pribadi** terkunci login email (client-side; sandi di konstanta `AKSES_SANDI`).

## Menjalankan

Cukup buka `index.html` di browser. Untuk server lokal:

```bash
python -m http.server 4599
# lalu buka http://localhost:4599/index.html
```

## Deploy

Static, siap deploy ke Vercel apa adanya. Tidak butuh build step. Live: https://plety-teal.vercel.app
