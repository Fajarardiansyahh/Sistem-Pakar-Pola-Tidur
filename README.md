#  PakarTidur.id - Sistem Pakar Gangguan Tidur

Aplikasi Sistem Pakar berbasis web untuk mendiagnosis gangguan tidur menggunakan metode **Certainty Factor (CF)**. Aplikasi ini dirancang untuk menganalisis pola dan kualitas tidur pengguna berdasarkan gejala-gejala klinis yang dialami.

##  Fitur Utama
* **Inferensi Certainty Factor:** Menghitung tingkat keyakinan diagnosis secara akurat berdasarkan pembobotan pakar.
* **28 Pertanyaan Kuesioner Lengkap:** Meliputi seluruh indikasi gejala klinis secara berurutan untuk hasil yang lebih valid.
* **Sistem Multi-User:** Mendukung peran Akun Tamu (Guest) dengan akses terbatas, Member Resmi, dan Konsol Administrator.
* **Cetak Rekam Medis (PDF):** Fitur unduh laporan hasil pemeriksaan resmi secara instan menggunakan `html2pdf.js`.
* **Panel Admin (Rekap Global):** Konsol khusus administrator untuk memantau, mengedit, dan menghapus log riwayat pemeriksaan global.

##  Daftar Penyakit yang Didukung
1. **Insomnia (P01)**
2. **Obstructive Sleep Apnea / OSA (P02)**
3. **Hypersomnia Primer (P05)**
4. **Delayed Sleep-Wake Phase Syndrome / DSPS (P06)**

##  Teknologi yang Digunakan
* HTML5 & JavaScript (Vanilla)
* Tailwind CSS (Styling & Glassmorphism Design)
* LocalStorage (Database Log & Session)
* html2pdf.js (Export PDF Engine)