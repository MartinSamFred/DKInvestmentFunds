# About Dataset

## DK Investment Funds

I created this dataset as I needed a bit of insight in the DK Investment funds universe. 

The dataset contains of 346 Danish investment funds with asset classes such as stock, bonds and mixed stock/bonds funds + a few alternatives and real estate funds. 

If you use the xlsx file: You can run part of my code for a cleaner / translated version.

If you use the csv file: cleaned to some extent and translated from Danish to English.

Code in: DKInv.ipynb

## Content

Each row in the dataset contains a Danish Investmest fund

## “Clean” columns (csv file):

0 'fund_name' : the funds organial name

1 'isin' : code of the fund

2 'currency' : fund trading currency / denomination 

3 'category' : stock, bond, mix etc.

4 'dividend' : dividend policy i.e. distributing or accumulating

5 'ann_cost' : annual cost in %

6 'rating_class' : rating of the fund

7 'risk_class' :

8 'sustainablity_class': sustainability category of the fund

9 '3y_ann_perf': % change (3 years), some annualized though 

10 '5y_ann_perf': % change (5 years) , some annualized though

11 'AUM_DKK' : AUM mill. DKK (most of them!)

12 'sharpe_ratio': sharpe ratio

13 'provider': cleaned/added provider name

14 'asset_class': cleaned/added asset class split

15 'geography: cleaned/added main investment geography


## “Raw” columns (xlsx file):

0 'Navn': Name of the fund

1 'Ticker': Ticker of the fund

2 'ISIN': ISIN code of the fund

3 'Valuta': fund trading currency / denomination

4 'Kategori': stock, bond, mix etc.

5 'Udbyttepolitik': dividend policy i.e. distributing or accumulating 

6 'Årlig omk. %: annual cost in %

7 'Rating': rating of the fund

8 'Risko': risk rating of the fund

9 'Bæredygtighed': sustainability category of the fund

10 'Belåningsgrad %': leverage (if any)

11 'Fås i månedsopsparingen': Included in monthly saving/investment feature 

12 'Antal ejere': number of ”shareholders”

13 'I dag %' : % change today

14 'I dag +/-' : price change today

15 'Seneste': latest price 

16 'Køb' : offer price

17 'Sælg' : bid price

18 'Spread %': spread in %

19 'Høj' : price high

20 'Lav' : price low

21 'Omsætning': volume traded

22 '1 d %': % change (day)

23 '1 uge %' : % change (1 week)

24 '1 måned %' : % change (1 month)

25 '3 måneder %' : % change (3 months)

26 'i år %' : % change (YTD)

27 '1 år %' : % change (1 year)

28 '3 år %' : % change (3 years)

29 '5 år %' : % change (5 years)

30 '10 år %'  : % change (10 years)

31 'AUM(mio.kr.)': AUM mill. DKK (most of them!)

32 'Standardafvigelse (%, 5 år)' : standard derivation

33 'Sharpe_ratio' : sharpe ratio

34 'Information Ratio' : information ratio

35 Tracking Error (%)' : tracking error

## Uses
Various analysis and visualization.
Practice exercises etc.
Uncleaned xlsx file is are great to practice cleaning, especially string cleaning. 

## Disclaimer
The data and information in the data set provided here are intended to be used primarily for educational purposes only. I do not own any data, and all rights are reserved to the respective owners as outlined in “Acknowledgements/sources”. The accuracy of the dataset is not guaranteed accordingly any analysis and/or conclusions is solely at the user's own responsibly and accountability.

## Acknowledgements/sources

All data is publicly available on:

BankInvest: https://bankinvest.dk/ 

C WorldWide: https://cww.dk/ 

Carnegie Invest: https://www.carnegie.dk/ 

Danske Invest: https://www.danskeinvest.dk/w/show_pages.front?p_nId=75 

Falcon Invest: https://falconinvest.dk/ 

Fundamental Invest: https://fundamentalinvest.dk/

IA Invest: https://iainvest.dk/ 

Maj Invest: https://majinvest.dk/ 

Multi Manager Invest: https://www.nordnet.dk/ 

Nordea Invest: https://www.nordeafunds.com/da

Nykredit Invest: https://www.nykreditinvest.dk/

SGD Invest: https://www.nordeafunds.com/da

SEB Invest: https://seb.dk/SEBinvest/

Sparinvest: https://www.sparinvest.dk/

Stockrate Asset Management: https://stockrate.dk/

Sydinvest: https://www.sydinvest.dk/

Wealth invest: https://wealthinvest.dk/

Dataset picture / cover photo: insung yoon (https://unsplash.com/)
