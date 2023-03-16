
use simple way to predict stock market.

=====================================================

Description:

There are two channels of data provided in this dataset:

News data: I crawled historical news headlines from Reddit WorldNews Channel (/r/worldnews). They are ranked by reddit users' votes, and only the top 25 headlines are considered for a single date.
(Range: 2008-06-08 to 2016-07-01)

Stock data: Dow Jones Industrial Average (DJIA) is used to "prove the concept".
(Range: 2008-08-08 to 2016-07-01)

I provided three data files in .csv format:

RedditNews.csv: two columns
The first column is the "date", and second column is the "news headlines".
All news are ranked from top to bottom based on how hot they are.
Hence, there are 25 lines for each date.

DJIA_table.csv:
Downloaded directly from Yahoo Finance: check out the web page for more info.

Combined_News_DJIA.csv:
To make things easier for my students, I provide this combined dataset with 27 columns.
The first column is "Date", the second is "Label", and the following ones are news headlines ranging from "Top1" to "Top25".


======================================

資料來源
Sun, J. (2016, August). Daily News for Stock Market Prediction, Version 1. Retrieved [Date You Retrieved This Data] from https://www.kaggle.com/aaron7sun/stocknews.
