# Write Up TJCTF 
## Fachrizal Rahmat Hidayat (05311840000005)
## Kecoak Association


### Login Sequel
1. bukan inspect element
2. disana akan terdapat kode ```cursor.execute('SELECT username, password FROM `userandpassword` WHERE username=\'%s\' AND password=\'%s\'' % (username, hashlib.md5(password.encode())))```
*insert image here
3. Dari kode di atas kita bisa memasukan username tanpa menggunakan password dengan menutup dan menjadikan comment bawahnya dengan menggunakan /*
*insert image here
4. Maka akan menampilkan flag 