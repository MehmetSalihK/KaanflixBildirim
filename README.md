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

### ⚡ v2.0 - Optimize Edilmiş Sürüm (PERFORMANS GÜNCELLEMESİ)

- **🦾 Sidebar Animasyon Toggle**: Yan menüdeki sürekli hareket eden animasyonları kapatarak CPU tasarrufu (düşük sistemler için).
- **🚀 Performans Modu**: Eklenti artık tarayıcıyı yormuyor. MutationObserver optimize edildi (%90 daha az işlemci kullanımı).
- **🛡️ Akıllı Bildirimler**: "Bildirimleri Kapat" dediğinizde ses de otomatik kapanır.
- **🛡️ Güvenlik & Gizlilik (ÖNEMLİ)**:
  - **IP Logger YOKTUR**.
  - **Kripto Mining YAPMAZ**.
  - **Çerez (Cookie) ÇALMAZ**.
  - _Kod tamamen açık kaynaktır ve güvenlidir._

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

## 🚀 Kurulum & Erişim

⚠️ **BU PROJE ÖZELDİR**

Bu eklenti ve kaynak kodları, güvenlik amacıyla **sadece Kaanflix ile paylaşılacaktır.**
Halka açık bir indirme linki veya mağaza sayfası bulunmamaktadır.

Kodlar güvenlik incelemesi için doğrudan iletilecektir.

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
