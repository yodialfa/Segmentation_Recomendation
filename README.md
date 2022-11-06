# Customer Segmentation and Product Recommendation
##### Datasets : Online Retail From :
![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)
https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

## Tableau Dashboarding
https://public.tableau.com/app/profile/yodi.ramadhani.alfariz/viz/olret/Dashboard1?publish=yes

## Customer Segmentation
### Data Understanding
- InvoiceNo : transacation code
- StockCode : item code/ product code
- Description : item description
- Quantity : total item
- InvoiceDate : date of customers transcation full with the time.
- UnitPrice : price per item.
- CustomerID : customer code
- Country : country of customers live.

### Business Problem
- Offering, diskon dan strategi marketing yang kurang terfokus memungkinkan memakan biaya yang sangat besar.
- Diperlukannya segmentasi untuk setiap customer agar dapat melihat pola dari setiap customers.
- Segmentasi adalah langkah awal untuk Customer Relationship Management

### Objectives
- Mengcluster Customer Berdasarkan RFM Analisis
- Improvement terhadap kekurangan pada transaksi seperti Marketing Campaign pada cluster tertentu



### RFM Analysis
#### Recency
Variabel untuk mengukur nilai pelanggan berdasarkan rentang waktu (tanggal, bulan, tahun) transaksi terakhir pelanggan sampai saat ini.
#### Frequency
Mengacu pada berapa kali pelanggan berinteraksi dengan produk atau melakukan transaksi dalam periode waktu tertentu.
#### Monetary
Menunjukkan jumlah total yang dihabiskan oleh pelanggan untuk membeli produk Anda dalam periode waktu tertentu.

### Clustering
Menggunakan Algoritma K-Means terhadap scoring data dari RFM Analysis

### Mapping Class from Cluster
 0 Best Customers
 
 1 Low Spendig Pasif Customers
 
 2 Middle Spending Activer Customers
 
 3 New Customer low spending
 
### Recommendation for each Class
For Best Customers:
```sh
Penawaran Product Baru atau Product yang mungkin belum dibeli 
sebelumnya
```
For Low Spending Pasif Customers:
```sh
Melakukan follow up dengan marketing campaign terkait bundling product dan memberikan rekomendasi product yang paling diminati.
```
```sh
Memberikan penawaran potongan harga agar customer spent lebih banyak.
```

For Middle Spending Active Customers:
```sh
Memberikan penawaran potongan harga agar menarik customer untuk bertransaksi lagi.
```
```sh
Memberikan poin sebagai reward dan dapat ditukarkan dengan product atau potongan harga
```
For New  Customers Low Spending :
```sh
Memberikan Rekomendasi Product berdasarkan product yang diminati customer lainnya.
```
```sh
Memberikan poin agar customer bertransaksi lebih intens.
```












