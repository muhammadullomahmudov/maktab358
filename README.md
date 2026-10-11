# 358-maktab sayti

Toshkent shahri, Bektemir tumanidagi 358-sonli umumta'lim maktabi sayti.
Uch tilda ishlaydi: o'zbek, rus va ingliz. Kunduzgi va tungi rejim bor.

## Holati: namoyish versiyasi

- **Haqiqiy ma'lumotlar:** yangiliklar va yutuqlar (maktabning Telegram kanalidan), Telegram va Instagram
  havolalari, maktab haqidagi faktlar va rasmlar (president.uz).
- **Namuna ma'lumotlar:** direktor, o'qituvchilar ismi, sinflardagi o'quvchilar soni, sinf rahbarlari,
  dars jadvali, qo'ng'iroqlar va to'garaklar jadvali.

Haqiqiy ma'lumotlar kiritilgach, `index.html` dagi `DEMO` ni `false` qiling: "Namoyish" belgisi yo'qoladi.

## Ma'lumotlarni o'zgartirish

Hamma narsa bitta `index.html` faylida, "1-QISM. SAYT MA'LUMOTLARI" bo'limida:

| Nima | Qayerda |
| --- | --- |
| Aloqa (Telegram, Instagram, telefon) | `CONTACTS`, `LOCATION` |
| Direktor | `DIRECTOR` |
| Sinflar va o'quvchilar soni | `CLASSES`, `CLASS_INFO` |
| O'qituvchilar | `TEACHERS`, fanlar `SUBJECTS` |
| Dars jadvali va qo'ng'iroqlar | `SCHEDULE`, `BELLS` |
| To'garaklar | `CLUBS` |
| Yutuqlar | `ACHIEVEMENTS` |
| Yangiliklar | `NEWS` |
| Bino xonalari | `ROOMS` |
| Favqulodda holat | `SAFETY`, `EXITS`, `ASSEMBLY`, `CALLS` |
| Ta'tilgacha sanoq | `HOLIDAYS` (sanalar namuna) |
| Maktab yo'li (tarix) | `PATH` |

Rasmlar `rasmlar` papkasida (ichidagi README ga qarang).

O'quvchilarning ism-familiyasi va rasmi faqat o'zi va ota-onasining roziligi bilan qo'yiladi.
Chiqish yo'llari (`EXITS`) faqat maktabning rasmiy evakuatsiya rejasidan yoziladi.
