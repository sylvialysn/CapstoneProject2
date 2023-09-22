# CapstoneProject2

TLC (Taxi and Limousine Commission) New York adalah badan pemerintah yang bertanggung jawab atas regulasi dan pengawasan layanan taksi, limusin, dan kendaraan sewaan lainnya di New York City. TLC bertanggung jawab memberi izin kepada pengemudi taksi, kendaraan yang digunakan, hingga menentukan standar tarif untuk taksi-taksi yang beroperasi di daerah new york.


TLC memiliki target untuk meningkatkan jumlah kendaraan yang dapat diakses oleh individu dengan disabilitas seperti pengguna kursi roda hingga 50%. Kendaraan terkait berupa Nissan NV200 atau 'The Taxi of Tomorrow' yaitu armada yang telah diakui oleh TLC sudah sesuai untuk memfasilitasi penumpang pengguna kursi roda. 

Maka dari itu, kita ingin mencari tahu kesiapan layanan taksi di new york city secara menyeluruh hingga dapat mengambil langkah lebih lanjut ini dan memprioritaskan para penumpang kursi roda.

Dataset yang digunakan adalah....

**Stakeholder :**
- Pengatur Regulasi (Regulatory Authorities) dari pihak Taxi and Limousine Commission (TLC) di New York: Pihak yang mengatur tarif taksi, yang bertanggung jawab untuk menetapkan dan mengawasi tarif taksi

- Pertanyaan utama : Apakah layanan taksi di new york city selama 2022-2023 sudah baik? 

Masalah : 

**Apakah taksi menjadi pilihan masyarakat?**
1. Mencari tahu apakah tarif yang diberikan kepada pelanggan sudah sesuai atau memuaskan. 
2. Apakah penggunaan itu meningkat atau tidak?
3. Apakah taksi menjadi pilihan bagi penumpang group-ride? 
4. Apakah taksi menjadi pilihan untuk pelanggan yang ingin berpergian jauh?
5. Kepuasan pelanggan dalam penggunaan layanan taksi

**Apakah layanan taksi sudah sesuai regulasi?**
1. Apakah MTA Tax dan improvement surcharge yang dikenakan sudah sesuai regulasi?
2. Apakah peraturan terkait tarif telah diaplikasikan secara teratur?
3. Apakah peraturan tarif sudah cukup memadai?
4. Sudah sesuaikah pengenaan congestion_surcharge?

**Apakah sistem layanan taksi sudah optimal?**

1. Melihat vendor yang lebih cepat dalam menanggulangi data perjalanan
2. Apakah integrasi pemesanan taksi ke sistem teknologi itu dimanfaatkan pelanggan?

## Berikut Informasi terkait dataset yang digunakan :
No |Nama Kolom | Penjelasan |
|---|---------|-----------------------------------------------------------------------------------------|
|1. |Vendor ID | Id perusahaan yang menyediakan rekaman data
|2. |LPEP_pickup_datetime | Waktu dan tanggal agrometer mulai menghitung atau waktu pickup pelanggan
|3. | LPEP_dropoff_datetime | Waktu dan tanggal agrometer terakhir menghitung atau waktu dropoff pelanggan
|4. |Passenger-count | Jumlah pelanggan yang naik taksi tersebut
|5. |Trip_distance | Jarak yang ditempuh
|6. |PULocationID | Zona pickup
|7. |DOLocationID | Zona dropoff
|8. |RateCodeID |Kode yang menandakan kategori tarif yang dikenakan pelanggan (1 yaitu Standard Rate, 2 yaitu JFK, jika perjalanannya berasal dari / berakhir di JFK airport, akan diberi flat rate atau tarif yang sudah ditetapkan (tidak menggunakan agrometer), 3 yaitu Newark, jika perjalanannya berasal dari / berakhir di Newark airport, akan diberi flat rate, 4 yaitu Nassau or Westchester, melampaui daerah new york city sehingga tarif akan lebih tinggi, 5 yaitu Negotiated fare, dimana pelanggan menegosiasi untuk mendapatkan tarif tertentu terkait lokasi tujuan spesifik yang diluar zona misalnya kota kecil yang tidak umum dilalui taksi, 6 yaitu group ride, dimana beberapa orang dengan destinasi yang sama melakukan pembagian tarif.)   
|9. |Store_and_fwd_flag | Yes = data terkait perjalanan tertentu tersimpan di sistem sementara, No = data terkait perjalanan tertentu tidak tersimpan karena langsung sampai ke sistem pusat
|10. |payment_type | Tipe pembayaran (cash, atau credit card, atau tidak terkena pembayaran, atau tidak diketahui, atau dispute)
|11. |Fare_amount | Tarif  
|12. |Extra | Biaya yang akan ditambah \$ 0.5  jika perjalanan dilakukan pada rush hour dan $1 jika pickup pada overnight yaitu umumnya jam 8 malam hingga 6 pagi,(seharusnya tidak lebih dari \$ 1.5).
|13. |MTA_tax | Pajak yang dikenakan untuk daerah new york yaitu \$ 0.5 (biaya tidak boleh lebih).
|14. |Improvement surcharge | Biaya \$ 0.30 per trip yang digunakan untuk meningkatkan kualitas sistem teknologi yang ada di taksi dan sebagainya. Update per 2022 biaya ini menjadi \$ 1.00 per trip (biaya tidak boleh lebih).
|15. |Tip_amount | Jumlah tips yang diberi 
|16. |Tolls_amount | Jumlah bayar tol
|17. |Total_amount | Jumlah yang dibayarkan tidak termasuk tips
|18. |Trip_type | Melihat apakah pelanggan melakukan pemesanan taksi sebelumnya atau tidak
|19. |Congestion_surcharge | Biaya yang dikenakan untuk daerah manhattan atau CBD (Central Business District) yang berupa fixed fee (\$ 2.5  Weekday, \$ 2.75  Weekend).



## Untuk menjawab permasalahan yang ada, proses yang dilalui oleh dataset ini yaitu : 
1. Data Understanding
2. Data Cleaning
3. Data Analysis
4. Conclusion & Recommendation

## Visualisasi dengan tableau
link
