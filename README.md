```Sinema Müşteri Yönetim Sistemi
Bu proje, bir sinema işletmesi için müşteri, film ve salon kayıtlarının yapılabileceği basit bir Java tabanlı konsol uygulamasıdır. Kullanıcılar, sistem üzerinden yeni kayıtlar oluşturabilir ve mevcut bilgileri görüntüleyebilir.

Projenin Amaçları ve Fonksiyonları
Amaç:
Sinema müşterilerini, filmleri ve salonları takip etmek için kullanışlı bir sistem tasarlamak.

Sistemin Yetkinlikleri:
Müşteri Kayıtları:
Müşteri ekleyebilir ve bu müşterileri salonlara atayabilirsiniz.
Film Yönetimi:
Yeni filmleri sisteme ekleyebilir ve filmlerle ilgili bilgileri görüntüleyebilirsiniz.
Salon Yönetimi:
Yeni salon oluşturabilir, salondaki mevcut filmi ve kayıtlı müşterileri görebilirsiniz.
Projenin Teknik Özellikleri
1. Kullanılan Sınıflar
BaseEntity:
Müşteri ve salon gibi ortak özelliklere sahip sınıflar için temel bir yapı.
id ve name gibi temel özellikleri içerir.
Musteri:
Müşteri bilgilerini barındıran sınıf. BaseEntity’den türetilmiştir.
Film:
Film adı, türü ve süresi gibi detayları içeren sınıf.
Salon:
Bir salonda hangi filmin gösterildiğini ve kayıtlı müşteri listesini tutan sınıf. BaseEntity’den türetilmiştir.
2. Interface Kullanımı
IBiletSistemi:
Sistem için gerekli bazı metotları (örneğin müşteri ekleme ve film ekleme) tanımlar.
Salon sınıfı bu interface’i kullanarak söz konusu metotları uygular.
3. Çok Biçimlilik (Polymorphism)
BaseEntity sınıfındaki bilgiGoster() metodu, türetilen sınıflarda (Musteri ve Salon) farklı bir biçimde çalışacak şekilde özelleştirilmiştir.
Kullanıcı İşlemleri
Sistem, aşağıdaki işlemleri gerçekleştirebilecek şekilde tasarlanmıştır:

Yeni Müşteri Ekleme: Sisteme yeni müşteri bilgileri kaydedilir.
Yeni Film Ekleme: Filmlerin adı, türü ve süresi gibi bilgileri sisteme girilebilir.
Yeni Salon Ekleme: Salon bilgileri sisteme kaydedilir.
Filmleri Listeleme: Sisteme eklenen tüm filmlerin detayları görüntülenebilir.
Salon Bilgilerini Görüntüleme: Salonlar ve oynatılan filmler hakkında bilgi alınabilir.
Salona Müşteri Ekleme: Bir müşteriyi belirli bir salona kaydedebilirsiniz.
Salon Müşteri Listesini Görme: Salonlara atanmış müşterilerin detayları görüntülenebilir.
Çıkış Yapma: Uygulama sonlandırılır.
```
