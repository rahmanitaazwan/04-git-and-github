1. What is the difference between git reset and git revert. When would you use one over the other?

Git Reset memgembalikan file ke kondisi sebelumnya, kemudian menghapus catatan sejarah commit berikutnya.
--soft akan mengembalikan dengan kondisi file dalam keadaan staged.
--mixed akan mengembalikan dengan kondisi file dalam keadaan modified.
--hard akan mengembalikan dengan kondisi file dalam keadaan commited.

Git revert mengembalikan file dengan tidak menghapus sejarah commit. 


2. What is the difference between git merge and git rebase. When would you use one over the other?
-Git merge menyatukan branch cabang fitur yang sudah kita kembangkan.
-Git rebase memungkinkan pengembang untuk mengintegrasikan perubahan dari satu cabang ke cabang lainnya.

3. What is the difference between git stash pop and git stash apply. When would you use one over the other?
-Git stash pop menerapkan elemen simpanan (paling atas, secara default) dan menghapusnya dari tumpukan (hapus dari daftar simpanan).
-Git stash apply melakukan hal yang sama, tetapi meninggalkannya di tumpukan simpanan (simpan di daftar simpanan).


4. What kinds of things can you do in interactive mode when rebasing?

