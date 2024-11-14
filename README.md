# TR: ECommerce_Microservices Projesini Dockerize edilmiş halidir.

Sayın [busraozdemir0](https://github.com/busraozdemir0) adlı kullanıcının ECommerce_Microservices Projesini Dockerize edilmiş halidir...

Proje linki: [ECommerce_Microservices](https://github.com/busraozdemir0/ECommerce_Microservices)

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

Proje Code First Approach metodu kullanarak dinamik şekilde veritabanını, .NET Core Uygulaması bazı ile yaratıp verileri otomatik girmesi sayesinde Docker'ınız daki veritabanını yarattığını ve kullanmaya başlayacağını göreceksiniz. 

Postman ile Docker'ınız da çalıştırdığınız mikroservisleri test edebilirsiniz. 

