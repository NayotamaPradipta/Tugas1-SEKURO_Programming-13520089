# .gitignore

.gitignore memungkinkan developer untuk mengabaikan file-file untracked yang tidak ingin ikut dicommit. Github memberikan saran berupa daftar file-file yang ingin diabaikan. <br>

Untuk menggunakan gitignore, caranya tinggal membuat file .gitignore pada folder repository dan mengisinya dengan daftar semua file yang ingin diabaikan. <br>

Sebagai contoh, semisal saya memiliki dua file, file pertama bernama Rangkuman7.md ingin saya commit, sedangkan file kedua bernama ignorethisfile.txt tidak saya ingin commit, maka saya tinggal create new file bernama .gitignore, dan menuliskan ignorethisfile.txt di dalam .gitignore. Selain file, kita juga bisa memasukkan nama folder dengan format ```folder_name/``` . Selain itu, jika kita ingin mengabaikan semua file jenis tertentu maka gunakan format ```*.<jenis file>``` contohnya ```*.exe, *.cpp, *.py```. <br>
Isi dari gitignore tergantung dengan projek yang sedang dikerjakan, untuk mengetahui file apa saja yang biasa diabaikan, kita dapat pergi ke website gitignore.io dengan mengisi OS, IDE, dan nama framework.
