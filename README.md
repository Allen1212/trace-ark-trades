# trace-ark-trades

This project records all purchases and sales made by [ARK Invest](https://ark-invest.com/) from 11/12/2019 to the present and utilizes [Pine script](https://www.tradingview.com/pine-script-docs/en/v4/index.html) to visualize these trades in [TradingView](https://www.tradingview.com). It includes trade records of 251 stocks. Through analyzing these trades, I think it's a good beginning to explore how ARK invests and builds your own investing system.

## Data sources

I [downloaded]((https://ark-invest.com/wp-content/trades/ARK_Trades.pdf)) trade data from 11/12/2019 - 11/11/2020.
 From 11/12/2020 to the present, I collected the trade records via subscribing to ARK's trade notifications. 
 You can subscribe to the services from [here](https://ark-funds.com/subscribe). ARK will email its trading log to you daily.

## Instructions

I will use Tesla Inc (TSLA) as an example to show how to use this project.

- Access TradingView website
  - Enter https://www.tradingview.com in your browser.

- Type the ticker in the search bar
  
  ![type-the-ticker](./images/type-ticker.png)

- Move to full-featured chart
  
  ![Access-full-featured-chart](./images/access-full-featured-chart.png)

- Find the ticker's folder and copy the script from the .pinescript file
  
  ![copy-the-script](./images/copy-script.png)

- Paste the script in the Pine Editor section and add to the chart
  
  ![paste-the-script](./images/paste-script.png)

## Other resources

[ARK Invest Active ETF Holdings Tracker](https://www.arktrack.com/)

## Thank you

I got inspired by a video made by this [Youtuber](https://youtu.be/DfSRNcCbEpA). I follow his idea to finish this project. He did lots of awesome videos to analyze the company's finances and introduce math knowledge behind the stock indicator. If you'd like to learn how to invest, I strongly recommend you to subscribe to his youtube channel.
