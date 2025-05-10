# 📱💳 Payment Options Landing Page

![Preview Website](https://github.com/YoshCasaster/Web-payment-list/blob/master/webnya.png?raw=true)  
*Gambarnya keren kan? Ini preview websitenya!*

## 🚀 Apa Ini?

Ini adalah landing page keren buat nampilin metode pembayaran lu, pake **HTML, CSS, JS semua dalam 1 file** doang! Fiturnya:

- 🎥 Hero section dengan video background keren
- 🌓 Tema terang/gelap (dark/light mode)
- 📋 Daftar payment method (DANA, OVO, GOPAY, PayPal, QRIS)
- 📋 Tombol copy nomor rekening otomatis
- 📱 Responsive (tampilan oke di HP & laptop)
- ✨ Animasi-animasi keren

## 🛠 Cara Pakai

Gampang banget! Tinggal:

1. **Edit nomor rekening** di bagian HTML (cari aja `08123456789`, ganti semua)
2. **Ganti logo** (cari `<img src="https://pomf2.lain.la/f/b4k5if9w.png"`)
3. **Ganti QRIS** (cari `<img src="https://encrypted-tbn0...`)

## 🎨 Customisasi

### 🖼 Ganti Gambar:
```html
<!-- Logo -->
<img src="LINK-LOGO-LU" alt="Company Logo">

<!-- QRIS -->
<img src="LINK-QRIS-LU" alt="QRIS Code">
```

### 🎥 Ganti Video Background:
```html
<source src="LINK-VIDEO-LU" type="video/mp4">
```

### 🌈 Ganti Warna:
Cari aja bagian ini di CSS:
```css
background: linear-gradient(to right, #a78bfa, #60a5fa);
```
Ganti kode warna sesuai selera lu!

## 💡 Fitur Keren

- **Dark/Light Mode** - Pencet tombol bulan di pojok kanan atas
- **Auto Copy** - Klik icon copy otomatis salin nomor
- **Typing Effect** - Text di hero section berubah-ubah sendiri

## 📝 Catatan Penting

1. **Untuk video background**, bisa pake link dari [Pexels](https://www.pexels.com/) atau upload sendiri
2. **Logo payment** udah include, tapi kalo mau ganti tinggal cari aja link gambarnya
3. **Kalo mau nambah payment method**, tinggal duplikat salah satu bagian `<div class="payment-row">` dan edit isinya

## 👨‍💻 Author

Dibuat sama [YoshCasaster](https://github.com/YoshCasaster) dengan ❤️

---

**Gampang kan?** Tinggal edit dikit, deploy, dan langsung bisa dipake! Keren kan single file doang tapi fiturnya lengkap? 😎