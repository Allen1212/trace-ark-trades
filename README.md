# trace-ark-trades

This project records all purchases and sales made by [ARK Invest](https://ark-invest.com/) from 11/12/2019 to the present and utilizes [Pine script](https://www.tradingview.com/pine-script-docs/en/v4/index.html) to visualize these trades in [TradingView](https://www.tradingview.com). 
It includes trade records of 302 stocks. 
Through analyzing these trades, I think it's an excellent beginning to investigate how ARK invests and build your own investing system. 
BTW, you can combine some charting tools, technical indicators, and my scripts to analyze your stocks in TradingView.

## :star2: New features

- Count how many Ark ETFs sold/bought your stock on the same day 

    ![aapl](./images/aapl.png)
    
    For example, ARKF, ARKG, and ARKQ sold AAPL on 1/8/2021. We mark "×3" on the label of 1/8/2021.
    
- View the trading records of each ETF on your stock

    - Click the **Settings** in indicator legend

        ![setting](./images/setting.png)
    
    - Choose an ETF which your stock belong to
    
        ![change_inputs](./images/change_inputs.png)
    
    - Observe the Sell/Buy information(share volume) and stock weight in the ETF
    
        ![etf](./images/etf.png)

## :page_with_curl: Data sources

I get trade data from 11/12/2019 - 10/15/2020 in this [pdf](https://ark-invest.com/wp-content/trades/ARK_Trades.pdf). 
From 10/16/2020 to the present, the stock's share change is calculated using its day to day position in ARK's holdings. 
You can check ARK's holdings from ARK's [website](https://ark-funds.com/investor-resources).

## :memo: Instructions

I will use Tesla Inc (TSLA) as an example to show how to use this project.

- Access TradingView website
  - Enter https://www.tradingview.com in your browser.

- Type the ticker in the search bar
  
  ![type-the-ticker](./images/type-ticker.png)

- Move to the full-featured chart
  
  ![Access-full-featured-chart](./images/access-full-featured-chart.png)

- Find the ticker's folder (Ctrl+F) and copy the script from the .pinescript file
  
  ![copy-the-script](./images/copy-script.png)

- Paste the script in the Pine Editor section and add to the chart
  
  ![paste-the-script](./images/ark-invest-tsla.png)
 
## :bulb: Tips

There are some tips to help you to analyze your stocks.

- Use tools provided by TradingView (Using Resistance Line as an example)

    ![tools](./images/tools.png)
 
- Add technical indicators (Using MACD as an example)

    ![add_indicator](./images/add_indicator.png)
    
    ![macd](./images/macd.png)
    
- Add source code of technical indicators to my script (Using Bollinger Bands as an example)

    ![indicator_source_code](./images/indicator_source_code.png)

    ![add_indicator_code](./images/add_indicator_code.png)
    
## :link: Other resources

- [Ark track - Alien tomato:tomato:](https://ark.alien-tomato.com/)

- [ARK Invest Active ETF Holdings Tracker](https://www.arktrack.com/)

- [Cheaper Than Guru](https://cheaperthanguru.com/)

## :warning: Disclaimer 

This project is for educational and entertainment purposes only. 
The information herein may be inaccurate or outdated. 
It is your responsibility to verify all information.
Your investments are solely your own responsibility.
It is very important for you to conduct your own research or consult a financial adviser before you make any investment decisions.
The author accepts no responsibility for buying or selling decisions made using the information provided by this repository.
 
## :tomato: Thank you

I got inspired by a video made by this [Youtuber](https://youtu.be/DfSRNcCbEpA). I follow his idea to finish this project. He did lots of awesome videos to analyze the company's finances and introduce math knowledge behind the stock indicator. If you'd like to learn how to invest, I strongly recommend you to subscribe to his youtube channel.


## :rocket: Update (6/11/2021)

6/11/2021
- ARKW: add a new ticker **BZ** 
- ARKQ: add a new ticker **BZ** 
- ARKK: remove a ticker **HUYA**

6/9/2021
- ARKG: remove a ticker **SYRS**

6/8/2021
- ARKK: remove a ticker **SYRS**
- ARKK: remove a ticker **ONVO**

6/3/2021
- ARKF: add a new ticker **GOOG**

6/2/2021
- ARKW: add a new ticker **ETSY**

5/26/2021
- ARKF: remove a ticker **GWRE**
- ARKG: add a new ticker **DYNS**
- ARKQ: remove a ticker **ADSK**
- ARKX: remove a ticker **WKHS**
- ARKX: remove a ticker **ADSK**

5/25/2021
- ARKG: add a new ticker **DRNA**
- ARKQ: remove a ticker **WKHS**
- ARKW: remove a ticker **API**
- ARKW: remove a ticker **HUBS**
- ARKX: remove a ticker **SPCE**

5/24/2021
- ARKW: add a new ticker **VUZI**
- ARKW: remove a ticker **TREE**
- ARKW: remove a ticker **PINS**
- ARKW: remove a ticker **SI**
- ARKX: add a new ticker **2618**
- ARKX: add a new ticker **U**

5/20/2021
- ARKF: remove a ticker **TREE**
- ARKF: remove a ticker **AAPL**
- ARKK: remove a ticker **TREE**
- ARKQ: remove a ticker **SPCE**
- ARKW: remove a ticker **FSLY**
- ARKW: remove a ticker **BIDU**

5/17/2021
- ARKF: remove a ticker **MKTX**
- ARKF: remove a ticker **NVDA**
- ARKG: remove a ticker **PHR**
- ARKG: remove a ticker **TMO**
- ARKK: remove a ticker **BIDU**
- ARKK: remove a ticker **PCAR**
- ARKX: add a new ticker **BLDE**

5/14/2021
- ARKK: remove a ticker **REGN**
- ARKW: add a new ticker **DIS**
- ARKW: remove a ticker **NVDA**
- ARKW: remove a ticker **CRWD**

5/11/2021
- ARKK: add a new ticker **ONVO**
- ARKQ: add a new ticker **SPCE**
- ARKW: add a new ticker **SNOW**
- ARKW: add a new ticker **SI**

5/10/2021
- ARKQ: add a new ticker **BLDE**
- ARKQ: remove a ticker **EXPC**
- ARKQ: remove a ticker **SPCE**

5/4/2021
- ARKW: remove a ticker **SI**

5/3/2021
- ARKF: add a new ticker **STNE**

4/28/2021
- ARKQ: add a new ticker **GLEO**

4/27/2021
- ARKW: remove a ticker **SNPS**
- ARKX: remove a ticker **XLNX**

4/26/2021
- ARKQ: remove a ticker **TSM**
- ARKQ: remove a ticker **XLNX**

4/22/2021
- ARKG: add a new ticker **ZY**

4/21/2021
- ARKF: add a new ticker **PATH**
- ARKG: add a new ticker **PATH**
- ARKK: add a new ticker **PATH**
- ARKK: add a new ticker **SKLZ**
- ARKQ: add a new ticker **PATH**
- ARKW: add a new ticker **PATH**
- ARKX: add a new ticker **PATH**

4/16/202
- ARKG: add a new ticker **RXRX**

4/15/202
- ARKK: add a new ticker **TSP**
- ARKQ: add a new ticker **TSP**
- ARKW: remove a ticker **TEAM**

4/14/202
- ARKF: add a new ticker **COIN**
- ARKK: add a new ticker **COIN**
- ARKW: add a new ticker **COIN**

4/13/2021
- ARKF: remove a ticker **SPLK**
- ARKF: remove a ticker **LSPD**
- ARKF: remove a ticker **VRSK**
- ARKK: remove a ticker **TSM**
- ARKK: remove a ticker **PYPL**

4/12/2021
- ARKX: remove a ticker **TSM**

4/8/2021
- ARKW: add a new ticker **OKTA**
- ARKW: remove a ticker **ADBE**

4/7/2021
- ARKX: add a new ticker **SPFR**

4/1/2021
- ARKK: add a new ticker **TRMB**

3/30/2021
- ARKK: add a new ticker **ONVO**
- ARKW: remove a ticker **FB**

3/29/2021
- Add [ARKX](https://ark-funds.com/arkx)
- ARKK: remove a ticker **ONVO**

3/25/2021
- ARKQ: add a new ticker **SPFR**

3/24/2021
- ARKQ: add a new ticker **SPFR**

3/18/2021
- ARKW: remove a ticker **TSM**

3/16/2021
- ARKF: remove a ticker **TSM**
- ARKW: remove a ticker **OKTA**

3/15/2021
- ARKG: remove a ticker **GOOGL**
- ARKQ: remove a ticker **AAPL**
- ARKQ: remove a ticker **AMZN**
- ARKQ: remove a ticker **FLIR**
- ARKQ: remove a ticker **ROK**
- ARKW: add a new ticker **PDD**

3/11/2021
- ARKQ: add a new ticker **DDD**

3/10/2021
- ARKW: add a new ticker **RBLX**

3/9/2021
- ARKQ: remove a ticker **SPLK**

3/8/2021
- ARKK: add a new ticker **DKNG**

3/5/2021
- ARKG: add a new ticker **SEER**

3/3/2021
- ARKQ: add a new ticker **U**

3/1/2021
- ARKK: add a new ticker **BLI**
- ARKK: remove a ticker **PINS**
- ARKK: remove a ticker **SNAP**
- ARKQ: add a new ticker **SPLK**
- ARKW: remove a ticker **AAPL**
- ARKW: remove a ticker **CRM**
- ARKW: remove a ticker **BABA**

2/26/2021
- ARKQ: remove a ticker **SPLK**

2/24/2021
- ARKG: remove a ticker **HIMS**
- ARKQ: add a new ticker **AONE**

2/22/2021
- ARKK: add a new ticker **TWTR**
- ARKQ: remove a ticker **HON**

2/19/2021
- ARKK: remove a ticker **SPLK**
- ARKQ: add a new ticker **VUZI**

2/18/2021
- ARKK: add a new ticker **PLTR**

2/16/2021
- ARKG: add a new ticker **BFLY**
- ARKG: add a new ticker **ABBV**
- ARKG: add a new ticker **SGFY**
- ARKG: remove a ticker **LGVW**
- ARKQ: add a new ticker **ACIC**

2/11/2021
- ARKG: add a new ticker **CMLF**

2/10/2021
- ARKF: add a new ticker **1833**

2/8/2021
- ARKF: add a new ticker **DKNG**
- ARKQ: add a new ticker **BABA**

2/5/2021
- ARKK: add a new ticker **SNAP**

2/4/2021
- ARKF: add a new ticker **BILL**

2/1/2021
- ARKK: add a new ticker **TER**
- ARKW: add a new ticker **DKNG**

1/27/2021
- ARKG: add a new ticker **HIMS**
- ARKK: add a new ticker **BEAM**

1/26/2021
- ARKQ: add a new ticker **PCAR**
- ARKW: add a new ticker **TWTR**