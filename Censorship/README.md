# Write Up TJCTF 
## Fachrizal Rahmat Hidayat (05311840000005)
## Kecoak Association


### Censorship
*image
1. Jika kita menjalakan `nc p1.tjctf.org 8003` akan keluar sebuah pertanyaan dan seberapa cepat menjawab akan keluar tcjtf{[CENCORED]}
2. Karena itu harus menjalankan kode censorship.py agar dapat dibaca
3. Pertama dengan membuka `nc p1.tjctf.org 8003` dengan `r = remote("p1.tjctf.org", 8003)`
4. Lalu menerima baris yang dikeluarkan dan mengambil angka serta mengirimkan hasilnya dalam waktu yang bersamaan
5. Setelah itu flagnya akan muncul
