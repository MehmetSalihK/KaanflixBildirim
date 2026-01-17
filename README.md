# 🔴 KaanFlix Bildirim - Topluluk Sürümü

**KaanFlix** (**Kaan Varlı**) ve topluluğu için özel olarak geliştirilmiş, Kick.com deneyimini geliştiren gelişmiş bir Chrome eklentisi.

![Preview](images/icon_on_128.png)

## ✨ Temel Özellikler

### 👥 Topluluk Sistemi (YENİ!)

Eklenti üzerinden **KaanFlix** topluluğuna katılın ve sohbette fark yaratın:

- **Özel Rozetler**: Sohbette isminizin yanında özel bir topluluk rozeti (**at ikonu**) belirir.
- **Canlı Senkronizasyon**: Rozetiniz, eklentiyi kullanan diğer tüm izleyiciler tarafından anında görülür.
- **Kişiselleştirme**: Sohbet renginizi (Cyan/Mor) seçin ve tarzınızı yansıtın.
- **Sadece Hedef Kanalda**: Rozetler yalnızca `kick.com/kaanflix` kanalında aktiftir, diğer kanallarda görünmez.
- **Özel Ayarlar Butonu**: Kick arayüzüne entegre edilmiş, **28px** boyutunda sabit bir ayar butonu (**atsetting.png**) ile kolay yönetim.

### 🎥 Canlı Yayın & Bildirimler

- **Anlık Bildirimler**: KaanFlix yayına girdiği anda Windows bildirimi ve özel "At Sesi" uyarısı.
- **Hızlı Kontrol**: Yayın durumunu her dakika otomatik kontrol eder.
- **Güvenilir Algılama**: Kick API (V1) ve HTML Scraping yöntemlerini birleştirerek %100 doğruluk sağlar.
- **Şık Arayüz**:
  - Yayındayken: Yayın başlığı, izleyici sayısı ve kategori bilgileri.
  - Çevrimdışı: **Siyah/Beyaz** özel arka plan görseli (**kaanoffline.jpg**) ve "ÇEVRİMDIŞI" durum metni.

### 📺 Sosyal Medya & İçerik

- **Son Videolar**: KaanFlix'in YouTube kanalındaki son videoları otomatik çeker.
- **Sosyal Medya Dock'u**: YouTube, Instagram, TikTok ve Discord hesaplarına hızlı erişim sağlayan iOS tarzı "Glassmorphism" menü.
- **YouTube Shorts**: Son Shorts videolarına tek tıkla erişim.

## 🚀 Kurulum

### 1. Eklentiyi Yükleme

1. Bu klasörü indirin ve bir yere çıkarın.
2. Google Chrome'u açın ve adres çubuğuna `chrome://extensions` yazın.
3. Sağ üst köşedeki **Geliştirici Modu**'nu (Developer Mode) açın.
4. Sol üstteki **"Paketlenmemiş öğe yükle"** (Load unpacked) butonuna tıklayın.
5. İndirdiğiniz `KickNotif` klasörünü seçin.

### 2. Kullanım

1. **Kick.com** adresine gidin.
2. Sağ üst menüde veya sohbetin yanında yeni eklenen **At İkonu** butonunu göreceksiniz.
3. Tıklayarak topluluğa katılın, renginizi seçin ve kaydedin.
4. Artık KaanFlix'in sohbetinde rozetiniz görünecek!

## 🛠️ Teknik Detaylar

- **Frontend**: HTML5, CSS3 (Glassmorphism, Neon Efektler), jQuery.
- **Backend API**: Node.js/Express (Render üzerinde barındırılan `kicknotif-backend`).
- **Veri Tabanı**: Topluluk kullanıcıları gerçek zamanlı senkronize edilir.
- **Güvenlik**: "Ghost Badge" koruması ve yetkisiz rozet kullanımını engelleyen doğrulamalar.
- **Dil**: Tamamen Türkçe arayüz ve loglama sistemi.

---

**Sürüm**: 1.0 - Dev by sketur60
_KaanFlix topluluğu için sevgiyle geliştirildi._
