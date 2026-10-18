# Node.js Basic

Repositori latihan pembelajaran dasar Node.js. Berisi contoh kode dan eksperimen kecil selama mempelajari konsep dasar Node.js, antara lain modularisasi (membagi kode ke beberapa berkas modul) dan penggunaan Node Package Manager (npm).

## Isi Repositori

- `app.js` - berkas utama latihan yang dijalankan dengan Node.js
- `modularization/` - contoh penerapan modularisasi kode JavaScript di Node.js
- `node-package-manager/` - contoh penggunaan npm dan paket pihak ketiga
- `lib/` - berkas pustaka pendukung latihan
- `package.json` - konfigurasi proyek, dependensi yang dipakai adalah lodash

## Teknologi

- Node.js
- JavaScript
- npm dan lodash

## Cara Menjalankan

Prasyarat: Node.js dan npm.

1. Clone repositori ini.
2. Instal dependensi:

   ```bash
   npm install
   ```

3. Jalankan berkas utama:

   ```bash
   npm start
   ```

   Perintah `npm start` menjalankan `app.js` dengan `NODE_ENV=production`, sedangkan `npm run start-dev` menjalankannya dengan `NODE_ENV=development`. Berkas latihan lain dapat dijalankan langsung dengan perintah `node <nama-berkas>`.
