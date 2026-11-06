# TalantUp / Birkönüllü

İş, könüllülük imkanları və fəaliyyət əsaslı namizəd kəşfi üçün ikidilli hackathon prototipi.

## Layihəni açmaq

Bu, build tələb etməyən statik frontend layihəsidir.

1. Repository-ni ZIP kimi endirin.
2. ZIP faylını tam çıxarın (`Extract all`).
3. `dist/index.html` faylını brauzerdə açın.

Faylı ZIP arxivinin içindən birbaşa açmayın: brauzer `app.js` və `styles.css` fayllarını həmin halda yükləməyə bilər.

## Lokal server

İstənilən statik serverlə `dist` qovluğunu təqdim edin. Məsələn:

```bash
npx serve dist
```

## Vercel

Kökdəki `vercel.json` Vercel-ə yayımlanacaq qovluğun `dist` olduğunu bildirir. `main` branch-ə hər push avtomatik yeni deployment yaratmalıdır.

## Quruluş

- `dist/index.html` — tətbiqin HTML giriş nöqtəsi
- `dist/app.js` — bütün ekranlar, demo məlumatları və interaksiyalar
- `dist/styles.css` — responsive dizayn sistemi
- `.openai/hosting.json` — ChatGPT Sites konfiqurasiyası
- `vercel.json` — Vercel konfiqurasiyası

Frontend yalnız lokal demo məlumatlarından istifadə edir; real backend, autentifikasiya və AI xidməti yoxdur.
