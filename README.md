# Plety

Dashboard modern untuk mengorganisir semua proyek Vercel — tema gelap, animasi candy, papan **drag & drop** (Proyek Pribadi ⇄ Proyek Umum) yang tersimpan otomatis di browser.

## Isi

- **`index.html`** — landing page (React + Tailwind via CDN, single-file, tanpa build). Berisi hero, papan 20 proyek Vercel dengan thumbnail + badge framework + status live, dan footer.
- **`hero.html`** — hero section alternatif (light theme).

## Menjalankan

Cukup buka `index.html` di browser. Untuk server lokal:

```bash
python -m http.server 4599
# lalu buka http://localhost:4599/index.html
```

## Deploy

Static, siap deploy ke Vercel apa adanya (drop folder ini). Tidak butuh build step.
