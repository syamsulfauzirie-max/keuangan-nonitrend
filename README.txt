APLIKASI KEUANGAN NONITREND — VERSI AWAL

Isi:
- index.html: aplikasi pencatatan.
- manifest.json dan sw.js: dukungan PWA/offline jika dihosting melalui HTTPS.

Cara mencoba:
1. Ekstrak ZIP.
2. Buka index.html melalui browser HP atau laptop.
3. Data disimpan di penyimpanan browser perangkat tersebut.

Agar bisa dipasang seperti aplikasi:
1. Upload seluruh isi folder ke GitHub repository.
2. Aktifkan GitHub Pages (Settings > Pages > Deploy from branch > main / root).
3. Buka URL HTTPS GitHub Pages di Chrome Android.
4. Pilih menu browser "Tambahkan ke layar utama" atau "Install app".

ATURAN HITUNG:
- Modal barang = Rp170.000 x jumlah pcs.
- TF: nominal yang diinput adalah harga produk yang ditransfer; ongkir penjual dikurangi dari laba.
- COD: total yang diinput sudah termasuk ongkir; ongkir dikurangi dari laba.
- COD default Pending; tidak masuk uang diterima/laba terealisasi sampai status Berhasil.
- Pengeluaran lain dicatat terpisah.
- Simpan backup JSON secara berkala. Data lokal tidak otomatis tersinkron ke perangkat lain.

Catatan:
Versi awal ini menghitung modal barang pada transaksi yang berhasil. COD gagal tidak masuk uang diterima maupun laba. Jika ada ongkir retur/biaya COD gagal, catat sebagai Pengeluaran lain agar tercermin dalam laporan.
