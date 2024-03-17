Dataset ini terdiri dari vektor fitur yang terkait dengan 12.330 sesi pengguna pada platform e-commerce. Tujuan dari pembentukan dataset ini adalah untuk memastikan bahwa setiap sesi milik pengguna yang berbeda dalam periode satu tahun, untuk menghindari kecenderungan pada kampanye tertentu, hari khusus, profil pengguna, atau periode tertentu.

Penjelasan Fitur
Administrative:
  Jumlah halaman administratif yang dikunjungi oleh pengguna selama sesi tersebut.
Administrative Duration:
  Durasi total yang dihabiskan oleh pengguna di halaman administratif selama sesi (dalam detik).
Informational:
  Jumlah halaman informatif yang dikunjungi oleh pengguna selama sesi.
Informational Duration:
  Durasi total yang dihabiskan oleh pengguna di halaman informatif selama sesi (dalam detik).
Product Related:
  Jumlah halaman terkait produk yang dikunjungi oleh pengguna selama sesi.
Product Related Duration:
  Durasi total yang dihabiskan oleh pengguna di halaman terkait produk selama sesi (dalam detik).
Bounce Rates:
  Persentase pengunjung yang masuk ke halaman tersebut dan langsung meninggalkan situs web ("bounce") selama sesi.
Region:
  Wilayah geografis pengguna.
Traffic Type:
  Jenis lalu lintas yang membawa pengguna ke situs web.
Visitor Type:
  Tipe pengunjung, apakah pengunjung baru atau pengunjung yang kembali.
Weekend:
  Indikator apakah kunjungan terjadi di akhir pekan atau tidak (True jika akhir pekan, False jika tidak).
Revenue:
  Label kelas, indikator apakah pengguna menghasilkan pendapatan (True jika iya, False jika tidak).

Business Insight:
Meningkatkan ProductRelated pada waktu menjelang SpecialDay dikarenakan jumlah pengunjung meningkat pada saat menjelang hari khusus tertentu, dengan meningkatkan ProductRelated kemungkinan kunjungan dapat menghasilkan revenue mengingat ProductRelated memiliki korelasi yang positif dengan revenue.  
Meningkatkan rekomendasi product terkait pada week day saat jumlah kunjungan meningkat yang mana meningkatkan kemungkinan suatu kunjungan menghasilkan revenue
