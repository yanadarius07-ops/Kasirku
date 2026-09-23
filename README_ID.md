# KasirKu — Proyek Android

Proyek ini membungkus aplikasi kasir web menjadi aplikasi Android menggunakan WebView.

## Membuat APK
1. Install Android Studio versi terbaru.
2. Pilih **Open** lalu pilih folder `KasirKuAndroid`.
3. Tunggu Gradle selesai melakukan sync.
4. Pilih **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. APK debug biasanya berada di:
   `app/build/outputs/apk/debug/app-debug.apk`

## Fitur
- Produk dan kategori
- Stok
- Keranjang
- Pembayaran dan kembalian
- Riwayat/laporan penjualan
- Data tersimpan di perangkat melalui localStorage

Catatan: proyek menggunakan Android Gradle Plugin 8.5.2 dan compileSdk 35. Android Studio akan mengunduh dependency yang diperlukan saat Gradle sync.
