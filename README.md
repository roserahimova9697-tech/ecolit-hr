# ECOLIT HR Portal

Ecolit Ceiling Solutions kompaniyasining HR portali (statik sayt, GitHub Pages uchun).

Bo'limlar: Bosh sahifa, Hodimlar bazasi, Bo'sh ish o'rinlari, Onlayn ariza berish, Test topshirish, Kompaniya haqida, HR yangiliklari, Mening profilim, Sozlamalar.

Eslatma: arizalar va test natijalari foydalanuvchi brauzerida (localStorage) saqlanadi — server/baza yo'q.

## Nomzod oqimi
1. Onlayn ariza (anketa) → HR Telegram botiga xabar + CV.
2. Mantiqiy test (31 savol) → javoblar serverda (Google Apps Script) tekshiriladi, natija faqat HR'ga boradi.
3. Nomzodga faqat "Korxonamizga qiziqish bildirganingiz uchun tashakkur!" chiqadi.

`index.html` ichidagi `API_URL` ga Apps Script Web app manzilini qo'ying. To'g'ri javoblar kaliti bu repozitoriyda YO'Q — u faqat Apps Script'da turadi.
