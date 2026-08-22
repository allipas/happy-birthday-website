# 💗 Birthday Website

Website ulang tahun interaktif, dibuat tanpa backend dan siap dipasang di GitHub Pages.

## Struktur

```text
birthday-website/
├── index.html
├── style.css
├── script.js
└── assets/
    ├── photo1.jpg
    ├── photo2.jpg
    ├── photo3.jpg
    ├── placeholder.svg
    └── music/
        ├── song1.mp3
        ├── song2.mp3
        └── song3.mp3
```

## Cara mengedit

Buka `script.js`, lalu cari:

```js
const CONFIG = {
  name: "Florence",
  birthday: "DECEMBER 29 · THE MOST SPECIAL DAY",
  music: [...]
};
```

Ganti `Florence` dengan nama orangnya dan tanggal sesuai kebutuhan.

### Foto

Masukkan foto ke folder `assets`, lalu beri nama:

- `photo1.jpg`
- `photo2.jpg`
- `photo3.jpg`

### Musik

Masukkan file MP3 ke:

`assets/music/`

dengan nama:

- `song1.mp3`
- `song2.mp3`
- `song3.mp3`

Kalau nama file berbeda, ubah bagian `file:` di `script.js`.

## Jalankan di PC

Paling gampang: buka `index.html` langsung di browser.

Untuk hasil terbaik saat development, bisa pakai VS Code + Live Server.

## Upload ke GitHub Pages

1. Buat repository baru.
2. Upload `index.html`, `style.css`, `script.js`, dan folder `assets`.
3. Commit changes.
4. Masuk `Settings` → `Pages`.
5. Pilih `Deploy from a branch`.
6. Branch: `main`, folder: `/ (root)`.
7. Save.
8. Tunggu beberapa saat sampai GitHub Pages selesai deploy.

## Fitur

- Loading screen
- Gift opening animation
- Hero birthday
- Floating particles
- Digital bouquet
- Interactive flower messages
- Photo gallery
- Image modal
- Reasons section
- Music player
- Playlist
- Progress bar
- Previous/next track
- Wish button
- Confetti
- Responsive mobile/PC
- Keyboard shortcut Space untuk play/pause
- Escape untuk menutup foto

Catatan: musik harus berupa file yang memang boleh kamu gunakan. Jangan upload lagu berhak cipta kalau kamu tidak punya izin yang diperlukan.
