# LUGUMI — Arabic Adventure

Game edukasi petualangan 3D low-poly untuk Bahasa Arab MTs kelas 8 dengan materi Fi'il Madhi dan Fi'il Mudhari'.

Slogan: **Jelajah Dunia, Kuasai Bahasa!**

## Isi proyek
- `index.html` — halaman utama dan source code game.
- `assets/lugumi-logo.png` — logo brand LUGUMI.

## Fitur
- Dunia desa 3D low-poly menggunakan Three.js.
- Maskot ayam petualang dengan tas dan syal.
- 10 pos tantangan dan 10 soal pilihan ganda bertingkat.
- Materi Fi'il Madhi dan Fi'il Mudhari' untuk MTs kelas 8.
- Reward 20 XP dan 10 koin untuk setiap jawaban benar.
- Indikator energi, progres, animasi, efek suara, fullscreen, dan jeda.
- Layout responsif untuk desktop, tablet, dan layar sentuh.

## Menjalankan lokal
Buka `index.html` melalui browser modern. Koneksi internet diperlukan karena Three.js dan font dimuat melalui CDN.

## Deploy ke Netlify melalui GitHub
1. Ekstrak ZIP ini.
2. Upload **isi folder** (file `index.html`, `README.md`, dan folder `assets`) ke root repository GitHub.
3. Hubungkan repository ke Netlify.
4. Build command: kosong.
5. Publish directory: `.`
6. Deploy site.

Pastikan `index.html` berada langsung di root repository, bukan di dalam subfolder tambahan. Folder `assets` harus tetap sejajar dengan `index.html` agar logo tampil.

## Mengubah soal
Bank soal tersimpan dalam array `QUESTIONS` di bagian awal JavaScript pada `index.html`.
