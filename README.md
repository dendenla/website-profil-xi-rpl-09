# website-profil-xi-rpl-09

Website ini merupakan proyek pembelajaran kolaborasi bala bala dan gehu.

anggota:

<<<<<<< Updated upstream
Denis Pirmansyah sebagai project manajer dan fitur anggota
Razq Sondari Putra: fitur kontak
fatir alfath sandila: fitur profil
=======
Denis Pirmansyah sebagai project manajer
Razq Sondari Putra: fitur kontak dan fitur anggota
fatir alfath sandila: fitur profil

Challenge 2: Jawaban Pertanyaan

Pertanyaan: Apa arti hasil git status?

Jawaban: git status berfungsi untuk menampilkan kondisi repositori lokal saat ini. Perintah ini menunjukkan branch yang sedang aktif, file mana yang telah diubah (modified), file baru yang belum dilacak (untracked), serta file yang sudah siap di-commit (staged).

Challenge 3: Analisis

Pertanyaan: Mengapa setiap developer tidak langsung bekerja pada main?

Jawaban: Branch main merupakan kode utama yang harus selalu stabil dan bebas dari bug. Bekerja di branch fitur terpisah mencegah kerusakan sistem utama jika terjadi error, serta memungkinkan banyak developer bekerja secara bersamaan tanpa saling menimpa pekerjaan satu sama lain.

Challenge 5: Analisis Commit

Pertanyaan: Apa perbedaan pesan commit git commit -m "update" dan git commit -m "Menambahkan halaman profil kelas"? Mana yang lebih baik?

Jawaban:

git commit -m "update" sangat ambigu dan tidak menjelaskan perubahan spesifik yang dibuat.

git commit -m "Menambahkan halaman profil kelas" memberikan penjelasan yang jelas, deskriptif, dan informatif mengenai fitur/perubahan yang dimasukkan.

Mana yang lebih baik: Pesan kedua ("Menambahkan halaman profil kelas") jauh lebih baik karena memudahkan tim melacak riwayat perubahan kode di masa mendatang.

agian U: Pertanyaan Analisis

Apa fungsi git pull?

Jawaban: git pull berfungsi untuk mengambil (fetch) pembaruan kode terbaru dari repositori remote (GitHub) dan langsung menggabungkannya (merge) ke repositori lokal di komputer kita.

Apa yang terjadi jika programmer tidak melakukan git pull?

Jawaban: Kode di komputer lokal akan ketinggalan zaman (outdated). Hal ini dapat menyebabkan potensi bentrok/konflik (merge conflict) atau galat saat hendak mengirimkan (push) perubahan baru ke GitHub.

Mengapa main harus dijaga agar tetap stabil?

Jawaban: Karena branch main merepresentasikan versi produk akhir (siap dirilis/di-deploy) yang digunakan oleh klien atau penggunan akhir. Jika main rusak, maka seluruh aplikasi atau website akan mengalami crash/gangguan.

agian X: Pertanyaan Conflict

Mengapa conflict terjadi?

Jawaban: Konflik terjadi ketika dua atau lebih developer mengubah baris kode yang sama di file yang sama secara bersamaan, sehingga Git tidak dapat menentukan otomatis perubahan mana yang harus digunakan.

Apakah conflict berarti Git rusak?

Jawaban: Tidak. Konflik adalah kondisi normal dalam kolaborasi tim. Ini adalah mekanisme keamanan Git untuk meminta keputusan manusia tentang kode mana yang benar.

Siapa yang harus menentukan versi kode yang benar?

Jawaban: Developer yang terlibat langsung dalam pembuatan kode tersebut bersama dengan Project Manager (PM) atau pengulas kode (reviewer).

Mengapa komunikasi antar programmer penting?

Jawaban: Komunikasi yang baik membantu mencegah tumpang tindih pengerjaan fitur yang sama, mempercepat penyelesaian konflik kode, dan memastikan standar pengerjaan proyek berjalan konsisten.
>>>>>>> Stashed changes
