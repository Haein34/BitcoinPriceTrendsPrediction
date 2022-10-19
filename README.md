# BitcoinPriceTrendsPrediction
본 프로젝트는 Reddit데이터와 LexisNexis 데이터를 이용하여 비트코인 가격의 방향성을 예측하기 위해 시행되었습니다.  
정확한 결과를 위해 기술지표와 감정지수가 계산되었으며, 비트코인 가격 추세를 이해하는데 참고 가능합니다.
  
This project was implemented to predict the trends of Bitcoin prices using Reddit data (i.e., social network services data) and LexisNexis data (i.e., News data).  
Technical indicators and sentiment indices were considered together, and it can be used as a reference for understanding the Bitcoin Price trend.

## Data Description
사용된 데이터는 2017년 8월 1일부터 2022년 2월 28일 까지의 기간동안 수집된 데이터입니다.  
LexisNexis에서 "Bitcoin", "Crypto", "Virtual Asset", "Ethereum", "BTC", "ETH" 및 "Blockchain" 쿼리를 사용하였으며, 총 26,441개의 뉴스가 수집되었습니다.  
Reddit에서 r/Bitcoin, r/Ethereum 및 r/cryptocurrency subreddit에 포함된 게시글과 댓글은 Pushshift API를 사용하여 수집되었습니다.  
총 359,943개의 제출물과 26,003,561개의 댓글이 수집되었습니다.  
  
The datasets used for analysis is from April 8, 2015 to September 2, 2021.  
In all, 26,441 data were collected from news articles obtained using “Bitcoin,” “Crypto,” “Virtual Asset,” “Ethereum,” “BTC,” “ETH,” and “Blockchain” queries from LexisNexis.  
On Reddit, submissions and comments contained in r/Bitcoin, r/Ethereum, and r/cryptocurrency subreddits were collected using the Pushshift application programming interface (API). A total of 359,943 submissions and 26,003,561 comments were collected.  

## Contents
<img src="https://img.shields.io/badge/Python-3776AB?style=plastic&logo=Python&logoColor=white">
ver 3.7.7
