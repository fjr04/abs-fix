# ABS Law Office V27 — Vercel Ready

Tampilan dan fitur aplikasi tetap sama dengan V27. Perubahan hanya pada konfigurasi instalasi dan deployment agar bersih untuk GitHub/Vercel.

## Test lokal

```bash
npm ci --no-audit --no-fund
npm run verify
npm run preview
```

## Test form/API lokal

```bash
cp .env.example .env.local
# Isi konfigurasi lokal di .env.local
npm run local
```

## Vercel

Konfigurasi sudah tersedia di `vercel.json`:

- Install Command: `npm ci --no-audit --no-fund`
- Build Command: `npm run build`
- Output Directory: `dist`
- Node.js: `22.x`
