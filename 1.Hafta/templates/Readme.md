# Personel Takip Sistemi
Bu proje, bir şirket veya kurumun personellerini takip edebilmesini sağlayan basit ve kullanıcı dostu web tabanlı bir yönetim paneli uygulamasıdır.


## Tasarım Özellikleri
- Bootstrap 5 framework kullanım: Modern tasarım ve hızlı geliştirme için Bootstrap 5 kullanılmıştır.
- Bootstrap Icons entegrasyonu: İkonlar kullanılarak kullanıcı arayüzü zenginleştirilmiştir.
- Kullanıcı dostu arayüz: Kolay navigasyon ve anlaşılır bir arayüz sunulmuştur.
- Personel yönetimi: Personel bilgileri ekleme, düzenleme, silme işlemleri yapılabilir.
- Raporlama: Personel maaş ortalamaları, pozisyon dağılımı gibi raporlar kullanıcıya sunulmaktadır.

## Sayfalar

### 1. **Dashboard (Ana Sayfa)**
- **Personel Takip Sistemi** başlığı altında kullanıcıya genel bilgi sunulur.
- Personel'in iş hakkında kendi bilgilerini görebilmesi mümkündür'.

### 2. **Personel Ekleme (ekleme.html)**
- Yeni personel eklemek için bir form sunulur.
- Personel adı, soyadı, pozisyonu, maaşı, işe başlama tarihi gibi alanlar doldurulup form kaydedilir.
- Ekleme formu başarıyla gönderildikten sonra personel veritabanına eklenir.

### 3. **Login (login.html)**
- Kullanıcıların sisteme giriş yapabilmesi için e-posta ve şifre ile giriş yapabileceği bir sayfa.
- Giriş başarılı olduğunda personel kendisi hakkındaki bilgilere ulaşabilir.

### 4. **Register (register.html)**
- Yeni kullanıcıların sisteme kaydolması için form alanları sunulur.
- Kullanıcı adı, e-posta, şifre ve şifre tekrar alanları doldurularak kaydolunur.

### 5. **Raporlar (raporlar.html)**
- Personel maaş ortalaması, pozisyonlara göre çalışan dağılımı ve işe başlama tarihine göre sıralı çalışanlar gibi istatistiksel raporlar görüntülenir.
- İstatistik kartları ve detaylı raporlar admin sayfasında görsel bir şekilde sunulur.

### 6. **Personel Listesi (listesi.html)**
- Personellerin listelendiği, her bir personel için düzenleme ve silme işlemlerinin yapılabildiği bir sayfa olarak tasarlanmıştır.
- Admin sayfaya yeni personel ekleyebilir, raporlar sayfasına ulaşabilir, personeller hakkındaki bilgilere ulaşabilir.

## Kullanılan Teknolojiler

- HTML5: Web sayfalarının yapısal tasarımı için kullanıldı.
- CSS3: Sayfa stil ve tasarımı için kullanıldı.
- Bootstrap 5: Responsive tasarım ve hızlı geliştirme için kullanıldı.
- Bootstrap Icons: Görsel öğelerin yerleştirilmesi için simgeler kullanıldı.
- Jinja2 Template Engine: Dinamik içerik için Jinja2 şablon motoru kullanıldı.
- Python Flask: Backend geliştirme ve web uygulaması sunucusu olarak kullanıldı.

## Proje Yapısı

## Proje Yapısı

```
1.Hafta/
├── templates/
│   ├── admin.html
│   ├── base.html
│   ├── dashboard.html
│   ├── ekleme.html
│   ├── index.html
│   ├── liste.html
│   ├── login.html
│   ├── raporlar.html
│   └── register.html
```
## Tasarım Özellikleri

### Renkler
- Primary: Mavi (#0d6efd)
- Success: Yeşil (#198754)
- Info: Açık Mavi (#0dcaf0)
- Warning: Sarı (#ffc107)

### Responsive Tasarım
- Tablet ve masaüstü için optimize edilmiş görünüm: Sayfa, farklı cihaz boyutlarına göre optimize edilmiştir.
- Grid sistemi ile esnek yerleşim: Sayfa elemanları grid sistemi kullanılarak yerleştirilmiştir.

### Kartlar
- Gölgeli tasarım: Kartlar, kullanıcı arayüzüne modern bir görünüm kazandırmak için gölgelendirilmiştir.
- Hover efektleri: Kartlar üzerinde hover efektleri ile görsel etkileşim sağlanır.
- İkon entegrasyonu: Her kartta ve butonlarda simgeler kullanılarak görsel zenginlik sağlanmıştır.
- Badge'ler ile kategori gösterimi: Her personel pozisyonu ve durumu badge'ler ile gösterilmektedir.
