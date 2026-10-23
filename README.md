# Lab Virtual Momentum dan Impuls — PWA

## Publikasi lewat GitHub Pages
1. Buat repository GitHub (misalnya `lab-momentum-impuls`).
2. Upload **seluruh isi folder ini** ke root repository, termasuk folder `icons`.
3. Buka **Settings → Pages → Build and deployment**.
4. Pilih **Deploy from a branch**, branch **main**, folder **/(root)**, lalu **Save**.
5. Tunggu proses deploy. Alamat biasanya:
   `https://USERNAME.github.io/lab-momentum-impuls/`

## Instal sebagai aplikasi
- Android/Chrome: buka alamat website, pilih **Install app** / **Tambahkan ke layar utama**.
- iPad/iPhone/Safari: buka website, tekan **Bagikan → Tambahkan ke Layar Utama**.

PWA memerlukan HTTPS (GitHub Pages sudah menyediakan HTTPS). Kunjungi website sekali saat online agar file tersimpan untuk penggunaan offline.

## Isi paket
- `index.html`: aplikasi dan animasi interaktif
- `manifest.json`: identitas dan pengaturan pemasangan aplikasi
- `sw.js`: service worker untuk cache offline
- `icons/icon-192.png` dan `icons/icon-512.png`: ikon aplikasi

Jika memperbarui aplikasi, ubah `momentum-impuls-v1` di `sw.js` menjadi `momentum-impuls-v2` agar cache lama dibersihkan.
