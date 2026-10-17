

### Bagian C — Fitur Analitik Rancangan Sendiri

Fitur analitik yang saya tambahkan pada class `CharacterManager` adalah method `countByType(String type)`. Method ini berfungsi untuk menghitung jumlah karakter berdasarkan tipe tertentu, seperti Warrior atau Mage.

Cara kerjanya adalah dengan memeriksa setiap karakter yang tersimpan di dalam daftar karakter, kemudian membandingkan tipe karakter tersebut dengan tipe yang dimasukkan oleh pengguna. Jika tipenya sesuai, jumlah penghitung akan bertambah satu. Setelah semua karakter diperiksa, method akan mengembalikan jumlah karakter yang sesuai.

Method ini menerapkan prinsip **encapsulation** karena tidak mengembalikan atau mengekspos `ArrayList` yang digunakan untuk menyimpan karakter. Method hanya mengembalikan nilai berupa bilangan bulat (`int`) yang menunjukkan jumlah karakter berdasarkan tipe tertentu.

Selain itu, method ini dilengkapi dengan **Javadoc** untuk menjelaskan fungsi method, parameter yang digunakan, dan nilai yang dikembalikan. Validasi juga diterapkan agar parameter yang bernilai `null` atau kosong tidak menyebabkan kesalahan saat method dijalankan.

Fitur ini dibuat untuk mempermudah pengguna mengetahui jumlah karakter berdasarkan tipenya tanpa harus menghitungnya secara manual. Dengan demikian, pengelolaan dan analisis data karakter menjadi lebih mudah dan efisien.

## Screenshot Output Terminal

![Screenshot Output](Screenshot 2026-10-17 123023.png)

## Struktur Folder Project

```text
AP3_Tugas/
├── Screenshot 2026-10-17 123023.png
├── README.md
└── src/
    ├── Main.java
    └── com/
        └── unpri/
            └── charactermanager/
                └── model/
                    ├── Character.java
                    └── CharacterType.java

Nama    : Ferdi Wiilson Herwansyah Siahaan
Nim     : (253303621227)
Kelas   : Semester 3 Pagi A
Link Google Docs : https://docs.google.com/document/d/1NfQNNXsIrucDt7KqxUM5YLN8f7SzGLRA_5qK-nVlh0g/edit?usp=sharing