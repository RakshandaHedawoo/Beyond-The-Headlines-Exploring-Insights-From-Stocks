# Beyond The Headlines: Exploring Insights From Stocks
Introduction and Summary:
The COVID-19 pandemic is a one off global event. It has sent shockwaves to economies across the globe. Similarly, other global crises have affected the market in ways that were previously unforeseen. In this project, we aim to perform an in-depth analysis of the impact of the COVID-19 pandemic, as well as global crises such as the Ukraine War, on the performance of the top 5 stocks within four sectors that were severely affected by the crisis. The four sectors we are focusing on are Tech, Pharma, Telecom and FMCG (Fast moving consumer goods) and only on US stocks for this. This analysis is pivotal in understanding how economic crises impact stock performance and the broader financial markets. The study will be conducted in a Jupyter Notebook environment using statistical models and is expected to span a duration of 40-45 days.  

In a more specific sense, creating these analyses may help us provide contextual and researched advice to investors that may want to invest in major stocks, but want to minimize risk. There is no way to accurately predict how stocks will perform, particularly in a crisis, but our analysis can help inform those who plan to invest in these sectors how to handle their investments in the event of any type of crisis that introduces great risk.  

In order to analyze stock performance throughout the pandemic and through the Ukraine War, we are pulling stock data from October 2019 to the current date. We will be taking a closer look at these dates listed below in order to hone in on the impacts from these specific events:  

Lockdown 1 :- March 2020 to July 2020  
Lockdown 2 (Omicron):- November 2021 to February 2022  
Ukraine War :- 24 February 2022 to till date  
Our research endeavors to address the following key questions:  
● How did economic shocks impact the price movements of the top 5 stocks in each sector?  
● In what ways did these sectors respond to the challenges and opportunities posed?  
● How to identify headwind /tailwind effect?  
● To what extent did tech sector deviate from the expected behavior?  
● Are there any anomalies that stand out?  
● Is Tech sector witnessing a permanent paradigm shift?  

We expect to gain valuable insights from our research on how different sectors and individual stocks responded to the impacts of the pandemic and the war. Our analysis aims to reveal patterns that show which sectors and stocks demonstrated resilience in the face of these external shocks and which ones proved vulnerable. Additionally, we will identify potential indicators that could predict how these sectors would react, whether in advance or with a delay. We plan to validate these patterns across various timeframes, depending on the results of our initial exploratory analysis. Ultimately, our findings are intended to offer important insights into how external shocks affect financial markets. These insights will serve as a valuable resource for investors and policymakers, helping them make more informed decisions in response to such events.  

**FMCG:** The majority of supermarkets and retail chains were closed during lockdown, which was anticipated to cause a dramatic decline in the share price.  
**PHARMA:** By the time COVID was in place, many pharma companies were already working on vaccines. During the second lockdown, vaccine development had advanced, and so this sector will respond the quickest of all the sectors.  
**TECH:** It took some time for them to comprehend that the price of digital goods would rise so they didn't hire immediately, but eventually the tech stocks did rise.  
**TELECOM:** The lockdown caused these sectors to perform well once 5G was released to the public due to the increased demand for data and high speeds owing to the lockdown.  
EDA to be done to infer more insights by digging deeper into our findings from the data.  
We anticipate a potential significant decline in the FMCG (Fast-Moving Consumer Goods) stocks, while pharmaceutical stocks may have experienced an extraordinary surge. We intend to substantiate this hypothesis by analyzing the patterns that emerged during the lockdown period and exploring other prevalent trends both before and after the lockdown.  


## Our Dataset  
The dataset will cover a specific time frame, aligning with the onset and duration of the COVID-19 pandemic, allowing us to capture the relevant period. The data stretches from October 2019. We will be combining the stock price data from 20 different stocks from 4 sectors, as well as the S&P 500 and Dow Jones into one dataset. Overall, we will have about 1,460 rows, 110 columns and around 160,600 observations.  
#### What variables are we looking at for each index and stock:  
● Closing stock price - The price of the stock when the market closed that day.  
● Opening stock price - The price of the stock when the market opened that day.  
● High - The highest the price rose that day.  
● Low - The lowest the price dipped that day.  
● Adjusted Close - Amended close price based on any corporate actions.  
● Traded Volume - Number of shares traded that day.  
● Date  
