---
layout: page
title: Cryptocurrencies in Quote
subtitle: Evolution of Cryptocurrencies Topics and Sentimental Influence on Cryptocurrencies Price
bigimg: img/head2.png
---
## History of Cryptocurrency
#### What is Cryptocurrency?

<script src="//cdn.wordart.com/wordart.min.js" async defer></script>
<div style="width: 500px; height: 500px; float:left" data-wordart-src="//cdn.wordart.com/json/tuhs2fh26usd"></div>
**Cryptocurrency** is such a prevailing topic that in the recent five years, not only business people but also many people from different fields were talking about it. However, the concept of cryptocurrency was largely constrained itself to a small group of computer scientists about a decade ago. After a huge wave of fluctuation on both cryptocurrency prices and graphic cards, people became more and more familiar with it and acquired different understandings about this newly developed, mysterious and state-of-art concept.

A **cryptocurrency** (crypto-currency, or crypto) is a collection of binary data which is designed to work as a medium of exchange. However, the attributes of cryptocurrency are quite ambiguous, especially the property of **decentralization**, which means that it’s not issued by any central bank. This leads to the fact that the currency has **no national force** to support it, and the price can be sensitive to many factors. Recall that in the stock market, sentiment towards a specific stock can be a huge factor to influence the price, so we wonder whether sentiment applies the same effect on the cryptocurrency price. With the help of the quotation dataset from [**Quotebank**](https://quotebank.dlab.tools/), we could explore the possibility of this idea. Before digging deeper, let’s first take a look at what people are talking about the cryptocurrency! 

## Quotations per Year and Topics Shifts 
#### What topics about Bitcoin are popular in Quotebank? What contents are included in each topic? How does the trend of topics about Bitcoin change over time?

From our quotation dataset, we find the distribution of quotations about cryptocurrency in different time periods.

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="550" src="plot/quote_dist.html"></iframe>

We can observe that people had a huge crush on cryptocurrency during the period between **the end of 2017 and the middle of 2018**. Before this period, the number of quotations was quite poor, no more than approximately 250 quotations per month, which is exactly the fact we are talking about in the [History of Cryptocurrency](#history-of-cryptocurrency). There were only a small number of people who were familiar with this concept at that time. After the huge breakout at the beginning of 2018, the number of quotations decreased to a stable level, around 500 per month. At that time, even layouts were very much aware of the concept, although the number of quotations underwent a sharp decay, it still had much attention. 

Notice that there is a huge peak around the end of 2017 and the beginning of 2018. We paid additional attention to this period by analyzing it separately in the following analysis. 

Since there are lots of discussions about cryptocurrency in the past five years, we are wondering how topics about cryptocurrency change over time? We summarize the most popular topics over different periods. We noticed that there are two topics, **Bitcoin's price** and **blockchain technology**, which are the most popular among all other topics in every period. In order to find more about the popular topics, we select several **other popular topics** in every period except them.

**Topic of 2015**

```markdown
Topic: Bitcoin is a new blockchain technology that revolutionise how payments are made by money.
```

>_"Bitcoin is here to revolutionize how payments are made. Bitcoin payments are instantaneous, 100% safe, and by far the cheapest. It will impact humanity in the same way as paper money did when it replaced gold and silver coins"_  _**--George Popescu, CEO of Backed Inc. & Partner at LunaCap Ventures**_

**Topic of 2016**

```diff
Topic 0: Smart contract is the advantage of Ethereum against Bitcoin despite they are all using blockchain technology, but Bitcoin is more secure than Ethereum.
```

>_"Our new relationship with money partners group is a huge win for Bitcoin and ethereum awareness and adoption around the world. the results we will achieve together will show other financial institutions why they should embrace digital assets and blockchain technologies"_  _**--Jesse Powell, CEO of Kraken**_

```diff
Topic 1: Bitcoin companies are look forward for financial institutions to embrace Bitcoin, whereas central banks are interested in developing their own digital money.
```

>_"China's central bank also is actively preparing to issue its digital currency, which is a positive signal for Bitcoin companies and investors. the recent devaluations of the cny has also helped to legitimize Bitcoin; this coupled with current macroeconomic crises around the world, we believe, has lead to substantial inflows of capital into Bitcoin as it is increasingly seen a safe haven asset in the eyes of local investors"_  _--**Dawei Li, CEO of CHBTC**_

**Topic of 2017 (Jan. 2017 - Sep. 2017)**

```diff
Topic: The involvement of enterprises contributes to prosperity of Bitcoin and Ethereum community
```

>_"We're honored to be able to contribute our pbft implementation to j.p. morgan's industry-leading quorum platform. having financial institutions as our primary customers meant we had to design from day one with their requirements in mind. j.p. morgan shares many of these requirements and recognized the value of adding an enterprise-grade pbft implementation to their ethereum-based platform"_  _--**Alex Liu, CEO of AMIS**_

**Topic of 2017 & 2018 (Oct. 2017 - Mar. 2018)**

```diff
Topic is about potential risks, such as price volatility, of investing in cryptocurrency, because it neither has any intrinsic value nor being backed by any kind of assets. Investors were making speculative investments in Bitcoin without fully understand its value and potential risks, which triggered the "bubble burst".
```

>_"The increase in media coverage and hype around icos and 'cryptocurrencies' , such as Bitcoin, has aroused public interest. however, the public might use these as speculative tools without full understanding of their nature and potential risks. through this series of public education initiatives, the government aims to provide the public with a correct and comprehensive understanding of icos and 'cryptocurrencies' , so that they can thoroughly assess the risks before making transactions or investment decisions"_  _--**Joseph Chan, the Under Secretary for Financial Services and the Treasury**_

**Topic of 2018 (Apr. 2018 - Dec. 2018)**

```diff
Topic 0: xrp has faster transaction time and cheaper transaction fee that Bitcoin can't really compete, which is the reason why "xrp" stand out from the crowd.
```

>_"Originally people thought it might solve a payments problem but when you have an asset like xrp that's a thousand times faster and a thousand times cheaper on a per transaction basis Bitcoin can't really compete on that level, you know an xrp transaction costs fractions of a penny and it settles in three seconds"_  _--**Brad Garlinghouse, CEO of Ripple Labs**_

```diff
Topic 1 is about "security" issues. Security refers to a share of ownership in a company—giving the shareholder a stake in the business and an interest in its profits. Most "xrp" related quotations are actually promoting knowledge about "xrp".
```

>_"I think it's really clear that xrp is not a security. xrp exists independent of ripple and it would operate even if ripple labs failed. i don't think that our ownership of xrp gives us control. saudi arabia owns a lot of oil that doesn't give them control of oil"_  _--**Brad Garlinghouse, CEO of Ripple Labs**_

**Topic of 2019**

_(In 2019, we haven't found any new topics from the quotations, but there seems to be an enduring interest in "Bitcoin" and "ethereum", which makes us curious about the content of Bitcoin/Ethereumn related quotes.)_

```diff
Topic 0 is about Bitcoin, to be more specific, its market aspects, such as the price and value of Bitcoin.
```
 
```diff
Topic 1 is about Ether. People are more interested in the technical level, e.g. the blockchain and smart contract technology.
```

**Topic of 2020 (Jan. 2020 - )**

```diff
Topic 0 is about safety-oriented asset allocation when facing the crisis, where people are seeking safe-havens (e.g. gold) for their assets, while Bitcoin is considered a risk asset.
```

>_"However, unlike traditional safe-havens (treasury notes, us dollar, swiss franc, japanese yen, gold), the Bitcoin market is a speculative one with high volatility, which might explain why they are failing to act as a safe-haven asset"_  _--**Yoni Assia, an early Bitcoin acolyte and CEO of social investment platform eToro**_

```diff
Topic 1 is about the unexpected rise and continued high Bitcoin price sparked the discussion to the potentials of Bitcoin as a safe-haven assets.
```

>_"Gold rose and stocks fell initially, but traders soon relaxed, so stocks recovered and gold fell. Bitcoin stayed high because its rise is not iran-related"_  _--**Glen Goodman, Cryptocurrency trader and author**_

From the result, we can see that the topic shifts over different years and we can generally observe how cryptocurrency evolves during the past five years. In **2015**, Bitcoins started to pop up and people were realizing the value of Bitcoin in the realm of payment methods. It demonstrates the very beginning of blockchain technology, especially Bitcoin, in the public realm. In **2016**, more cryptocurrencies were coming into the market and economic system more deeply, including Ethereum, also one of the new cryptocurrencies and the hottest one in 2016. Etheruem received more discussions due to a new kind of blockchain technology used for it and it shows right after the beginning of Bitcoin, the development in blockchain technology developed very fast within one year. At the same time, cryptocurrency companies were urged to expand the influence of cryptocurrency by looking for financial institutions to support them. Also from the topic, we can observe there are interest conflicts between banks and cryptocurrency companies. In **the first half of 2017**, Bitcoin and ETH seemed promising and many companies were willing to increase their market value of it. While in **the second half of 2017 and at the beginning of 2018**, people were becoming more aware of the potential risk of cryptocurrency. This had a coincidence in time with the huge Bitcoin price fluctuation. After the huge prosperity of Bitcoin, people cooled down a little bit and tried to take it seriously. Topic in **the rest of 2018** shows that more cryptocurrencies based on different blockchain technologies were entering the market at the time. This may be due to the security issues and the unreasonable fluctuation of price in the last period. And those topics still remained in **2019**. In **2020**, Bitcoin became the safe haven for people who talked about it. This pandemic is due to the coronavirus pandemic and geopolitical uncertainties, which is also reflected in this year's quotations.


## Like it? Or hate it?
#### Let’s take a look at people’s attitudes towards cryptocurrency! 

We divide periods annually except for the time period around the beginning of 2018. It was so popular at that time!

Let's first take a bite of people's general attitudes.
<style type="text/css">
.myban{
    width:700x;
    height:400px;
    border:1px solid #ccc;
    
}
.myban img{
    width:350px;
    height:400px;
    float:left;
}
</style>

<!--div class="myban"-->

<!--/div-->

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="550" src="plot/general_comp.html"></iframe>

(_By clicking the different tags at the top-right corner to hide the corresponding trace, you may have a clearer view!_)

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="550" src="plot/general_dist.html"></iframe>

Playing around the above plots, we find that people may have a more **“positive”** attitude towards cryptocurrency than a **“negative”** attitude.   

Then let's take a closer look at different periods and try to figure out whether different sentiments have an effect on the bitcoin price.

<div class="myban">
    <img src="web_img/time_positive.png" />
    <img src="web_img/time_negative.png" />
</div>



<div class="myban">
    <img src="web_img/time_neu.png" />
    <img src="web_img/time_comp.png" />
</div>

- From **compound score** stats, we can see that there exists a valley point of the mean value, _50%_ percentile (median), and _75%_ percentile during the event period, this reveals that the distribution is less right-skewed, we can confirm this by examining the compound store histogram and the score stats of the event period. The histogram shows that the difference between the left section (generally negative) and the right section (generally positive) is smaller. The score stats also show that the percentage of negative and neutral quotations both reach a summit, whereas the percentage of positive quotations clearly reduces. Besides, we can catch a general sentiment trend from 2015 to 2020 by examining the line graphs: **speakers in QuoteBank are losing their positive comments towards crypto-related topics**.

- From **positive score** stats, we can see that the percentage of positive quotations is at the highest in 2015, then steadily declines and reaches the lowest point in the event period, although the percentage bounces in 2018 & 2019, it still drops in 2020's quotations. The positive score mean, median, and _75%_ percentile are consistent with this trend, except for the mean reaching the valley point in 2020. However, we notice that the most positive quotation happens to occur in the event period. In the histogram, we also notice there exist more very positive quotations (_positive score > 0.6_) than any other period both numerically and proportionally, this implies a polarized sentiment trend during this period.

- From **negative score** stats, we can see that the percentage of negative quotations greatly increases in 2016 and then gradually increases to the highest during the event period. Although slightly decreasing later, it still remains at highs. The negative score means _75%_ percentile follows this trend. An interesting point is that over _50%_ of quotations have no negative sentiment and the _75%_ percentile is less than _0.1_, this means that the level of negative sentiment is relatively low.

- From **neutral score** stats, we can see that the percentage of neutral quotations fluctuates among different periods, lowest in 2016 and highest in the event period. Combining the former analysis, quotations are becoming more neutral throughout the years (generally rising mean and the quantiles), and shows a polarized sentiment pattern (lowest neutral score in the event period, and an increasing proportion of very biased (_neutral score < 0.4_) quotations).


## Speaker Portrait
#### Who talk about cryptocurrency the most? What are their attitudes towards it?

We divide people into different occupations and make an analysis based on this division. There are people with more than _300_ hundred occupations discussing cryptocurrency. We list the top _**4**_ occupations and plot the distributions in the order of total quotation numbers.

<style>
table {
margin: auto;
}
</style>

Occupation | Number of quotation
 :-: | :-: 
Businessperson | 2096 
Politacian | 1526 
Journalist | 1171 
Researcher | 1058 

We can observe that **businesspeople** have the most quotation number among all other occupations. **Politicians** come second with _1526_ quotations. **Journalists** and **researchers** are the third and fourth most frequent speakers about cryptocurrency with _1171_ and _1058_ quotations within the last five years.

We are interested in the analysis within different occupations—different perspectives of people differ with specialized skills. We focus on the top two occupations, business people and politicians. 

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="110%" height="600" src="plot/occu_compare.html"></iframe>

According to the relevant words and the representative quotations spoken by businesspeople and politicians, we have the following findings that are high associated with the detected topics:

**Politicians**

```diff
Topic 0: Government anouncements on accepting cryptocurrencies for payment has shown its adoption to cryptocurrencies.
```

>_"Cryptocurrencies are becoming increasingly accepted as forms of payment for many transactions across the state, including by government entities. the seminole county tax collector announced that the office will accept bitcoin as payment for property taxes, identification cards and license plates"_  _**--Jimmy Patronis, Florida Chief Financial Officer**_

```diff
Topic 1: Some countries are funding digital currency researches and making investments on cryptocurrencies.
```

>_"The £ 10m in funding for digital currency research demonstrates that this government is serious about making the uk an attractive destination for cryptocurrency entrepreneurs and investment. no other government has made such a positive overture to bitcoin"_  _**--Tom Robinson, a board member of the UK Digital Currency Association**_

```diff
Topic 2: Although politicians are concerned about the risk of cryptocurrencies as a "bubble", they attaches great importance to the underneath blockchain technology.
```

>_"Blockchain technology could change our world more than people imagine. bitcoin, however, could be a bubble"_  _**--Jack Ma, leader of Multinational technology conglomerate Alibaba Group**_


**Businesspeople**

**Compound scores** of businessmen and politicians tell us that the general attitude towards cryptocurrency is **decreasing**. 2015 is the most **optimistic** year for businessmen, probably because there was potential commercial interest at the very beginning of cryptocurrency. Afterward, between 2016-2018, businessmen started to **doubt** the advantages of cryptocurrency. But the sentiment changes are rather flat during the huge wave of the cryptocurrency price fluctuation. However, in 2019, businessmen were again **positive** about cryptocurrency with a large increase in the compound score but still didn’t exceed the optimistic attitude in 2015. Finally, in 2020, businessmen **lost their interest** again and become more neutral.

As for the politician, the general attitude is more neutral and flat compared with businessmen, partially because the cryptocurrency is not issued by any national institution. From topic analysis, we found that politician's quotations are highly associated with the actions taken by the government, they are more sided with the government and rarely express their own views.


## Combined analysis of quotation numbers with Bitcoin Price

The Bitcoin price can be extracted from [CoinMarketCap](https://coinmarketcap.com/currencies/bitcoin/historical-data/). We wanna know if there is a correlation between quotation numbers with the Bitcoin price.

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="550" src="plot/price_quote.html"></iframe>

This figure describes the quotation numbers and the fluctuation of Bitcoin prices simultaneously. Because there are some dates that are missing the quotations of Bitcoin, we take a period of 14 days as an analysis basis (rolling 14 days) to see the correlation. Y-axis on the left (rolling_14_close) is the Bitcoin price at the end of the 14 days period.

From the above line plots, we would initially speculate that the number of quotations may correlate with the fluctuation of Bitcoin price in a general sense, especially in the period around 2017 and 2018. Around the beginning of 2018, the quotation underwent a vast boost and this trend matches perfectly well with the bitcoin price peak around that time.

If we run a **Pearson test**, we have a p-value (_1.70e-23_) which is far smaller than _0.05_, meaning that the Bitcoin price and 14-day rolling mean of the number of quotations do **positively correlate** with each other, with a small correlation _**r = 0.24**_. Based on this fact, we will find out the period which gives the largest correlation _abs(r)_ with _**p << 0.05**_.

We further look into the correlation over different time periods.

| Period | P Value | r |
| :------: |:---: | :---: |
| 01/2015 - 12/2015 | p > 0.05 | not correlated |
| 01/2016 - 12/2016 | p > 0.05 | not correlated |
| 01/2017 - 09/2017 | p < 0.05 | -0.703 |
| 10/2017 - 03/2018 | p < 0.05 | 0.563 |
| 04/2018 - 12/2018 | p < 0.05 | -0.239 |
| 01/2019 - 12/2019 | p < 0.05 | -0.286 |
| 01/2020 - 03/2020 | p > 0.05 | not correlated |

We summarize in the below:
- The **general** Pearson test on Bitcoin price and 14-day rolling mean of the number of quotations give **a small but positive correlation** between these two indicators. This means that from a larger scale over the periods when Bitcoin price rises, the 14-day rolling mean of the number of quotations has a tendency to increase correspondingly. Generally, we could say that the fluctuation of Bitcoin price does affect speakers' interest in crypto-related topics. However, from the line plots and separated Pearson tests we could still see that this general correlation acts poorly for 2015 - 2016, 2019 - 2020. But if we take a closer look at the curve trend, in 2015-2016 both Bitcoin price and the number of quotations remains at low quantity. This may reveal that cryptocurrency is not widely known to the public and it has not yet become a popular topic.

- Separated analysis on Jan. 2017 - Sep. 2017 and Apr. 2018 - Dec. 2018 gives us **a negative correlation** result which counters our expectation. By checking the line plots, there exists **a possible delay effect** between the indicators: if we right shift the rolling mean curve, then we could possibly get a more positive correlated result. This delay effect may reflect speakers' comments and attitudes towards the cryptocurrency market, and they later bring impact to the Bitcoin market since named speakers are most influential.

- The Bitcoin price **increases rapidly** in 2017, and suddenly **drops** in 2018, and the number of quotations fluctuates correspondingly. Pearson tests in 2017 - 2018 and the event period confirms this trend. 

## Bitcoin price and sentiment correlation

Finally, we are curious about whether there is a correlation between Bitcoin price and people’s sentiment towards it. To do this, we ran a sentiment analysis on all the quotations over different time periods and analyzed the correlation with positive, negative, neutral, and compound scores.

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="110%" height="600" src="plot/price_compound.html"></iframe>

First, we present different scores and bitcoin prices over time. The y-axis on the left (Close) is the Bitcoin price at the end of each day. Although it may seem that they have no correlation from the line plot, the general Pearson test shows us the general sentiment actually has a **weak positive correlation** (_**r=0.1033039125275**, **p=2.102025314648e-05**_) with the fluctuation of Bitcoin price. By checking the line plot, we speculate that this correlation comes mainly from the event after 2017. Now we conduct separated correlation testing within different time periods to test our hypothesis.

| Period | P Value | r |
| :------: |:---: | :---: |
| 01/2015 - 12/2015 | p > 0.05 | not correlated |
| 01/2016 - 12/2016 | p > 0.05 | not correlated |
| 01/2017 - 09/2017 | p < 0.05 | 0.442 |
| 10/2017 - 03/2018 | p < 0.05 | 0.268 |
| 04/2018 - 12/2018 | p < 0.05 | 0.168 |
| 01/2019 - 12/2019 | p < 0.05 | 0.260 |
| 01/2020 - 03/2020 | p > 0.05 | not correlated |

We make a summarization in the below:
- The result of **general analysis** on compound, positive, and negative sentiment scores reveals that crypto-related quotations' sentiment does **have a correlation** with the Bitcoin price. However, the Pearson _r_ for all four sentiment scores is relatively small, which means the **correlations are not strong**. 

- Separation analysis on the **compound score** and the **positive score** shows a similar **positive correlation** from 2016 to 2019, whereas the **negative score** shows a **negative correlation** only in 2016, 2019, and 2020. This correlation pattern may suggest that a positive score determines the compound score correlation more than the negative score.

- Separation analysis on the **neutral score** shows that in each separation during 2017-2018, the neutral score is **negatively correlated** to Bitcoin price. Combining the fact that quotations are heavily distributed in these separations, this suggests that polarized cryptocurrency quotations may correlate to a decrease in Bitcoin price, which means the Bitcoin price would affect speakers' neutrality.

## Conclusions
### The evolution story of cryptocurrency, Bitcoin in the last 5 years

The first cryptocurrency, Bitcoin, was founded in 2009 and has gone through a very short time in the economic market compared with stocks. But for Bitcoin itself, ten years is really a long time because of the fluctuation of the price and quick topic shifts about it. In 2015, people were interested in the investment potential of it and in 2016 and 2017, it attracted more companies for investigation. Also, the cryptocurrency companies were seeking cooperation with the government at that time. In 2017 and 2018, due to the crazy fluctuation of the Bitcoin price, people had more doubts about its security of it. Since then the issue of security and the urgent need to have more stability led to more cryptocurrencies based on different technologies popping up. As for the speaker occupation, it’s natural for businessmen to discuss cryptocurrency, but politicians have the second quotation numbers in the dataset. It reveals the fact that it attracted more attention from society and also had more influence overall. Considering the short history of cryptocurrency, we would be really amazed by the influence. 

Given the analysis above, we may reach the answer to the puzzle stated at the very beginning of our data analysis. In general, **there seems to be a weak correlation between the bitcoin price and people’s sentiment towards it**. If we take the compound score over different time periods seriously, we may easily reach the conclusion that Bitcoin prices are actually correlated with people’s sentiment, which also makes sense because people will complain or praise Bitcoin if the price is fluctuating and indeed people’s attitude will influence the prices in turn. 

There are many reasons that can count for the weak correlation. One of the biggest factors is that there are many **unobserved covariates** that will affect speakers’ attitudes and the Bitcoin price simultaneously. Given the limitation of Quotebank dataset, we cannot avoid such problems. One way to deal with it is to introduce other datasets and complex economic theory, which is too much for our analysis. Also, the way we process the Bitcoin price and the division of time period will also have an influence on the final analysis of the sentiment correlation result. 

Finally, are we in a position that is safe to have our conclusion? Equipped with quotation from [**Quotebank**](https://quotebank.dlab.tools/), the answer would most probably be “no”. Even with more data and more complex theories about how to find the correlation between price and people’s sentiment towards it, we may also largely not be able to have any conclusion. After all, data science is just a way to reinforce what we have at the very first beginning: we follow a theory and its concept to quantify our real world and then do the analysis. But the connection between the concept and the reality is rather weak and we don’t actually know whether we can quantify to have some result especially in the realm of society. This fundamental ontology is not so valid for us to really have sound conclusions about anything. And would this be the end of our data story? We would say yes…and No!!!
