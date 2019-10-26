
Langkah-langkah Membuat Repository dan Repository Pada Github serta Membuat File README.md

Yang harus di lakukan adalah :

1. membuat akun github pada https://github.com
lalu sign up setelah itu isi data diri

![Screenshot (70)](https://user-images.githubusercontent.com/56973033/67624761-2baf4880-f85f-11e9-8496-cfe0e143e7b2.png)
![Screenshot (6)](https://user-images.githubusercontent.com/56973033/67624769-48e41700-f85f-11e9-9f13-3aa9e0222103.png)
2. setelah akun terverifikasi maka kita bisa SIGN IN pada akun github

![Screenshot (72)](https://user-images.githubusercontent.com/56973033/67624792-a6786380-f85f-11e9-93d9-a0e9481e6e7e.png)
3. lalu kita akan masuk pada akun github yang sudah dibuat

![Screenshot (27)](https://user-images.githubusercontent.com/56973033/67624889-1804e180-f861-11e9-9cc4-05ee4f6a70da.png)
![Screenshot (28)](https://user-images.githubusercontent.com/56973033/67624862-c8beb100-f860-11e9-912d-fbdcebae9686.png)
4. lalu kita akan dialihkan ke tab baru untuk creat a new repository isi repository name lalu klik creat repository

![Screenshot (52)](https://user-images.githubusercontent.com/56973033/67624919-6c0fc600-f861-11e9-9440-3fa9d2fe1067.png)
![Screenshot (54)](https://user-images.githubusercontent.com/56973033/67624959-f5bf9380-f861-11e9-8e80-67b5abe09344.png)

5. Download software GIT di "git-scm.com" lalu install software terlebih dahulu, maka akan muncul tampilan sebagai berikut

![Screenshot (25)](https://user-images.githubusercontent.com/56973033/67625004-9746e500-f862-11e9-9dcc-7b6259e794e9.png)

![Screenshot (26)](https://user-images.githubusercontent.com/56973033/67625013-a3cb3d80-f862-11e9-9cec-c074a4793f5d.png)


6. jika instalasi git di windows sudah selesai, periksa apakah git sudah bisa digunakan, dengan cara membuka command prompt dan ketik git version, jika muncul versi git maka proses yang dilakukan berhasil dan git sudah bisa digunakan
![Screenshot (30)](https://user-images.githubusercontent.com/56973033/67625089-8f3b7500-f863-11e9-9518-39b6f2a7800e.png)

7. lalu buka document dan buat folder baru klik kanan pada folder lalu plih "Git Bash Here"

![Screenshot (45)](https://user-images.githubusercontent.com/56973033/67625138-315b5d00-f864-11e9-9c01-ff0c9d749f21.png)

8. lalu konfigurasi dengan memasukan perintah "git config --global user.name "nama_user" dan "git config --global user.email "nama_user"

![Screenot (47)](https://user-images.githubusercontent.com/56973033/67625188-d24a1800-f864-11e9-92f2-733b37d42593.png)

![Screenshot (48)](https://user-images.githubusercontent.com/56973033/67625190-dd04ad00-f864-11e9-9ec1-cdfed221b27c.png)
sh

9. buat direktorasi baru dengan menggunakan perintah "mkdir latihanpytn1" lalu cd latihanpytn1


![Screenshot (49)](https://user-images.githubusercontent.com/56973033/67625232-982d4600-f865-11e9-8bed-b7abe17a5a5e.png)

![Screenshot (43)](https://user-images.githubusercontent.com/56973033/67625236-a8ddbc00-f865-11e9-9303-55aeb495b626.png)

10. jalankan perintah "git init" untuk membuat file kosong berfomat git

![Screenshot (42)](https://user-images.githubusercontent.com/56973033/67626322-d03b8580-f873-11e9-909f-1e59909b602b.png)

11. lalu buat 1 file bernama README.md  dengan memasukan perintah "echo "#latihanpytn">>README.md lalu ketik perintah "ls -l" untuk melihat file

![Screenshot (44)](https://user-images.githubusercontent.com/56973033/67626360-90c16900-f874-11e9-86a5-16b0801388fd.png)

![Screenshot (50)](https://user-images.githubusercontent.com/56973033/67626363-9b7bfe00-f874-11e9-9d96-d96e5e8f789c.png)

12. Menambahkan file README.md pada repository local dengan menggunakan perintah "git add"

![Screenshot (51)](https://user-images.githubusercontent.com/56973033/67626414-5ad0b480-f875-11e9-9def-4fa257726b5c.png)

13. ketik perintah "git commit -m" komentar saya" untuk menyimpan perubahan yang ada kedalam database repository

![Screenshot (55)](https://user-images.githubusercontent.com/56973033/67626457-da5e8380-f875-11e9-9b42-1bb858ebd282.png)

14. Masuk lagi ke wesite github lalu masuk ke repository yang sebelumnya di buat pada bagian quick setup terdapat url github kita, url ini nantinya akan digunakan pada perintah "git remote add origin [url]" dan perintah git clone "git clone [url]" contoh "git remote add origin https://github.com/SitiRohmayati/LATIHAN_PYTHON.git"

![Screenshot (54)](https://user-images.githubusercontent.com/56973033/67626522-99b33a00-f876-11e9-87a2-49165e1664d6.png)

15. Lalu ketikan perintah "git remote add [url] "

![Screenshot (69)](https://user-images.githubusercontent.com/56973033/67626570-1cd49000-f877-11e9-89cb-c7471f73e335.png)

16. Untuk mengirim perubahan local repository ke server gunakan perintah git push "git push -u origin master"

![Screenshot (73)](https://user-images.githubusercontent.com/56973033/67626621-e2b7be00-f877-11e9-87be-65920a18d355.png)

17. Untuk melihat hasilnya cek di github dan lihat di repositorynya

![Screenshot (63)](https://user-images.githubusercontent.com/56973033/67626654-7a1d1100-f878-11e9-8140-087b590ef6c2.png)

18. jika ingin melakukan clone repository gunakan perintah "git clone [url]"


![Screenshot (74)](https://user-images.githubusercontent.com/56973033/67626738-23b0d200-f87a-11e9-987d-93ba43bfe2b1.png)







