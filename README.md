# Hands on Data Cleaning and Scraping 
# 資料清理與爬蟲實作

### Please paste the URL from Github to https://nbviewer.jupyter.org/ if failed to load.

Just finished my 100 days challenge on machine learning basics and feel like I need to review and actually get hands on cleaning the data. This challenge will (hopefully) also contains some real world data scraping and cleaning.

打醬油剛(蹣跚)完成第二屆機器學習百日馬拉松，想藉<a href="https://ithelp.ithome.com.tw/users/20119709/ironman/2270">IT邦幫忙30日鐵人賽</a>重點複習資料清理的部分，並爬取有興趣的數據來實際操作。

### Content 目錄
<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day01_Jupyter_Notebook/Day01%20Jupyter%20Notebook%20Jupyter%20Notebook%E5%9F%BA%E6%9C%AC%E5%AE%89%E8%A3%9D%E8%88%87%E6%93%8D%E4%BD%9C.ipynb">Day01 Jupyter Notebook. Jupyter Notebook基本安裝與操作</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day02_What_is_EDA/Day02%20What%20is%20EDA%20(Exploratory%20Data%20Analysis)%20%E6%B7%BA%E8%AB%87%E4%BD%95%E8%AC%82%E6%8E%A2%E7%B4%A2%E5%BC%8F%E8%B3%87%E6%96%99%E5%88%86%E6%9E%90.ipynb">Day02 What is EDA (Exploratory Data Analysis)? 淺談何謂探索式資料分析</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day03_Pandas_DataFrame_Label_Encoding_and_One_Hot_Encoding/Day03%20Pandas%20DataFrame%2C%20Label%20Encoding%20and%20One%20Hot%20Encoding.ipynb">Day03 Pandas DataFrame, Label Encoding, and One Hot Encoding 基本資料類型、標籤編碼與獨熱編碼</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day04_Outlier_and_some_Numpy/Day04%20Outlier%20and%20some%20Numpy%20%E9%9B%A2%E7%BE%A4%E5%80%BC%E8%88%87Numpy%E6%93%8D%E4%BD%9C.ipynb">Day04 Outlier and some Numpy 離群值與Numpy操作</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day05_Pandas_Read_in_Files/Day05%20Pandas%20skills%20read%20in%20files%20Pandas%E8%AE%80%E5%8F%96%E4%B8%8D%E5%90%8C%E6%A0%BC%E5%BC%8F.ipynb">Day05 Pandas skills: read in files. Pandas操作：讀取不同格式</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day06_Data_Wrangling_Pandas/Day06%20Pandas%20skills_Data%20Wrangling.ipynb">Day06 Pandas skills: Data Wrangling. Pandas操作：資料角力</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day07_Pandas_Cheat_Sheet_Translation/Day07%20Pandas%20skills%20Pandas%20cheat%20sheet%20.ipynb">Day07 Pandas skills: Pandas cheat sheet. Pandas操作：快查表中文化</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day08_Data_Visualization_with_Pandas/Day08%20Basic%20Data%20Visualizations%20with%20Pandas%201of2.ipynb">Day08 Basic Data Visualizations with Pandas 1/2. Pandas視覺化資料基礎 1/2</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day09_Data_Visualization_with_Pandas/Day09%20Basic%20Data%20Visualizations%20with%20Pandas%202of2.ipynb">Day09 Basic Data Visualizations with Pandas 2/2. Pandas視覺化資料基礎 2/2</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day10_Data_Visualization_Tools_Matplotlib/Day10%20Data%20Visualization%20Tools%20Matplotlib.ipynb">Day10 Data Visualization Tools: Matplotlib 視覺化資料工具：Matplotlib</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day11_Data_Visualization_Tools_Plotly/Day11%20Data%20Visualization%20Tools%20Plotly.ipynb">Day11 Data Visualization Tools: Plotly 視覺化資料工具：Plotly</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day12_Data_Visualization_Tools_Seaborn/Day12%20Data%20Visualization%20Tools%20Seaborn.ipynb">Day12 Data Visualization Tools: Seaborn. 視覺化資料工具：Seaborn</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day13_Converting_Continuous_Variable_into_Discrete_Values/Day13%20Converting%20Continuous%20Variables%20into%20Discrete%20Values.ipynb">Day13 Converting Continuous Variables into Discrete Values 連續型變數離散化</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day14_Feature_Engineering_Kurtosis_and_Skewness/Day14%20Feature%20Engineering%20Kurtosis%20and%20Skewness%20.ipynb">Day14 Feature Engineering, Kurtosis and Skewness 淺談特徵工程、峰度與偏度</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day15_Numerical_Data_1of2_replace_NA_or_outlier/Day15%20Numerical%20Data%201of2%20replace%20NA%20or%20outlier.ipynb">Day15 Numerical Data 1/2 replace N/A or outlier  數值型特徵 1/2 填補N/A與離群值</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day16_Numerical_Data_2of2_reduce_skewness/Day16%20Numerical%20Data%202of2%20reduce%20skewness%20.ipynb">Day16 Numerical Data 2/2 reduce skewness 數值型特徵 2/2 去除偏態</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day17_Categorical_Data_1of2_mean_encoding/Day17%20Categorical%20Data%201of2%20mean%20encoding.ipynb">
Day17 Categorical Data 1/2 mean encoding 類別型特徵 1/2 均值編碼</a>

<a href="https://github.com/tgnco1218/Data-Cleaning-and-Scraping-30Days/blob/master/Day18_Categorical_Data_2of2_counting_and_feature_hashing/Day18%20Categorical%20Data%202of2%20counting%20and%20feature%20hashing.ipynb">Day18 Categorical Data 2/2 counting and feature hashing 類別型特徵 2/2 計數編碼與特徵雜湊</a>
