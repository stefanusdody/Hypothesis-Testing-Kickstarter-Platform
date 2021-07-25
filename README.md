## Gambaran Data
Data didapatkan dan dikumpulkan dari Kickstarter Platform dan dapat digunakan untuk analisis proyek.


## Sumber Data

Dataset asli berasal dari kaggle dengan link: https://www.kaggle.com/kemical/kickstarter-projects?select=ks-projects-201801.csv

seluruh column memiliki deskripsi sama seperti artinya, kecuali:

- usd_pledged: konversi dalam dolar AS dari the pledged column (konversi dilakukan oleh kickstarter).
- usd_pledge_real: konversi dalam dolar AS dari the pledged column (konversi dari Fixer.io API).
- usd_goal_real: konversi dalam dolar AS dari the goal column (konversi dari Fixer.io API).

## Objective

Melakukan Hypothesis testing terhadap dataset apakah ada hubungan antara Jumlah yang dijanjikan dalam mata uang proyek (variabel usd pledged) dengan statement yang berkaitan dengan keberhasilan peluncuran produk (variabel state)   
