# website-profil-xi-rpl-09

Website ini merupakan proyek pembelajaran kolaborasi GIT DAN GITHUB.

### Anggota Tim:
* **Denis Pirmansyah:** Project Manager & Fitur Anggota
* **Razq Sondari Putra:** Fitur Kontak & Fitur Anggota
* **Fatir Alfath Sandila:** Fitur Profil

---

## Challenge 2: Jawaban Pertanyaan

**Pertanyaan:** Apa arti hasil `git status`?  
**Jawaban:** `git status` berfungsi untuk menampilkan kondisi repositori lokal saat ini. Perintah ini menunjukkan *branch* yang sedang aktif, file mana yang telah diubah (*modified*), file baru yang belum dilacak (*untracked*), serta file yang sudah siap di-commit (*staged*).

---

## Challenge 3: Analisis

**Pertanyaan:** Mengapa setiap developer tidak langsung bekerja pada `main`?  
**Jawaban:** *Branch* `main` merupakan kode utama yang harus selalu stabil dan bebas dari *bug*. Bekerja di *branch* fitur terpisah mencegah kerusakan sistem utama jika terjadi *error*, serta memungkinkan banyak developer bekerja secara bersamaan tanpa saling menimpa pekerjaan satu sama lain.

---

## Challenge 5: Analisis Commit

**Pertanyaan:** Apa perbedaan pesan commit `git commit -m "update"` dan `git commit -m "Menambahkan halaman profil kelas"`? Mana yang lebih baik?  
**Jawaban:**
* `git commit -m "update"` sangat ambigu dan tidak menjelaskan perubahan spesifik yang dibuat.
* `git commit -m "Menambahkan halaman profil kelas"` memberikan penjelasan yang jelas, deskriptif, dan informatif mengenai fitur/perubahan yang dimasukkan.

**Mana yang lebih baik:** Pesan kedua (`"Menambahkan halaman profil kelas"`) jauh lebih baik karena memudahkan tim melacak riwayat perubahan kode di masa mendatang.

---

## Bagian U: Pertanyaan Analisis

1. **Apa fungsi `git pull`?**  
   **Jawaban:** `git pull` berfungsi untuk mengambil (*fetch*) pembaruan kode terbaru dari repositori *remote* (GitHub) dan langsung menggabungkannya (*merge*) ke repositori lokal di komputer kita.

2. **Apa yang terjadi jika programmer tidak melakukan `git pull`?**  
   **Jawaban:** Kode di komputer lokal akan ketinggalan zaman (*outdated*). Hal ini dapat menyebabkan potensi bentrok/konflik (*merge conflict*) atau galat saat hendak mengirimkan (*push*) perubahan baru ke GitHub.

3. **Mengapa `main` harus dijaga agar tetap stabil?**  
   **Jawaban:** Karena *branch* `main` merepresentasikan versi produk akhir (siap dirilis/di-deploy) yang digunakan oleh klien atau pengguna akhir. Jika `main` rusak, maka seluruh aplikasi atau website akan mengalami *crash*/gangguan.

---

## Bagian X: Pertanyaan Conflict

1. **Mengapa *conflict* terjadi?**  
   **Jawaban:** Konflik terjadi ketika dua atau lebih developer mengubah baris kode yang sama di file yang sama secara bersamaan, sehingga Git tidak dapat menentukan otomatis perubahan mana yang harus digunakan.

2. **Apakah *conflict* berarti Git rusak?**  
   **Jawaban:** Tidak. Konflik adalah kondisi normal dalam kolaborasi tim. Ini adalah mekanisme keamanan Git untuk meminta keputusan manusia tentang kode mana yang benar.

3. **Siapa yang harus menentukan versi kode yang benar?**  
   **Jawaban:** Developer yang terlibat langsung dalam pembuatan kode tersebut bersama dengan *Project Manager* (PM) atau pengulas kode (*reviewer*).

4. **Mengapa komunikasi antar programmer penting?**  
   **Jawaban:** Komunikasi yang baik membantu mencegah tumpang tindih pengerjaan fitur yang sama, mempercepat penyelesaian konflik kode, dan memastikan standar pengerjaan proyek berjalan konsisten.

---

## AE. Refleksi Akhir


* **Sebelum belajar GitHub, saya berpikir bahwa...** GitHub itu cuma tempat *backup* kodingan atau pajangan portofolio saja, dan kalau kerja kelompok tinggal kirim-kiriman folder ZIP lewat WA.
* **Setelah melakukan kolaborasi dengan GitHub, saya memahami bahwa...** GitHub sangat berguna untuk mengatur versi kodingan bersama tim. Kita bisa bagi-bagi tugas pakai *branch* tanpa takut kodingan teman ketimpa, lalu menggabungkan kodenya secara praktis.
* **Kesalahan/error yang saya alami mengajarkan saya bahwa...** mendapat *merge conflict* atau *error* saat *push* mengajarkan untuk tidak panik, membaca pesan *error*-nya dengan teliti, dan wajib hukumnya melakukan `git pull` sebelum mulai ngoding agar kode selalu aman.
* **Jika saya bekerja sebagai programmer dalam sebuah tim, saya akan...** membuat *branch* sendiri untuk tiap fitur agar tidak berantakan, rajin melakukan *commit* dengan pesan yang jelas, serta aktif berkomunikasi dengan tim agar tidak terjadi tabrakan saat *merge* kode.
