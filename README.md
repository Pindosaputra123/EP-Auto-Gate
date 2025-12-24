# EP Auto Gate
EP Auto Gate adalah aplikasi berbasis web yang digunakan untuk **pendataan kendaraan**, **manajemen parkir**, dan **pembayaran parkir otomatis**. Sistem ini dirancang untuk mempermudah pengelolaan parkir secara digital, akurat, dan efisien.

## 🚗 Fitur Utama
- Pencatatan kendaraan masuk dan keluar
- Perhitungan tarif parkir otomatis
- Pembayaran parkir (tunai / digital)
- Manajemen data petugas dan admin
- Laporan dan rekap data parkir
- Ekspor laporan (Excel)
- Sistem autentikasi (Admin & Petugas)

## 🛠️ Teknologi yang Digunakan
- **Backend**: PHP  
- **Database**: MySQL  
- **Frontend**: HTML5, CSS3, Vanilla JavaScript  
- **Web Server**: Apache  
- **Version Control**: Git

## 🚀 Instalasi
### **Persyaratan**  
- PHP ≥7.4  
- MySQL ≥5.7  
- Apache/Nginx (XAMPP rekomendasi)

### **Setup Lokal**
1. **Clone the repository**:  
   ```bash
   https://github.com/Pindosaputra123/EP-Auto-Gate.git
   cd EP-Auto-Gate
   ```
   
2. **Import Database**
   - Jalankan file `database/parkir.sql` melalui phpMyAdmin
     
3. **Configure koneksi database**:  
   Edit file `config/db.php`:  
   ```php
   define('DB_HOST', 'localhost');
   define('DB_USER', 'root');
   define('DB_PASS', '');
   define('DB_NAME', 'parkir');
   ```

4. **Jalankan Aplikasi**:  
   ```bash
   php -S localhost:8000
   ```  
