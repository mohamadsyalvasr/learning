#database #sql

Di artikel ini, kamu akan berkenalan dengan PostgreSQL dimana pada saat artikel ini dibuat menempati posisi ke-4 dalam **10 Database Terpopuler di Dunia** menurut data dari [DB-engines](https://db-engines.com/en/ranking). 

Penasaran dengan PostgreSQL ? Simak pembahasannya sampai habis!

# Apa itu PostgreSQL ?

Menurut [Wikipedia](https://id.wikipedia.org/wiki/PostgreSQL), **PostgreSQL** adalah sebuah sistem basis data yang disebarluaskan secara bebas menurut Perjanjian lisensi BSD. Peranti lunak ini merupakan salah satu basis data yang paling banyak digunakan saat ini, selain MySQL dan Oracle. PostgreSQL menyediakan fitur yang berguna untuk replikasi basis data. Fitur-fitur yang disediakan PostgreSQL antara lain DB Mirror, PGPool, Slony, PGCluster, dan lain-lain.

Dikembangkan oleh **Berkeley Computer Science Department** pada tahun 1986 dengan nama awal yaitu POSTGRES dan rilis pertama kali pada tahun 1989 kemudian pada tahun 1996 berganti nama menjadi PostgreSQL. Memiliki manajemen sistem database relasional (RDBMS) yang sifatnya *open source*, membuat database ini dapat mengolah data dalam tabel yang memiliki relasi satu dengan yang lainnya dan dapat dikustomisasi sesuai kebutuhan serta gratis. PostgreSQL mendukung baik SQL (relasi) dan JSON (non relasi) kueri.

PostgreSQL sangat cocok untuk aplikasi yang membutuhkan pengolahan data yang sangat kompleks contohnya seperti Sistem Informasi Geografis (GIS) meskipun begitu, banyak digunakan juga pada aplikasi web, aplikasi mobile, dan aplikasi analytics. Banyak perusahaan yang menggunakan PostgreSQL seperti Apple, Fujitsu, Red Hat, Cisco, Juniper Network, Instagram dan lain sebagainya.

Untuk dukungan bahasa pemrograman, PostgreSQL mendukung berbagai bahasa seperti .NET, C/C++, C#, Delphi, Go, Java, JavaScript, Perl, PHP, Python, Ruby dan TCL sehingga pengembangan sebuah aplikasi akan menjadi lebih mudah karena tidak ada kendala ketidakcocokan dengan manajemen yang digunakan.

# Fitur-Fitur PostgreSQL

[Fitur-fitur](https://www.niagahoster.co.id/blog/postgresql-adalah/#Fitur-Fitur_PostgreSQL) yang disediakan PostgreSQL, antara lain:

-   **Asynchronous Replication –** Menggandakan database secara asinkron.
-   **Data Integrity** – Mendukung Primary Key, Foreign Key, dan lain-lain.
-   **Inheritance –** Mewariskan karakteristik obyek induk ke obyek keturunan.
-   **Locking Mechanism –** Melakukan pengamanan terhadap database.
-   **Non-Relational Support –** Mendukung perintah non-relasional seperti JSON.
-   **Point-in-time Recovery –** Melakukan backup server secara terus-menerus.
-   **Procedural Languages –** Mendukung bahasa prosedural misalnya Python, Perl, dan sebagainya.
-   **Rule Customization –** Melakukan kustomisasi terhadap perintah seperti INSERT, UPDATE, atau DELETE.
-   **Savepoints –** Menangani error pada transaksi kompleks.
-   **Tablespaces –** Menentukan media penyimpanan database, schema, atau tabel.

dan masih banyak lagi fitur-fitur lainnya yang bisa kamu cek di [situs resmi](https://www.postgresql.org/about/featurematrix/).

# Tipe Data

Tipe-tipe data yang digunakan di PostgreSQL:

-   **Boolean –** true, false, null.
-   **Character –** CHAR, VARCHAR, TEXT.
-   **Numeric –** SMALLINT, INT, SERIAL, float, real, numeric.
-   **Temporal –** DATE, TIME, TIMESTAMP, TIMESTAMPTZ, INTERVAL.
-   **Array –** Array string, Array integer.
-   **JSON –** JSON, JSONB.
-   **UUID –** uuid-ossp, uuid_generate_v1, uuid_generate_v4.
-   **Special Data Types –** box, line, point, lseg, polygon, inet, macaddr.