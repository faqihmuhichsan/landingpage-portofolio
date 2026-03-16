# Assets Folder Structure

```
assets/
├── images/
│   ├── portfolio/     → Screenshot & thumbnail project (contoh: studyflow.png, taskapp.jpg)
│   ├── profile/       → Foto profil & avatar (contoh: faqih-profile.jpg)
│   └── icons/         → Custom icon & favicon (contoh: favicon.ico, logo.svg)
├── videos/            → Video demo project (contoh: studyflow-demo.mp4)
└── documents/         → CV, resume, sertifikat (contoh: cv-faqih.pdf)
```

## Cara Pakai

### Untuk Portfolio Project Image:
Simpan screenshot project di `images/portfolio/`, lalu update di `index.html`:
```html
<!-- Ganti project-placeholder dengan img -->
<div class="project-image">
    <img src="assets/images/portfolio/nama-project.png" alt="Nama Project">
    ...
</div>
```

### Untuk Profile Photo:
Simpan foto profil di `images/profile/`, lalu update avatar di about section.

### Format yang Disarankan:
- **Gambar**: `.jpg`, `.png`, `.webp` (optimized, max 500KB)
- **Video**: `.mp4`, `.webm` (max 10MB)
- **Dokumen**: `.pdf`
