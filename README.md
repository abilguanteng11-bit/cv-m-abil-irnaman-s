# Abil Irnaman 7x — About Me

Halaman biodata dan portfolio pribadi bertema dark aesthetic: timeline, kartu minat, dashboard skill bergaya status RPG, dan pemutar musik. Dibuat dengan HTML, CSS, dan JavaScript murni.

## Satu file saja

Seluruh halaman, termasuk CSS, JavaScript, foto, video background, dan dua lagu, ada di dalam **`index.html`** (sekitar 11 MB). Tidak ada file lain yang perlu di-upload, jadi tidak ada gambar atau lagu yang bisa hilang.

## Menjalankan di VS Code

1. Buka folder ini di VS Code (`File > Open Folder`).
2. Pasang ekstensi **Live Server**.
3. Klik kanan `index.html`, lalu pilih **Open with Live Server**.

Halaman juga bisa dibuka langsung dengan klik dua kali `index.html`.

## Upload ke GitHub

```bash
git init
git add .
git commit -m "Add About Me page"
git branch -M main
git remote add origin https://github.com/USERNAME/NAMA-REPO.git
git push -u origin main
```

Lewat web GitHub: **Add file > Upload files**, lalu seret `index.html` (batas 25 MB per file, dan file ini sekitar 11 MB).

## Menayangkan dengan GitHub Pages

Di repo GitHub: **Settings > Pages > Branch: main / (root) > Save**. Buka `https://USERNAME.github.io/NAMA-REPO/` setelah 1-5 menit. Jangan buka lewat tampilan file di github.com atau tombol Raw, karena halaman tidak akan tampil dengan benar di sana.

## Mengubah isi

Ubah teks langsung di `index.html`. Nilai awal skill dan data grafik ada di bagian `DEF`, dan daftar lagu ada di bagian `/* music player */`.

## Catatan

Pastikan kamu punya hak untuk memakai lagu dan video yang ada di halaman ini sebelum repo dibuat publik.
