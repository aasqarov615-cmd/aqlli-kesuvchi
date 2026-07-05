<div align="center">

# ✂️ Aqlli kesuvchi

**DSP, LDSP, laminat, MDF, faner, profil va oyna uchun aqlli kesish optimizatori**

Offlayn ishlaydigan, telefon va kompyuterga o'rnatiladigan (PWA) bir faylli veb-ilova.
MaxRects algoritmi asosida materialni eng kam chiqim bilan kesib beradi, moliyaviy hisobotni aniq chiqaradi.

![HTML](https://img.shields.io/badge/HTML5-single--file-e34f26?style=flat-square&logo=html5&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-offline-5a0fc8?style=flat-square)
![Til](https://img.shields.io/badge/til-Uz%20%7C%20Ru-1eb53a?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

</div>

---

## 📌 Bu nima?

**Aqlli kesuvchi** — mebel ustalari, oyna kesuvchilar va materialni listlab sotib olib bo'laklarga bo'lib ishlatadigan har bir kishi uchun mo'ljallangan dastur. Siz list o'lchamini va kerakli bo'laklarni kiritasiz, dastur esa:

- Bo'laklarni listga eng optimal (kam chiqimli) joylashtiradi
- Nechta list kerakligini va har birining andozasini chizib beradi
- Necha foiz material foydali ishlatilgani va qancha atxotga ketganini ko'rsatadi
- Tan narxi va ustama asosida **aniq daromad, rasxod va foyda** hisobini chiqaradi

Hamma narsa bitta HTML faylda — internet, server yoki o'rnatish kerak emas.

---

## ✨ Asosiy imkoniyatlar

### 🧩 Kesish optimizatsiyasi
- **MaxRects** algoritmi (bir nechta evristika: BAF, BSSF, BLSF, BL) — eng kam list soni va eng kam atxod
- Arra haqqi (kerf) hisobga olinadi — millimetrgacha aniq
- Bo'laklarni 90° aylantirish (ixtiyoriy)
- Kesish yo'nalishi: Avto / Gorizontal / Vertikal
- Har bir bo'lak va qoldiq (ortiq) o'lchami bilan vizual andoza

### 💰 Moliyaviy hisobot
- Butun list tan narxidan **1 m² tan narxi** real vaqtda avtomatik hisoblanadi
- Ustama (1 m² uchun daromad) asosida sof foyda
- Foydali bo'laklar va atxotga ketgan material qiymati
- **Har bir o'lcham bo'yicha alohida** va umumiy hisobot jadvali
- Summalar bo'sh joy bilan formatlanadi: \`1 000 000 so'm\`

### 🗂 Materiallar bazasi
- Ko'p ishlatiladigan materiallarni (o'lcham + narx) nom bilan saqlash
- Keyingi safar bir bosishda tanlab yuklab olish
- Yig'iladigan ro'yxat — ish maydonini egallamaydi

### 📦 Arxiv
- Har bir bajarilgan buyurtmani sana va vaqti bilan saqlash
- Buyurtmachini tanlab, ishni to'liq (o'lchamlar, bo'laklar, hisobot) qayta ochish va davom ettirish
- Ismni tahrirlash, bittalab yoki hammasini o'chirish
- Bir xil ism saqlashdan himoya

### 🌐 Qulayliklar
- **To'liq offlayn** — internetsiz ishlaydi
- **PWA** — telefon yoki kompyuterga ilova sifatida o'rnatiladi
- Ikki til: 🇺🇿 O'zbekcha / 🇷🇺 Русский
- Kun / Tun rejimi
- m / sm / mm o'lchov birliklari
- Faqat kerakli ma'lumotlarni chop etish yoki PDF saqlash
- Barcha ma'lumot brauzer xotirasida saqlanadi (\`localStorage\`)

---

## 🚀 Ishlatish

### Onlayn (GitHub Pages)
1. Repozitoriyani forklang yoki clone qiling
2. GitHub'da **Settings → Pages → Source: \`main\` branch** ni tanlang
3. Berilgan havola orqali oching (masalan \`https://username.github.io/aqlli-kesuvchi/\`)

### Lokal
Shunchaki \`index.html\` faylini istalgan brauzerda oching. Boshqa hech narsa kerak emas.

### Telefonga o'rnatish (Android / iOS)
1. Faylni brauzerda (Chrome / Safari) oching
2. Menyudan **"Bosh ekranga qo'shish" (Add to Home screen)** ni tanlang
3. Ilova ikonka sifatida o'rnatiladi va offlayn ochiladi

> 📱 Haqiqiy \`.apk\` kerak bo'lsa: shu faylni [PWABuilder](https://www.pwabuilder.com/) ga berib APK generatsiya qilishingiz yoki Android Studio'da WebView bilan o'rashingiz mumkin.

---

## 🛠 Texnologiya

| | |
|---|---|
| **Frontend** | Sof HTML + CSS + Vanilla JavaScript (freymvorksiz) |
| **Algoritm** | MaxRects bin-packing (ko'p evristikali) |
| **Offlayn** | Service Worker + Web App Manifest (sahifa ichida generatsiya qilinadi) |
| **Saqlash** | \`localStorage\` (sozlamalar, materiallar, arxiv) |
| **Bog'liqliklar** | Yo'q — 100% mustaqil bitta fayl |

---

## 📂 Fayllar tuzilishi

\`\`\`
.
├── index.html   # Butun dastur (HTML + CSS + JS bir faylda)
├── README.md
└── LICENSE
\`\`\`

> 💡 HTML fayl \`index.html\` deb nomlansa, GitHub Pages'da avtomatik ochiladi.

---

## 📸 Skrinshotlar

> Bu yerga ilovaning skrinshotlarini qo'shing:
>
> \`\`\`
> ![Asosiy ekran](screenshots/main.png)
> ![Kesish andozasi](screenshots/result.png)
> ![Moliyaviy hisobot](screenshots/finance.png)
> \`\`\`

---

## 🗺 Rejalar (Roadmap)

- [ ] Buyurtmani rasm (PNG) sifatida yuklab olish
- [ ] Bir listda bir necha xil material qalinligini boshqarish
- [ ] Arxivni fayl (JSON) sifatida eksport / import qilish
- [ ] Bo'laklar ro'yxatini Excel/CSV dan import qilish

---

## 👨‍💻 Muallif

**Azizbek Asqarov**

📞 +998 93 483 12 89
📞 +998 94 689 35 15

---

## 📄 Litsenziya

MIT License asosida tarqatiladi — erkin foydalanish, o'zgartirish va tarqatish mumkin. Batafsil: [LICENSE](LICENSE) faylida.

<div align="center">

⭐ Agar dastur foydali bo'lsa, repozitoriyaga yulduzcha qo'ying!

</div>
