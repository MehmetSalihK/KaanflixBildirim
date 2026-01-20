# Gizlilik Politikası (Privacy Policy)

**Son Güncelleme:** 20 Ocak 2026

**KaanFlix Bildirim - Topluluk Sürümü (v2.0)** ("biz", "bizim" veya "eklenti") olarak, kullanıcılarımızın gizliliğine en üst düzeyde önem veriyoruz. Bu Gizlilik Politikası, **Google Chrome Web Mağazası Geliştirici Program Politikaları**'na tam uyumlu olarak hazırlanmış olup, verilerinizin nasıl işlendiğini şeffaf bir şekilde açıklar.

## 1. Veri Toplama ve Kullanım

Bu eklenti, veri minimizasyonu ilkesine göre tasarlanmıştır. **Kişisel verileriniz satılmaz, kiralanmaz veya üçüncü taraflarla ticari bir amaçla paylaşılmaz.**

### 1.1. Otomatik Olarak Toplanan Bilgiler (Yerel)

Eklentinin çalışması için gerekli olan aşağıdaki veriler, yalnızca tarayıcınızın kendi güvenli depolama alanında (`chrome.storage.local`) saklanır ve cihazınızdan dışarı aktarılmaz:

- **Kullanıcı Tercihleri:** Bildirim sesi durumu, ses seviyesi, tema tercihleri, **Sidebar animasyon durumu**.
- **Önbellek Verileri:** Son yayın durumu takibi (tekrarlayan bildirimleri önlemek için)
- **Oturum Verileri:** Admin panel oturum bilgileri (sadece yerel tarayıcıda, 2 saat geçerli)

### 1.2. Harici Hizmetler ve Veri İletimi

Eklenti, işlevlerini yerine getirebilmek için sınırlı durumlarda dış sunucularla iletişim kurar:

- **Yayın Durumu:** `kick.com` API'sinden yalnızca "Canlı Yayın" bilgisini (başlık, izleyici sayısı, mesajlar) çeker. Bu işlem sırasında kişisel kimlik veriniz gönderilmez.
- **Topluluk Özellikleri (İsteğe Bağlı):** Eğer "Topluluk Rozeti" özelliğini aktif ederseniz; seçtiğiniz Kullanıcı Adı ve Rozet Rengi, eklentinin güvenli arka uç sunucusunda (`kicknotif-backend.onrender.com`) işlenir. Bu veri, yalnızca diğer topluluk üyelerine rozetinizi göstermek amacıyla kullanılır.
- **Admin Panel (Yönetici Kullanımı):** Admin paneli üzerinden gönderilen bildirimler, ekran işgali içerikleri ve profil resimleri yerel sunucunuzda (`localhost:3000`) saklanır ve yalnızca eklenti kullanıcılarına iletilir.
- **Link Toplayıcı:** Chat'te paylaşılan linkler, spam tespiti için yerel sunucunuzda geçici olarak saklanır. Bu veriler üçüncü taraflarla paylaşılmaz.

### 1.3. GELİŞMİŞ GÜVENLİK BEYANI (Kullanıcı Güvenliği)

Topluluğumuzun güvenliği bizim için her şeyden önemlidir. Bu eklenti:

- **ASLA** arka planda kripto para madenciliği (mining) yapmaz.
- **ASLA** IP adresinizi kaydetmez veya izlemez (IP Logger yoktur).
- **ASLA** tarayıcı çerezlerinizi (cookies) çalmaz veya başka bir sunucuya göndermez.
- **ASLA** kişisel dosyalarınıza erişmez.

### 1.4. Admin Panel Özellikleri

Admin paneli (`localhost:3000/admin`) şifre korumalıdır ve yalnızca yetkilendirilmiş kişiler tarafından kullanılmalıdır. Panel üzerinden:

- **Bildirimler:** Kullanıcılara Windows bildirimleri gönderebilirsiniz
- **Ekran İşgali:** Kick.com sayfasında tam ekran overlay gösterebilirsiniz
- **Profil Resmi Yönetimi:** Online/Offline durumuna göre profil resmi değiştirebilirsiniz
- **Link Toplayıcı:** Chat'te paylaşılan linkleri izleyebilir ve spam tespiti yapabilirsiniz
- **Topluluk Yönetimi:** Rozet sahibi kullanıcıları görüntüleyebilirsiniz
- **Geçmiş (Logs):** Tüm admin işlemleri kayıt altına alınır

## 2. İzinlerin Kullanım Gerekçeleri

Eklentinin talep ettiği izinler, "Tek Amaç" (Single Purpose) politikasına uygun olarak yalnızca temel işlevler için kullanılır:

- **`alarms`:** Arka planda kaynak tüketmeden periyodik yayın kontrolü yapmak için
- **`notifications`:** Yayın başladığında kullanıcıyı haberdar etmek için
- **`storage`:** Kullanıcı ayarlarını yerel olarak hatırlamak için
- **`offscreen`:** Arka planda özel bildirim sesi (.mp3) oynatabilmek için (Chrome teknik gerekliliği)
- **Host Permissions (Site Erişimi):**
  - `https://kick.com/*`: Yayın verilerini çekmek, sohbet mesajlarını okumak ve rozet eklemek için
  - `https://www.youtube.com/*`: Yayıncının son YouTube videolarını göstermek için
  - `https://kicknotif-backend.onrender.com/*`: Topluluk verilerini senkronize etmek için
  - `http://localhost:3000/*`: Admin panel ile iletişim kurmak için (sadece yerel kullanım)

## 3. Üçüncü Taraf Hizmetleri

Hizmetimizi sağlamak için aşağıdaki güvenilir altyapı sağlayıcılarını kullanıyoruz:

- **Kick.com & YouTube:** İçerik verisi kaynağı olarak
- **Render.com:** Topluluk sunucusu barındırma hizmeti olarak
- **Socket.IO:** Gerçek zamanlı bildirim iletimi için

## 4. Veri Güvenliği

- Tüm veri iletişimi endüstri standardı **HTTPS (SSL/TLS)** şifrelemesi ile korunmaktadır
- Admin panel şifre korumalıdır (`AdalSexModu31`)
- Oturum bilgileri 2 saat sonra otomatik olarak sona erer
- Yerel sunucu (`localhost:3000`) sadece sizin bilgisayarınızda çalışır

## 5. Veri Saklama ve Silme

- **Yerel Veriler:** Tarayıcı önbelleğini temizleyerek silebilirsiniz
- **Topluluk Verileri:** Eklentiyi kaldırarak veya "Kaydı Kaldır" butonunu kullanarak silebilirsiniz
- **Admin Panel Verileri:** `database.json` dosyasını silerek veya ilgili "Temizle" butonlarını kullanarak silebilirsiniz

## 6. Çocukların Gizliliği

Bu eklenti 13 yaşın altındaki bireyleri hedeflemez ve onlardan bilerek kişisel bilgi toplamaz.

## 7. Değişiklikler

Bu Gizlilik Politikası'nda yapılacak değişiklikler, eklenti güncellemeleri ile birlikte duyurulacaktır.

## 8. İletişim

Gizlilikle ilgili her türlü sorunuz için geliştirici ile iletişime geçebilirsiniz:

**Geliştirici:** sketur60  
**E-posta:** contact@mehmetsalihk.fr  
**Discord:** sketur60  
**Proje Deposu:** [GitHub](https://github.com/MehmetSalihK/KaanflixBildirimPannel)
