# Hayot Dried Fruit

Quritilgan meva ishlab chiqaruvchi kompaniya uchun ko'p tilli tanishtiruv sayti.

**Jonli:** [abduazizbobomalikovnode.github.io/hayotdriedfruit.uz](https://abduazizbobomalikovnode.github.io/hayotdriedfruit.uz/)

---

## Nima uchun

Eksportga chiqadigan kompaniyaning saytini xorijiy xaridor ham, mahalliy hamkor ham ochadi. Shu sababli sayt bir necha tilda bo'lishi va mahsulot haqida aniq ma'lumot berishi kerak: nima ishlab chiqariladi, qanday qadoqlanadi, kim bilan bog'lanish mumkin.

Bu sayt shuning uchun yozilgan — hech qanday freymvork ishlatilmagan, faqat HTML, CSS va JavaScript. Natijada u tez ochiladi va istalgan oddiy hostingda ishlaydi.

## Nima bor

- **Mahsulotlar** — turlari va tavsifi bilan
- **Kompaniya haqida** — ishlab chiqarish va sifat haqida
- **Bog'lanish** — aloqa ma'lumotlari va forma
- **Ko'p tillilik** — til fayllari `lang/` papkasida alohida
- **Moslashuvchan** — telefon va kompyuterda bir xil ishlaydi

## Ishga tushirish

Build kerak emas — `index.html` ni brauzerda ochish kifoya.

Lokal serverda ko'rish uchun:

```bash
git clone https://github.com/AbduazizBobomalikovNode/hayotdriedfruit.uz.git
cd hayotdriedfruit.uz
python3 -m http.server 8000
```

Keyin: `http://localhost:8000`

## Uslublarni tahrirlash

Uslublar SCSS'da yozilgan (`scss/`), tayyor CSS `css/` papkasida turadi. SCSS'ni o'zgartirsangiz, qayta kompilyatsiya qilish kerak:

```bash
sass scss/main.scss css/main.css
```

## Tuzilma

```
index.html    bosh sahifa
pages/        ichki sahifalar
css/          tayyor uslublar
scss/         uslub manbasi
js/           skriptlar
lang/         til fayllari
img/          rasmlar
lib/          tashqi kutubxonalar
```

## Texnologiyalar

HTML · CSS · SCSS · JavaScript
