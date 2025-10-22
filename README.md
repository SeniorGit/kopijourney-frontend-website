# ☕ Kopi Journey — From Farm to Cup, Every Sip Tells a Story

### 🌍 Transparent Coffee Supply Chain Platform

Kopi Journey adalah platform web fullstack yang menghubungkan petani kopi, roaster, dan penikmat kopi dalam satu ekosistem digital yang transparan.  
Proyek ini dirancang untuk menghadirkan **transparansi rantai pasok**, **cerita di balik setiap biji kopi**, serta **pengalaman personal bagi konsumen**.

## 🛠 Built With

### Frontend
- [Next.js 14 (App Router)](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)

### Backend
- [Node.js + Express.js](https://expressjs.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [Redis](https://redis.io/)
- [Socket.io](https://socket.io/)

### Services & APIs
- [Mapbox](https://www.mapbox.com/) — Geolocation  
- [Cloudinary](https://cloudinary.com/) — Media Storage  
- [Resend](https://resend.com/) — Email Delivery  
- [Vercel Analytics](https://vercel.com/analytics) — Performance Tracking

## 🚀 Key Features
- 🌱 **Supply Chain Transparency** — Lacak perjalanan kopi dari petani hingga ke cangkir.
- ☕ **Personalized Recommendations** — Rekomendasi kopi berdasarkan profil rasa pengguna.
- 🔒 **Secure Authentication** — Sistem login dengan token-based authentication.
- 📦 **Order & Inventory System** — Manajemen produk dan pesanan secara real-time.
- 📊 **Farmer & Roaster Dashboard** — Tampilan analitik sederhana untuk pengelolaan data.

## 🎯 Functional Overview

### 👥 User Management
- Registrasi & login dengan verifikasi email.  
- Role-based access: *Consumer, Farmer, Roaster, Admin.*  
- Pengelolaan profil dengan data preferensi & riwayat transaksi.

### 🌍 Coffee Journey Tracking
- Petani dapat menambahkan data batch panen, lokasi, dan kualitas.  
- Visualisasi perjalanan kopi dalam bentuk **timeline interaktif dan peta geografis**.

### 🛒 Product Catalog
- Sistem katalog produk dengan pencarian dan filter berdasarkan asal, rasa, atau roaster.  
- Setiap batch kopi memiliki **cerita unik dan metrik kualitas**.

### 💳 Order Management
- Fitur keranjang belanja, checkout, dan pelacakan pesanan secara real-time.  
- Notifikasi status pemanggangan dan pengiriman.

## ⚙️ Non-Functional Highlights (Publik)
- 🚀 **Performance:** Halaman utama memuat < 2 detik.  
- 🔐 **Security:** Enkripsi data dan perlindungan terhadap XSS/SQL Injection.  
- 📱 **Responsive Design:** Optimal di desktop, tablet, dan perangkat mobile.  
- 🌍 **Accessibility:** Mengikuti standar **WCAG 2.1 AA**.  
- 🧠 **Maintainability:** Menggunakan TypeScript, ESLint, dan Prettier untuk konsistensi kode.

## 💻 Getting Started

### Prerequisites
Pastikan kamu sudah menginstal:
- Node.js 18+
- PostgreSQL
- Git

### Setup
```bash
# Clone repository
git clone https://github.com/username/kopi-journey.git
cd kopi-journey
```

### Install
```bash
npm install
```

### Environment Setup
Buat file `.env` berdasarkan `.env.example` dan isi dengan konfigurasi yang sesuai (tanpa mempublikasikan kredensial).

### Run Development
```bash
npm run dev
```

## 👥 Authors
**Alfito Nur Fadhila**  
- GitHub: [@alfitoNF](https://github.com/SeniorGit)  
- LinkedIn: [linkedin.com/in/alfito-nur-fadhila](https://linkedin.com/in/alfitofadhil-dev)

## 🔭 Future Features
- 🔮 AI-based coffee blend recommendations  
- 📱 Progressive Web App (PWA) support  
- 🌐 Blockchain-based traceability system  
- 💬 Community space for farmers and roasters

## 🙏 Acknowledgements
Proyek ini terinspirasi dari semangat *"transparency in every sip"*, dan bertujuan untuk memberdayakan komunitas kopi lokal melalui teknologi modern.

---

## 📝 License
This project is licensed under the [MIT License](./LICENSE).

---

<p align="right">(<a href="#readme-top">Back to top</a>)</p>
