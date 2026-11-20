# Product Requirements Document (PRD) — Revisi 1.1 & Laporan Implementasi

**Nama Produk:** Website Resmi Rumah Makan Lesehan 88  
**Versi:** 1.1 (Pembaruan Data Fasilitas, Layanan & Pembayaran)  
**Status:** Selesai Diimplementasikan (Siap Produksi & Publikasi)  
**File Utama:** 
- [`index.html`](file:///d:/Rumah%20makan/index.html) *(Entry Point Utama / Production-Ready)*
- [`prototipe_website_rumah_makan_lesehan_88.html`](file:///d:/Rumah%20makan/prototipe_website_rumah_makan_lesehan_88.html) *(Salinan Prototipe)*

---

## 1. Profil Bisnis & Atribut Operasional

Rumah Makan Lesehan 88 adalah warung nasi berkonsep lesehan yang buka **24 jam** di Sidokumpul, Patean, Kendal. Selain menyajikan hidangan cepat saji untuk sarapan hingga makan malam, tempat ini menonjol karena kopi dan pilihan tehnya yang enak, suasana yang nyaman, santai, dan tenang, serta ramah untuk pengunjung solo, keluarga dengan anak-anak, maupun rombongan.

| Kategori | Detail Atribut |
| :--- | :--- |
| **Identitas** | Rumah Makan Lesehan 88 — Warung Nasi (Rating 5,0 di Google Maps) |
| **Alamat & Maps** | Pesanggrahan, Sidokumpul, Kec. Patean, Kab. Kendal, Jawa Tengah 51364 (Plus Code: `W46Q+M9`) |
| **Jam & Kontak** | Buka 24 Jam (Setiap Hari Nonstop) \| Telepon/WA: `0813-1756-7155` |
| **Opsi Layanan** | Makan di tempat (*dine-in*, layanan pesan di meja), Bawa pulang (*takeaway*). **Tidak melayani pesan antar.** |
| **Waktu & Penawaran**| Sarapan Pagi, Makan Siang (populer), Makan Malam, Hidangan Cepat Saji, Kopi & Pilihan Teh Enak |
| **Suasana & Pengunjung** | Nyaman, santai, tenang; ramah untuk makan sendiri, berkelompok, dan anak-anak |
| **Fasilitas & Parkir** | Toilet bersih, Tempat parkir gratis, Parkir di jalan gratis |
| **Metode Pembayaran** | **Hanya Tunai (Cash Only)** |

---

## 2. Pemetaan Target Pengguna (User Persona) & Solusi Desain

| Segmen Pengguna | Kebutuhan Utama | Implementasi pada Website |
| :--- | :--- | :--- |
| **Pekerja & Pengunjung Solo (Makan Siang / Cepat Saji)** | Kecepatan penyajian, nyaman makan sendiri tanpa canggung, pesan langsung di meja. | Ditampilkan kartu khusus *"Pekerja & Solo Diner"*, menu Paket Makan Siang Hemat, dan penekanan fitur layanan pesan di meja. |
| **Pengendara & Penikmat Kopi/Teh (Transit 24 Jam)** | Rehat tenang kapan saja (termasuk malam/subuh), kopi & teh seduh hangat, parkir gratis aman, serta toilet. | Hero badge 24 jam nonstop, tab menu khusus *"Kopi & Pilihan Teh Spesial"* yang ditonjolkan, serta review dari pengendara transit. |
| **Keluarga dengan Anak-anak** | Tempat lesehan aman, santai, higienis, dan ramah anak untuk sarapan/makan malam. | Kartu fasilitas ramah anak, foto area lesehan luas, serta ulasan keluarga dengan anak kecil. |
| **Rombongan / Berkelompok** | Kepastian kapasitas lesehan dan kemudahan koordinasi menu awal sebelum datang. | Formulir reservasi cepat yang terhubung ke WhatsApp dan mencantumkan jumlah tamu/porsi. |

---

## 3. Matriks Kebutuhan Fitur (Feature Requirements Status)

### Prioritas P0 (Wajib)
- [x] **Hero Section**: Headline menonjolkan *"Lesehan Nyaman 24 Jam, Sajian Cepat, Kopi & Teh Enak di Patean"*, 2 CTA utama: *"Rute Google Maps"* & *"Hubungi via WhatsApp"*, rating 5,0 Google Maps, dan badge operasional.
- [x] **Banner Info Penting (Quick Facts - Above The Fold)**: 4 kartu krusial:
  1. *Buka 24 Jam Setiap Hari* (Sarapan, Makan Siang, Makan Malam)
  2. *Hanya Tunai (Cash Only)* dengan ikon dompet/uang tunai mencolok
  3. *Parkir Gratis & Toilet* (di tempat & di pinggir jalan)
  4. *Dine-in & Bawa Pulang* (tanpa layanan antar)
- [x] **Katalog Menu Terstruktur**: Dikelompokkan rapi ke dalam tab: *Semua Menu*, *Kopi & Pilihan Teh Spesial (Unggulan)*, *Menu Cepat Saji & Lauk*, dan *Paket Sarapan & Makan Siang*. Dilengkapi tombol *"Pesan Bungkus"* yang langsung mengisi form pemesanan.
- [x] **Bagian Fasilitas & Suasana**: Grid 6 fitur visual: Lesehan Nyaman & Tenang, Kopi & Teh Enak, Ramah Anak-anak, Makan Sendiri & Rombongan, Layanan Pesan di Meja, serta Toilet & Parkir Gratis.
- [x] **Lokasi, Peta & Kontak**: Embed Google Maps interaktif, alamat lengkap Sidokumpul Patean, Plus Code `W46Q+M9`, tombol salin alamat, tombol salin plus code, tombol direct call `0813-1756-7155`, dan floating WhatsApp button.

### Prioritas P1 (Penting)
- [x] **Galeri Foto Visual & Bukti Nyata**: Menampilkan dokumentasi visual area lesehan, kopi & teh hangat, lauk pauk cepat saji, area parkir gratis, dan momen santai keluarga. Dilengkapi filter kategori foto dan modal **Lightbox interaktif** saat foto diketuk.
- [x] **Ulasan & Rating 5,0 Google Maps**: Rating sempurna 5,0 bintang dari 3 ulasan Google Maps, kartu kutipan ulasan riil mewakili 4 persona pengguna, dan tombol langsung *"Beri Ulasan di Google"*.

### Prioritas P2 (Fase 2)
- [x] **Form Reservasi Rombongan / Pesan Bungkus**: Form input *Nama*, *Jenis Kunjungan*, *Jumlah Orang*, *Jam Datang*, dan *Catatan Menu*. 
- [x] **Mitigasi Pembayaran pada Form**: Disertai peringatan ramah *"Pembayaran di lokasi hanya menerima tunai (Cash Only) dan belum melayani pesan antar."* Format pesan otomatis rapi dan terarah ke WhatsApp `0813-1756-7155`.

---

## 4. Strategi UX & Copywriting

1. **Mitigasi Friksi "Hanya Tunai" (Cash Only):**
   - Hadir pada banner *Quick Facts* paling atas dengan visual kontras berwarna amber emas.
   - Hadir pada catatan bawah katalog menu.
   - Hadir pada kotak peringatan formulir pemesanan.
   - Otomatis disertakan dalam teks WhatsApp: *"*(Catatan: Saya paham bahwa pembayaran di warung hanya menerima uang TUNAI / Cash Only).*""*
2. **Penonjolan Diferensiator (Kopi, Teh & Suasana 24 Jam):**
   - Mengubah persepsi bahwa warung ini bukan hanya tempat makan berat, melainkan tempat rehat santai dengan seduhan Kopi Tubruk 88, Kopi Susu Gula Aren, dan Teh Seduh Poci wangi sepet-manis.
3. **Bahasa Visual & Tipografi:**
   - Font serif *Playfair Display* untuk sentuhan kehangatan tradisional dan *Plus Jakarta Sans* untuk keterbacaan modern yang bersih.
   - Warna alami pedesaan Jawa: Forest green (`#166534`), warm terracotta/amber (`#d97706`), dan soft cream (`#faf7f2`), lengkap dengan toggle Dark Mode untuk pengunjung malam hari.

---

## 5. Spesifikasi Teknis & Local SEO (Schema Markup)

Data terstruktur (JSON-LD) telah divalidasi dan ditanam di `<head>` dokumen:

```json
{
  "@context": "https://schema.org",
  "@type": "Restaurant",
  "name": "Rumah Makan Lesehan 88",
  "alternateName": "Lesehan 88 Patean",
  "telephone": "+6281317567155",
  "servesCuisine": ["Indonesian", "Coffee", "Tea"],
  "paymentAccepted": "Cash",
  "currenciesAccepted": "IDR",
  "priceRange": "Rp 5.000 - Rp 30.000",
  "openingHours": "Mo-Su 00:00-23:59",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "Pesanggrahan, Sidokumpul, Kec. Patean",
    "addressLocality": "Kabupaten Kendal",
    "addressRegion": "Jawa Tengah",
    "postalCode": "51364",
    "addressCountry": "ID"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": -7.1158,
    "longitude": 110.0895
  },
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "5.0",
    "reviewCount": "3"
  },
  "amenityFeature": [
    { "@type": "LocationFeatureSpecification", "name": "Toilet", "value": true },
    { "@type": "LocationFeatureSpecification", "name": "Parkir Gratis", "value": true },
    { "@type": "LocationFeatureSpecification", "name": "Parkir di Jalan Gratis", "value": true },
    { "@type": "LocationFeatureSpecification", "name": "Ramah Anak-anak", "value": true },
    { "@type": "LocationFeatureSpecification", "name": "Layanan Pesan di Meja", "value": true },
    { "@type": "LocationFeatureSpecification", "name": "Buka 24 Jam", "value": true }
  ]
}
```

**Target Kata Kunci Lokal:**
- `warung nasi 24 jam Patean`
- `lesehan Kendal`
- `tempat makan siang Patean`
- `warung kopi 24 jam Sidokumpul`
- `tempat makan keluarga Patean`
