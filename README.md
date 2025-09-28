# Certinaris – Platform Seminar Digital  

## 👥 Anggota Kelompok  
1. 2311102032 – Muhammad Rifki Fadhilah  
2. 2311102050 – Galih Trisna  
3. 2311102135 – Amelia Azmi  
4. 2311102152 – Arsya Fathiha Rahman  

---

## 📌 Deskripsi Proyek  
**Certinaris**  merupakan sebuah aplikasi berbasis web yang dikembangkan untuk mendukung pengelolaan seminar secara menyeluruh. Platform ini dirancang dengan konsep satu sistem yang menampung banyak seminar, sehingga siapa pun dapat berperan sebagai penyelenggara maupun peserta.  

Bagi penyelenggara, Certinaris menyediakan kemudahan dalam membuat dan mempublikasikan seminar, mengatur kapasitas, menentukan biaya pendaftaran, serta memantau data peserta. Sementara bagi peserta, proses pendaftaran dibuat sederhana karena dapat dilakukan tanpa akun (guest checkout). Peserta cukup mengisi data diri dan email, kemudian melanjutkan ke tahap pembayaran.

Setelah pembayaran terverifikasi, sistem akan mengirimkan tiket digital yang dilengkapi dengan QR Code untuk kehadiran. Pada saat seminar berlangsung, QR Code tersebut dipindai sebagai bukti kehadiran. Peserta yang hadir akan secara otomatis menerima sertifikat digital yang dikirimkan melalui email.

Dengan alur yang terintegrasi mulai dari pendaftaran, pembayaran, kehadiran, hingga penerbitan sertifikat, Certinaris diharapkan mampu meningkatkan efisiensi penyelenggaraan seminar sekaligus memberikan pengalaman yang lebih praktis dan transparan bagi peserta.
---

## 🎯 Tujuan  
- Memudahkan penyelenggara dalam mengelola seminar.  
- Mempermudah peserta mendaftar tanpa harus login.  
- Menyediakan sistem pembayaran terintegrasi.  
- Menghadirkan fitur absensi berbasis QR Code.  
- Menghasilkan sertifikat digital otomatis.  

---

## ⚙️ Teknologi yang Digunakan  
- **Next.js** – frontend & backend (API route)  
- **Vercel** – hosting & deployment  
- **Supabase (Postgres, Auth, Storage)** – basis data, autentikasi, dan penyimpanan
- **Midtrans/Xendit** – payment gateway untuk transaksi online
- **Tailwind CSS + shadcn/ui** – styling responsif  
- **Resend/SMTP** – layanan pengiriman email  
- **QR Code & PDF Generator** – pembuatan tiket dan sertifikat digital  

---

## ✨ Fitur Utama  
- Multi-seminar (banyak penyelenggara, banyak event).  
- Guest checkout (peserta bisa daftar tanpa akun).  
- Pembayaran otomatis terintegrasi.  
- Tiket digital dengan QR Code unik.  
- Verifikasi kehadiran via scan QR.  
- Sertifikat otomatis dengan halaman verifikasi publik.
  
## 💳 Sistem Pembayaran  
### Gateway  
- **Midtrans**  

### Metode Tersedia  
- **QRIS** – metode utama, cepat & mudah digunakan peserta  
- **E-Wallet** – GoPay, OVO, Dana, ShopeePay  
- **Transfer Bank** – BCA, Mandiri, BRI, BNI, dll  

### Alur Pembayaran  
1. Peserta memilih metode pembayaran saat checkout  
2. Sistem membuat transaksi dengan kode unik atau QRIS  
3. Midtrans memverifikasi pembayaran secara otomatis  
4. Tiket digital dikirim ke peserta melalui **Email** dan **WhatsApp**  

---

## 📖 Kesimpulan  
Dengan **Certinaris**, seluruh alur seminar – mulai dari pendaftaran, pembayaran, kehadiran, hingga penerbitan sertifikat – dapat dilakukan secara otomatis dan terintegrasi. Platform ini diharapkan mampu memberikan solusi efisien bagi penyelenggara seminar dan pengalaman yang lebih praktis bagi peserta.
