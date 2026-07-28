# 🎨 Portfolio Modern & Profesional

Portfolio website yang modern, responsif, dan profesional dengan desain yang menarik dan fitur interaktif.

## ✨ Fitur

- **Desain Modern**: Gradient warna yang menarik dan animasi smooth
- **Fully Responsive**: Tampilan optimal di semua perangkat (desktop, tablet, mobile)
- **Smooth Animations**: Animasi scroll dan hover effects
- **Navigation Bar**: Fixed navbar dengan smooth scroll
- **Sections Lengkap**:
  - Hero Section dengan CTA buttons
  - About Section
  - Skills Section dengan progress bars
  - Projects Portfolio
  - Contact Form
  - Social Media Links

## 🚀 Cara Menggunakan

1. **Buka file `index.html`** di browser Anda
2. **Customize konten** sesuai kebutuhan Anda:

### Mengganti Informasi Pribadi

#### Di `index.html`:

**Hero Section** (baris 29-36):
```html
<h1 class="hero-title">
    Halo, Saya <span class="highlight">Nama Anda</span>
</h1>
<p class="hero-subtitle">Web Developer & Designer</p>
```
Ganti "Nama Anda" dengan nama Anda dan ubah job title sesuai profesi Anda.

**About Section** (baris 59-74):
Ganti teks deskripsi tentang diri Anda.

**Skills Section** (baris 80-145):
Tambah atau kurangi skill sesuai keahlian Anda. Ubah `data-progress` untuk menyesuaikan persentase keahlian (0-100).

**Projects Section** (baris 150-231):
Tambah atau edit proyek Anda. Ganti gambar placeholder dengan screenshot proyek Anda.

**Contact Section** (baris 246-250):
```html
<p>email@example.com</p>
<p>+62 812-3456-7890</p>
<p>Lampung, Indonesia</p>
```
Ganti dengan informasi kontak Anda yang sebenarnya.

**Social Media Links** (baris 39-44 & 295-300):
```html
<a href="#" class="social-link"><i class="fab fa-github"></i></a>
```
Ganti `href="#"` dengan URL profil sosial media Anda yang sebenarnya:
- GitHub: `href="https://github.com/username"`
- LinkedIn: `href="https://linkedin.com/in/username"`
- Twitter: `href="https://twitter.com/username"`
- Instagram: `href="https://instagram.com/username"`

### Mengganti Warna

Di `style.css` (baris 2-12), ubah variabel CSS:
```css
:root {
    --primary-color: #6366f1;    /* Warna utama */
    --secondary-color: #8b5cf6;  /* Warna sekunder */
    --accent-color: #ec4899;     /* Warna aksen */
}
```

### Menambah Gambar

1. Buat folder `images` di direktori yang sama dengan `index.html`
2. Letakkan foto profil Anda di folder tersebut
3. Ganti `<div class="image-placeholder">` di About Section dengan:
```html
<img src="images/foto-profil.jpg" alt="Foto Profil">
```

4. Untuk gambar proyek, ganti di Project Cards:
```html
<div class="project-image">
    <img src="images/project1.jpg" alt="Nama Proyek">
</div>
```

### Menambah Font Custom

Tambahkan di `<head>` section pada `index.html`:
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

Lalu di `style.css`, ubah:
```css
body {
    font-family: 'Poppins', sans-serif;
}
```

## 📱 Responsive Breakpoints

- Desktop: > 768px
- Tablet: 768px
- Mobile: < 480px

## 🎨 Customisasi Lanjutan

### Mengaktifkan Efek Opsional

Di `script.js`, uncomment fungsi berikut:

**Typing Effect**:
```javascript
createTypingEffect(); // Efek mengetik pada nama
```

**Parallax Effect**:
```javascript
parallaxEffect(); // Efek parallax di hero section
```

**Particles Effect**:
```javascript
createParticles(); // Partikel animasi di background
```

**Custom Cursor**:
```javascript
createCursorEffect(); // Kursor custom saat hover
```

## 🔧 Form Contact

Saat ini form menampilkan alert. Untuk mengirim email sungguhan:

1. Gunakan service seperti:
   - **EmailJS**: https://www.emailjs.com/
   - **Formspree**: https://formspree.io/
   - **Web3Forms**: https://web3forms.com/

2. Atau setup backend sendiri dengan:
   - Node.js + Nodemailer
   - PHP mail()
   - Python Flask/Django

## 📦 File Structure

```
portofolio/
│
├── index.html          # File HTML utama
├── style.css           # Styling dan desain
├── script.js           # JavaScript untuk interaktivitas
├── README.md           # Dokumentasi (file ini)
│
└── images/             # (Opsional) Folder untuk gambar
    ├── foto-profil.jpg
    ├── project1.jpg
    └── project2.jpg
```

## 🌐 Deploy Website

Anda dapat hosting portfolio ini secara GRATIS di:

1. **GitHub Pages**
   - Push code ke GitHub repository
   - Enable GitHub Pages di Settings
   - Access di: `username.github.io/nama-repo`

2. **Netlify**
   - Drag & drop folder ke netlify.com/drop
   - Atau connect GitHub repo
   - Custom domain gratis

3. **Vercel**
   - Import GitHub repository
   - Auto-deploy pada setiap push
   - Custom domain gratis

4. **Cloudflare Pages**
   - Connect GitHub repository
   - Fast CDN worldwide
   - Unlimited bandwidth

## 💡 Tips

1. **Optimasi Gambar**: Compress gambar sebelum upload (gunakan TinyPNG atau Squoosh)
2. **SEO**: Tambahkan meta tags untuk SEO
3. **Performance**: Minify CSS dan JS untuk production
4. **Testing**: Test di berbagai browser (Chrome, Firefox, Safari)
5. **Mobile First**: Selalu test tampilan mobile

## 📝 Lisensi

Free to use untuk personal dan komersial. Tidak perlu atribusi.

## 🤝 Kontribusi

Feel free untuk modify dan customize sesuai kebutuhan Anda!

---

**Dibuat dengan ❤️ menggunakan HTML, CSS, dan JavaScript**

Selamat menggunakan portfolio Anda! 🚀
