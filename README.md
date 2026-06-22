# PostManagement

## Türkçe

SocialManagement, ASP.NET Core MVC ve jQuery kullanılarak geliştirilmiş tam kapsamlı bir sosyal medya yönetim sistemidir. Sistem hem **admin paneli** hem de **kullanıcı (frontend) tarafı** içermektedir.

Kullanıcılar içerikleri görüntüleyebilir ve postlar hakkında şikayet oluşturabilir. Admin paneli üzerinden ise tüm içerik, şikayet ve log yönetimi yapılır.

---

## Özellikler

### Admin Panel
- Post yönetimi (CRUD)
- Şikayet yönetimi (görüntüleme, düzenleme, çözümleme)
- Aktivite log takibi
- Arama ve filtreleme sistemi
- AJAX tabanlı veri işlemleri
- Excel export (EPPlus)
- PDF export (QuestPDF)
- Dashboard istatistikleri
- CreatedAt tarih yönetimi

### User (Kullanıcı Paneli)
- Post listeleme
- Post detay görüntüleme
- Şikayet oluşturma (Complaint submission)
- Sosyal medya benzeri akış arayüzü
- Dinamik veri yükleme (AJAX)

---

## Kullanılan Teknolojiler

- ASP.NET Core MVC
- Entity Framework Core
- jQuery
- Bootstrap
- SQL Server
- QuestPDF
- EPPlus
- AJAX

---

## Proje Mimarisi

- MVC (Model - View - Controller)
- Controller tabanlı API endpoint yapısı (JSON)
- AJAX tabanlı frontend iletişimi
- Admin/User ayrımı
- Katmanlı veri yönetimi

---

## English

SocialManagement is a full-featured social media management system built with ASP.NET Core MVC and jQuery. The system includes both an **admin panel** and a **user-facing interface**.

Users can view posts and submit complaints about them. Admins manage posts, complaints, and system logs through a dedicated panel.

---

## Features

### Admin Panel
- Post management (CRUD operations)
- Complaint management (view, update, resolve)
- Activity log tracking
- Dynamic search and filtering
- AJAX-based operations
- Excel export (EPPlus)
- PDF export (QuestPDF)
- Dashboard statistics
- CreatedAt date handling

### User Panel
- Post listing
- Post detail view
- Complaint submission (users can report posts)
- Social media style feed UI
- AJAX-based dynamic loading

---

## Technologies Used

- ASP.NET Core MVC
- Entity Framework Core
- jQuery
- Bootstrap
- SQL Server
- QuestPDF
- EPPlus
- AJAX

---

## Notes

- Users can create complaints for posts
- Admin reviews and resolves complaints
- PDF and Excel reports are available in admin panel
- Project is designed for portfolio and learning purposes
