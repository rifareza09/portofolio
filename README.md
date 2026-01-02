# 🌟 Portfolio Website - Rifa Reza Fahlevi

Portfolio website untuk mahasiswa Computer Science yang mencari internship opportunities.

## ✨ Fitur Utama

- 🎨 **Desain Modern tapi Tidak Berlebihan** - Cocok untuk mahasiswa/fresh graduate
- 🌓 **Dark Mode** - Toggle antara light dan dark theme
- 📱 **Fully Responsive** - Sempurna di semua device (mobile, tablet, desktop)
- 🚀 **Smooth Animations** - Animasi yang halus pada setiap elemen
- 💼 **Project Showcase** - Menampilkan project dengan link ke GitHub
- 📧 **Multiple Contact Links** - WhatsApp, Email, LinkedIn, Instagram, GitHub
- ⚡ **Fast Loading** - Tidak menggunakan API external, lebih cepat
- 🎯 **Internship-Ready** - Sesuai untuk apply magang atau entry-level position

## 🛠️ Teknologi yang Digunakan

- HTML5
- CSS3 (dengan CSS Variables untuk theming)
- JavaScript (Vanilla JS)
- GitHub API
- Font Awesome Icons

## 📸 Foto Profil

Untuk menampilkan foto profil Anda:

### Spesifikasi Foto:
1. **Nama file**: `profile.jpg` atau `profile.png` (penting!)
2. **Ukuran**: 500x500px (kotak/square) - recommended
3. **Format**: JPG atau PNG
4. **Lokasi**: Simpan di folder `images/`

### Langkah-langkah:
1. Rename foto Anda menjadi `profile.jpg` atau `profile.png`
2. Paste foto ke folder `images/` (buat folder jika belum ada)
3. Edit file `index.html` di bagian hero section (sekitar baris 68-73)
4. Uncomment baris berikut (hapus `<!--` dan `-->`):

```html
<img src="images/profile.jpg" alt="Rifa Reza Fahlevi">
```

5. Hapus atau comment bagian `<div class="image-placeholder">...</div>`

## 🚀 Cara Deploy ke GitHub Pages

### Opsi 1: Repository username.github.io (Recommended)

```bash
# 1. Buat repository baru di GitHub dengan nama: rifareza09.github.io

# 2. Di folder project, jalankan:
git init
git add .
git commit -m "Initial commit: Portfolio website"

# 3. Connect ke GitHub dan push
git branch -M main
git remote add origin https://github.com/rifareza09/rifareza09.github.io.git
git push -u origin main

# 4. Website otomatis live di: https://rifareza09.github.io
```

### Opsi 2: Repository Biasa dengan GitHub Pages

```bash
# 1. Buat repository dengan nama apapun, misal: portfolio

# 2. Di folder project, jalankan:
git init
git add .
git commit -m "Initial commit: Portfolio website"

# 3. Connect ke GitHub dan push
git branch -M main
git remote add origin https://github.com/rifareza09/portfolio.git
git push -u origin main

# 4. Aktifkan GitHub Pages:
#    - Buka repository di GitHub
#    - Klik Settings > Pages
#    - Source: pilih branch 'main' dan folder '/ (root)'
#    - Klik Save
#    - Website akan live di: https://rifareza09.github.io/portfolio
```

### Update Website Setelah Deploy

Setiap kali ada perubahan:

```bash
git add .
git commit -m "Update: deskripsi perubahan"
git push
```

Website akan otomatis update dalam 1-2 menit.

## 📝 Cara Menambah Project Baru

Edit file `index.html` di section Projects, duplikasi card dan edit:

```html
<div class="project-card reveal">
    <div class="project-image">
        <i class="fab fa-github"></i> <!-- atau icon lain -->
    </div>
    <div class="project-content">
        <h3 class="project-title">Nama Project Baru</h3>
        <p class="project-description">
            Deskripsi singkat tentang project Anda.
        </p>
        <div class="project-links">
            <a href="https://github.com/rifareza09/nama-repo" target="_blank" rel="noopener noreferrer" class="project-link project-link-primary">
                <i class="fab fa-github"></i>
                <span>View on GitHub</span>
            </a>
        </div>
    </div>
</div>
```

## 📞 Contact Information

Pastikan semua link sudah benar di file `index.html`:

- **Email**: rifarezafahlevi09@gmail.com
- **WhatsApp**: +62 821-1431-2390
- **LinkedIn**: Update sesuai profile Anda
- **Instagram**: [@rifareza_](https://www.instagram.com/rifareza_/)
- **GitHub**: [github.com/rifareza09](https://github.com/rifareza09)

## 🎯 Struktur Folder

```
portofolioeja/
│
├── index.html          # File HTML utama
├── styles.css          # Semua styling dan animasi
├── script.js           # JavaScript untuk interaktivity
├── README.md           # Dokumentasi
│
└── images/            # Folder untuk foto (buat manual)
    └── profile.jpg    # Foto profil Anda
```

## 🌐 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

## 📱 Testing

Untuk testing di local sebelum deploy:

### Opsi 1: Live Server (VS Code Extension)
1. Install extension "Live Server" di VS Code
2. Right-click pada `index.html`
3. Pilih "Open with Live Server"

### Opsi 2: Python Simple Server
```bash
# Jika ada Python 3
python -m http.server 8000

# Buka browser ke http://localhost:8000
```

### Opsi 3: PHP Built-in Server (Laragon)
```bash
# Di folder project
php -S localhost:8000

# Buka browser ke http://localhost:8000
```

## 🎨 Fitur Animasi

- ✨ Typing effect pada hero section
- 🌊 Floating particles background
- � Smooth scroll reveal animations pada semua section
- 🔢 Smooth transitions
- 🎭 Hover effects pada cards dan buttons
- 🌓 Smooth theme transition (dark/light mode)
- 📱 Mobile-optimized animations

Semua elemen penting sudah diberi class `reveal` untuk animasi saat scroll!

## 🎯 Target Penggunaan

Website ini cocok untuk:
- ✅ Mahasiswa Computer Science
- ✅ Fresh graduate
- ✅ Internship applications  
- ✅ Entry-level developer positions
- ✅ Freelance portfolio

---

**Made with ❤️ by Rifa Reza Fahlevi**

Portfolio ini sudah disesuaikan untuk mahasiswa yang mencari magang - tidak terlalu profesional tapi tetap menarik untuk HRD!
