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
![2  Intellij_Bukti bahwa Waifu merupakan ComboBox](https://github.com/user-attachments/assets/38ef7b28-59e9-409b-b528-e33d25171c94)

3. Bukti Bahwa Hobby merupakan ComboBox
![3  Intellij_Bukti bahwa Hobby merupakan ComboBox](https://github.com/user-attachments/assets/bdcafe9d-db1a-40d6-8703-aca912e6fced)

4. Tampilan ketika data berhasil ditambahkan
![4  Intellij_Tampilan ketika data berhasil di tambahkan](https://github.com/user-attachments/assets/4cf3d60e-2889-48c9-8513-507aab7e41e7)

5. Tampilan ketika data sudah diisi namun memilih untuk menekan tombol cancel
![5  Intellij_Tampilan ketika data sudah diisi namun menekan tombol cancel](https://github.com/user-attachments/assets/55a6ab06-a161-456a-8b30-c2bcc8cd4026)

6. Tampilan ketika proses Cancel dan menekan tombol yes
![6  Intellij_Tampilan ketika proses Cancel menekan Yes](https://github.com/user-attachments/assets/c184cce8-770b-49b3-84ce-7bf29df2924a)

7. Tampilan ketika proses Cancel dan menekan tombol no
![7  Intellij_ Tampilan ketika proses Cancel menekan tombol No](https://github.com/user-attachments/assets/63e1c5b5-48c1-48dc-a03c-00b6847d84fb)

8. Tampilan ketika ingin menghapus data dengan menekan tombol delete
![8  Intellij_Tampilan ketika ingin menghapus data terdapat confirmation prompt](https://github.com/user-attachments/assets/2354717a-4291-4219-ae01-d1d0c4fa68f7)

9. Tampilan ketika proses Delete dan menekan tombol yes
![9  Intellij_Tampilan ketika proses Delete menekan tombol no](https://github.com/user-attachments/assets/14b2740a-9eba-42f5-9e62-cebfb00eb964)

10. Tampilan ketika proses Delete dan menekan tombol no
![10  Intellij_Tampilan ketika proses Delete menekan tombol yes](https://github.com/user-attachments/assets/d0dfd6f5-4d3d-4722-8914-1db9e210e335)

11. Tampilan ketika proses Update di database yang sudah tersedia
![11  Intellij_Tampilan ketika update data yang sudah tersedia di database statis](https://github.com/user-attachments/assets/5134c7de-2046-4c5f-9823-eafc950ec9b3)


