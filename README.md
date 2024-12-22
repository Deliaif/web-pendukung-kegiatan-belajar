# Website Pendukung Kegiatan Belajar 😎

Website ini dirancang untuk membantu meningkatkan produktivitas selama belajar dengan menyediakan fitur-fitur seperti **Pomodoro Timer**, **To-Do List**, dan **Spotify Playlist**. 

---

## Fitur

1. **Pomodoro Timer**  
   Membantu mengatur waktu belajar dan istirahat dengan menggunakan teknik Pomodoro:
   - Input waktu belajar dan waktu istirahat (dalam menit).
   - Menampilkan hitungan mundur waktu belajar dan istirahat.
   - Memberikan notifikasi saat waktu belajar atau istirahat selesai.

2. **To-Do List**  
   Mempermudah manajemen tugas yang harus diselesaikan:
   - Tambahkan tugas baru ke dalam daftar.
   - Tandai tugas sebagai selesai.
   - Hapus tugas yang tidak diperlukan.
   - Semua tugas tersimpan di **LocalStorage** sehingga tidak hilang meskipun halaman di-refresh.

3. **Spotify Playlist**  
   Mendukung suasana belajar dengan menyediakan playlist musik dari Spotify yang dapat diputar langsung di website.

---

## Teknologi yang Digunakan

- **HTML5**: Untuk struktur halaman.
- **CSS3** (dengan Bootstrap 5.3): Untuk desain yang responsif dan tampilan modern.
- **JavaScript**: Untuk interaktivitas fitur seperti Pomodoro Timer dan To-Do List.
- **LocalStorage**: Untuk menyimpan daftar tugas secara lokal pada browser.

---

## Cara Kerja

### 1. **Pomodoro Timer**
   - Masukkan durasi waktu belajar dan waktu istirahat pada form input.
   - Klik tombol **Mulai** untuk memulai hitungan mundur.
   - Timer akan menampilkan waktu tersisa dan memberikan alert ketika sesi belajar atau istirahat selesai.
   - Klik tombol **Hentikan** untuk menghentikan sementara waktu. Timer dapat dilanjutkan tanpa mengulang dari awal.


### 2. **To-Do List**
   - Masukkan nama tugas pada kolom input dan klik tombol **Tambah**.
   - Tugas baru akan muncul dalam daftar.
   - Gunakan tombol **Selesai** untuk menandai tugas sebagai selesai.
   - Gunakan tombol **Hapus** untuk menghapus tugas.
   - Daftar tugas disimpan di LocalStorage sehingga tidak hilang setelah halaman di-refresh.

### 3. **Spotify Playlist**
   - Playlist Spotify yang relevan dapat diputar langsung melalui embedded player.
   - Mendukung fitur seperti autoplay, skip, dan shuffle.

---
