# 📘 **Rangkuman ACT 3 – ACT 6 (Rekayasa Perangkat Lunak 2)**

Dokumentasi ini merangkum empat aktivitas utama dalam praktikum **Rekayasa Perangkat Lunak 2 (RPL 2)**.
Setiap ACT berisi tahapan pengembangan aplikasi mahasiswa dengan pendekatan bertahap, mulai dari konsep MVC dasar hingga integrasi Spring Boot & Hibernate.

---

## 🧩 **ACT 3 – Membangun Fondasi: Model–View–Controller (MVC)**

Pada ACT 3, fokus utama berada pada **penerapan pola arsitektur MVC**. Mahasiswa diminta membangun aplikasi sederhana untuk mengelola data mahasiswa, dengan pembagian komponen sebagai berikut:

* **Model** berfungsi sebagai representasi data dan menyediakan logika untuk memproses atau mengakses database.
* **View** bertugas menampilkan antarmuka pengguna menggunakan Java Swing.
* **Controller** mengatur interaksi antara input pengguna (View) dan logika aplikasi (Model).

Aktivitas ini juga melibatkan pengaturan dependensi lewat **pom.xml**, serta menampilkan hasil akhir berupa GUI sederhana.

> **Tujuan utama:** memahami bagaimana mengorganisir aplikasi agar lebih modular, mudah dikelola, dan terstruktur.

---

## 🧩 **ACT 4 – Menyempurnakan Sistem dengan CRUD**

Setelah memahami konsep dasar MVC, ACT 4 membawa mahasiswa ke tahap selanjutnya: **mengimplementasikan fitur CRUD** di dalam arsitektur yang sama.

Hal-hal yang diselesaikan di tahap ini mencakup:

* Menambahkan formulir input untuk menambah atau mengedit data.
* Menyediakan tabel untuk menampilkan seluruh data mahasiswa.
* Memperkuat peran Controller dalam menangani operasi tambah, ubah, hapus, dan tampil data.
* Menjalin hubungan yang lebih dinamis antara View → Controller → Model.

> **Tujuan utama:** mempelajari siklus penuh manajemen data dan bagaimana setiap lapisan MVC berinteraksi.

---

## 🧩 **ACT 5 – Pengenalan dan Penerapan Hibernate (ORM)**

ACT 5 memperkenalkan konsep penting di dunia pengembangan aplikasi modern: **ORM (Object Relational Mapping)** menggunakan **Hibernate/JPA**.

Beberapa hal yang dikerjakan pada tahap ini:

* Membuat entity class menggunakan anotasi seperti `@Entity` dan `@Id`.
* Menggunakan repository untuk akses database otomatis tanpa penulisan SQL manual.
* Menyiapkan konfigurasi Hibernate lewat `application.properties`.
* Menghubungkan mekanisme CRUD dengan ORM sehingga manajemen data menjadi lebih efisien.

> **Tujuan utama:** memahami bagaimana Hibernate menggantikan query SQL manual dan mempermudah pengelolaan data.

---

## 🧩 **ACT 6 – Integrasi Spring Boot, Hibernate, dan Desktop GUI**

Tahap terakhir ini menggabungkan seluruh konsep sebelumnya ke dalam ekosistem **Spring Boot**, sembari tetap mempertahankan tampilan desktop menggunakan **Java Swing**.

Beberapa komponen penting dalam ACT 6:

* **pom.xml** dengan konfigurasi Spring Boot, JPA, dan MySQL.
* **Entity dan Model Tabel** untuk memetakan data dan mengelola penampilan di GUI.
* **Repository** berbasis `JpaRepository` untuk akses database otomatis.
* **Service** sebagai tempat logika bisnis, memanfaatkan **Dependency Injection** melalui `@Autowired`.
* **Controller** yang menjadi perantara antara GUI dan service.
* **View Swing** yang tetap digunakan sebagai tampilan aplikasi.
* **MahasiswaApp** sebagai class utama yang menjalankan aplikasi Spring dan membuka GUI.

> **Tujuan utama:** melihat bagaimana teknologi modern seperti Spring Boot dapat berpadu dengan aplikasi desktop, sambil menerapkan prinsip Dependency Injection dan ORM secara nyata.

---

## 🏁 **Ringkasan Pencapaian**

Setiap ACT membentuk satu langkah menuju aplikasi yang semakin lengkap:

| Pertemuan | Fokus Pengembangan           | Teknologi Utama               |
| --------- | ---------------------------- | ----------------------------- |
| **ACT 3** | Dasar MVC                    | Java Swing, Database          |
| **ACT 4** | Operasi CRUD                 | Java Swing                    |
| **ACT 5** | ORM dengan Hibernate         | JPA, Hibernate                |
| **ACT 6** | Integrasi Spring + Hibernate | Spring Boot, Hibernate, Swing |
