# KaanFlix Bildirim Eklentisi (v2.0) - Güvenlik Açıklaması 🛡️

## 🚨 ÖZET: Eklenti %100 Güvenlidir.

> Bu eklenti **Kaanflix'e özel** geliştirilmiştir.  
> v2.0 güncellemesi ile performans optimize edilmiş ve **CPU kullanımı minimuma indirilmiştir.**

Merhaba arkadaşlar! Toplulukta eklentiyle ilgili bazı yanlış anlaşılmalar (Trojan, Kripto Madenciliği, Çerez Çalınması vb.) olduğunu duydum. Geliştirici olarak içinizi rahatlatmak ve teknik detayları **şeffaf** bir şekilde açıklamak istiyorum.

## 🔍 İddialara Teknik Cevaplar

### ❌ İddia 1: "Çerezleri (Cookies) Çalıyor"

**GERÇEK:** Kesinlikle hayır.

- **Kanıt:** Eklenti kodunda (JavaScript) `document.cookie` verisini dışarıya (başka bir sunucuya) gönderen HİÇBİR satır kod yoktur.
- **Neden 'storage' izni var?**: Sadece sizin **ayarlarınızı** (Ses düzeyi, Rozet rengi, Seçtiğiniz kanal) tarayıcınızın kendi hafızasına kaydetmek için kullanılır. Bu veriler bilgisayarınızdan dışarı çıkmaz.

### ❌ İddia 2: "Kripto Mining Yapıyor / PC Kasıyor"

**GERÇEK:** İmkansız.

- **Kanıt:** v2.0 güncellemesiyle eklentiye **"Akıllı Bekleme"** özelliği eklendi. Tarayıcıyı yoran işlemler (MutationObserver) saniyenin onda biri kadar çalışır ve sonra uykuya geçer. Görev Yöneticisi'ni açıp Chrome'un CPU kullanımına bakarsanız eklentinin %0.1 bile harcamadığını görebilirsiniz.

### ❌ İddia 3: "Trojan / Virüs Var"

**GERÇEK:** Bu bir Chrome Eklentisi (.CRX / .ZIP), bir `.EXE` dosyası değildir.

Chrome Eklentileri, tarayıcının "Kum havuzu" (Sandbox) dediği güvenli ortamda çalışır. Bilgisayarınızın dosyalarına, şifrelerine veya sistem ayarlarına erişemez. Google Web Store'a yüklenirken Google'ın güvenlik taramalarından geçer.

### ❌ İddia 4: "IP Logger Var / IP Çalıyor"

**GERÇEK:** Kesinlikle hayır.

- **Kanıt:** Eklenti, sadece rozetleri göstermek için sunucuyla iletişim kurar. İnternetteki HER siteye (Google, YouTube dahil) girdiğinizde IP adresiniz iletişim için kullanılır, bu internetin doğasıdır. Ancak bu eklentide veya sunucuda IP adresinizi kaydeden, takip eden veya depolayan **HİÇBİR** sistem yoktur.

### ❌ İddia 5: "API Güvensiz / Herkes Herkesi Silebilir"

**GERÇEK:** Hayır, bu açık kapatıldı.

- **Kanıt:** Kayıt sistemi artık **UUID (Gizli Anahtar)** teknolojisi ile korunmaktadır. Eklenti, kaydolurken size özel gizli bir anahtar üretir. Bu anahtar olmadan kimse (geliştirici hariç) kaydınızı silemez veya değiştiremez.

## 🛠️ v2.0 ile Neler Değişti? (Güvenlik & Performans)

Yeni sürümde sizin güvenliğiniz ve bilgisayar performansınız için şunları yaptık:

1. **Sidebar Animasyon Anahtarı:** İsterseniz yan menü animasyonlarını tamamen kapatarak CPU tasarrufu yapabilirsiniz.
2. **Akıllı Bildirim:** Bildirimleri kapatınca ses de otomatik kapanır, gereksiz işlem yapmaz.
3. **Kick API Kontrolü:** Her dakikada bir `kick.com/api/v1/channels/kaanflix` adresine "Yayında mı?" diye sorar.
4. **Görsel Düzenleme (Inject):** Kick sayfasına girdiğinizde sadece gerekli scriptler çalışır, gereksiz kodlar silindi.

## 🤝 Güvenlik Garantisi

> Kodların güvenliği konusundaki en büyük teminatımız, **kaynak kodlarının incelenmek üzere sadece Kaanflix'e teslim edilmesidir.**  
> Eklenti onaylanıp paylaşıldığında, tamamen güvenli olduğundan emin olabilirsiniz.
>
> **Gönül rahatlığıyla kullanabilirsiniz! 💚**

---

_Saygılarımla,_  
**KaanFlix Bildirim! (v2.0) - Dev By sketur60**
