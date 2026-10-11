# Racik V60

Kalkulator seduh V60 harian (PWA statis, tanpa build step). Bisa di-install ke home screen dan tetap jalan offline.

## Deploy ke Vercel

1. Vercel → **Add New → Project** → import repo ini.
2. **Root Directory**: `racik-v60`
3. **Framework Preset**: `Other` (build command & output directory dikosongin).
4. Deploy.

## Update isi app

Edit `index.html`, lalu naikin `VERSION` di `sw.js` (mis. `racik-v60-v2`) biar HP yang udah install ambil versi baru.
