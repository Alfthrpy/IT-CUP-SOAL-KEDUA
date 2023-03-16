# IT-CUP-SOAL-KEDUA

```
mulai
  deklarasi:
    int w_masuk,w_keluar,w_akhir,hasil
    
  display "Menghitung Biaya Parkir"
  display "Jam Masuk :"
  read (w_masuk)
  display "Jam Keluar :"
  read (w_keluar)
  
  w_akhir = w_keluar - w_masuk
  if w_akhir < 3 then
      hasil = 3000
  else
      hasil = 3000 + (w_akhir - 2) * 1000
  
  display "Durasi Parkir :" + w_akhir
  
  display "Biaya Parkir :" + hasil
akhir
```
