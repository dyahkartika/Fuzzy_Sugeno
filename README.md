Laporan Implementasi Fuzzy Sugeno

Nama: Dyah Kartika Damarsiwi
NIM: P31.2024.02646

Deskripsi Singkat
Penelitian ini bertujuan untuk memodelkan prediksi jumlah produksi berdasarkan tiga variabel input lingkungan kerja:
Suhu (°C)
Kebisingan (dB)
Pencahayaan (lux)

Detail Sistem
Jumlah Data: 810 data mentah (30 pekerja × 27 kombinasi)
Data yang digunakan: Rata-rata dari 27 kombinasi eksperimen
Jumlah aturan fuzzy: 27 aturan
Output: Prediksi jumlah produksi (unit produk)

Fungsi Utama
Fungsi Keanggotaan untuk tiap variabel (RENDAH, NORMAL, TINGGI, dll)
Inferensi Sugeno: menggunakan bobot berdasarkan min(μ_suhu, μ_kebisingan, μ_pencahayaan)
Output konstan pada setiap aturan (berdasarkan nilai rata-rata produksi)
