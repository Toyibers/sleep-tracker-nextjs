# Sleep Tracker App - Next.js 15 Full-Stack Tutorial

Ini adalah repositori untuk membangun aplikasi **Sleep Tracker** modern yang responsif dan siap produksi menggunakan ekosistem Next.js terbaru.

## 🚀 Deskripsi Proyek
Proyek ini mengajarkan cara membangun aplikasi *full-stack* dari nol. Aplikasi ini memungkinkan pengguna untuk melacak kualitas tidur, memvisualisasikan data dalam grafik, serta mengelola riwayat rekaman tidur mereka dengan sistem autentikasi yang aman.

Berikut adalah pembaruan *Tech Stack* untuk aplikasi **Sleep Tracker** Anda, disesuaikan dengan versi *dependencies* spesifik yang Anda berikan agar sesuai dengan dokumentasi teknis yang relevan:

### 🛠️ Tech Stack & Versi Proyek
*   **Framework**: [Next.js](https://nextjs.org) **v15.5.19** (App Router, Server Actions, & SSR)
*   **Library UI**: [React](https://react.dev) **v19.1.0** & [React DOM](https://react.dev) **v19.1.0**
*   **Styling**: [Tailwind CSS](https://tailwindcss.com) (Untuk desain responsif)
*   **Database & ORM**: [Neon PostgreSQL](https://neon.tech) dengan [Prisma](https://www.prisma.io) **v6.19.3**
*   **Authentication**: [@clerk/nextjs](https://clerk.com) **v6.1.0**
*   **Data Visualization**: [Chart.js](https://www.chartjs.org) **v4.4.9** & [React-Chartjs-2](https://react-chartjs-2.js.org) **v5.3.0**
*   **Deployment**: [Vercel](https://vercel.com)

## 📋 Fitur Utama
*   **Autentikasi Pengguna**: Login/Sign up via Google, GitHub, Facebook, atau Email (didukung oleh Clerk).
*   **Dashboard Dinamis**: Menampilkan data tidur personal dengan grafik interaktif.
*   **Formulir Pelacakan**: Input kualitas tidur, durasi, dan tanggal.
*   **Analitik Tidur**: Menampilkan rata-rata tidur (30 hari terakhir) serta analisis tidur terbaik & terburuk.
*   **Riwayat & Manajemen**: Melihat riwayat tidur dan kemampuan untuk menghapus data.
*   **Responsif**: Desain yang dioptimalkan untuk berbagai ukuran layar.

## ⚙️ Cara Memulai

### 1. Instalasi
Pastikan Anda memiliki [Node.js](https://nodejs.org/) terinstal, lalu jalankan perintah berikut:
bash
npx create-next-app@latest sleep-tracker

Ikuti konfigurasi: Pilih TypeScript, Tailwind CSS, dan App Router.

### 2. Setup Database & Auth
*   **Database**: Buat proyek di [Neon](https://neon.tech) dan sambungkan dengan Prisma.
*   **Auth**: Konfigurasi [Clerk](https://clerk.com) di dashboard mereka dan tambahkan `API keys` ke dalam file `.env` lokal Anda.

### 3. Menjalankan Aplikasi
bash
npm install
npm run dev

Buka [http://localhost:3000](http://localhost:3000) di browser Anda.

## 📚 Struktur Folder (Berdasarkan Tutorial)
*   `app/`: Berisi rute aplikasi (pages, layouts).
*   `components/`: Komponen UI yang dapat digunakan kembali (Navbar, Footer, Charts).
*   `actions/`: *Server Actions* untuk logika database (Get records, Delete record, dsb).
*   `lib/`: Konfigurasi koneksi database (DB instance).
*   `types/`: Definisi tipe TypeScript untuk data aplikasi.

--- 
*Dibuat oleh React & Next js Projects with Sahand.*