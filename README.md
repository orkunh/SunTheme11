# 🌅 SunTheme11

> **Automatic Windows 11 Light/Dark theme switching based on your local sunrise and sunset.**  
> **Windows 11 için yerel gün doğumu ve gün batımına göre otomatik Açık/Koyu tema geçişi.**

<p align="center">

Lightweight • Open Source • Privacy Friendly  
Hafif • Açık Kaynak • Gizlilik Dostu

Windows 11 • x64 • ARM64 • MIT License

</p>

---

# 🌍 Language / Dil

🇺🇸 English • 🇹🇷 Türkçe

---

# 🇺🇸 English

## ✨ Features

- 🌅 Automatic Light/Dark theme switching
- 📍 Automatic approximate location detection
- 🌍 Local sunrise & sunset calculation
- 💾 Offline cached location
- 🔄 Hybrid theme detection
- 🚀 Automatic startup
- 🔇 Silent background operation
- ⚡ Very low CPU and memory usage
- 💻 Windows 11 x64
- 💻 Windows 11 ARM64

---

## 🚀 Why SunTheme11?

Windows can switch themes only at fixed times.

SunTheme11 follows your **real local sunrise and sunset** automatically.

No schedules.

No configuration.

Install once and forget it.

---

## ⚙️ How it Works

```text
Computer starts
        │
        ▼
 SunTheme11 starts
        │
        ▼
 Detect location
        │
        ▼
 Calculate sunrise & sunset
        │
        ▼
 Read current Windows theme
        │
        ▼
 Theme correct?
     ┌───────┐
 YES │       │ NO
     ▼       ▼
 Sleep     Apply theme
 until      if needed
 next
 event
```

---

## 🏗 Architecture

```text
                Windows 11
                     │
                     ▼
               SunTheme11.exe
                     │
      ┌──────────────┼──────────────┐
      ▼              ▼              ▼
 Location      Sunrise/Sunset   Theme Watch
      │              │              │
      └──────────────┼──────────────┘
                     ▼
          Apply theme only if required
```

---

## 📦 Installation

1. Download the correct package from **Releases**
2. Extract the ZIP
3. Run **Install.bat**
4. Done

---

## ✅ Tested

- Windows Restart
- Multiple reboot tests
- Sleep / Resume
- Manual theme changes
- Offline cached location
- Automatic startup
- Sunrise / Sunset switching

---

## 🔒 Privacy

SunTheme11 requests only an approximate location from your public IP.

It does **NOT** collect:

- Personal information
- Telemetry
- Analytics
- Advertising identifiers
- User tracking

---

## ❓ FAQ

### Does it require Internet?

Only for the first location detection.

The last successful location is used while offline.

### Does it have a user interface?

No.

SunTheme11 runs silently in the background.

No configuration window.

### Windows 10?

Not supported.

### ARM64?

Supported.

Native x64 and ARM64 builds are available.

---

# 🇹🇷 Türkçe

## ✨ Özellikler

- 🌅 Gün doğumu ve gün batımına göre otomatik tema değişimi
- 📍 Yaklaşık konum algılama
- 🌍 Yerel güneş saatlerini hesaplama
- 💾 Çevrimdışı son konumu kullanma
- 🔄 Hibrit tema algılama
- 🚀 Otomatik başlangıç
- 🔇 Sessiz arka plan çalışması
- ⚡ Çok düşük işlemci ve bellek kullanımı
- 💻 Windows 11 x64
- 💻 Windows 11 ARM64

---

## 🚀 Neden SunTheme11?

Windows yalnızca belirlediğiniz saatlerde tema değiştirebilir.

SunTheme11 bulunduğunuz konumdaki **gerçek gün doğumu ve gün batımını** takip eder.

Saat ayarlamanıza gerek kalmaz.

Bir kez kurun ve gerisini SunTheme11'e bırakın.

---

## ⚙️ Nasıl Çalışır?

```text
Bilgisayar açılır
        │
        ▼
 SunTheme11 başlar
        │
        ▼
 Konumu belirler
        │
        ▼
 Gün doğumu / batımını hesaplar
        │
        ▼
 Windows temasını okur
        │
        ▼
 Tema doğru mu?
     ┌──────────┐
 EVET│          │HAYIR
     ▼          ▼
 Bekle      Temayı uygula
 Sonraki
 olaya kadar
```

---

## 🏗 Mimari

```text
                Windows 11
                     │
                     ▼
               SunTheme11.exe
                     │
      ┌──────────────┼──────────────┐
      ▼              ▼              ▼
   Konum      Gün Doğumu/Batımı   Tema Takibi
      │              │              │
      └──────────────┼──────────────┘
                     ▼
      Yalnızca gerektiğinde tema değiştir
```

---

## 📦 Kurulum

1. **Releases** bölümünden uygun paketi indirin.
2. ZIP dosyasını çıkarın.
3. **Install.bat** dosyasını çalıştırın.
4. Hazır.

---

## ✅ Test Edilen Özellikler

- Windows yeniden başlatma
- Çoklu yeniden başlatma testi
- Uyku modundan dönüş
- Manuel tema değiştirme
- Çevrimdışı son konumu kullanma
- Otomatik başlangıç
- Gün doğumu / gün batımı geçişleri

---

## 🔒 Gizlilik

SunTheme11 yalnızca yaklaşık konum belirlemek için genel IP adresinizi kullanır.

Toplanmayan veriler:

- Kişisel bilgiler
- Telemetri
- Analitik veriler
- Reklam kimlikleri
- Kullanıcı takibi

---

## ❓ Sık Sorulan Sorular

### İnternet gerekli mi?

Sadece ilk konum tespiti için.

Daha sonra internet olmasa bile son başarılı konum kullanılmaya devam edilir.

### Kullanıcı arayüzü var mı?

Hayır.

SunTheme11 sessizce arka planda çalışır.

Herhangi bir ayar penceresi bulunmaz.

### Windows 10 destekleniyor mu?

Hayır.

Yalnızca Windows 11 desteklenmektedir.

### ARM64 destekleniyor mu?

Evet.

Hem x64 hem ARM64 sürümleri bulunmaktadır.

---

## 🤝 Contributing / Katkıda Bulunma

Bug reports, feature requests and pull requests are welcome.

Hata bildirimleri, özellik önerileri ve katkılar memnuniyetle karşılanır.

---

## 📜 License / Lisans

MIT License / MIT Lisansı

---

<p align="center">

Made with ❤️ for Windows 11 users.

Windows 11 kullanıcıları için geliştirildi.

</p>
