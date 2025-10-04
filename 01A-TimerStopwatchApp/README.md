⏱️ Proyek 1: Stopwatch Sederhana (Vanilla JavaScript Mastery)
Jalur Belajar: Fasa I - Fondasi JavaScript Inti

Proyek ini bertujuan untuk menguasai konsep dasar JavaScript seperti Event Handling, DOM Manipulation, dan fungsi waktu (setInterval). Stopwatch ini adalah aplikasi client-side murni (tanpa backend) yang menampilkan waktu dalam format Jam:Menit:Detik.

🌟 Konsep JavaScript Kunci yang Dikuasai
Proyek ini secara langsung menerapkan beberapa pilar penting dari JavaScript:

Pengelolaan Waktu Asinkron (setInterval & clearInterval):

Menggunakan setInterval(fungsi, 1000) untuk menjalankan fungsi pembaruan waktu setiap 1000 milidetik (1 detik).

Menggunakan clearInterval(id) untuk menghentikan loop waktu, misalnya saat menekan tombol "Jeda" atau "Reset".

DOM Manipulation (Interaksi Tampilan):

Membaca (Selector): Menggunakan document.getElementById untuk mengambil elemen tombol dan display.

Menulis (Update): Mengubah konten teks (display.textContent) dan kelas CSS (classList.add/remove) untuk mengubah tampilan tombol (Mulai/Jeda).

Menciptakan (Lap): Menggunakan document.createElement dan lapList.prepend() untuk secara dinamis menambahkan catatan waktu (lap) ke dalam daftar.

Event Handling:

Menggunakan addEventListener('click', fungsi) untuk menghubungkan tombol Mulai/Jeda, Reset, dan Catat (Lap) ke logika JavaScript yang sesuai.

State Management Sederhana:

Penggunaan variabel Boolean (isRunning) untuk melacak status aplikasi (sedang berjalan atau berhenti), yang mengontrol semua fungsi lainnya (startStop, recordLap).

🛠️ Cara Menjalankan Aplikasi
Aplikasi ini adalah file HTML tunggal dan dapat dijalankan langsung di browser apa pun.

Simpan File: Pastikan Anda menyimpan kode HTML di atas ke dalam file bernama index.html (atau stopwatch.html) di folder proyek Anda (misalnya 01-timer-stopwatch/).

Buka Browser: Klik dua kali file tersebut, atau buka menggunakan browser Chrome/Firefox/Edge Anda.

Uji Fungsi:

Tekan Mulai untuk memulai hitungan.

Tekan Catat untuk menambahkan lap ke daftar.

Tekan Jeda untuk menghentikan hitungan.

Tekan Lanjut untuk melanjutkan dari waktu yang sama.

Tekan Reset untuk mengembalikan ke 00:00:00.

📂 Struktur File
01-timer-stopwatch/
├── index.html          <-- File Utama (HTML, CSS, dan JS digabung)
└── README.md           <-- Dokumentasi Proyek ini