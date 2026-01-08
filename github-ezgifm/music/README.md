# 🎵 Müzik Klasörü

Bu klasöre MP3 dosyalarını yükle.

## 📋 Desteklenen Formatlar

- MP3 (Önerilen)
- WAV
- OGG

## 📏 Dosya Boyutu

GitHub'da dosya başına maksimum 100MB sınırı var.
Büyük dosyalar için Git LFS kullan.

## 📝 Dosya Adlandırma

- Türkçe karakter kullanma
- Boşluk yerine tire (-) kullan
- Örnek: `sarki-adi.mp3`

## 🔄 Playlist Güncelleme

Müzik ekledikten sonra `index.html` içindeki playlist'i güncelle:

```javascript
const playlist = [
    {
        title: "Şarkı Adı",
        url: "music/sarki-adi.mp3"
    }
];
```