# Write Up TJCTF 
## Fachrizal Rahmat Hidayat (05311840000005)
## Kecoak Association


### Zipped Up
*image
1. Download file zip 
2. Ekstrak file menggunakan ```for i in {0..1001}; do find -iname \* -exec 7z e -aos -bso0 {} \;; find -iname \* -exec 7z e -aos -bso0 {} \;; find -iname \* -exec 7z e -aos -bso0 {} \;; done```
3. Setiap file yang ada di dalam zip akan di unzip menggunakan 7z
4. Setelah File selesai, ```cat *.txt | grep -v "tjctf{n0t_th3_fl4g}" ```