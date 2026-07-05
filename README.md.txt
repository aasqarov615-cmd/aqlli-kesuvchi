# ✂️ Aqlli kesuvchi

**DSP, LDSP, laminat, MDF, faner, profil va oyna uchun aqlli kesish optimizatori**

Offlayn ishlaydigan, telefon va kompyuterga o'rnatiladigan (PWA) bir faylli veb-ilova. MaxRects algoritmi asosida materialni eng kam chiqim bilan kesib beradi, moliyaviy hisobotni aniq chiqaradi.

---

## 📌 Bu nima?

**Aqlli kesuvchi** — mebel ustalari, oyna kesuvchilar va materialni listlab sotib olib bo'laklarga bo'lib ishlatadigan har bir kishi uchun mo'ljallangan dastur. Siz list o'lchamini va kerakli bo'laklarni kiritasiz, dastur esa:

* Bo'laklarni listga eng optimal (kam chiqimli) joylashtiradi
* Nechta list kerakligini va har birining andozasini chizib beradi
* Necha foiz material foydali ishlatilgani va qancha atxotga ketganini ko'rsatadi
* Tan narxi va ustama asosida aniq daromad, rasxod va foyda hisobini chiqaradi

**Hamma narsa bitta HTML faylda** — internet, server yoki o'rnatish kerak emas.

---

## ✨ Asosiy imkoniyatlar

### 🧩 Kesish optimizatsiyasi
* MaxRects algoritmi (BAF, BSSF, BLSF, BL evristikalari) — eng kam list soni va eng kam atxod
* Arra haqqi (kerf) hisobga olinadi — millimetrgacha aniq
* Bo'laklarni 90° aylantirish (ixtiyoriy)
* Kesish yo'nalishi: Avto / Gorizontal / Vertikal
* Har bir bo'lak va qoldiq (ortiq) o'lchami bilan vizual andoza

### 💰 Moliyaviy hisobot
* Butun list tan narxidan $1 \text{ m}^2$ tan narxi real vaqtda avtomatik hisoblanadi
* Ustama ($1 \text{ m}^2$ uchun daromad) asosida sof foyda
* Foydali bo'laklar va atxotga ketgan material qiymati
* Har bir o'lcham bo'yicha alohida va umumiy hisobot jadvali
* Summalar bo'sh joy bilan formatlanadi: `1 000 000 so'm`

### 📂 Materiallar bazasi
* Ko'p ishlatiladigan materiallarni (o'lcham + narx) nom bilan saqlash
* Keyingi safar bir bosishda tanlab yuklab olish
* Yig'iladigan ro'yxat — ish maydonini egallamaydi

### 📦 Arxiv
* Har bir bajarilgan buyurtmani sana va vaqti bilan saqlash
* Buyurtmachini tanlab, ishni to'liq (o'lchamlar, bo'laklar, hisobot) qayta ochish va davom ettirish
* Ismni tahrirlash, bittalab yoki hammasini o'chirish
* Bir xil ism saqlashdan himoya

### 🌐 Qulayliklar
* To'liq oflayn — internetsiz ishlaydi
* PWA — telefon yoki kompyuterga ilova sifatida o'rnatiladi
* Ikki til: **uz O'zbekcha** / **ru Русский**
* Kun / Tun rejimi
* m / sm / mm o'lchov birliklari
* Faqat kerakli ma'lumotlarni chop etish yoki PDF saqlash
* Barcha ma'lumot brauzer xotirasida saqlanadi (`localStorage`)

---

## 🚀 Ishlatish

### Onlayn (GitHub Pages)
1. Repozitoriyani forklang yoki clone qiling
2. GitHub'da **Settings -> Pages -> Source: `main` branch** ni tanlang
3. Berilgan havola orqali oching

### Lokal
Shunchaki `index.html` faylini istalgan brauzerda oching. Boshqa hech narsa kerak emas.

### Telefonga o'rnatish (Android / iOS)
1. Faylni brauzerda (Chrome / Safari) oching
2. Menyudan **"Bosh ekranga qo'shish" (Add to Home screen)** ni tanlang
3. Ilova ikonka sifatida o'rnatiladi va offlayn ochiladi

> 📱 Haqiqiy `.apk` kerak bo'lsa: shu faylni [PWABuilder](https://www.pwabuilder.com/) ga berib APK generatsiya qilishingiz yoki Android Studio'da WebView bilan o'rashingiz mumkin.

---

## 🛠️ Texnolgiya

| Yo'nalish | Texnologiya |
|---|---|
| **Frontend** | Sof HTML + CSS + Vanilla JavaScript (freymvorksiz) |
| **Algoritm** | MaxRects bin-packing (ko'p evristikali) |
| **Offlayn** | Service Worker + Web App Manifest (sahifa ichida generatsiya qilinadi) |
| **Saqlash** | `localStorage` (sozlamalar, materiallar, arxiv) |
| **Bog'liqliklar** | Yo'q — 100% mustaqil bitta fayl |

---

## 📂 Fayllar tuzilishi

```text
.
├── index.html       # Butun dastur (HTML + CSS + JS bir faylda)
├── README.md
└── LICENSE