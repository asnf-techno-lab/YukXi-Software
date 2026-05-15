# ⚡ YukXi Software Installer Suite v5.00.6
**Powered by Shinko Engine Core | ASNF Techno Lab**

![Version](https://img.shields.io/badge/Version-5.00.6_Stable-blue)
![Platform](https://img.shields.io/badge/Platform-Windows_10%2F11-lightgrey)
![Language](https://img.shields.io/badge/Language-Batchfile-brightgreen)
![Status](https://img.shields.io/badge/Status-Active-success)

YukXi Software Installer Suite adalah sebuah *deployment toolkit* cerdas berbasis Batch yang dirancang untuk mengotomatisasi proses pengunduhan dan instalasi puluhan perangkat lunak esensial di sistem operasi Windows. 

Ditenagai oleh **Shinko Engine Core**, tool ini memungkinkan *Smart Auto-Setup*, di mana aplikasi akan diunduh secara *real-time* dari server resmi dan diinstal secara *silent* (latar belakang) untuk efisiensi waktu yang maksimal.

---

## 📖 The Origin Story: Mengapa YukXi Diciptakan?

> *"Semuanya bermula dari sebuah masalah sederhana yang sering kita temui. Setelah melakukan instalasi ulang Windows, saya mendapati sistem saya benar-benar kosong tanpa browser bawaan yang memadai. Niat awal saya sangatlah sederhana: saya hanya ingin menulis satu file `.bat` kecil untuk mengunduh dan menginstal Google Chrome secara otomatis agar saya tidak perlu repot.* > 
> *Namun, setelah script Chrome itu berhasil berjalan, sebuah ide besar muncul di kepala saya. Jika saya bisa mengotomatisasi satu browser, mengapa tidak mengotomatisasi seluruh ekosistem *software* yang saya butuhkan pasca-install ulang? Dari satu baris kode sederhana untuk Chrome, proyek ini berevolusi dan berkembang pesat menjadi YukXi Software Installer Suite yang kalian lihat sekarang—sebuah utilitas cerdas dengan 55 opsi perangkat lunak yang terintegrasi langsung dengan standar AnXin Technology Project."*
>
> **— M. Nabil Irza Prawira, Director & Founder ASNF Techno Lab**

---

## ✨ Fitur Utama

* **🚀 Smart Auto-Setup Protocol (Shinko Engine)**: Script secara cerdas membedakan mana aplikasi yang mendukung *Silent Install* (tanpa interaksi *user*) dan mana yang membutuhkan antarmuka instalasi manual.
* **🌐 Real-Time Curl Fetching**: Tidak ada *installer* usang yang disimpan di dalam script. Semua *software* (55 menu) diunduh langsung secara *live* menggunakan URL resmi versi *stable* terbaru ke direktori `Downloads\YukXi_Downloads`.
* **🛡️ Auto-Administrator Privilege**: Script memiliki modul keamanan *self-elevating* yang otomatis meminta hak akses Administrator saat dijalankan untuk mencegah kegagalan *write-permission* di `C:\Program Files`.
* **🖥️ ShinkoUI Locked Resolution**: Antarmuka terminal yang sangat bersih dan rapi, dikunci secara presisi pada resolusi `120x40` agar susunan tabel menu tetap *pixel-perfect*.
* **🎨 Custom UI Themes**: Mendukung personalisasi warna terminal (Liquid Glass Cyan, Matrix Terminal, dll) langsung dari menu Settings.

---

## 📦 Kategori Software yang Tersedia (55 Menu)

YukXi mencakup seluruh kebutuhan pengguna modern, kreator, hingga *developer*:
1.  **Web Browsers** (Chrome, Firefox, Brave, Opera GX, Edge)
2.  **Communication** (Zoom, Discord, Telegram, WhatsApp, Slack, dll)
3.  **Utilities** (7-Zip, WinRAR, Rufus, AnyDesk, CPU-Z, MSI Afterburner, dll)
4.  **Development** (VS Code, Git, Node.js, Python, XAMPP, Docker, PuTTY, dll)
5.  **Gaming & Media** (Steam, Epic Games, OBS Studio, VLC, Spotify, dll)
6.  **Design & Office** (GIMP, Blender, Figma, LibreOffice, dll)
7.  **Security & Misc** (Malwarebytes, Bitwarden, FileZilla, qBittorrent, dll)

---

---

## 🚀 Protokol Instalasi & Penggunaan (New Delivery System)

Demi menjaga keamanan *source code* dan memberikan pengalaman deployment yang futuristik, YukXi kini menggunakan sistem *Shinko Dropper* dan proteksi kata sandi berbasis web. Ikuti langkah-langkah berikut:

**Fase 1: Inisialisasi Dropper**
1. Unduh file `instalasiYukXi.bat` dari halaman **Releases** di repositori ini.
2. Jalankan file tersebut (klik dua kali). 
3. *Shinko Engine* akan otomatis menarik package utama (`YukXi_YdK.zip`) dari server, mengekstraknya ke folder `Downloads`, dan menghapus file zip mentahnya secara otomatis untuk menjaga kebersihan storage.

**Fase 2: Autentikasi & Dekripsi**
4. Buka folder hasil ekstraksi tersebut di direktori `Downloads` kamu.
5. Klik dua kali pada file **`Index.html`**. File ini akan bertindak sebagai jembatan *Meta Refresh* yang otomatis membuka portal web rahasia ASNF Techno Lab di *browser* kamu.
6. Tunggu *loading screen* selesai, dan ambil **Password Ekstraksi** yang tertera di panel bawah pada halaman web bergaya *Liquid Glass* tersebut.
7. Kembali ke folder lokalmu, lalu ekstrak file arsip `YukXi_Software.zip` menggunakan kata sandi yang baru saja kamu dapatkan.

**Fase 3: Eksekusi Utama**
8. Di dalam folder yang sudah terbuka kuncinya, jalankan **`YukXi_Software.bat`**.
9. *Catatan:* Kamu cukup klik dua kali. Sistem Shinko sudah dirancang cerdas untuk otomatis meminta hak akses Administrator layar biru (UAC).
10. Ketik nomor *software* yang ingin diinstal, lalu tekan **Enter**. Duduk santai, dan biarkan sistem bekerja!

---

## 👨‍💻 Tentang Ekosistem

YukXi Software Installer Suite adalah bagian dari ekosistem teknologi **ASNF Techno Lab** dan **AnXin Technology Project**, berjalan berdampingan dengan proyek-proyek inovatif lainnya seperti *AnXin A.I., Shinko Bio, ShinkoUI, AI Name Vault, Magic Random Pro,* dan *AIOG*.

**"Lhokseumawe Pride - Innovating the Future of Tech"**

---
*© 2026 M. Nabil Irza Prawira | ASNF Techno Lab. All Rights Reserved.*