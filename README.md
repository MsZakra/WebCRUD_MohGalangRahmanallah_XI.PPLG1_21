📝 MyTask — Simple & Clean Task Management Web App

MyTask adalah aplikasi CRUD (Create, Read, Update, Delete) sederhana berbasis web yang dibuat untuk membantu mengatur tugas harian dengan tampilan yang bersih dan mudah digunakan.
Dibangun menggunakan PHP + MySQL, aplikasi ini cocok sebagai projek latihan backend dan dasar-dasar manajemen data.

🚀 Fitur Utama
✔️ Tambah Tugas

Kamu bisa menambahkan tugas baru lengkap dengan:

Judul tugas

Deskripsi

Deadline

Data akan tersimpan ke database secara otomatis.

📋 Lihat Semua Tugas

Halaman utama menampilkan semua tugas dalam bentuk tabel yang rapi, urut berdasarkan deadline agar kamu bisa fokus ke tugas yang paling dekat.

✏️ Edit Tugas

Setiap tugas bisa diperbarui kapan saja melalui halaman edit.

🗑️ Hapus Tugas

Tugas yang sudah selesai bisa dihapus melalui fungsi delete yang aman dan mudah digunakan.

🧩 Teknologi yang Digunakan

Ai (GPT,Deepseek,Gemini,plexity)

PHP (Proses CRUD)

MySQL (Database)

Bootstrap 5 (UI / Frontend)

FontAwesome (Ikon)

XAMPP / LAMPP (Local Development)

📂 Struktur Folder
/mytask
│── config.php
│── index.php             → Menampilkan semua tugas
│── add_task.php          → Form tambah tugas
│── edit_task             → Form edit tugas
│── delete_task.php       → Fungsi hapus tugas
│── style.css             → style sheet
│── app.js                → Js
│── toggle_status.php     → Switch
│── task.php


⚙️ Cara Instalasi

Clone repository:

git clone https://github.com/username/mytask.git


Import database:

Buat database: db_todolist

Import file mytask.sql (jika ada)

Atur koneksi di config.php:

$mysqli = new mysqli("localhost", "root", "", "db_todolist");


Jalankan di browser:

http://localhost/mytask/

📸 Screenshot (Opsional)

<img width="1920" height="1080" alt="Screenshot (51)" src="https://github.com/user-attachments/assets/bdf4fcc0-0626-445b-aea2-e3e45a43b428" />

🤝 Kontribusi

Pull request terbuka untuk perbaikan dan fitur tambahan.

📜 Lisensi

Proyek ini menggunakan lisensi MIT — Bebas digunakan untuk keperluan pribadi atau komersial.
