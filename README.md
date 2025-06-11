# Segmentasi-Konsumen-untuk-Optimasi-Strategi-Promosi-Penjualan-pada-Pusat-Perbelanjaan.

Dalam dunia bisnis modern, khususnya di industri ritel dan pusat perbelanjaan, memahami karakteristik perilaku dan preferensi konsumen menjadi kunci utama dalam menyusun strategi pemasaran yang efektif, meningkatkan kepuasan pelanggan, dan meningkatkan profit. Perubahan perilaku konsumen yang dinamis menuntut perusahaan untuk tidak lagi menggunakan pendekatan promosi yang bersifat umum, melainkan mengarah pada pendekatan yang lebih personal dan spesifik. Oleh karena itu, segmentasi konsumen menjadi langkah strategis untuk mengelompokkan pelanggan ke dalam kelompok-kelompok yang memiliki kesamaan karakteristik, kebutuhan, atau perilaku sehingga memfasilitasi pendekatan yang ditargetkan dan dipersonalisasi. Segmentasi konsumen didefinisikan sebagai pembagian konsumen berdasarkan aspek demografi (usia, jenis kelamin, status pernikahan) dan perilaku. 

Proyek ini bertujuan untuk menerapkan algoritma K-Means dan Agglomerative Clustering dalam melakukan segmentasi tipe konsumen pada pusat perbelanjaan, guna mendapatkan wawasan tentang perilaku dan preferensi konsumen, serta menggunakan wawasan tersebut untuk merancang dan menerapkan pemasaran bertarget dan rekomendasi produk yang dipersonalisasi.

#  Perbandingan Agglomerative Clustering vs K-Means Clustering

| **Aspek**                       | **Agglomerative Clustering**                  | **K-Means Clustering**                        |
|---------------------------------|-----------------------------------------------|-----------------------------------------------|
| Jumlah Cluster                  | Sebanyak 3 cluster                            | Sebanyak 3 cluster                            |
| Banyak PC                      | PC1 sampai PC2                                | PC1 sampai PC2                                |
| Inisialisasi                    | Tidak membutuhkan inisialisasi               | Membutuhkan inisialisasi awal centroid        |
| Durasi Runtime                  | 0.4405 detik                                  | 0.4299 detik                                  |
| **Silhouette Score**            | 0.4654                                       | 0.4972                                       |
| **Calinski-Harabasz Index**     | 2827.26                                      | 3179.81                                      |
| **Davies-Bouldin Index**        | 0.7756                                       | 0.7333                                       |
| **Posisi Cluster 0**            | Tengah-atas (PC1 sedang, PC2 tinggi)         | Kanan bawah (PC1 tinggi, PC2 ≈ 0)            |
| **Posisi Cluster 1**            | Bawah tengah (PC1 -3 s.d. 0, PC2 negatif)    | Kiri atas (PC1 negatif, PC2 positif)         |
| **Posisi Cluster 2**            | Kanan bawah (PC1 > 2, PC2 < 0)               | Tengah atas (PC1 0–3, PC2 tinggi)            |
