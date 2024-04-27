# Store-Crud-Operation-With-Spring-Boot-Mvc
# Spring Boot MVC CRUD Demo - Store Application

Bu proje, Spring Boot, Thymeleaf, MySQL ve Spring Data JPA kullanılarak geliştirilmiş bir CRUD (Create, Read, Update, Delete) demo uygulamasıdır. Bu uygulama, bir mağaza sisteminin temel işlevlerini içerir: ürün ekleme, görüntüleme, güncelleme ve silme.

## Başlarken

Projenin yerel ortamınıza kurulumu ve çalıştırılması için aşağıdaki adımları izleyin:

1. **Gereksinimler**: Projenin çalışması için Java 21, Maven, ve MySQL kurulu olmalıdır.

2. **MySQL Veritabanı Ayarları**:
    - MySQL veritabanınızda bir veritabanı oluşturun (örneğin: `store_demo`).
    - `application.properties` dosyasında, `spring.datasource.url`, `spring.datasource.username` ve `spring.datasource.password` alanlarını kendi MySQL ayarlarınıza göre yapılandırın.

3. **Projeyi İndirin**:
    ```bash
    git clone https://github.com/your_username/store-demo.git
    ```

4. **Uygulamayı Başlatın**:
    - Terminalde proje klasörüne gidin ve aşağıdaki komutu çalıştırın:
    ```bash
    mvn spring-boot:run
    ```
    - Uygulama başarıyla başladığında, tarayıcınızda `http://localhost:8080` adresine giderek uygulamayı görüntüleyebilirsiniz.

## Kullanılan Teknolojiler

- Spring Boot
- Spring MVC
- Thymeleaf
- Spring Data JPA
- MySQL

## Proje Yapısı


![1](https://github.com/Ulasgltkn/Store-Crud-Operation-With-Spring-Boot-Mvc/assets/103432181/85f04cf2-9c8a-4be1-bf08-0ea61a7b0ccb)
![2](https://github.com/Ulasgltkn/Store-Crud-Operation-With-Spring-Boot-Mvc/assets/103432181/6e8dd130-10a8-40da-8348-02f9a484a6b7)
![3](https://github.com/Ulasgltkn/Store-Crud-Operation-With-Spring-Boot-Mvc/assets/103432181/338df43e-d77b-486e-ab7f-715900daf070)
![4](https://github.com/Ulasgltkn/Store-Crud-Operation-With-Spring-Boot-Mvc/assets/103432181/f0650af0-fe5f-4981-94a3-47d3e045d567)
![5](https://github.com/Ulasgltkn/Store-Crud-Operation-With-Spring-Boot-Mvc/assets/103432181/ca1f0e2e-fdad-4257-b2f1-7495ce785aa3)
