![ProjectLogo](/Resources/groupprojectlogo.png)
# Crypto and Covid: An analysis of cryptocurrencies and the financial markets during the covid era

### Project team members: Benjamin Weymouth, Mohamed Berrachdi, Sadia Akbar ###
-----------------------------
Our motivation is to understand how the covid pandemic affected market trends, volatility and correlations between various market forces in cryptocurrencies, commodities and the semiconductor industry. We will address the connection between cryptocurrencies, the covid pandemic, and various X-Factors: semiconductors, meme stocks and gold. 


### Table of Contents ### 
-----------------------------
1. [Topic of Research](#topic-of-research) 
1. [DashBoard Video](#dashboard-video) 
1. [Powerpoint Analysis](#powerpoint-analysis) 
1. [Gold and Cryptocurrency Analysis, by Sadia Akbar](#Gold-and-Cryptocurrency-Analysis-by-Sadia-Akbar) 
1. [Meme Stock and Cryptocurrency Analysis, by Mohamed Berrachdi](#Meme-Stock-and-Cryptocurrency-Analysis-by-Mohamed-Berrachdi) 
1. [Semiconductor and Cryptocurrency Analysis, by Benjamin Weymouth](#Semiconductor-and-Cryptocurrency-Analysis-by-Benjamin-Weymouth) 
1. [Sources for Datasets](#Sources-for-Datasets) 
1. [Installation Requirements](#Installation-Requirements) 
 
## Topic of Research

We sought to uncover the answer to these questions: is there a correlation between the performance of our X-Factor, cryptocurrency and the covid crisis? 
If an investor had a choice, should they have invested in an X-Factor or in cryptocurrencies based on pre and post covid performance? For our cryptocurrency, gold and the semiconductor industry analysis, we utilized Yahoo Finance. We looked at other commodities on finance but narrowed our scope and gained some momentum. For our data on the covid crisis, we turned to an internationally recognized body, the World Health Organization. We were able to find csv data on covid case numbers. 

## DashBoard Video:  

Here is a recording of our final dashboard, which includes data visualizations from all three group members. 
![DashBoardRecording](https://github.com/benjaminweymouth/fintech-project1-data-analysis/blob/main/Resources/DashboardGroupVideo.gif)

## Powerpoint Analysis
Here is a recording of our powerpoint slide deck, which includes notes and highlights from all three group members. Here's the [link](https://github.com/benjaminweymouth/fintech-project1-data-analysis/blob/main/Resources/Project%201_Group%201_%20Covid%20Market%20Trends.pptx) for the PPT (please download to view the slide deck properly.)
![PowerPointVideo](https://github.com/benjaminweymouth/fintech-project1-data-analysis/blob/main/Resources/PowerPointGroupVideo.gif)

## Gold and Cryptocurrency Analysis by Sadia Akbar

In this part of the group project we compare cryptocurrency and gold in terms of daily and cumulative returns, volatility and correlations before and during covid. The rapid rise of cryptocurrencies over the past few years has drawn the attention of investors and analysts alike, and most often investments in cryptocurrencies are compared to investments in gold. Although there might be some similarities, it is widely acknowledged that gold and cryptocurrencies have no correlation. The most prominent difference between the two is that cryptocurrency does not exist in physical form, and there is no need for banking intermediaries to facilitate the transaction.

Section 1: Cryptocurrencies and Gold comparability in pre covid era.

Section 2: Cryptocurrencies and Gold comparability in during the covid era.

Section 3: An investment analysis to answer the most weighted question of which is a better long term investment? Gold or cryptocurrency?

### Video for Jupyter Notebook  
Here is a recording of Sadia's Jupyter notebook on Gold and Cryptocurrency Analysis. Here's the [link](https://github.com/benjaminweymouth/fintech-project1-data-analysis/blob/main/Python%20Code/DataAnalysis1_Sadia-Final.ipynb) for Sadia's notebook. 
![GoldandCryptocurrencyRecording](https://github.com/benjaminweymouth/fintech-project1-data-analysis/blob/main/Resources/Sadia_analysis_video.gif)

## Meme Stock and Cryptocurrency Analysis by Mohamed Berrachdi
<br>

### Subject of this research

Showing the fluctuation that occured for the so called Meme stocks pre covid and during covid, the majority of the stock for these
companies was stable then saw a sharp fluctuation once they got picked up by the larger internet social commnunities, mainly reddit.

As the case study sample, we will be using reddit and particulary a subreddit (or a group) called Wallstreetbets. https://www.reddit.com/r/wallstreetbets/

Using date results from https://swaggystocks.com/dashboard/stocks/terminal/TSLA which is a website that analysises sentiment and comment over reddit and wallstreetbets forums, the chosen stocks where the most spoken about.
### Case Study: an Investment portfolio in Meme Stocks and BTC

To illustrate the above analysis with a real life case study, we are here listing an investment scenario for different amount both in Meme Stocks and BTC.

### Video for Jupyter Notebook  
Here is a recording of Mo's Jupyter notebook on Meme Stock and Cryptocurrency Analysis. Here's the [link](https://github.com/benjaminweymouth/fintech-project1-data-analysis/blob/main/Python%20Code/DataAnalysis1_Mo_Cleaned_2.ipynb)  for Mo's notebook. 
![MemeStockandCryptocurrency](https://github.com/benjaminweymouth/fintech-project1-data-analysis/blob/main/Resources/Mo_Jupyter_Video.gif)
<br>

## Semiconductor and Cryptocurrency Analysis by Benjamin Weymouth
<br>
This section of our group project seeks to deconstruct some of the key features, trends and correlations relating to cryptocurrency and the semiconductor chip industry during the covid era. The rises, dips and variations in the semiconductor industry are significant because it impacts many other industries. Notable changes in the cryptocurrency space are often highlighted but are rarely correlated the semiconductor industry. Thus, this analysis will examine these sectors in the covid era within three sections that build upon one another.<br><br>

<br> 
<strong> Section 1: Cryptocurrencies and Semiconductors </strong> The first section will utilize financial analytical tools to compare the performance of three major cryptocurrencies to an ETF representing the semiconductor industry.<br> <br>
<strong> Section 2: Covid Cases and Financial Analysis </strong>The second section will build upon the first, and introduces covid cases into the financial analysis using data from the World Health Organization.<br> <br>
<strong> Section 3: A 3-point Portfolio Analysis </strong>The third section will analyse the performance of a portfolio that is semiconductor-centric but also includes cryptocurrency in both the pre-covid and post-covid timeframes. It will highlight 3 distinct points in time: the pre-covid, peak-covid and post covid timeframes.
<br>

Further details, conclusions and key takeaways are provided in [Ben's Jupyter Notebook](https://github.com/benjaminweymouth/fintech-project1-data-analysis/blob/main/Python%20Code/DataAnalysis1_Ben.ipynb)

<br>

### Video for Jupyter Notebook
Here is a recording of Ben's Jupyter notebook on Semiconductor and Cryptocurrency Analysis. Here's the [link](https://github.com/benjaminweymouth/fintech-project1-data-analysis/blob/main/Python%20Code/DataAnalysis1_Ben.ipynb) for Ben's notebook.  <br> 

![SemiconductorandCryptocurrency](https://github.com/benjaminweymouth/fintech-project1-data-analysis/blob/main/Resources/Ben_Jupyter_Video.gif)

## Sources for Datasets
* API for yfinance, Yahoo Finance (meme stocks, gold, semicondunctor ETF) 
* yfinance for VanEck Vectors Semiconductor ETF (SMH)
* Meme Stocks: used yfinance
* Gold: used yfinance
* New library used: yfinance 
* World Health Organization (WHO) csv for Covid case dataset

## Installation Requirements

In order to run this code you must have installed the following items: 

* Python, Anaconda and Jupyter Lab
* PlotLy
* Pandas 
* Hvplot 
* Holoviz Panel (for dashboard) 
* Matplotlib and pyplot
* Scatter
* Bokeh Server
* yfinance (Yahoo finance) 
* Download CSV for WHO Covid-19 data 
* Path and all required import statements 
* Place the Yahoo API key in an environment variable file, to reference in your local file explorer. 

