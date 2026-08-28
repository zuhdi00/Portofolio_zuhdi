# Portofolio Zuhdi Abdillah Hidayat

Website portofolio/CV pribadi berbasis **single-page HTML** yang menampilkan profil, pengalaman kerja, pendidikan, keahlian teknis, dan kontak — dibangun dengan tampilan modern bertema *neon/dark mode*.

🔗 **Live Preview:** Buka `index.html` langsung di browser, atau deploy ke GitHub Pages (lihat bagian [Deploy](#-deploy-ke-github-pages) di bawah).

## ✨ Fitur

- **Hero Section** — foto profil, nama, jabatan, dan perusahaan saat ini
- **Tentang Saya** — profil singkat, info kontak (lokasi, pendidikan, email, telepon), dan tautan sosial media
- **Keahlian Teknis** — dikelompokkan per kategori: Backend & Database, Frontend & Web, Tools & Frameworks, Data & ML, Mobile, IT Infrastructure
- **Pengalaman Kerja** — ditampilkan dalam bentuk *timeline* interaktif
- **Pendidikan** — riwayat pendidikan beserta detail skripsi dan proyek
- **Kontak** — tautan langsung ke email, telepon, LinkedIn, dan GitHub
- **Desain Responsif** — menyesuaikan tampilan untuk perangkat mobile
- **Animasi & Efek Visual** — smooth scroll, efek glow neon, dan animasi *fade-in*

## 🛠️ Teknologi

- **HTML5** — struktur halaman
- **CSS3** — styling custom (gradient, animasi, layout grid/flexbox), tanpa framework CSS eksternal
- **JavaScript (vanilla)** — smooth scroll untuk navigasi anchor link
- **Font Awesome 6** — ikon (sosial media, kontak, dll.)
- **Google Fonts** — *Poppins* & *JetBrains Mono*
- `phpinfo.php` — file bantuan untuk mengecek konfigurasi PHP server (opsional, tidak terkait langsung dengan tampilan portofolio)

## 📁 Struktur File

```
Portofolio_zuhdi/
├── index.html      # Halaman utama portofolio
├── phpinfo.php      # Info konfigurasi PHP server (opsional)
├── portrait.JPG      # Foto profil yang ditampilkan di halaman
└── README.md          # Dokumentasi repository ini
```

## 🚀 Cara Menjalankan

### Opsi 1 — Buka langsung di browser
Karena halaman ini murni HTML/CSS/JS statis, cukup:
```bash
git clone https://github.com/zuhdi00/Portofolio_zuhdi.git
cd Portofolio_zuhdi
```
lalu buka file `index.html` langsung dengan double-click, atau lewat browser.

### Opsi 2 — Menggunakan local server (disarankan)
Supaya path gambar (`portrait.JPG`) dan font/ikon eksternal termuat dengan baik:
```bash
# Jika punya Python
python -m http.server 8000

# Atau menggunakan Live Server extension di VS Code
```
Lalu akses `http://localhost:8000` di browser.

## 🌐 Deploy ke GitHub Pages

Repo ini bisa langsung dipublikasikan sebagai website gratis lewat GitHub Pages:

1. Buka repo di GitHub → **Settings** → **Pages**
2. Pada bagian **Source**, pilih branch `main` dan folder `/ (root)`
3. Klik **Save**
4. Setelah beberapa saat, website akan aktif di:
   ```
   https://zuhdi00.github.io/Portofolio_zuhdi/
   ```

## 👤 Tentang Saya

**Zuhdi Abdillah Hidayat**
IT Software Developer di PT. Supracor Sejahtera — Mojokerto

- 🎓 S1 Matematika, Universitas Airlangga
- 📍 Tulungagung, Jawa Timur
- 📧 zuhdiabdillahhidayat@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/zuhdi-abdillah-hidayat-766192204) · [GitHub](https://github.com/zuhdi00)

## 📌 Catatan

- File `phpinfo.php` sebaiknya **tidak diikutkan saat deploy ke server publik** — file ini menampilkan detail konfigurasi server yang sensitif dan berpotensi menjadi celah keamanan informasi jika diakses publik.
- Data kontak (email, nomor telepon) pada halaman ini bersifat publik sesuai keinginan pemilik untuk keperluan networking/rekrutmen.

## 📄 Lisensi

Konten dan desain merupakan hak milik pribadi Zuhdi Abdillah Hidayat. Silakan hubungi pemilik repo untuk izin penggunaan ulang.
