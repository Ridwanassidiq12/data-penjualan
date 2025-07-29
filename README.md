# data-penjualan
Automasi Analisis Data Penjualan di Excel & Dashboard Visualisasi dengan Google Looker 
data prparation :

1.menggabungkan semua data dari file Customer_Info ke sheet Order_Data di file Main_Ecommerce.

2.Tarik data dari file Product_Catalog, tapi terlebih dahulu bersihkan kolom Stock_Unit, kemudian pindahkan seluruh data beserta key-nya ke file Main_Ecommerce pada sheet Order_Data.

3.Tarik data dari file Order_Records, lalu isi kolom Total_Amount menggunakan informasi dari file Product_Catalog. Setelah itu, pindahkan seluruh data beserta key-nya ke file Main_Ecommerce pada sheet Order_Data.

4.Tarik data dari file Review_Data, namun terlebih dahulu bersihkan kolom Review_Text berdasarkan Rating. Tambahkan kolom Anomaly yang menandai ketidaksesuaian antara isi review (positif atau negatif) dengan rating yang diberikan. Kolom Anomaly ini berfungsi untuk mengidentifikasi mismatch semantik yang mengindikasikan masalah atau tugas khusus.

5.Tarik data dari file Shipping_Info berdasarkan key, lalu masukkan ke file Main_Ecommerce pada sheet Order_Data.

insight :
di data penjualan ecomerce memiliki total pendapatan Rp.7.225.150.000 dengan total barang yang terjual 1480 unit adapun stok barang yang belum terjual 50.132 unit.
kategori product paling laris ada Electronic : 164
product yang paling memiliki kontribusi terbanyak terhadap pendapatan yaitu Uniqlo Dry-EX : 255 jt
tahun dengan pendapatan tertinggi yaitu pada tahun 2024 : Rp.4.353.750.000
jumlah payment type yang paling banyak digunakan ada debit : 138 dan gopay :137
jumlah membership tier rata rata sama tidak jauh berbeda sekita 30 %an
courier yang paling banyak digunakan yaitu antar saja : 132
ada 4 kota yang memiliki kontribusi terbesar yaitu surabaya, jakarta, bali, badung
