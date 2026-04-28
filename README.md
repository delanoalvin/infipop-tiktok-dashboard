# Infipop TikTok Dashboard

Dashboard performa TikTok @infipop.id. Deploy: https://infipop-tiktok-dashboard.vercel.app

## Status saat ini

- **Frontend:** Static HTML self-contained (Chart.js + SheetJS via CDN, DM Sans + Space Mono via Google Fonts)
- **Data:** Embedded di `index.html` sebagai JSON (199 posts April 2026)
- **Backend:** Belum ada — Phase B (Supabase)
- **Autosync:** Belum ada — Phase C (Composio TikTok)

## Cara update data (sementara, sebelum Phase B)

1. Edit `index.html` — cari blok `<script>` yang berisi array `posts`
2. Replace data
3. Commit + push ke `main` → Vercel auto-deploy

## Cara update tampilan/logic

Edit `index.html` (semua HTML + CSS + JS dalam 1 file). Push ke `main` → auto-deploy.

## Roadmap

- **Phase A** (done): Repo + auto-deploy via Vercel
- **Phase B** (next): Supabase backend, tim edit data via Studio web UI
- **Phase C** (later): Auto-pull data TikTok via Composio (replace manual upload)

Detail lengkap: lihat `Infipop_TikTok_Dashboard_Technical_Build.md` (handover doc dari Shafa).

## Owner

- **Dashboard logic, classification, analysis:** Shafa (Entertainment Desk)
- **Infrastructure, deployment:** Delano (Engineering)
- **Approval, access:** Dhanu (CCO)
