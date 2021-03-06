[<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/banner.png" width="888" alt="Visit QuantNet">](http://quantlet.de/)

## [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/qloqo.png" alt="Visit QuantNet">](http://quantlet.de/) **FRM_2_SteadyCoinStudy** [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/QN2.png" width="60" alt="Visit QuantNet 2.0">](http://quantlet.de/)

```yaml

Name of QuantLet:   'FRM_2_SteadyCoinStudy'



Published in:       'DEDA_Class_2019WS'



Description:       "Selecting the coins for analysis\n
		    1) Analysis period: 2017 Jan - 2018 Nov\n
	            2) Input data: weekly market capitalization data of the top 200 coins\n
	            3) Selecting criteria:\n
                        3.1) Top 15 coins according to the average market cap\n
                             Result: 15 coins ['BTC' 'ETH' 'XRP' 'BCH' 'LTC' 'EOS' 'ADA' 'XLM' 'MIOTA' 'TRX' 'BSV' 'USDT' 'DASH' 'BNB' 'NEO']\n
                             Market Cap share of the selected coins: 0.899\n
                        3.2) Consistent appearance in the top 200 chart based on the market cap\n
                             Result: 28 coins ['BCN' 'BTC' 'BTS' 'DASH' 'DCR' 'DGB' 'DGD' 'DOGE' 'ETC' 'ETH' 'FCT' 'GNT' 'LSK' 'LTC' 'MAID' 'NEO' 'REP' 'SC' 'STEEM' 'STRAT' 'USDT' 'WAVES' 'XEM' 'XLM' 'XMR' 'XRP' 'XZC' 'ZEC']\n
                             Market Cap share: 0.849\n
                        3.3) coins satidfy 1) and 2) above\n
                             Result: 8 coins  ['BTC' 'DASH' 'ETH' 'LTC' 'NEO' 'USDT' 'XLM' 'XRP']\n
                             Market Cap share of the selected coins: 0.795\n
                     4) Final Data Input\n
                             ['BTC' 'ETH' 'XRP' 'BCH' 'LTC' 'EOS' 'XMR' 'NEO' 'MIOTA' 'DASH' 'ETC' 'ZEC']\n
                             Market Cap share of the selected coins: 0.88"



Keywords:           Cryptocurrency, Market Capitalization, Coin Selection, weekly Capitalizations, Plotly animation 



Author:             Qi Wu, Seokhee Moon



Submitted:          Sun December 08 2019 by Qi Wu, Seokhee Moon



Input :             'total_market_cap_17-19.csv, 1718hourlyReturn_withZEC.csv'



Output:             'The change of Market Cap information over time in .html format'

```

### [IPYNB Code: FRM_2_SteadyCoinStudy.ipynb](FRM_2_SteadyCoinStudy.ipynb)


automatically created on 2020-01-31