# CafeFlow

**Full-Stack Restoran Yönetim Platformu**

CafeFlow; restoranların masa, sipariş, stok, kullanıcı ve müşteri menüsü gibi operasyonlarını yönetmek amacıyla geliştirilmiş full-stack bir restoran yönetim uygulamasıdır.

Proje; **Java, Spring Boot, PostgreSQL ve Flutter** kullanılarak, REST API tabanlı bir backend mimarisiyle geliştirilmiştir.

## Kullanılan Teknolojiler

### Backend

* Java
* Spring Boot
* Spring Security
* REST API
* JPA / Hibernate
* JWT

### Veritabanı

* PostgreSQL

### Mobil

* Flutter
* Dart

### Geliştirme

* Git
* GitHub
* OOP
* MVC
* Rol Bazlı Yetkilendirme

## Özellikler

* JWT ile kullanıcı kimlik doğrulama
* Rol bazlı yetkilendirme
* Owner ve Waiter kullanıcı rolleri
* Restoran masa yönetimi
* Sipariş yönetimi
* Stok yönetimi
* QR kod ile müşteri menüsü
* Raporlama
* Bildirimler
* Backend ve mobil uygulama arasında REST API iletişimi

## Uygulama Yapısı

### Backend

Backend, **Java ve Spring Boot** kullanılarak geliştirilmiştir ve uygulamanın iş mantığı ile veri yönetimi için REST API endpoint'leri sağlamaktadır.

Kimlik doğrulama ve yetkilendirme işlemleri için **Spring Security ve JWT** kullanılmaktadır.

### Veritabanı

İlişkisel veritabanı olarak **PostgreSQL** kullanılmaktadır.

Backend ile veritabanı arasındaki iletişim **JPA / Hibernate** üzerinden sağlanmaktadır.

### Mobil Uygulama

Mobil uygulama **Flutter ve Dart** kullanılarak geliştirilmiştir.

Kullanıcının rolüne göre farklı uygulama akışları ve erişim yetkileri sunulmaktadır.

## Kullanıcı Rolleri

### Owner

* Restoran yönetimi
* Masa yönetimi
* Stok yönetimi
* Raporlama
* Kullanıcı işlemleri

### Waiter

* Masa işlemleri
* Sipariş yönetimi
* Restoran operasyon süreçleri

### Customer

* QR kod üzerinden restoran menüsüne erişim

## Deployment

Backend bir **cloud ortamına deploy edilmiş** ve Flutter mobil uygulaması ile REST API üzerinden iletişim sağlayacak şekilde yapılandırılmıştır.

## Proje Ekran Görüntüleri
## Proje Ekran Görüntüleri

<p align="center">
  <b>Giriş Ekranı</b><br>
  <img src="screenshots/login.jpg" width="300">
</p>

<p align="center">
  <b>Owner Paneli</b><br>
  <img src="screenshots/owner_dashboard 1.jpg" width="300">
  <img src="screenshots/owner_dashboard 2.jpg" width="300">
</p>

<p align="center">
  <img src="screenshots/owner_menu.jpg" width="300">
  <img src="screenshots/owner_order details.jpg" width="300">
</p>

<p align="center">
  <b>Ürün Yönetimi</b> &nbsp;&nbsp;&nbsp; <b>Sipariş Yönetimi</b><br>
  <img src="screenshots/owner_product management.jpg" width="300">
  <img src="screenshots/owner_order management.jpg" width="300">
</p>

<p align="center">
  <b>Masa Yönetimi</b><br>
  <img src="screenshots/owner_table management.jpg" width="280">
  <img src="screenshots/owner_table_order  history.jpg" width="280">
  <img src="screenshots/owner_tableqr.jpg" width="280">
</p>

<p align="center">
  <b>Raporlar ve Analitik</b><br>
  <img src="screenshots/owner_reports and analyses 1.jpg" width="300">
  <img src="screenshots/owner_reports and analyses 2.jpg" width="300">
</p>

<p align="center">
  <img src="screenshots/owner_reports and analyses pdf 1.jpg" width="300">
  <img src="screenshots/owner_reports and analyses pdf 2.jpg" width="300">
</p>

<p align="center">
  <b>Personel Yönetimi</b> &nbsp;&nbsp;&nbsp; <b>Ayarlar</b><br>
  <img src="screenshots/owner_user management.jpg" width="300">
  <img src="screenshots/owner_settings.jpg" width="300">
</p>
<p align="center">
  <b>Waiter Paneli</b><br>
  <img src="screenshots/waiter_panel.jpg" width="300">
</p>

<p align="center">
  <b>Masa Sipariş Bilgisi</b> &nbsp;&nbsp;&nbsp; <b>Masa Ödeme Al & Masa Kapat</b><br>
  <img src="screenshots/waiter_table_orders.jpg" width="300">
  <img src="screenshots/waiter_table payment.jpg" width="300">
</p>

<p align="center">
  <b>Yeni Sipariş Ekle</b><br>
  <img src="screenshots/waiter_add new order products.jpg" width="300">
  <img src="screenshots/waiter_add new order.jpg" width="300">
</p>
<p align="center">
  <b>Siparişler</b> &nbsp;&nbsp;&nbsp; <b>Ayarlar</b><br>
  <img src="screenshots/waiter_orders.jpg" width="300">
  <img src="screenshots/waiter_settings.jpg" width="300">
</p>
<p align="center">
  <b>Müşteri Qr Sipariş Menü</b><br>
  <img src="screenshots/customer_menu.png" width="200">
  <img src="screenshots/customer_menu_placeanorder.png" width="200">
  <img src="screenshots/customer_menu_orderreceived.png" width="200">
</p>
## Proje Durumu

Bu proje; backend geliştirme, mobil uygulama geliştirme, veritabanı yönetimi, kimlik doğrulama, yetkilendirme ve cloud deployment konularında pratik deneyim kazanmak amacıyla geliştirilmiş kapsamlı bir full-stack uygulamadır.
