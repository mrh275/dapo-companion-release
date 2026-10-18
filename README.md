# Dapo Companion

**Dapo Companion** adalah aplikasi pendamping untuk **Dapodik** yang membuat pekerjaan operator sekolah sehari-hari jadi jauh lebih mudah, cepat, dan nyaman.

## Apa itu Dapo Companion?

Dapodik (Data Pokok Pendidikan) adalah sistem resmi dari Kemendikbudristek untuk mengelola data sekolah. Masalahnya, tampilan antarmuka Dapodik bawaan sering membuat pekerjaan rutin terasa lambat, kaku, dan memakan banyak waktu.

Di sinilah **Dapo Companion** berperan. Aplikasi ini **tidak menggantikan Dapodik** — semua data tetap tersimpan aman di server Dapodik lokal sekolah Anda. Dapo Companion menghadirkan **antarmuka modern, cepat, dan pintar**, sehingga tugas-tugas administratif yang sebelumnya membutuhkan puluhan klik dan langkah rumit kini dapat diselesaikan dalam hitungan detik.

## Untuk Siapa Aplikasi Ini?

Untuk siapa saja yang mengelola data pendidikan di satuan pendidikan:
**Operator Sekolah (SD, SMP, SMA, SMK, SLB, dan PKBM)** yang memerlukan kecepatan, otomatisasi, dan kemudahan olah data massal.

## Apa Saja yang Bisa Dilakukan?

### Data Siswa (Peserta Didik)
- **Data Periodik Terikat Semester Aktif**: Data periodik (tinggi, berat badan, lingkar kepala, jarak, dan waktu tempuh) kini otomatis terisolasi dan tersimpan per semester aktif. Saat semester baru dibuka, aplikasi secara otomatis menyiapkan pencatatan baru tanpa menimpa histori semester lampau.
- **Pencarian Cepat & Filter Komprehensif**: Cari siswa berdasarkan nama, NISN, NIK, rombel, status penerima PIP/KIP, maupun kebutuhan khusus (ABK).
- **Integritas Identitas Terlindungi**: Penguncian field identitas resmi (NIK, NISN, Nama, Tanggal Lahir, Nama Ibu Kandung) sesuai regulasi pusat untuk mencegah ketidaksinkronan data dengan Dukcapil/Verval PD.
- **Pencarian Wilayah Dinamis**: Fitur pencarian live untuk desa/kelurahan dengan fallback kode wilayah otomatis.
- **Kelola Ortu, Wali, & Kesejahteraan**: Dukungan logika orang tua wafat, penunjukan wali yang rapi, formulir beasiswa dengan pemilihan rentang tahun yang fleksibel, dan resolusi instansi sertifikasi resmi.
- **Manajemen Mutasi & Batal Keluar**: Kelola siswa keluar (lulus/mutasi) dengan aman, termasuk fitur **Membatalkan Keluar** jika terjadi salah input.

### Data Guru & Tenaga Kependidikan (GTK)
- **Ringkasan Kepegawaian Eksekutif**: Pantau jumlah guru bersertifikasi, sebaran status kepegawaian (PNS, PPPK, GTT, Honorer), dan kualifikasi akademik dalam bentuk kartu statistik visual.
- **Perlindungan Data Sensitif**: NIK dan data kepegawaian tertentu dikunci untuk menjaga sinkronisasi dengan Verval PTK.
- **Sinkronisasi Regulasi Resmi**: Modal dokumen khusus seperti KITAS disediakan dalam mode *view-only* informatif yang terhubung dengan panduan pembaruan resmi melalui portal SP Datadik.
- **Riwayat Lengkap**: Kelola riwayat pendidikan formal, kenaikan pangkat, kenaikan gaji berkala (KGB), tunjangan, pelatihan/diklat, beasiswa, hingga data keluarga.

### Rombel (Rombongan Belajar / Kelas)
- **Tarik & Letak Siswa (Drag & Drop)**: Pindahkan siswa antar-kelas dengan cepat dan visual.
- **Lanjutkan Rombel Antar-Semester**: Salin dan teruskan susunan kelas dari semester lalu ke semester baru hanya dengan satu klik.
- **Dynamic Entry Level Resolver**: Menangani penempatan siswa baru dan siswa mutasi yang belum memiliki histori rombel tanpa galat penentuan tingkat.
- **Rombel Fleksibel**: Dukungan penuh untuk rombel reguler, mata pelajaran pilihan (Kurikulum Merdeka), kelas ekstrakurikuler (tanpa kewajiban kurikulum kaku), serta kelas khusus kebutuhan khusus.

### Sarana & Prasarana (Sarpras)
- **Filter Cerdas Opsi Alat**: Pemilahan inventaris alat secara terarah (alat peraga, alat praktik, dan sarana penunjang) lengkap dengan pencatatan spesifikasi teknis.
- **Inventaris Terintegrasi**: Kelola tanah, sertifikat, bangunan, ruang kelas, laboratorium, buku kurikulum, hingga armada angkutan sekolah.
- **Pemilih Tanggal Seragam**: Antarmuka pemilih tanggal terstandarisasi untuk pengadaan buku dan angkutan.
- **Panduan Terintegrasi**: Banner informasi resmi pengalihan tata cara penambahan ruang via portal SP Datadik.

### Data Sekolah
- **Widget Uji Kecepatan (Speed Test) & Provider**: Tes kecepatan koneksi internet sekolah secara langsung dan pilih provider ISP dari daftar terverifikasi.
- **Integritas Pajak & BOSP**: Kolom NPWP dan Nama Wajib Pajak terlindungi secara *read-only* guna menjaga kesesuaian dengan sistem BOSP Kemendikbud.
- **Data Sanitasi & Agregasi Otomatis**: Perhitungan otomatis jumlah tempat cuci tangan dari modul sarpras serta normalisasi email resmi sekolah.
- **Kepanitiaan Sekolah**: Kelola kepanitiaan internal (PPDB, UKS, Tim Penjaminan Mutu, dsb.) dengan form yang ringkas dan jelas.

### Cek Validasi Data
- **Pemeriksaan 8 Kategori**: Validasi instan untuk kategori Sekolah, Sarpras, Peserta Didik, GTK, Rombel, Pembelajaran, Nilai, dan Referensi sebelum melakukan sinkronisasi ke server pusat.
- **Deteksi Masalah Instan**: Indikator *Invalid* dan *Warning* yang jelas memudahkan operator memperbaiki anomali data.
- **Ekspor Laporan Validasi**: Unduh rekap daftar eror validasi ke format spreadsheet Excel untuk dibagikan kepada rekan kerja atau arsip.

### Ekspor & Impor Excel Cerdas
- **Impor Siswa Massal**: Unggah data siswa dari file Excel dengan pembersihan otomatis, penanganan status wali, dan normalisasi nomor HP.
- **Perlindungan NIK/KK 16-Digit**: Penerapan format teks murni dan penyesuaian lebar kolom otomatis pada berkas ekspor/impor sehingga angka NIK dan No KK tidak rusak oleh format notasi ilmiah (`scientific notation`) Excel.
- **Dua Pilihan Format Ekspor**:
  - Format Modern **Dapo Companion** (lengkap dengan filter data periodik semester aktif).
  - Format Resmi **Dapodik Kemendikbud** untuk pelaporan dinas pendidikan.

---

## Fitur Andalan: Pindah Paksa

Pernah mengalami data siswa mutasi yang "terkunci" atau "nyangkut" di rombel lama dan ditolak masuk ke kelas tujuan oleh validasi bawaan Dapodik? 

Menu **Pindah Paksa** hadir sebagai solusi khusus untuk mengatasi hambatan tersebut:
- Memindahkan siswa langsung ke rombel tujuan yang benar secara aman dan tervalidasi di basis data lokal.
- Mendukung seluruh jenjang pendidikan (SD, SMP, SMA, SMK, SLB, dan PKBM).
- Mengatasi anomali tingkat kelas dengan algoritma *dynamic level resolver*.

---

## Keamanan & Integritas Sistem (Security & Hardening)

Dapo Companion dibangun dengan memprioritaskan keamanan data sekolah:
- **Proteksi Data Lokal**: Seluruh data tersimpan di server lokal sekolah Anda; tidak ada data yang dikirim atau dibagikan ke server pihak ketiga.
- **Content Security Policy (CSP)**: Mencegah injeksi skrip asing yang tidak sah di lingkungan aplikasi.
- **Sanitasi HTML (XSS Defense)**: Mensterilkan setiap output rendering dinamis (termasuk pada modul Validasi) untuk mencegah serangan *Cross-Site Scripting*.
- **Keamanan Jaringan & API**: Pembatasan *CORS origin*, pembatasan frekuensi request (*rate limiting*), dan perlindungan terhadap *directory traversal*.
- **Privasi Kredensial**: Sanitasi otomatis log dan penyaringan data sesi/kuki autentikasi agar kredensial Dapodik tetap aman.
- **Validasi Protokol Eksternal**: Perlindungan protokol IPC pada Electron untuk memastikan pembukaan URL eksternal hanya mengizinkan protokol resmi `http` dan `https`.

---

## Catatan Penting

- Aplikasi ini **tidak menyimpan salinan data sekolah di internet** — seluruh transaksi data berjalan langsung dengan database Dapodik lokal di perangkat Anda.
- Selalu jalankan menu **Validasi** dan pastikan status *Invalid* bersih sebelum melakukan sinkronisasi berkala ke server pusat Dapodik Kemendikbudristek.
- Dapo Companion adalah aplikasi privat (*proprietary*) yang dirancang khusus untuk kenyamanan, produktivitas, dan efisiensi kerja operator sekolah di Indonesia.
