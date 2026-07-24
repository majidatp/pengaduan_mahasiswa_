# 📢 Web Pengaduan Mahasiswa

## 👨‍🎓 Identitas Mahasiswa
**Nama:** Abdul Majid  
**NIM:** 210170211  

---

# 🚀 Deskripsi Aplikasi

**Web Pengaduan Mahasiswa** merupakan aplikasi berbasis web yang digunakan untuk mempermudah mahasiswa dalam menyampaikan laporan atau pengaduan secara online.  

Aplikasi ini memiliki tiga hak akses utama, yaitu:
- 👨‍💼 Admin
- 🧑‍💻 Petugas
- 👨‍🎓 Mahasiswa

Setiap pengguna memiliki fitur dan hak akses yang berbeda sesuai dengan perannya.

---

# ✨ Fitur Utama Aplikasi

## 👨‍💼 Fitur Admin

### 🏠 Dashboard
Admin dapat melihat informasi dan notifikasi terkait pengaduan mahasiswa yang masuk ke dalam sistem.

### 💬 Tanggapi Pengaduan
Admin dapat memantau jumlah pengaduan yang telah diproses dan melihat status tanggapan dari petugas.

### 📂 Data Master
Admin dapat mengelola seluruh data yang terdapat dalam sistem, meliputi:

- 👨‍💼 Data Petugas
- 👨‍🎓 Data Mahasiswa
- 📢 Data Pengaduan

### 👥 Data Petugas
Admin memiliki akses untuk:
- Menambahkan akun petugas baru.
- Menghapus akun petugas.
- Membuat akun admin lainnya tanpa melalui proses registrasi.

### 📄 Data Pengaduan
Admin dapat:
- Melihat seluruh laporan pengaduan mahasiswa.
- Melihat laporan yang sudah ditanggapi.
- Melakukan ekspor laporan pengaduan ke dalam format PDF.

---

# 🧑‍💻 Fitur Petugas

### 🏠 Beranda
Petugas dapat melihat notifikasi apabila terdapat pengaduan baru dari mahasiswa.

### ✅ Verifikasi Pengaduan
Petugas dapat:
- Melihat detail laporan mahasiswa.
- Melakukan pemeriksaan terhadap laporan.
- Memverifikasi pengaduan yang masuk.

---

# 👨‍🎓 Fitur Mahasiswa

### 📝 Tulis Laporan
Mahasiswa dapat membuat laporan pengaduan dengan mengisi formulir yang tersedia, seperti:

- 👤 Nama
- 🪪 NIK
- 📌 Judul Pengaduan
- 📝 Isi Laporan
- 📷 Foto Bukti (Opsional)

### 📋 Lihat Laporan
Mahasiswa dapat melihat perkembangan laporan yang telah dibuat, seperti:

- ⏳ Menunggu verifikasi
- 🔄 Sedang diproses
- ✅ Sudah ditanggapi

---

# 🔑 Akun Uji Coba

## 👨‍💼 Admin

Email : adin
Password : adin


## 🧑‍💻 Petugas

Email : odin
Password : odin


## 👨‍🎓 Mahasiswa

Email : intan
Password : 2010


---

# ⚙️ Panduan Menjalankan Aplikasi

### 1️⃣ Persiapan Project
Buka folder aplikasi:


pengaduan


### 2️⃣ Membuat Database
1. Jalankan **XAMPP**.
2. Aktifkan:
   - Apache
   - MySQL
3. Buka **phpMyAdmin**.
4. Buat database
   
Buat database pengaduan di phpMyAdmin
        ↓
Setting .env
        ↓
php artisan config:clear
        ↓
php artisan migrate
        ↓
Database Laravel tersambung


### 3️⃣ Menjalankan Aplikasi
Jalankan file:


index.html


### 4️⃣ Login Admin/Petugas
Klik tombol:


Login Sebagai Petugas/Admin


Gunakan akun uji coba yang tersedia.

### 5️⃣ Login Mahasiswa
Klik tombol:


Login Sebagai User/Mahasiswa


Kemudian masuk menggunakan akun mahasiswa.

---

# 📸 Dokumentasi Aplikasi

## 🏠 Menu Utama

<img width="1366" height="768" alt="Screenshot (87)" src="https://github.com/user-attachments/assets/6334818a-b04f-4633-a2aa-4591007e9e3e" />

---

## 🔐 Halaman Login

<img width="1366" height="768" alt="Screenshot (88)" src="https://github.com/user-attachments/assets/6f52c840-1533-4536-adde-691030b595fc" />

---

## 📝 Halaman Registrasi

<img width="1366" height="768" alt="Screenshot (89)" src="https://github.com/user-attachments/assets/59c41106-d150-4347-9d5c-2e6d99a4a7b0" />

---

# 👨‍💼 Dokumentasi Admin

## 📊 Dashboard Admin

<img width="1366" height="768" alt="Screenshot (90)" src="https://github.com/user-attachments/assets/35e77bfb-1a5f-4b6d-a960-4401066842cc" />

---

## 👥 Daftar Petugas

<img width="1366" height="768" alt="Screenshot (91)" src="https://github.com/user-attachments/assets/0e5d183a-5a16-4d53-bbfc-d5e4938bbadf" />

---

## 📂 Data Laporan Pengaduan

<img width="1366" height="768" alt="Screenshot (92)" src="https://github.com/user-attachments/assets/a5668a76-3b96-47c0-ad3e-a112e789e966" />

---

## 📄 Detail Laporan & Ekspor PDF

<img width="1366" height="768" alt="Screenshot (94)" src="https://github.com/user-attachments/assets/55ca02f8-8ef0-4bd0-8dad-ca95b413e31c" />

---

# 👨‍🎓 Dokumentasi Mahasiswa

## 🏠 Dashboard Mahasiswa

<img width="1366" height="768" alt="Screenshot (95)" src="https://github.com/user-attachments/assets/f4ad211b-da67-4ecb-875d-7be6ea04e907" />

---

## 📝 Form Tulis Laporan

<img width="1366" height="768" alt="Screenshot (96)" src="https://github.com/user-attachments/assets/aeeb7b6f-ef2b-438e-b52e-638b282be107" />

---

## 📋 Status Laporan Pengaduan

<img width="1366" height="768" alt="Screenshot (97)" src="https://github.com/user-attachments/assets/4d9f5e06-d0b6-4586-ad5f-93c402b6bbd6" />


# 🛠️ Teknologi yang Digunakan

💻 **Frontend**
- HTML
- CSS
- JavaScript
- Bootstrap

⚙️ **Backend**
- PHP

🗄️ **Database**
- MySQL

🚀 **Server**
- XAMPP

---

# 📌 Catatan

Aplikasi ini dibuat sebagai sistem informasi pengaduan mahasiswa yang bertujuan untuk meningkatkan efektivitas proses pelaporan, verifikasi, dan penyelesaian pengaduan secara digital.
