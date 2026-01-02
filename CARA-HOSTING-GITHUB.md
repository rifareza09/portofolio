# 🚀 CARA HOSTING DI GITHUB PAGES

## Langkah 1: Buat Repository di GitHub

1. Buka https://github.com
2. Login ke akun Anda (rifareza09)
3. Klik tombol **"New"** (hijau) atau ikon **"+"** di kanan atas > **"New repository"**
4. Isi form:
   - **Repository name**: `rifareza09.github.io` (PENTING: pakai format username.github.io)
   - **Description**: Portfolio website (opsional)
   - **Public** (harus public untuk GitHub Pages gratis)
   - Jangan centang "Add a README file"
5. Klik **"Create repository"**

## Langkah 2: Upload Website ke GitHub

Buka Command Prompt / Terminal di folder `D:\portofolioeja`, lalu jalankan:

```bash
# 1. Initialize git
git init

# 2. Add semua file
git add .

# 3. Commit
git commit -m "Initial commit: Portfolio website"

# 4. Rename branch ke main
git branch -M main

# 5. Connect ke GitHub (ganti dengan URL repository Anda)
git remote add origin https://github.com/rifareza09/rifareza09.github.io.git

# 6. Push ke GitHub
git push -u origin main
```

### Jika diminta username dan password:
- **Username**: rifareza09
- **Password**: Gunakan **Personal Access Token** (bukan password biasa)
  
  Cara buat token:
  1. GitHub > Settings > Developer settings > Personal access tokens > Tokens (classic)
  2. Generate new token > Centang "repo"
  3. Copy token dan paste sebagai password

## Langkah 3: Aktifkan GitHub Pages (Otomatis)

Jika repository bernama `username.github.io`, GitHub Pages otomatis aktif!

Website langsung bisa diakses di: **https://rifareza09.github.io**

Tunggu 1-2 menit untuk deployment pertama.

## Cara Update Website

Setiap kali ada perubahan:

```bash
git add .
git commit -m "Update: deskripsi perubahan"
git push
```

Website akan otomatis update dalam 1-2 menit.

---

## Alternative: Pakai GitHub Desktop (Lebih Mudah)

1. Download **GitHub Desktop**: https://desktop.github.com
2. Install dan login
3. Klik **"Add"** > **"Add existing repository"**
4. Pilih folder `D:\portofolioeja`
5. Klik **"Publish repository"**
6. Nama repository: `rifareza09.github.io`
7. Hilangkan centang "Keep this code private"
8. Klik **"Publish repository"**

Selesai! Website live di: **https://rifareza09.github.io**

---

## Troubleshooting

**❌ Error: repository already exists**
- Repository sudah dibuat, tinggal push saja
- Gunakan: `git remote add origin https://github.com/rifareza09/rifareza09.github.io.git`

**❌ Website belum muncul**
- Tunggu 2-5 menit
- Cek di: GitHub > Repository > Settings > Pages
- Pastikan Source: Deploy from branch "main"

**❌ Error 404**
- Pastikan ada file `index.html` di root folder
- Pastikan repository public
- Clear cache browser (Ctrl + Shift + R)

---

## Lihat Website Anda

Setelah deploy sukses, buka di browser:

🌐 **https://rifareza09.github.io**

Share link ini di CV Anda! 🎉
