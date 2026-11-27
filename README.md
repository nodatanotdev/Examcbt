# CBT ABM 2 — Mode Tes

Repositori ini menyimpan APK CBT ABM 2 asli dan versi **Mode Tes** yang disesuaikan dengan tampilan awal *Config By NODATA*. Aplikasi membuka halaman CBT melalui WebView; akun dan aturan ujian tetap dikelola oleh penyelenggara ujian.

## Unduh

- [Unduh CBTABM2_ModeTes.apk](https://github.com/nodatanotdev/Examcbt/releases/download/v1.0.0/CBTABM2_ModeTes.apk)
- [Lihat halaman rilis](https://github.com/nodatanotdev/Examcbt/releases/tag/v1.0.0)
- APK asli tersedia sebagai [`CBTABM2.apk`](CBTABM2.apk) di repositori.

## Perbedaan versi

| | APK asli | Mode Tes |
|---|---|---|
| Nama file | `CBTABM2.apk` | `CBTABM2_ModeTes.apk` |
| Identitas Android | `com.coco.cbtabm2` | `com.coco.cbtabm2.modetes` |
| Nama aplikasi | CBT ABM 2 | CBT ABM 2 Mode Tes |

Identitas yang berbeda memungkinkan kedua versi dipasang berdampingan. Data aplikasi dan sesi login **terpisah**. APK asli di repositori tidak diubah.

## Penyesuaian Mode Tes

- Kartu putih **Config By NODATA** dan foto profil ditampilkan selama 5 detik sebelum halaman CBT dimuat.
- Kunci layar (*screen pinning*), pembatasan split-screen/aplikasi mengambang, `FLAG_SECURE`, dan alarm kecurangan lokal dinonaktifkan.
- Suara selesai diputar ketika keluar menggunakan tombol merah setelah konfirmasi.
- Tombol Back kembali ke halaman sebelumnya jika ada riwayat WebView; jika tidak ada, aplikasi dipindahkan ke latar belakang. Home dan Recent Apps tidak memicu alarm lokal.

## Instalasi

1. Unduh APK Mode Tes dari tautan rilis di atas ke perangkat Android.
2. Buka file unduhan dan izinkan pemasangan dari sumber tersebut jika Android memintanya.
3. Pasang dan buka **CBT ABM 2 Mode Tes**. APK asli tidak perlu dihapus.

Versi Mode Tes lama yang menggunakan identitas aplikasi asli tidak otomatis memindahkan data atau login ke versi baru. APK terbaru sudah diperiksa tanda tangan dan alignment-nya, tetapi belum diuji pemasangannya pada perangkat fisik atau emulator. Persyaratan minimum pada APK adalah Android 7.0 (API 24).

## Privasi dan penggunaan

Penyesuaian aplikasi **tidak menjamin aktivitas tidak terpantau**. Situs CBT yang dibuka dapat mencatat data yang dikirim ke server dan mungkin mendeteksi perubahan fokus atau visibilitas halaman. Kemampuan yang tersedia bergantung pada situs dan izin perangkat. Gunakan aplikasi sesuai aturan dan izin penyelenggara ujian.

Kode akses unik per pengguna belum diterapkan pada versi ini. Akun atau token ujian tetap diperoleh dari penyelenggara.
