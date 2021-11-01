# hitung
## Program menghitung luas dan keliling lingkaran dengan python
### Berikut flowchart dan program nya 
Kita akan menggunakan visual studi code untuk editor nya
Rumus Luas & Keliling Lingkaran<p>
    
    Luas     = π × r²
    Keliling = 2 x π × r
    
    Nilai Phi yang akan kita gunakan adalah 3.14
    rmerupakan jari-jari lingkaran

Phi merupakan nilai konstanta di matematika sementara jari-jari merupakan jarak antara titik pusat dengan tepi lingkaran. Sebetulnya ada rumus lain untuk menghitung keliling lingkaran yaitu dengan menggunakan diameter, tapi pada kasus ini kita cukup menggunakan jari jari lingkaran saja.<p>
berikut ini program nya:<P>
![gambar 1](screenshot/bb3.PNG)
berikut script nya:<p>
    import math
    r  = float(input("Masukan Jari-jari : "))

    luas = math.pi*(r*r)
    keliling = 2*math.pi*r

    print ("Luas Lingkaran \t= ",format(luas,'.2f'))
    print ("Keliling Lingkaran \t= ",format(keliling,'.2f'))
Berikut untuk output nya:<p>
![gambar 2](screenshot/bb2.PNG)
Beginilah output nya:<p>

    Luas Lingkaran          =  20106.19
    Keliling Lingkaran      =  502.65
berikut flowchart nya:<p>
![gambar 3](screenshot/ff2.png)
berikut adalah program nya terimakasih bila ada kekurangan mohon maaf wassalamuallaikum wr wb.<p>
