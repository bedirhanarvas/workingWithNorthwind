Northwind with Spring Framework

Bu proje, Northwind veritabanını kullanarak Spring Framework ile geliştirilmiş bir backend uygulamasıdır. Projede Spring Boot, JPA, Hibernate gibi teknolojiler kullanılmış olup, temel CRUD işlemleri gerçekleştirilmiştir.

🚀 Proje İçeriği

Bu projede Northwind veritabanı üzerinden çalışarak aşağıdaki işlemleri gerçekleştirdim:

📌 Spring Boot ile RESTful API oluşturma

📌 Spring Data JPA ile veritabanı yönetimi

📌 Hibernate kullanarak nesne ilişkisel modelleme (ORM)

📌 PostgreSQL/MySQL gibi ilişkisel veritabanlarıyla entegrasyon

📌 Swagger UI ile API dokümantasyonu

📌 Lombok ile kod sadeleştirme

🛠 Kullanılan Teknolojiler

Java 17+

Spring Boot

Spring Data JPA

Hibernate

PostgreSQL / MySQL

Lombok

Swagger UI

🛠 API Örnekleri

📌 Tüm Ürünleri Listeleme
GET /api/products
Dönen Örnek Yanıt:
[
  { "id": 1, "name": "Chai", "price": 18.0 },
  { "id": 2, "name": "Chang", "price": 19.0 }
]
📌 Yeni Bir Ürün Ekleme
POST /api/products
Dönen Örnek Yanıt:
{
  "name": "New Product",
  "price": 25.5
}
