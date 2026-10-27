# Yuk Nazorat

Yuk avtomobillari parkini GPS orqali kuzatish tizimining demo interfeysi.

## Rollar (demo hisoblar)

| Rol | Login | Parol | Bo'limlar |
| --- | --- | --- | --- |
| Logistika rahbari | `rahbar` | `demo123` | Xarita, Yoqilg'i, Ogohlantirishlar, Hisobotlar |
| Administrator | `admin` | `demo123` | Xarita, Mashinalar, GPS qurilmalar, Foydalanuvchilar, Sozlamalar |

## Hisobotlar (Excelga yuklab olinadi)

Davrni tanlash mumkin: bugun, 7 kun yoki 30 kun. Har bir Excel fayl bir nechta varaqdan iborat.

- **Probeg (km)**: umumiy jadval va kunlik jadval
- **Yoqilg'i**: umumiy, kunlik, quyishlar va to'kishlar
- **Tezlik**: umumiy jadval va har bir buzish
- **To'xtashlar**: umumiy jadval va to'xtashlar ro'yxati
- **Geozonalar**: umumiy jadval va tashriflar
- **Haydovchilar reytingi**: 100 balllik baho

Barcha ma'lumotlar namunaviy (demo) va brauzerda simulyatsiya qilinadi. Administrator kiritgan o'zgarishlar faqat shu brauzerda saqlanadi. Hozircha server, ma'lumotlar bazasi va GPS qurilmalar ulanmagan.

## Ishga tushirish

Bu oddiy statik sayt: `index.html` faylini brauzerda ochish kifoya. Excel eksport uchun SheetJS kutubxonasi cdnjs orqali yuklanadi.

## Vercel

Repozitoriya Vercelga ulangan. `main` branchiga qilingan har bir push saytni avtomatik yangilaydi.
