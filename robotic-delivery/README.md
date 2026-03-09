# 🤖 Robotic Delivery — Konnex World

10 bölümlük bir robot teslimat oyunu.

## 🚀 Vercel'e Deploy Etme

### Yöntem 1: GitHub üzerinden (Önerilen)
1. Bu klasörü GitHub'a push edin
2. [vercel.com](https://vercel.com) → **New Project**
3. GitHub repo'nuzu seçin
4. Framework olarak **Create React App** otomatik algılanır
5. **Deploy** butonuna tıklayın — bitti!

### Yöntem 2: Vercel CLI
```bash
npm install -g vercel
vercel
```

## 🛠 Yerel Geliştirme
```bash
npm install
npm start
```

## 🎮 Oyun Kontrolleri
- **WASD / Ok Tuşları** — Hareket
- **SPACE** — Ateş et
- **📦** Paketi al → **🏠** Adrese teslim et
- **🚨** Düşman robotlardan kaç!

## 📁 Proje Yapısı
```
robotic-delivery/
├── public/
│   └── index.html
├── src/
│   ├── App.js        ← Oyun kodu
│   ├── index.js      ← Giriş noktası
│   └── styles.css    ← Temel stiller
├── package.json
├── vercel.json       ← Vercel yapılandırması
└── .gitignore
```
