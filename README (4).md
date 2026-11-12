# Persamaan Laju Reaksi dan Orde Reaksi

Materi interaktif Kimia SMA/MA Kelas XI, Bab Laju Reaksi, Subbab 3. Halaman ini membahas persamaan laju reaksi, orde reaksi, cara menentukan orde dari data percobaan, serta tetapan laju dan satuannya. Materi dilengkapi tiga simulasi, contoh soal bertahap, cek cepat, dan latihan pilihan ganda kompleks.

## Isi halaman

- **Persamaan laju reaksi:** bentuk umum, arti tiap lambang, dan contoh reaksi yang ordenya berbeda dari koefisien.
- **Orde nol, satu, dan dua:** rumus dasar perubahan laju akibat perubahan konsentrasi, tabel, dan contoh soal.
- **Simulasi 1: Penjelajah orde reaksi.** Pilih orde dan kelipatan konsentrasi, lalu lihat diagram batang, grafik laju terhadap konsentrasi, dan perhitungannya.
- **Menentukan orde dari data:** rumus perbandingan dua percobaan beserta contoh soal NO₂ + CO.
- **Simulasi 2: Laboratorium reaksi misteri.** Ukur laju awal pada konsentrasi pilihan, bandingkan dua percobaan secara otomatis, lalu tebak persamaan lajunya.
- **Tetapan laju (k):** rumus, contoh perhitungan dan pemeriksaan, serta penurunan satuan k.
- **Simulasi 3: Penurun satuan k** untuk orde total 0 sampai 3.
- Dua contoh soal lengkap, rangkuman, dan 10 soal latihan dengan skor.

## Struktur file

```
sub-bab-3/
├── index.html
└── README.md
```

Seluruh CSS, JavaScript, ornamen, dan ikon tab sudah berada di dalam `index.html`. Font dimuat dari Google Fonts, termasuk STIX Two Text untuk penulisan rumus. Proyek ini tidak memerlukan `package.json`, proses build, atau `vercel.json`.

## Deploy ke Vercel

### Periksa dua hal ini sebelum mengunggah

1. **Nama file harus persis `index.html`.** Browser sering menambahkan angka saat mengunduh, misalnya `index (1).html`. Ganti namanya kembali menjadi `index.html`. Hal yang sama berlaku untuk `README.md`.
2. **`index.html` harus terlihat langsung di halaman utama repositori GitHub**, bukan di dalam folder.

### Lewat GitHub

1. Buka repositori, lalu pilih **Add file → Upload files**.
2. Seret `index.html` dan `README.md` (filenya saja, bukan foldernya), lalu tekan **Commit changes**.
3. Pastikan daftar file di repositori menampilkan `index.html` tanpa tambahan angka.
4. Di [vercel.com](https://vercel.com), impor repositori tersebut dengan **Framework Preset: Other**, kosongkan Build Command dan Output Directory, lalu tekan **Deploy**.

Jika repositorinya sudah terhubung ke Vercel, cukup ganti `index.html` di GitHub. Vercel akan men-deploy ulang secara otomatis.

## Jika muncul 404: NOT_FOUND

| Yang terlihat di GitHub | Cara memperbaiki |
|---|---|
| `index (1).html` atau nama lain | Klik file → ikon pensil → ubah nama menjadi `index.html` → Commit changes |
| Ada folder dan `index.html` di dalamnya | Di Vercel: Settings → Build and Deployment → Root Directory, isi dengan nama folder, lalu Redeploy |
| `index.html` tidak ada | Unggah ulang dan pastikan menekan **Commit changes** |

## Mencoba di komputer sendiri

Buka `index.html` dengan klik dua kali. Halaman berjalan langsung di browser tanpa server.
