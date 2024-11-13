# ECommerce_Microservices Projesini Dockerize edilmiş halidir.

Sayın [busraozdemir0](https://github.com/busraozdemir0) adlı kullanıcının ECommerce_Microservices Projesini Dockerize edilmiş halidir...

## Docker Nedir?

Docker, uygulamaları hızlı ve taşınabilir bir şekilde çalıştırmayı sağlayan bir konteyner platformudur. Geleneksel sanal makinelerden farklı olarak, Docker konteynerları işletim sistemi seviyesinde izole edilen, kendi bağımsız ortamlarında çalışan ve işletim sistemi kaynaklarını verimli bir şekilde paylaşan yapılardır. Böylece her konteyner, gerekli kütüphaneler, bağımlılıklar ve ayarlarla birlikte, istediğiniz ortamda aynı şekilde çalıştırılabilir hale gelir.

## Docker ve .NET Mikroservis İlişkisi

- Konteynerizasyon: Docker, her bir .NET mikroservisinin bağımsız çalışması için izolasyon sağlar. Böylece, her mikroservisin kendine ait bağımlılıkları, yapılandırmaları ve versiyonları olabilir.

- Taşınabilirlik: Docker imajları, bir sistemden diğerine taşınabilir olduğundan, geliştirme ortamında çalıştırılan bir .NET mikroservis, aynı imaj kullanılarak test ve üretim ortamlarında da sorunsuz çalışabilir.

- Kolay Yönetim ve Dağıtım: Docker, mikroservislerin daha hızlı dağıtılmasını sağlar. Bir konteyner ortamı içinde paketlenen .NET mikroservis, Kubernetes gibi konteyner orkestrasyon araçları ile kolayca yönetilebilir.

## Docker Konteynır'ını çalıştırma:

CMD' yi açın. ECommerce_Microservices-master isimli çözüm klasörümüze cd komutu ile gidin.

```
docker-compose up --build
```
Komutu ile projeyi dockerize edin. Hata olmaz ise Docker Desktop'ta projenin MSSQL Veritabanı ve Mikroservislerini göreceksiniz. 

![image](https://github.com/user-attachments/assets/a8946341-002b-4a61-9333-55d9afe9eb3d)


# Mikroservis E-Ticaret Projesi
## Proje hakkında

###
Bu proje; mikroservis mimarisi kullanılarak geliştirilmiş mini bir e-ticaret mantığındaki web sitesidir. Kullanıcıların kayıt olup giriş yapabilme, ana sayfadaki ürünleri veya detayları görüntüleme, 
sepete ürün ekleme, sepetteki ürünlere kupon uygulayabilme, ürün ve kupon için ilgili operasyonları gerçekleştirebilme gibi işlemleri içermektedir.

ASP.NET Core 8.0 Web API ve MVC kullanarak geliştirdiğim mikroservis projemde, tüm CRUD işlemleri için Back-End'de Web API kullanılmış olup Front-End'de ise bu API katmanları consume edilmiştir. 
Dinamik veritabanı işlemleri için ise Entity Framework Code First yaklaşımından yararlanılmıştır.
###

# Kullanılan Teknolojiler
- Asp.Net Core 8.0 MVC
- Asp.Net Core 8.0 Web API
- Mikroservis Mimarisi
- MSSQL Server
- Entity Framework Code First
- Swagger
- Identity
- Html, Css
- Bootstrap
- Automapper

# Front-End
- Asp.Net Core 8.0 MVC
- Html
- Css
- Bootstrap
- Toastr Bildirimleri

# Back-End
- Asp.Net Core 8.0 Web API
- MSSQL Server
- Entity Framework
- Swagger
- Automapper
  
# Projenin Öne Çıkan Özellikleri
- Veritabanı işlemleri için Entity Framework Code First kullanımı
- Identity ile Giriş ve Kayıt Olma işlemleri.
- Rolleme
- Ürün ve kuponlara yönelik ilgili CRUD işlemleri
- Ana sayfada listelenen ürünlerin detayını görüntüleme
- Ürünü sepete ekleme, çıkarma (Ürün sepette varsa ürün adeti 1 arttırılmaktadır.)
- Sepetteki ürünlere kupon uygulama, kaldırma


# Projenin Görselleri

### Ana Sayfa 
![Ana ekran](https://github.com/busraozdemir0/ECommerce_Microservices/blob/master/ProjectScreenShots/home1.png)

![Ana sayfa](https://github.com/busraozdemir0/ECommerce_Microservices/blob/master/ProjectScreenShots/home_detail.png)

### Kayıt Ol Sayfası
![Ana sayfa](https://github.com/busraozdemir0/ECommerce_Microservices/blob/master/ProjectScreenShots/registerPage.png)

### Alışveriş Sepeti
![Ana sayfa](https://github.com/busraozdemir0/ECommerce_Microservices/blob/master/ProjectScreenShots/shoppingCart2.png)

![Ana sayfa](https://github.com/busraozdemir0/ECommerce_Microservices/blob/master/ProjectScreenShots/shoppingCart3_coupon.png)

### Kupon Listesi Sayfası
![Ana sayfa](https://github.com/busraozdemir0/ECommerce_Microservices/blob/master/ProjectScreenShots/couponList.png)

### Ürün Listesi Sayfası
![Ana sayfa](https://github.com/busraozdemir0/ECommerce_Microservices/blob/master/ProjectScreenShots/productList.png)

### Ürün Güncelleme İşlemi
![Ana sayfa](https://github.com/busraozdemir0/ECommerce_Microservices/blob/master/ProjectScreenShots/productUpdatePage.png)
