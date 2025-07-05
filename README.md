# Hospital Management Dashboard (HTML/CSS/JS)

Ini adalah implementasi _dashboard_ sistem manajemen rumah sakit _front-end_ yang responsif, dibangun menggunakan HTML, CSS murni, dan JavaScript dasar. Proyek ini menampilkan antarmuka pengguna yang modern dan interaktif untuk mengelola berbagai aspek operasional rumah sakit, seperti pasien, dokter, janji temu, departemen, farmasi, laboratorium, laporan, dan pengaturan.

## Daftar Isi

* [Gambaran Umum Proyek](#gambaran-umum-proyek)
* [Fitur Utama](#fitur-utama)
* [Demo Langsung](#demo-langsung) (Opsional)
* [Struktur Direktori](#struktur-direktori)
* [Teknologi yang Digunakan](#teknologi-yang-digunakan)
* [Instalasi dan Menjalankan Proyek](#instalasi-dan-menjalankan-proyek)
    * [Prasyarat](#prasyarat)
    * [Langkah-langkah Instalasi](#langkah-langkah-instalasi)
* [Penggunaan Aplikasi](#penggunaan-aplikasi)
* [Kustomisasi](#kustomisasi)
* [Kontribusi](#kontribusi)
* [Lisensi](#lisensi)

---

## Gambaran Umum Proyek

Proyek ini adalah simulasi _dashboard_ sistem manajemen rumah sakit yang berfokus pada desain antarmuka pengguna dan pengalaman pengguna. Meskipun ini adalah aplikasi _front-end_ murni (tidak ada _backend_ atau persistensi data), ia menunjukkan kemampuan untuk membangun tata letak yang kompleks dan interaktif dengan teknologi web standar. Ini dapat menjadi dasar yang kuat untuk diintegrasikan dengan sistem _backend_ yang sebenarnya.

## Fitur Utama

* **Desain Responsif**: Antarmuka pengguna menyesuaikan diri dengan berbagai ukuran layar (desktop, tablet, mobile).
* **Sidebar Navigasi Interaktif**:
    * Dapat diciutkan (_collapsed_) untuk menghemat ruang.
    * Mencakup tautan ke berbagai bagian _dashboard_ (Dashboard, Patients, Doctors, Appointments, Departments, Pharmacy, Laboratory, Reports, Settings).
    * Animasi transisi halus saat diciutkan/diperluas.
* **Header Dashboard**: Menampilkan judul, tombol _toggle_ _sidebar_, notifikasi, dan profil pengguna.
* **Kartu Statistik Dashboard**: Menampilkan metrik kunci rumah sakit (Total Pasien, Total Dokter, Janji Temu Hari Ini, Pendapatan Bulanan) dengan indikator perubahan.
* **Tabel Data Dinamis (Simulasi)**: Menampilkan data dalam format tabel yang mudah dibaca, dengan _status badge_ dan tombol aksi.
* **_Quick Actions_**: Tombol aksi cepat untuk tugas-tugas umum di setiap bagian.
* **Bilah Pencarian**: _Placeholder_ untuk fungsionalitas pencarian.
* **Formulir Input**: Contoh elemen formulir untuk bagian pengaturan.
* **Animasi UI**: Efek transisi dan animasi _fade-in_ untuk meningkatkan pengalaman visual saat berpindah antar bagian.

## Demo Langsung

*(Jika Anda telah mendeploy aplikasi ini ke platform seperti GitHub Pages, Vercel, atau Netlify, sertakan tautan di sini.)*

[Link Demo Langsung Anda di Sini](https://your-github-username.github.io/hospital-dashboard-demo/)

## Struktur Direktori

Proyek ini terdiri dari satu file HTML yang menggabungkan struktur, _styling_, dan _scripting_: