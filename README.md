# EN: Dockerized Version of the ECommerce_Microservices Project.
This is the Dockerized version of the [ECommerce_Microservices](https://github.com/busraozdemir0) project by [busraozdemir0](https://github.com/busraozdemir0).

Project link: [ECommerce_Microservices](https://github.com/busraozdemir0/ECommerce_Microservices)
## What is Docker?

Docker is a container platform that allows applications to run quickly and portably. Unlike traditional virtual machines, Docker containers operate at the operating system level, running in their isolated environments while efficiently sharing OS resources. This ensures that each container, with its necessary libraries, dependencies, and configurations, can run identically across different environments.

## The Relationship Between Docker and .NET Microservices

- **Containerization**: Docker provides isolation for each .NET microservice, enabling them to operate independently with their own dependencies, configurations, and versions.

- **Portability**: Since Docker images are portable, a .NET microservice running in a development environment can seamlessly run in testing or production environments using the same image.

- **Ease of Management and Deployment**: Docker facilitates faster deployment of microservices. A .NET microservice packaged in a container environment can be easily managed with container orchestration tools like Kubernetes.

## Running the Docker Container

1. Open your command prompt (CMD).
2. Navigate to the solution folder named `ECommerce_Microservices-master` using the `cd` command.

Run the following command to dockerize the project:

```bash
docker-compose up --build
```
If there are no errors, you will see the project's MSSQL database and microservices in Docker Desktop.

![image](https://github.com/user-attachments/assets/a8946341-002b-4a61-9333-55d9afe9eb3d)

The project uses the Code First Approach to dynamically create the database from the .NET Core application and automatically insert data. You will see that Docker creates and begins using the database accordingly.

You can test the microservices running in Docker using Postman.

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

