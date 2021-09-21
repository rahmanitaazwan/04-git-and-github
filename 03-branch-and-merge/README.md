BRANCH AND MERGE

1. What does git clean do?
git clean adalah metode mudah untuk menghapus file yang tidak terlacak di direktori kerja repo. 
File yang tidak terlacak adalah file yang ada di direktori repo tetapi belum ditambahkan ke indeks repo dengan ekstensi git add. 
Secara keseluruhan efek git cleandapat dicapai dengan menggunakan git statusdan alat penghapusan asli sistem operasi. 
Git cleandapat digunakan bersama git resetuntuk sepenuhnya membatalkan penambahan dan komit dalam repositori.


2. What do the -d and -f flags for git clean do?
-git-d untuk menghapus cabang.
-git -f, --force memungkinkan menambahkan file yang diabaikan

3. What git command creates a branch?
-Git branch

4. What is difference between a fast-forward and recursive merge?
-Fast-forward
Dalam strategi penggabungan yang paling umum digunakan ini, sejarah hanyalah satu garis lurus. 
Saat Anda membuat cabang, buat beberapa komit di cabang itu, saat Anda siap untuk menggabungkan, tidak ada penggabungan baru di master. Dengan begitu penunjuk master hanya bergerak lurus ke depan dan sejarah adalah satu garis lurus.
-Recursive merge
Dalam Recursive merge , setelah Anda bercabang dan membuat beberapa komit, ada beberapa komit asli baru di ' master '. 
Jadi, ketika saatnya untuk menggabungkan, git berulang di atas cabang dan membuat komit gabungan baru. Komit gabungan terus memiliki dua orang tua.

5. what git command chages to another branch?
-Git checkout

6. How do you remove modified or deleted files from the working directory?
-git add -u

7. What git command deletes a branch?
-Git branch -d

8. What does the git diff command do?
-Git diff memberi tahu perubahan yang terjadi diantara dua titik referensi git.

9. How do you remove files from the staging area?
-Git reset HEAD --<file> #(untuk satu file)
-Git reset HEAD --<directoryName> #(seluruh direktori/folder)


10. How do  merge conflicts happen?
Konflik penggabungan dapat terjadi saat menggabungkan cabang, rebasing cabang, atau cherry memilih komit.
