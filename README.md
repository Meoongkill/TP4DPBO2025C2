# TP4DPBO2025C2

# Janji Desain dan Pemrograman Berorientasi Objek
Saya Muhammad Fathan Putra dengan NIM 2300330 mengerjakan soal Tugas Praktikum 4 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

# Desain Program
Program ini merupakan aplikasi Graphical User Interface (GUI) berbasis bahasa JAVA, untuk mengelola data Mahasantuy. Aplikasi ini memungkinkan user untuk menambahkan, memperbaharui, dan menghapus data mahasiswa yang meliputi NIM, Nama, Jenis Kelamin, Waifu, dan Hobby. 

# Struktur Kelas
1. Mahasiswa
Kelas model untuk merepresentasikan data mahasiswa dengan atribut:
- Nama berjenis JText
- NIM berjenis JText
- jenis Kelamin berjenis JComboBox
- Waifu berjenis JComboBox
- Hobby berjenis JComboBox
  
2. Menu
Kelas utama yang berisi GUI aplikasi dengan komponen:
- JTextField untuk input NIM dan Nama.
- JComboBox untuk memilih Jenis Kelamin (Laki-laki dan Perempuan).
- JComboBox untuk memilih Waifu (Furiri, Clorinde, Nilou, Childe, Diluc, Al-Haitam).
- JComboBox untuk memilih Hobby (Writing, Gaming, Reading, Cycling).
- JTable untuk menampilkan data mahasiswa.
- JButton untuk operasi CRUD (Create, Read, Update, Delete).

# Penjelasan Alur
Alur dari Codingan dapat ditelaah dari Alur Berikut:
![image](https://github.com/user-attachments/assets/229870cd-15a0-4c33-b88e-12826e47026d)
- User menginput data Mahasantuy melalui form GUI.
- Data yang dimasukkan akan ditampilkan tabel Mahasantuy.
- User dapat mengupdate atau mendelet data yang telah dimasukkan.
- Setiap penghapusan dan cancel akan dikonfirmasi menggunakan JOptionPane.
- Data yang sudah diperbaharui atau dihapus akan diperbaharui di tabel secara otomatis.

# Fitur Program
- Menampilkan Data Mahasantuy dalam bentuk tabel.
- Menampilkan Data Mahasantuy baru.
- Memperbaharui Data Mahasantuy yang sudah ada di database statis.
- Mendelete Data Mahasantuy yang dipilih.
- Konfirmasi Delete Button menggunakan JOptionPane.
- Konfirmasi Cancel Button menggunakan JOptionPane.

# Dokumentasi
1. Tampilan awal ketika code dijalankan
![1  Intellij_Tampilan awal ketika code dijalankan](https://github.com/user-attachments/assets/bd7881fa-0c28-4f82-842a-ab027070e0a8)

2. Bukti Bahwa Waifu merupakan ComboBox
![1  Intellij_Tampilan awal ketika code dijalankan](https://github.com/user-attachments/assets/1dda8181-c6f5-4b17-8161-9bce6e4c6de8)

3. Bukti Bahwa Hobby merupakan ComboBox
![1  Intellij_Tampilan awal ketika code dijalankan](https://github.com/user-attachments/assets/9727a186-925a-41da-8692-9d4526aa2ba6)

4. Tampilan ketika data berhasil ditambahkan
![1  Intellij_Tampilan awal ketika code dijalankan](https://github.com/user-attachments/assets/97f513f4-94b0-4842-90a2-d34bca341061)

5. Tampilan ketika data sudah diisi namun memilih untuk menekan tombol cancel
![1  Intellij_Tampilan awal ketika code dijalankan](https://github.com/user-attachments/assets/2bc0399d-6bb2-4ece-89ad-8d6e06e7ed83)

6. Tampilan ketika proses Cancel dan menekan tombol yes
![1  Intellij_Tampilan awal ketika code dijalankan](https://github.com/user-attachments/assets/167b672f-bd64-4971-9c91-e475ddc1cadf)

7. Tampilan ketika proses Cancel dan menekan tombol no
![1  Intellij_Tampilan awal ketika code dijalankan](https://github.com/user-attachments/assets/d8dba504-c624-4af2-87fa-781b17e14850)

8. Tampilan ketika ingin menghapus data dengan menekan tombol delete
![1  Intellij_Tampilan awal ketika code dijalankan](https://github.com/user-attachments/assets/a21874b7-ea03-4847-a98f-7e5561c1c11f)

9. Tampilan ketika proses Delete dan menekan tombol yes
![1  Intellij_Tampilan awal ketika code dijalankan](https://github.com/user-attachments/assets/76895814-8545-4775-88c7-672a7c5bf193)

10. Tampilan ketika proses Delete dan menekan tombol no
![1  Intellij_Tampilan awal ketika code dijalankan](https://github.com/user-attachments/assets/6027c018-812c-4bb8-9b0d-7f601ff98237)

11. Tampilan ketika proses Update di database yang sudah tersedia
![image](https://github.com/user-attachments/assets/5abd6b4b-5434-4b06-8b35-17fedf27d0e1)

