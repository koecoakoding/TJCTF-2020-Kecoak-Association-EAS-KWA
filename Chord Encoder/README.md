# Write Up TJCTF 
## Fachrizal Rahmat Hidayat (05311840000005)
## Kecoak Association


### Chord Encoder
1. Dengan melihat encode sheet music `1121112111211002112101121121001001210000101221121011200102000110120200101100100111211011001020020010111012011202001011112110121121011211211002112110020200101111210112020010111121010112102001121100211211011020020001010`
2. Diartikan menjadi kata dari chord
A 0112
B 2110
C 1012
D 020
E 0200
F 1121
G 001
a 0122
b 2100
c 1002
d 010
e 0100
f 1011
g 000
3. Maka akan menghasil kata `FFFcFAFGGbGaFAGDGCEfGGfGGFfGDEfCAEfFCFAFcFcEfFAEfFsFEFxFfDDGd`
4. Dengan melihat chord_encoder.py maka huruf kapital dirubah menjadi angka yang akan mendapatkan `666c61677b7a6174735f776f745f315f63616c6c5f615f6d656c6f447d`

*insert image here
5. Dan jika di convert ke ascii maka akan mendapatkan tulisan 
`flag{zats_wot_1_call_a_meloD}`