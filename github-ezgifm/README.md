# 🎵 Ezgi FM - Bedava Radyo

GitHub Pages ile 7/24 çalışan bedava radyo sitesi.

## 🚀 Kurulum

1. Bu repository'yi fork et
2. `music` klasörüne MP3 dosyalarını yükle
3. `index.html` içindeki playlist'i güncelle
4. GitHub Pages'i aktifleştir

## 📁 Dosya Yapısı

```
ezgifm-radio/
├── index.html          # Ana radyo sayfası
├── music/              # Müzik dosyaları
│   ├── song1.mp3
│   ├── song2.mp3
│   └── ...
└── README.md           # Bu dosya
```

## 🎵 Müzik Ekleme

1. `music` klasörüne MP3 dosyalarını yükle
2. `index.html` içindeki `playlist` array'ine ekle:

```javascript
const playlist = [
    {
        title: "Şarkı Adı",
        url: "music/dosya-adi.mp3"
    }
];
```

## 🌍 Erişim

Site GitHub Pages ile otomatik yayınlanır:
`https://kullaniciadin.github.io/ezgifm-radio`

## ✨ Özellikler

- 📱 Mobil uyumlu
- 🎵 Otomatik playlist
- ⏭ Sonraki şarkı
- 🔄 Sürekli çalma
- 🆓 Tamamen bedava
- 🌍 7/24 erişilebilir

## 📋 GitHub Pages Kurulum

1. Repository Settings → Pages
2. Source: Deploy from a branch
3. Branch: main
4. Folder: / (root)
5. Save

Site 5-10 dakika içinde hazır olur!