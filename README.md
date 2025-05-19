# 🚀 keterbatasan server atau rumah hosting tidak semua paket hosting menyediakan terminal ssh dan support untuk php, 
# laravel hanya bisa dideploy dengan vps atau paket pro/exclusive. tidak tersedia untuk pake mini dan ekonomis, membatasi explorasi programmer tidak mampu publish dengan domain name pribadi.

> Login Menu Member Area adalah sistem autentikasi berbasis Laravel yang menyediakan fitur login, registrasi, reset password, dan manajemen akun dengan antarmuka sederhana.
## # 🇮🇩 Gitlabs for Laravel – Platform Open Source Hosting Laravel Gratis

# 🔧 Proyek ini adalah inisiatif **nirlaba** dari komunitas Laravel dan PHP Indonesia untuk membangun alternatif open source seperti GitHub/GitLab, tetapi **khusus untuk Laravel/PHP Projects**, dengan tujuan:

- 💻 Menyediakan **hosting gratis** untuk proyek Laravel open source
- 🧑‍🤝‍🧑 Membangun **platform kolaboratif komunitas** Laravel/PHP
- 🚀 Mendemokratisasi deployment Laravel (tanpa bayar hosting mahal)
- 🎁 Dibiayai oleh zakat, donasi, dan dana foundation dari **Gloriabank x Gudanglaba**

---

## 🏁 Tujuan Jangka Pendek

- [x] Sistem Git UI untuk commit, push, pull project Laravel
- [x] Docker-based runner untuk menjalankan Laravel (artisan, composer, dll)
- [x] Interface deploy otomatis (via `.deploy.yml` atau sejenis)
- [x] Grup FB & komunitas dev bisa upload proyek Laravel mereka → langsung dihosting
- [ ] Pendaftaran komunitas Laravel se-Indonesia untuk berkontribusi
- [ ] Git SSH Access → `git@gitlabs-laravel.id:user/repo.git`

---

## 🔧 Fitur Utama

| Fitur                        | Keterangan                                                   |
|-----------------------------|--------------------------------------------------------------|
| ✅ Git-Based UI              | Clone / Commit / Push / Fork / Merge Laravel Projects        |
| ✅ Laravel Runtime Support   | Composer + Artisan Ready (Tanpa SSH Hosting)                |
| ✅ Deploy Pipeline           | Jalankan Laravel secara otomatis via Webhook / Push Trigger |
| ✅ Open Source               | Semua kode di-push di GitHub: [github.com/ozxstudio/gitlabs-for-laravel](https://github.com/ozxstudio/gitlabs-for-laravel) |
| 🔐 Autentikasi Git           | Gunakan token atau akun Git untuk autentikasi                |
| 📁 Upload Project Laravel    | Unggah .zip / git repo → langsung deploy otomatis            |

---

## ⚙️ Teknologi yang Digunakan

- 🧠 **PHP 8.2 / Laravel 11**
- 🐋 **Docker + Laravel Sail**
- ⚙️ **GitPHP / Gitea (Self-host Git)**
- 🌐 **VueJS / InertiaJS for UI Panel**
- 🛠️ **Supervisor / Cron / Custom Deploy Engine**
- 📦 **PostgreSQL / Redis / MySQL**

---

## 💡 Kontribusi Komunitas

Proyek ini terbuka untuk semua teman-teman dari:

- Grup Facebook: Laravel Dev Indonesia / PHP Indonesia
- Komunitas Coding Madrasah / Pondok Digital
- Mahasiswa, freelance, dev rumahan yang mau deploy Laravel tapi:
  - ❌ Tidak punya akses SSH
  - ❌ Hosting tidak support Composer/Artisan
  - ❌ Tidak bisa beli server VPS sendiri

---

## 🤝 Cara Kontribusi

1. Fork proyek ini
2. Clone ke lokal
3. Jalankan `php artisan serve` atau `sail up`
4. Submit Pull Request via GitHub
5. Diskusi dan kolaborasi di grup FB: `PHP Indonesia`

---

## 📦 Donasi & Pendanaan

🎁 Proyek ini **tidak komersial** dan tidak bertujuan mencari keuntungan.  
Didukung oleh:

- 💰 **Gloriabank Foundation**
- 🏭 **Gudanglaba Zakat Fund**
- 🫱🏽‍🫲🏽 Donatur pribadi & komunitas developer

**Scan QR, kirim donasi, atau support di situs resmi: [wpu.web.id](https://www.wpu.web.id/)**

---

## 🚀 Roadmap Rilisan Awal

- [ ] Beta domain: `gitlabs-laravel.my.id`
- [ ] UI Git berbasis web (Fork / Merge / File Editor)
- [ ] Realtime logs deploy Laravel
- [ ] Support `.deploy.yml` seperti Netlify
- [ ] Support untuk private repo dan hosting Laravel tanpa batas

---

## 📜 Lisensi

MIT — Bebas digunakan, dimodifikasi, dan dikembangkan bersama-sama.

---

## 🌟 Penutup

> “Tidak semua orang punya privilege beli server. Tapi semua orang berhak deploy Laravel.”  
> 🎙️ *— Komunitas Gudanglaba*

**Bangun bareng, deploy bareng, pahala bareng. Bismillah.**



#Sumber kode Git dapat ditemukan di:

[Repository Git resmi:](https://github.com/git/git?fbclid=IwZXh0bgNhZW0CMTAAAR22lv05JTDBhgPYjJ7gcQxFHjcUjrjnHFp0dJj-erxVoI9eaQS6fEPh0NU_aem_lb6G703Xj12eLpyRoiOAvA)

[Repository GitHub:](https://github.com/git/git?fbclid=IwZXh0bgNhZW0CMTAAAR0rnLT8vYECtPvL46-y4uigZuOeoDnYaB7qoLQVk9QX5qfI-jFgKDYFDFY_aem_HUy0xRO-LHMUbxDgv4PIrw)

[Repository GitLab:](https://gitlab.com/users/sign_in)

## 🎯 Fitur
✅ Register & Login User  
✅ Validasi Email & Password  
✅ Hashing Password (Bcrypt)  
✅ Logout & Session Management  
✅ Reset Password  
✅ Notifikasi Error jika Login Gagal  
✅ Desain Responsif dengan Tailwind CSS  

---

✅ Banyak yang harus diperhatikan:

Validasi email & password
Hashing password (biar aman)
Session & cookie handling
Redirect setelah login/logout
Notifikasi error kalau login gagal
Reset password, OTP, 2FA, dll.

## ⚡ 1️⃣ **Instalasi & Setup**
### **🛠️ Prasyarat:**
- PHP 8.x  
- Composer  
- MySQL / MariaDB  
- Node.js & NPM (untuk frontend)  

### **📌 Cara Install**
```sh
git clone https://github.com/username/login-menu.git
cd login-menu
composer install
npm install && npm run dev
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve

