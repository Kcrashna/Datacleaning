# Datacleaning
This repository contains a comprehensive data cleaning project aimed at preprocessing and cleaning datasets for analysis. The project implements various techniques to handle missing values, remove duplicates, and format data correctly, ensuring high data quality for further analysis or machine learning tasks.
I used the US shein appliances dataset. The dataset consists if 8 columns namel ['goods-title-link--jump', 'goods-title-link--jump href', 'rank-title',
'rank-sub', 'price', 'discount', 'selling_proposition','goods-title-link'] and 3986 rows. 
The chart in figure1 shows the missing values in the dataset. yellow represents missing values and purple represents non-missing values.
I dropped the columns 'goods-title-link--jump' and 'goods-title-link--jump href' which consisted of more than 50% missing values. Then replaced other column's missing values with the most frequent value. The figure2 shows that dataset is now clean.
