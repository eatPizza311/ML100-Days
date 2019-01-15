# 100 Days Of ML Code :running:
## Day001 (2018/12/15)
### 資料介紹與評估指標
4 questions to ask before starting.
1. Why is it important?
2. Where do data come from?
3. What are they?
4. What is our goal? (Evaluate by Evaluation Metrics)
***
## Day002
### EDA - 讀取資料
Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns,to spot anomalies,to test hypothesis and to check assumptions with the help of summary statistics and graphical representations.
#### 資料的row和column數量
> 使用[shape](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.shape.html#pandas.DataFrame.shape)可以得到DataFrame的維度，以 tuple(row, col) 呈現。
#### 列出所有欄位
> 使用[columns](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.columns.html#pandas.DataFrame.columns)得到所有的欄位名稱後，利用[tolist](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Index.tolist.html#pandas.Index.tolist)將其化成list方便印出。
#### 擷取部分資料
> 可以使用[.loc\[indexName\]](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.loc.html#pandas.DataFrame.loc)來取出特定index的資料，或使用[.iloc\[position\]](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.iloc.html#pandas.DataFrame.iloc)按照位置來擷取。

> [.head(n)](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.head.html#pandas.DataFrame.head)可擷取前n行(預設為5行)，而[.tail(n)](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.tail.html#pandas.DataFrame.tail)則為後n行。
***
