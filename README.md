# Library Automation System (Kütüphane Otomasyon Sistemi)

## English

This project is a simple Library Automation System developed in Java using the Swing framework for the graphical user interface. It allows users to manage library books, borrow, return, and order books, and stores user and book information in a Microsoft Access database.

### Features

- User login and authentication
- Borrowing books from the library
- Returning borrowed books
- Placing orders for new books
- Storing book and user information in an Access database
- Exporting book orders to a file
- Simple, user-friendly interface

### Technologies Used

- Java SE (Swing for GUI)
- Microsoft Access (Database)
- UCanAccess JDBC Driver (for database connection)

### Installation and Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/barisbutun/Kutuphane_Otomasyon_Sistemi.git
   ```

2. **Open the project in your preferred Java IDE (e.g., NetBeans, IntelliJ IDEA, Eclipse).**

3. **Install the [UCanAccess](http://ucanaccess.sourceforge.net/site.html) JDBC driver** and add it to your project's classpath to enable Java–MS Access connectivity.

4. **Ensure the Access database file (`database2023.accdb`) is located at `src/proje1/database2023.accdb`.**

5. **Run the `proje2.java` file.**

### Notes

- Default password for login is: `parola`
- The user interface is in Turkish.
- The system is designed for demonstration and educational purposes.

---

## Türkçe

Bu proje, Java ve Swing ile geliştirilmiş, basit bir Kütüphane Otomasyon Sistemi'dir. Kullanıcıların kütüphane kitaplarını yönetmesine, kitap ödünç alıp iade etmesine ve yeni kitap siparişi vermesine olanak tanır. Kullanıcı ve kitap bilgileri Microsoft Access veritabanında saklanır.

### Özellikler

- Kullanıcı girişi ve doğrulama
- Kütüphaneden kitap ödünç alma
- Ödünç alınan kitabı iade etme
- Yeni kitap siparişi verme
- Kitap ve kullanıcı bilgilerinin Access veritabanında saklanması
- Kitap siparişlerini dosyaya aktarabilme
- Basit ve kullanıcı dostu arayüz

### Kullanılan Teknolojiler

- Java SE (Swing ile grafik arayüz)
- Microsoft Access (Veritabanı)
- UCanAccess JDBC Sürücüsü (veritabanı bağlantısı için)

### Kurulum ve Kullanım

1. **Depoyu klonlayın:**
   ```bash
   git clone https://github.com/barisbutun/Kutuphane_Otomasyon_Sistemi.git
   ```

2. **Projeyi tercih ettiğiniz Java IDE'sinde açın (ör. NetBeans, IntelliJ IDEA, Eclipse).**

3. **[UCanAccess](http://ucanaccess.sourceforge.net/site.html) JDBC sürücüsünü indirip projeye ekleyin** (Java'nın Access veritabanı ile bağlantısı için).

4. **Access veritabanı dosyasının (`database2023.accdb`) `src/proje1/database2023.accdb` yolunda olduğundan emin olun.**

5. **`proje2.java` dosyasını çalıştırın.**

### Notlar

- Giriş için varsayılan şifre: `parola`
- Kullanıcı arayüzü Türkçedir.
- Sistem, eğitim ve tanıtım amaçlı tasarlanmıştır.

---

**Author / Yazar:** Barış Bütün
