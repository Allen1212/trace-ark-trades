# trace-ark-trades

This project records all purchases and sales made by [ARK Invest](https://ark-invest.com/) from 11/12/2019 to the present and utilizes [Pine script](https://www.tradingview.com/pine-script-docs/en/v4/index.html) to visualize these trades in [TradingView](https://www.tradingview.com). 
It includes trade records of 259 stocks. 
Through analyzing these trades, I think it's an excellent beginning to investigate how ARK invests and build your own investing system. 
BTW, you can combine some charting tools, technical indicators, and my scripts to analyze your stocks in TradingView.

## Data sources

I downloaded trade data from 11/12/2019 - 11/11/2020 from [here](https://ark-invest.com/wp-content/trades/ARK_Trades.pdf). 
From 11/12/2020 to the present, I collected the trade records via subscribing to ARK's trade notifications. 
You can subscribe to the services from [here](https://ark-funds.com/subscribe). ARK will email its trading log to you daily.

## Instructions

I will use Tesla Inc (TSLA) as an example to show how to use this project.

- Access TradingView website
  - Enter https://www.tradingview.com in your browser.

- Type the ticker in the search bar
  
  ![type-the-ticker](./images/type-ticker.png)

- Move to the full-featured chart
  
  ![Access-full-featured-chart](./images/access-full-featured-chart.png)

- Find the ticker's folder and copy the script from the .pinescript file
  
  ![copy-the-script](./images/copy-script.png)

- Paste the script in the Pine Editor section and add to the chart
  
  ![paste-the-script](./images/ark-invest-tsla.png)
 
## Tips

There are some tips to help you to analyze your stocks.

- Use tools provided by TradingView (Using Resistance Line as an example)

    ![tools](./images/tools.png)
 
- Add technical indicators (Using MACD as an example)

    ![add_indicator](./images/add_indicator.png)
    
    ![macd](./images/macd.png)
    
- Add source code of technical indicators to my script (Using Bollinger Bands as an example)

    ![indicator_source_code](./images/indicator_source_code.png)

    ![add_indicator_code](./images/add_indicator_code.png)
    
## Other resources

- [ARK Invest Active ETF Holdings Tracker](https://www.arktrack.com/)

- [Cheaper Than Guru](https://cheaperthanguru.com/)

## Disclaimer 

This project is for educational and entertainment purposes only. 
The information herein may be inaccurate or outdated. 
It is your responsibility to verify all information.
Your investments are solely your own responsibility.
It is very important for you to conduct your own research or consult a financial adviser before you make any investment decisions.
The author accepts no responsibility for buying or selling decisions made using the information provided by this repository.
 
## Thank you

I got inspired by a video made by this [Youtuber](https://youtu.be/DfSRNcCbEpA). I follow his idea to finish this project. He did lots of awesome videos to analyze the company's finances and introduce math knowledge behind the stock indicator. If you'd like to learn how to invest, I strongly recommend you to subscribe to his youtube channel.
