# Customer Segmentation and Product Recommendation
##### Datasets : Online Retail From :
![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)
https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

## Customer Segmentation
### Data Understanding
- InvoiceNo : number code of the transacation
- StockCode : the code of item
- Description : the description of item
- Quantity : count of item buying.
- InvoiceDate : date of customers transcation full with the time.
- UnitPrice : the price per item.
- Country : country of customers live.

### Business Problem
- Segmentasi customer belum diterapkan agar strategi marketing tepat sasaran
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
### RFM Scoring
| Score | Recency | Frequency | Monetary |
| ------ | ------ | ------ | ------ |
| 1 | Transaksi terakhir 301 hari - 365 hari | 0 < x <=  3| 0 < x <=  1.000
| 2 | Transaksi terakhir 241 hari - 300 hari| 3  <= x <  5 |1.000 < x <=  3.000|
| 3 | Transaksi terakhir 181 hari - 240 hari | 5 <= x <  7 |3.000 < x <=  5.000|
| 4 | Transaksi terakhir 121 hari - 180 hari| 7 <= x < 10 |5.000 < x <=  7.000|
| 5 | Transaksi terakhir 61 hari - 120 hari | 10  <= x < 15|7.000 < x <=  10.000|
| 6 | Transaksi terakhir 0 hari - 60 hari | 15  =< x  |x >  10.000|

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












