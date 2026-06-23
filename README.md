# TanyaAja - Sistem Q&A Real-time

Aplikasi Q&A real-time untuk seminar, workshop, dan konferensi profesional.

## Fitur Utama

- 📱 **Akses Instan via QR Code**: Bagikan kode QR untuk peserta bergabung ke sesi
- 🛡️ **Moderasi Aman**: Admin dapat mengelola sesi dan pertanyaan
- 🔔 **Notifikasi Suara**: Dapatkan notifikasi ketika ada pertanyaan baru
- 🎨 **Kustomisasi Branding**: Ubah nama aplikasi, warna, logo, dan latar belakang
- 📊 **Dasbor Admin**: Kelola sesi, pengguna, dan pengaturan sistem
- 📄 **Export PDF**: Unduh daftar pertanyaan dalam format PDF

## Teknologi yang Digunakan

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla JS)
- **Styling**: Tailwind CSS
- **Database**: Firebase Realtime Database
- **Analytics**: Firebase Analytics
- **Icons**: Lucide Icons

## Struktur Proyek

```
qna/
├── index.html      # Halaman utama aplikasi
├── app.js          # Logika aplikasi utama
├── styles.css      # Kustom styling
├── Kode.gs         # Script Google Apps Script (opsional)
└── README.md       # Dokumentasi ini
```

## Cara Instalasi

1. **Clone atau unduh** repositori ini
2. **Buka index.html** di browser untuk menjalankan aplikasi secara lokal

## Konfigurasi Firebase

Pastikan kamu sudah mengkonfigurasi Firebase:

1. Buat project di [Firebase Console](https://console.firebase.google.com/)
2. Enable **Realtime Database**
3. Dapatkan konfigurasi Firebase dan masukkan ke `index.html`:

```javascript
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_PROJECT.firebaseapp.com",
    databaseURL: "YOUR_DATABASE_URL",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_PROJECT.appspot.com",
    messagingSenderId: "YOUR_SENDER_ID",
    appId: "YOUR_APP_ID"
};
```

## Cara Menggunakan

### Sebagai Admin

1. Buka aplikasi dan klik **Admin Access**
2. Login dengan akun admin (default: `admin` / `admin`)
3. Buat sesi baru dengan mengklik **Buat Sesi Baru**
4. Bagikan kode QR atau kode sesi ke peserta
5. Kelola pertanyaan dari dasbor admin

### Sebagai Peserta

1. Buka aplikasi dan masukkan kode sesi
2. Atau scan QR code yang dibagikan
3. Ajukan pertanyaan dan berikan suara

## Pengaturan Sistem

Admin dapat mengakses **System Control** untuk:
- Mengubah nama aplikasi
- Mengganti warna utama
- Mengunggah logo dan latar belakang
- Menyesuaikan teks pada landing page
- Mengelola pengguna admin

## Default Akun

- **Administrator**: `administrator` / `passwordadmin123`
- **Admin**: `admin` / `admin`

## Lisensi

© 2026 TanyaAja System
