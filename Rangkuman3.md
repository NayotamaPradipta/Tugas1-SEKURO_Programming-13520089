# Branch

Konsep Branch merupakan konsep git, akan tetapi dapat dilakukan dan dipahami dengan mudah menggunakan github <br>
Dalam satu repo, developer dapat membuat banyak branch <br>
Kegunaan branch adalah membuat snapshot tanpa mengganggu main branch, biasanya untuk mencoba fitur experimental atau ketika ada dua developer yang sedang bekerja dengan fitur yang sama. <br>
Pada saat developer ingin melakukan commit, developer dapat memilih untuk commit pada master branch atau membuat branch baru.
<br>
Untuk berpindah ke branch lain, tinggal tekan tombol branch di kiri atas repository dan pilih branch yang dituju. <br>
Semua perubahan yang terjadi di branch tidak akan terjadi di branch lain selama belum dilakukan merge. <br>
Merge di github dilakukan dengan menekan tombol <i>compare & pull request</i>. Selanjutnya akan ada halaman <i>Open a pull request</i> yang menampilkan apakah branch dapat digabungkan atau tidak. Jika tidak ada konflik, maka merge dapat dilakukan dan pull request akan selesai dengan sukses. Branch master akan berubah karena telah dilakukan merge <br>

Untuk merge dengan konflik, pull request dapat dilakukan tetapi merge tidak dapat dilakukan. Pemilik master harus menyelesaikan masalah secara manual. 
