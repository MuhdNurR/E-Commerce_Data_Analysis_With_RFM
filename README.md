# Brazilian E-Commerce Public Dataset by Olist

## 📝 About Dataset

Welcome! This is a Brazilian ecommerce public dataset of orders made at Olist Store. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. We also released a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.This is real commercial data, it has been anonymised, and references to the companies and partners in the review text have been replaced with the names of Game of Thrones great houses.

## Context

This dataset was generously provided by Olist, the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners. See more on our website: www.olist.com After a customer purchases the product from Olist Store a seller gets notified to fulfill that order. Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where he can give a note for the purchase experience and write down some comments.

## Attention 
1. An order might have multiple items.
2. Each item might be fulfilled by a distinct seller.
3. All text identifying stores and partners where replaced by the names of Game of Thrones great houses.

### Defining Question
1. Produk dengan penjualan terbanyak ? Termasuk dalam kategori produk mahal atau murah ?
2. Berapa rata-rata pengeluaran pelanggan ? Apakah berhubungan dengan geografis ?
3. Lokasi geografis mana yang memiliki pelanggan terbanyak ?
4. Tingkat kepuasan pembelian terhadap layanan ?
5. Bagaimana data pembelian order setiap bulan ?

## 📊 Dashboard with Streamlit
### Streamlit Cloud

View the dashboard on streamlit could directly on this link: https://e-commerceda.streamlit.app/

### Run Streamlit on Local

#### Setup environment

To install all the required libraries, open your terminal/command prompt/conda prompt, navigate to this project folder, and run the following command:

```bash
conda create --name main-ds python=3.9
conda activate main-ds
pip install numpy pandas matplotlib scipy streamlit seaborn
```

#### Run Steamlit App
```bash
streamlit run dashboard.py
```
