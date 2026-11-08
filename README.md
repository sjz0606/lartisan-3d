# L'artisan — 3D veb-sayt (konsept)

Toshkentdagi **L'artisan Ice Cream & Desserts** jelateriyasi uchun 3D interaktiv sayt konsepti.

**Jonli demo:** https://sjz0606.github.io/lartisan-3d/

> Bu konsept-dizayn, L'artisan'ning rasmiy sayti emas.

## Imkoniyatlar
- **3D hero:** haqiqiy suratlar 3D fazoda, scroll bilan kamera ular orasidan uchib o'tadi (Three.js, WebGL shader)
- **Chuqurlik relyefi:** har bir surat uchun AI (Depth Anything V2) bilan yaratilgan depth map, suratlar hajmli bo'rtib chiqadi
- **Vitrina 360°:** egilgan panellardan iborat aylanuvchi 3D halqa (scroll + sudrash)
- **Mavsumlar:** gorizontal scroll, 3D parallaks suratlar
- Instagram reels (rasmiy embed), UZ/RU tillari, mobil moslashuv, `prefers-reduced-motion` qo'llab-quvvatlanadi

## Texnologiyalar
Three.js r186 · GSAP + ScrollTrigger · Lenis · sof HTML/CSS/JS (build talab qilinmaydi)

## Lokal ishga tushirish
```bash
python -m http.server 8765
# http://localhost:8765
```

## O'z videolaringizni qo'shish
`videos/reel1.mp4 … reel8.mp4` fayllarini qo'ying, sayt ularni avtomatik Instagram embed o'rniga ko'rsatadi.

## Litsenziya
Kod: MIT (`LICENSE`). Suratlar: CC0 / public domain (`img/CREDITS.txt`).
"L'artisan" nomi va brendi o'z egalariga tegishli; MIT litsenziyasi ularga taalluqli emas.
