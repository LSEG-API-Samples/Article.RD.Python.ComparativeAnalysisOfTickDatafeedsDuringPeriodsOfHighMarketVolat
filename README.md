# Article.RD.Python.ComparativeAnalysisOfTickDatafeedsDuringPeriodsOfHighMarketVolat

## <a id="overview"></a>Overview
The aim of this research is to analyse the FX data offerings from LSEG – the Blended Rate (TRB), FXAll Pricestream data (FXV) and our contributor data (Super RIC). These data sets have differing methodologies and sources to accommodate for a wide range of use cases and accurately reflect the different market tiers that exist in Foreign Exchange. This means that the LSEG data offering can provide a bespoke fit to our clients’ specific requirements and the markets they operate in to maximise accuracy.

While the Super RIC generally reflects the overall market price with indicative pricing and will serve the needs of most market participants, such as a trader eyeballing the market, the Blended Rate and Pricestream data offers pricing derived from real market activity and offers tick level granularity. These feeds reflect the most accurate price in the market and react instantly in highly volatile periods. This will be important as an input for client pricing calculation, high frequency traders and other market participants who are interested in high frequency price updates both for liquid and illiquid currency pairs.

We will use various metrics, such as mid-price, spreads, and realized variance to compare the data sets and show the strength of the Refinitiv FX data offering during specific times of high volatility. This research will show the users of this data how each data set reacts to a particular market move as well as the picture of the market that each data set displays.

The Article comprises of four main sections. In section 1, we will discuss the differences between Refinitiv FX data venues. Further, we will introduce tick data ingestion and aggregation process for all markets using Refinitiv's latest RD Library API. Section 3 will describe a FX market comparison use-case with a developed market currency, such as EUR and GBP. Finally, we will explore TRB, FXV and Super RIC market movements in emerging markets currencies, such as ZAR and SGD. In this analysis we will show how the Blended Rate and Pricestream data help to avoid the lags during sudden price movements and offer a noiseless pricing feed.

## <a id="disclaimer"></a>Disclaimer
The source code presented in this project has been written by Refinitiv only for the purpose of illustrating the concepts of creating example scenarios using the Refinitiv Data Library for Python.

***Note:** To [ask questions](https://community.developers.refinitiv.com/index.html) and benefit from the learning material, I recommend you to register on the [Refinitiv Developer Community](https://developers.refinitiv.com)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

- A Refinitiv Data Libraries license that has API access 
- Tested with Python 3.7 and 3.9
- Packages: see inside the notebook
- RD Library for Python installation:  '**pip install refinitiv-data**'


  
## <a id="authors"></a>Authors
* **Haykaz Aramyan, Jason Ramchandani, JJ Chalmers**
