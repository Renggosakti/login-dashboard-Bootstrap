# login-dashboard-Bootstrap

Proyek ini merupakan tugas akhir mata kuliah **Pemrograman Web (PWEB)**  
yang dikembangkan oleh **Arya Rangga Putra Pratama (5025241072)**  
kelas **Pemrograman Web A**, di bawah bimbingan **Bapak Fajar Baskoro, S.Kom., M.T.**

---

## 🚀 Deskripsi Singkat

Portal Taman Bungkul adalah **aplikasi web interaktif** yang dirancang untuk menampilkan sistem **Login, Register, dan Dashboard** menggunakan **HTML, CSS, dan JavaScript murni** tanpa framework tambahan.  
Desain mengusung tema **futuristik dan modern**, lengkap dengan efek **gradient, animasi partikel, dan tampilan responsif berbasis Bootstrap**.

---

## ✨ Fitur Utama

### 🔹 1. Register
- Pengguna dapat mengisi **Nama Lengkap**, **Display Name**, **Email**, dan **Password**.  
- Data akan disimpan secara **lokal di browser** menggunakan `localStorage`.  
- Jika validasi berhasil, muncul pesan:
  > ✅ Akun berhasil dibuat! Silakan login.

### 🔹 2. Login
- Memverifikasi kecocokan email & password dengan data `bungkulUser`.  
- Jika sesuai, data disalin ke `loggedInUser` dan diarahkan ke **dashboard.html**.  
- Jika format email salah, sistem menolak login.

### 🔹 3. Dashboard
- Menampilkan **sapaan pengguna** menggunakan display name yang disimpan.  
- Dilengkapi tampilan **card berita, event, dan tombol logout**.  
- Menggunakan Bootstrap untuk tampilan elegan dan rapi.

### 🔹 4. Logout
- Menghapus data `loggedInUser` dari localStorage.
- Mengarahkan kembali ke halaman login (`index.html`).

---

## 🧠 Alur Kerja Sistem

Register → Simpan bungkulUser → Login → Simpan loggedInUser → Dashboard → Logout → Hapus loggedInUser

yaml
Salin kode

Keterangan:
- `bungkulUser` → data akun utama (persisten di browser).
- `loggedInUser` → data sesi sementara saat login aktif.

---

## 🧩 Teknologi yang Digunakan

| Komponen | Deskripsi |
|-----------|------------|
| **HTML5** | Struktur halaman login, register, dan dashboard |
| **CSS3 + Bootstrap 5** | Tampilan modern, responsif, dan futuristik |
| **JavaScript (murni)** | Logika autentikasi, validasi, dan penyimpanan data |
| **localStorage** | Menyimpan data pengguna tanpa backend |
| **Audio Interaction** | Efek suara klik & sukses dari CDN Pixabay |

---

## 💻 Struktur Folder

📁 portal-taman-bungkul/
├── index.html # Halaman login & register futuristik
├── dashboard.html # Halaman dashboard setelah login
├── assets/
│ ├── style.css # (opsional) CSS tambahan
│ └── audio/ # Suara klik dan notifikasi
└── README.md # Dokumentasi proyek

yaml
Salin kode

---

## 🧪 Cara Menjalankan Proyek

### 🔸 1. Clone Repository
```bash
git clone https://github.com/aryarangga/portal-taman-bungkul.git
cd portal-taman-bungkul
