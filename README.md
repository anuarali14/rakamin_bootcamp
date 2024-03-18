Dataset ini terdiri dari vektor fitur yang terkait dengan 12.330 sesi pengguna pada platform e-commerce. Tujuan dari pembentukan dataset ini adalah untuk memastikan bahwa setiap sesi milik pengguna yang berbeda dalam periode satu tahun, untuk menghindari kecenderungan pada kampanye tertentu, hari khusus, profil pengguna, atau periode tertentu.

Penjelasan Fitur
1. Administrative:
  Jumlah halaman administratif yang dikunjungi oleh pengguna selama sesi tersebut.
2. Administrative Duration:
  Durasi total yang dihabiskan oleh pengguna di halaman administratif selama sesi (dalam detik).
3. Informational:
  Jumlah halaman informatif yang dikunjungi oleh pengguna selama sesi.
4. Informational Duration:
  Durasi total yang dihabiskan oleh pengguna di halaman informatif selama sesi (dalam detik).
5. Product Related:
  Jumlah halaman terkait produk yang dikunjungi oleh pengguna selama sesi.
6. Product Related Duration:
  Durasi total yang dihabiskan oleh pengguna di halaman terkait produk selama sesi (dalam detik).
7. Bounce Rates:
  Persentase pengunjung yang masuk ke halaman tersebut dan langsung meninggalkan situs web ("bounce") selama sesi.
8. Region:
  Wilayah geografis pengguna.
9. Traffic Type:
  Jenis lalu lintas yang membawa pengguna ke situs web.
10. Visitor Type:
  Tipe pengunjung, apakah pengunjung baru atau pengunjung yang kembali.
11. Weekend:
  Indikator apakah kunjungan terjadi di akhir pekan atau tidak (True jika akhir pekan, False jika tidak).
12. Revenue:
  Label kelas, indikator apakah pengguna menghasilkan pendapatan (True jika iya, False jika tidak).

Exploratory Data Analysis:
Ringkasan Wawasan EDA dari E-Commerce Insights Unlocking Online Shopper Behavior

1. Tren Pembelian Berdasarkan Hari dalam Seminggu:
Analisis menunjukkan bahwa ada perbedaan perilaku pembelian antara hari kerja dan akhir pekan. Meskipun jumlah total pengunjung pada akhir pekan lebih sedikit, persentase pengunjung yang menjadi pembeli relatif lebih tinggi pada akhir pekan. Ini menunjukkan bahwa akhir pekan memiliki potensi penjualan yang signifikan.

2. Pengaruh Hari Khusus Terhadap Pembelian:
Perilaku pembelian juga dipengaruhi oleh hari-hari khusus atau 'Special Days'. Sebagian besar pengunjung pada hari-hari dengan 'Special Days' yang dekat (kategori 'Close') cenderung menjadi non-pembeli, sementara jumlah pembeli cenderung lebih tinggi pada hari-hari dengan 'Special Days' yang jauh (kategori 'Far').

3. Perilaku Pembelian Berdasarkan Jenis Pengunjung:
Analisis menunjukkan bahwa ada perbedaan perilaku pembelian antara tipe pengunjung. Sebagian besar pengunjung yang merupakan 'Returning Visitor' cenderung menjadi non-pembeli, sementara pengunjung 'New Visitor' memiliki tingkat konversi yang lebih rendah daripada 'Returning Visitor'.

4. Pengaruh Durasi Kunjungan Terhadap Pembelian:
Durasi kunjungan pada halaman produk ('Product Related Duration') memiliki pengaruh yang signifikan terhadap perilaku pembelian. Meskipun distribusi durasi kunjungan cenderung skew ke kanan, pengunjung dengan durasi kunjungan yang lebih lama cenderung memiliki tingkat konversi yang lebih tinggi.

5. Hubungan antara Fitur Website dan Pembelian:
Terdapat hubungan antara beberapa fitur website seperti 'Page Values', 'Exit Rates', dan 'Bounce Rates' dengan perilaku pembelian. Tingkat 'Page Values' yang tinggi umumnya berkorelasi dengan peningkatan konversi, sementara 'Exit Rates' dan 'Bounce Rates' yang tinggi cenderung menunjukkan tingkat konversi yang lebih rendah.

Business Insight:
Meningkatkan ProductRelated pada waktu menjelang SpecialDay dikarenakan jumlah pengunjung meningkat pada saat menjelang hari khusus tertentu, dengan meningkatkan ProductRelated kemungkinan kunjungan dapat menghasilkan revenue mengingat ProductRelated memiliki korelasi yang positif dengan revenue.  
Meningkatkan rekomendasi product terkait pada week day saat jumlah kunjungan meningkat yang mana meningkatkan kemungkinan suatu kunjungan menghasilkan revenue
