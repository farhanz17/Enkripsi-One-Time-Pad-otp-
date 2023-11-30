# Enkripsi-One-Time-Pad (OTP)

# Tugas Kriptografi
### Profil
| #               | Biodata           |
| --------------- | ----------------- |
| **Nama**        | Muhammad Farhan   |
| **NIM**         | 312110128         |
| **Kelas**       | TI.21.A1          |
| **Mata Kuliah** | Kriptografi       |


## Result Pyhton :

 <img width="815" alt="Screenshot 2023-11-30 225127" src="https://github.com/farhanz17/Enkripsi-One-Time-Pad-otp-/assets/92637117/d5da4b80-ea2c-4c63-bdab-d542cea67d3b">

## Result PHP : 
 <img width="960" alt="Screenshot 2023-11-30 225053" src="https://github.com/farhanz17/Enkripsi-One-Time-Pad-otp-/assets/92637117/93ee2920-00f4-48a9-a01c-32eacdec9e04">


Ketika kita menampilkan hasil enkripsi, format keluarannya mencakup istilah "ctrl" dan karakter yang dianggap sebagai kontrol ASCII, dengan memanfaatkan nilai desimal dari hasil XOR. Namun, perlu diingat bahwa tidak semua karakter ASCII di bawah 32 dapat terlihat secara visual di layar konsol.
Beberapa karakter kontrol mungkin tidak memiliki representasi grafis yang dapat terlihat, membuatnya sulit untuk diidentifikasi saat mencetak ke layar. 

Untuk mengatasi hal ini, saya menambahkan nilai biner pada setiap "ctrl" yang pasti disertakannya (dalam bentuk biner) agar huruf dapat terlihat di rumus.
Jadi, meskipun beberapa karakter kontrol mungkin tidak terlihat langsung saat dicetak ke layar, penambahan nilai biner ini membantu mempertahankan informasi dan memastikan bahwa hasil enkripsi tetap jelas dan tidak kehilangan makna ketika ditampilkan.

