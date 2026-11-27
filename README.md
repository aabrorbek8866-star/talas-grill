# Talas Grill — grilxona hisob-kitob paneli

Qirg'iziston, Talas shahridagi grilxona uchun admin panel. 4 til (o'zbek, rus, ingliz, qirg'iz), 4 rol: administrator, sotuvchi (kassir), oshpaz, direktor.

## Fayllar

| Fayl | Nima |
|---|---|
| `index.html` | **Demo versiya.** Namuna ma'lumotlar bilan to'liq ishlaydi, ma'lumotlar faqat brauzerda saqlanadi. Hamma loginlar paroli: `demo`. Faylni brauzerda ochish kifoya. |
| `panel.html` | Ishchi panel kodi. U claude.ai Artifact sifatida ishlaydi va claude.ai ma'lumotlar bazasidan (`db` imkoniyati) foydalanadi, shuning uchun alohida serverda o'zi ishlamaydi. |

## Imkoniyatlar

- **Kassir:** sotuv (grill, lavash, non, sous), oshpazga buyurtma (soni va vaqti majburiy), tayyor grillar soni, ishga kelish, kunlik oylik (oldim / keyin olaman), xarajat yozish, direktorga xabar va avans so'rovi.
- **Oshpaz:** "Tandirga qo'ydim" taymeri (20–30 daqiqa), jiringlaydigan eslatmalar: 10 va 5 daqiqa qolganda, yangi buyurtma kelganda, buyurtmadan 40 daqiqa oldin, sotishga grill kam qolganda, omborda tovuq kam qolganda. Ombor, o'tin hisobi, oylik ish haqi (1 grill = 30 KGS), direktorga xabar va avans.
- **Direktor:** bosh sahifa (pishirilgan / sotilgan / farq, kassadagi naqd, sotuvchi kelgan vaqt), kassa nazorati va pul olib ketish, kirim-chiqim va foyda-zarar, o'tin (kam qolganda eslatma), xabarlar va avanslarga javob, premiya va bonus berish, analitika, kun jurnali.
- **Valyuta:** barcha summalar KGS, USD yoki UZS da ko'rinadi.

## Xavfsizlik

Loginlar va parollar bu repozitoriyda **yo'q**. Parollar faqat tuzlangan SHA-256 xesh ko'rinishida claude.ai bazasida saqlanadi va administrator "Sozlamalar" bo'limida almashtiradi.
