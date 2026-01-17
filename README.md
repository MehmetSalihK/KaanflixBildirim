# 🔴 KaanFlix Bildirim - Topluluk Sürümü

**KaanFlix** (**Kaan Varlı**) ve topluluğu için özel olarak geliştirilmiş, Kick.com deneyimini zenginleştiren, görsel ve işlevsel özelliklerle donatılmış gelişmiş bir Chrome eklentisi.

![Preview](images/icon_on_128.png)

## ✨ Temel Özellikler

### 🎥 Canlı Yayın & Bildirimler (Gelişmiş)

- **Anlık Bildirimler**: KaanFlix yayına girdiği anda Windows bildirimi ve özel **"At Sesi"** uyarısı.
- **Ses Kontrolü**: Bildirim ses seviyesini doğrudan eklenti üzerinden ayarlayabilme (0% - 100%).
- **Akıllı Algılama**:
  - **Hibrit Kontrol**: API ve HTML Scraping ("Son canlı yayın zamanı" metni kontrolü) birleştirilerek %100 doğruluk.
  - **Hatalı Bildirim Koruması**: "Ghost live" durumlarını süzer, sadece gerçek yayınları bildirir.

### ⚡ v1.5- Yeni Nesil Özellikler (YENİ)

- **🦾 Ekran Efektleri (Screen Takeover)**: Yayıncının yönettiği "Sistem Hacklendi" tarzı **Cyberpunk/Glitch** animasyonları ve özel duyurular ekranınızda belirir.
- **🛡️ Anti-Spam Bildirim**: İnternet kopmalarında veya anlık kesintilerde (Anti-Flap) bildirim tekrarını önleyen akıllı sistem.
- **👻 Ghost Mode**: Arka planda %0 CPU kullanımı ile sessiz çalışma. F12 konsolunda hiçbir iz bırakmaz.

### 🎨 Görsel Özelleştirmeler (Profil)

KaanFlix'in profili (`kick.com/kaanflix`) artık duruma göre şekil değiştiriyor:

- **🟢 CANLI Modu**:
  - Avatarın etrafında **Gökkuşağı (Rainbow)** animasyonu döner.
  - "LIVE" rozeti nabız gibi atar (Pulse efekti).
- **⚫ ÇEVRİMDIŞI Modu**:
  - Avatar **Siyah/Beyaz (Grayscale)** olur.
  - Avatarın üzerinde **"Zzz" uyku animasyonu** belirir.
  - Başlıkta özel "ÇEVRİMDIŞI" görseli aktif olur.

### 👥 Topluluk Sistemi

Eklenti üzerinden **KaanFlix** topluluğuna katılın:

- **Özel Rozetler**: Sohbette isminizin yanında özel bir topluluk rozeti (**at ikonu**) belirir.
- **Canlı Senkronizasyon**: Rozetiniz, eklentiyi kullanan diğer tüm izleyiciler tarafından anında görülür.
- **Kişiselleştirme**: Sohbet renginizi (Cyan/Mor) seçin.
- **Sadece Hedef Kanalda**: Rozetler yalnızca `kick.com/kaanflix` kanalında aktiftir.

### 📺 Sosyal Medya Dock'u

- **Entegre Menü**: YouTube, Instagram, TikTok ve Discord'a hızlı erişim sağlayan iOS tarzı "Glassmorphism" menü.
- **YouTube Shorts & Videolar**: Son içerikleri otomatik çeker ve listeler.

## 🚀 Kurulum

### 1. Eklentiyi Yükleme

1. Bu klasörü indirin (veya `git clone` ile alın).
2. Google Chrome'u açın ve adres çubuğuna `chrome://extensions` yazın.
3. Sağ üst köşedeki **Geliştirici Modu**'nu (Developer Mode) açın.
4. Sol üstteki **"Paketlenmemiş öğe yükle"** (Load unpacked) butonuna tıklayın.
5. İndirdiğiniz `KickNotif` klasörünü seçin.

### 2. Kullanım

1. **Kick.com** adresine gidin.
2. Sağ üst menüde veya sohbetin yanında yeni eklenen **At İkonu** butonunu göreceksiniz.
3. Tıklayarak topluluğa katılın, renginizi seçin ve ses seviyenizi ayarlayın.
4. Artık KaanFlix'in sohbetinde rozetiniz görünecek, yayın bildirimlerini alacak ve özel hacker efektlerine hazır olacaksınız!

## 🛠️ Teknik Detaylar

- **Frontend**: HTML5, CSS3 (Glassmorphism, Neon Efektler, Keyframe Animasyonları), jQuery.
- **Backend API**: Node.js/Express (Render üzerinde barındırılan sistem).
- **Veri Tabanı**: Topluluk kullanıcıları `database.json` üzerinde tutulur ve WebSocket benzeri polling ile senkronize edilir.
- **Güvenlik**:
  - **Ghost Badge Koruması**: Yetkisiz rozet kullanımını engelleyen sunucu tabanlı doğrulama.
  - **Güvenli İletişim**: Tüm veri trafiği HTTPS üzerinden şifrelenir.
- **Dil**: Tamamen Türkçe arayüz ve loglama sistemi.

## 🔒 Gizlilik ve Güvenlik

Kullanıcı verilerinizin güvenliği bizim için önceliklidir. Detaylı bilgi için [GUVENLIK_ACIKLAMASI.md](GUVENLIK_ACIKLAMASI.md) dosyasını inceleyebilirsiniz.

---

**Geliştirici**: sketur60 -
_KaanFlix topluluğu için sevgiyle geliştirildi._
