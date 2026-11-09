# UCGSO – Upiek Cake | Demo GitHub Pages

**Versi:** 0.3 – demo antarmuka statis, gratis untuk GitHub Pages.

## Perhatian
- Semua angka keuangan, nama produk, harga, dan pesanan adalah **data simulasi** dan **bukan data asli**.
- Form PO rapat dan kasir hanya simulasi. Tidak mengirim data atau menyimpan transaksi nyata.
- Tidak ada login, backend, database, ataupun integrasi Google Sheets dalam paket ini.
- Jangan masukkan nomor WhatsApp, alamat, atau informasi pelanggan sesungguhnya ke formulir demonstrasi.

## Cara terbitkan gratis di GitHub Pages

1. Login di GitHub dan buka https://github.com/new . Buat repository `ucgso-upiek-demo` sebagai **Public**, centang **Add a README file**, klik **Create repository**.
2. Di repository pilih **Add file → Upload files**. Upload file `index.html` dan `.nojekyll` dari folder yang Anda ekstrak. Klik **Commit changes**. (Jangan upload ZIP saja: GitHub Pages tidak akan mengekstraknya.)
3. Buka **Settings → Pages**. Di **Build and deployment**, pilih **Deploy from a branch**, `main`, `/(root)` kemudian **Save**.
4. Setelah status berhasil, di halaman Pages klik **Visit site**. Alamat proyek biasanya berformat `https://NAMA-USER.github.io/ucgso-upiek-demo/`; gunakan link yang benar-benar muncul di GitHub, jangan menebak.

**Alternatif:** Jika GitHub sudah mengizinkan ChatGPT mengakses repository baru tersebut, setelah membuat repository Anda bisa cukup mengirim URL-nya untuk mencoba membiarkan ChatGPT mengunggah `index.html`. Pengaturan GitHub Pages tetap perlu dilakukan oleh pemilik repository karena konektor tidak memiliki aksi administrasi Pages.

## Paket isi
- `index.html` – seluruh UI + CSS + JavaScript dalam satu file.
- `.nojekyll` – mencegah proses Jekyll tidak diperlukan.
- `README.md` – petunjuk dan batasan demo.

## Perkembangan selanjutnya
Untuk transaksi nyata, kembangkan backend Python FastAPI dengan PostgreSQL persisten, autentikasi pengguna, kontrol hak akses, audit log, backup, dan sinkronisasi laporan Google Sheets. Jangan menjalankan transaksi produksi di GitHub Pages karena hanya hosting file statis.
