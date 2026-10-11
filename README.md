# 358-maktab sayti

Toshkent shahri, Bektemir tumanidagi 358-sonli umumta'lim maktabi saytining qoralamasi.
Sayt uch tilda ishlaydi: o'zbek, rus va ingliz.

Holati: qoralama. Maktab ma'muriyati tasdiqlaganidan keyin e'lon qilinadi.

## Ma'lumotlarni o'zgartirish

Hamma narsa bitta `index.html` faylida. Fayl ichidagi "1-QISM. SAYT MA'LUMOTLARI"
bo'limida direktor, sinflar, o'qituvchilar, to'garaklar va yangiliklar yoziladi.

- `todo: true` deb belgilangan joylar hali to'ldirilmagan.
- Sinflardagi o'quvchilar soni hozircha **namuna**. Haqiqiy sonlarni yozgach,
  `CLASSES_SAMPLE` ni `false` qiling.
- Rasmlar `rasmlar` papkasiga qo'yiladi (ichidagi README ga qarang).

## Qiziqarli funksiyalar

- **Hozir maktabda**: Toshkent vaqti bo'yicha nechanchi dars yoki tanaffus ekanini ko'rsatadi.
  Qo'ng'iroqlar jadvali `BELLS` da, hozircha namuna (`BELLS_SAMPLE`).
- **Bino sxemasi**: xonalar `ROOMS` da.
- **Nazorat ishi**: savollar `QUIZ` da, birinchi javob to'g'risi.
- **Manzil**: `LOCATION` da. Aniq koordinata yozilgach `exact: true` qiling.
- Aloqa (Telegram, Instagram, telefon): `CONTACTS` da.
- Dizayn: afisha uslubi (juda yirik harflar, qalin chiziqlar, qattiq soyalar), 3D kub, 3D bino va xonalar; kunduzgi va tungi rejim.
- **Kim hozir qayerda**: o'qituvchilar `TEACHERS` da, dars jadvali `SCHEDULE` da (hozircha namuna, `SCHEDULE_SAMPLE`).
- **Faxrimiz**: bitiruvchi va o'quvchilar yutuqlari `ACHIEVEMENTS` da. Faqat rozilik bilan qo'shing.
- **Favqulodda holat**: qoidalar `SAFETY` da. Chiqish yo'llari (`EXITS`) va yig'ilish joyi (`ASSEMBLY`)
  faqat maktabning rasmiy evakuatsiya rejasidan yoziladi.
