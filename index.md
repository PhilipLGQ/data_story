---
layout: page
title: Cryptocurrencies in Quote
subtitle: Evolution of Cryptocurrencies Topics and Sentimental Influence on Cryptocurrencies Price
bigimg: img/head2.png
---
## History of Cryptocurrency
#### What is Cryptocurrency?


<script src="//cdn.wordart.com/wordart.min.js" async defer></script>
<div style="width: 800px; height: 800px;" data-wordart-src="//cdn.wordart.com/json/tuhs2fh26usd"></div>

Cryptocurrency is quite a prevailing topic in the recent 5 years and we can hear not only business people but also many layouts talk about it. But this concept was largely constrained itself only in a small group of computer scientists one decade ago. After it exerted influence on the price of Graphics and underwent huge price fluctuations, people were becoming more and more familiar with this newly developed concept with different understandings and behavior. 

A cryptocurrency, crypto-currency, or crypto is a collection of binary data which is designed to work as a medium of exchange. However, the attributes of cryptocurrency are quite ambiguous, especially in the property of decentralization, which means that it’s issued by the central bank. This leads to the fact that the currency has no national force to support it, the price can be more sensitive for many reasons. Recall that in the stock market, sentiment towards a specific stock can be a huge factor of its price, so we wonder whether it applies the same for the cryptocurrency price. Equipped with the quotation dataset, we may be able to have a research into it. But before going into the influence of people’s sentiment, let’s first start with analyzing in what sense people are talking about the crypto currency. 


## Quotations per Year and Topics Shifts 
#### What topics about Bitcoin are popular in Quotebank, what contents are included in each topic? & How does the trend of topics about Bitcoin change over time?

From the quotation dataset, we find the distribution of quotations about crypto currency during different time periods.

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="550" src="plot/scatterplot_lack_of_correlation.html"></iframe>

We can observe that people are more likely to discuss it from the end of 2017 to the middle of 2018. Before that time, there were no more than approximately 250 quotations per month, which corresponds to the fact that there were only a small number of people who were familiar with this concept at that time. After the huge breakout around the beginning of 2018, the number of quotations decreased to a stable level around 500 per month. At that time, even layouts were actually very much aware of the concept and although the number of quotations underwent a sharp deacy, it still had much attention. 

Notice that there is a huge peak around the beginning of 2018, so we paid special attention to this period by taking it along in the following analysis. 

Since there are a lot of discussions about the crypto currency during the past five years, we are wondering how topics about crypto currency change over time? We summarize the hottest topics over different years. 

<img src="img/varroa_annotated.png">

From the result, we can see that the topic shifts significantly over different years and we can generally observe how crypto evolves during the past five years. In 2015, Bitcoins started to pop up and people were realizing the value of Bitcoin in the realm of payment methods. It demonstrates the very beginning of blockchain technology, especially Bitcoin, in the public realm. In 2016, more cryptos were coming into the market and economic system more deeply, including Ethereum, also one of the new cryptos and the hottest one in 2016. Etheruem received more discussions due to a new kind of blockchain technology used for it and it shows right after the beginning of Bitcoin, the development in blockchain technology developed very fast within one year. At the same time, crypto companies were urged to expand the influence of crypto by looking for financial institutions to support them. Also from the topic, we can observe there are interest conflicts between banks and crypto companies. 


## Sentiment Analysis
#### What sentiment/attitude does each topic present, how does politician/researcher comment on Bitcoin differently? & Does sentiment/attitude have a correlation with the fluctuation of Bitcoin price generally and for each topic?

Now let’s take a look at people’s sentiment towards cryptos. We divide different periods basically by one year except for the time period around the beginning of 2018. 

We first make a very general analysis over all quotations.
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

<div class="myban">
    <img src="web_img/general_pos.png" />
    <img src="web_img/general_neg.png" />
</div>
<div class="myban">
    <img src="web_img/general_neu.png" />
    <img src="web_img/general_comp.png" />
</div>

From the general analysis, we find that more people have a positive attitude towards crypto than people who have a negative attitude.   

Then we take a closer look at different periods for our purpose to figure out how different sentiment may have an effect on the bitcoin price.

<div class="myban">
    <img src="web_img/time_positive.png" />
    <img src="web_img/time_negative.png" />
</div>


<div class="myban">
    <img src="web_img/time_neu.png" />
    <img src="web_img/time_comp.png" />
</div>

- From compound score stats, we can clearly see that there exists a valley point of the mean value, 50% percentile (median), and 75% percentile during the event period, this reveals that the distribution is less right-skewed, we can confirm this by examining the compound store histogram and the score stats of the event period. The histogram shows that the difference of the left section (generally negative) and the right section (generally positive) is smaller. The score stats also show that the percentage of negative and neutral quotations both reach a summit, whereas the percentage of positive quotations clearly reduces. Besides, we can catch a general sentiment trend from 2015 to 2020 by examining the line graphs: **speakers in QuoteBank are losing their positive comments towards crypto-related topics**.

- From positive score stats, we can see that the percentage of positive quotations is at the highest in 2015, then steadily declines and reaches a lowest point in the event period, although the percentage bounces in 2018 & 2019, it still drops in 2020's quotations. The positive score mean, median, and 75% percentile are consistent with this trend, except for the mean reaching the valley point in 2020. However, we notice that the most positive quotation happens to occur in the event period. In the histogram we also notice there exists more very positive quotations (positive score > 0.6) than any other period both numerically and proportionally, this hints a polarized sentiment trend during this period.

- From negative score stats, we can see that the percentage of negative quotations greatly increases in 2016 and then gradually increases to the highest during the event period. Although slightly decreasing later, it still remains at highs. The negative score means 75% percentile follows this trend. An interesting point is that over 50% of quotations have no negative sentiment and the 75% percentile is less than 0.1, this means that the level of negative sentiment is relatively low.

- From neutral score stats, we can see that the percentage of neutral quotations fluctuates among different periods, lowest in 2016 and highest in the event period. Combining the former analysis, quotations are becoming more neutral throughout the years (generally rising mean and the quantiles), and shows a polarized sentiment pattern (lowest neutral score in the event period, and increasing proportion of very biased (neutral score < 0.4) quotations).


**AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA**










Clearly, in terms of the average death rate, all states are roughly equal: it's a nation-wide problem. **Every year, roughly half of the bee population is decimated**, be it in California or Minnesota. But each state doesn't have the same bee population so what about the raw counts?

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="500" allowfullscreen="true" src="plot/yearly_loss_of_colonies_unit.html"></iframe>

We notice something interesting: **California, Texas and North-Dakota experience much more collapsed colonies**. What makes those states so special?


The fact is that beekeepers rely less on honey making, and more on **migratory beekeeping**. It represents now up to **50% of their revenue**. They pack their hives, mount them on trucks and scout the US throughout the year to pollinize fields, among which[^6]:

- **Almonds** in **California** (February)
- **Alfalfa**, **clover** and **sunflowers** in **North Dakota** (June / July)
- **Pumpkins** in **Texas** (October)

<img src="img/alfalalafa.jpg">

This migratory beekeeping explains the high death-count: the colonies die in _those_ places, because that's where they spend most of their life.

This way of renting out hives and transporting them across an entire continent incurs high stresses on the bees, weakening them and exposing them to environmental parameters they are not used to. Additionally, now that bees can travel throughout the entire USA, their pest can as well. This is exactly how the Varroa Destructor came to the USA/Europe in the first place, emigrating from Asia in the 70's[^7].

The main event of this migratory beekeeping is the blooming of California's almond orchards in February, gathering 31 billion honeybees within one single state[^6].

## The life of an American bee in February
#### An almond love story

Strapped on lorries, more than a million hives arrive in California around Valentine's day. Their little dwellers will work hard for the next few weeks in the hundred of thousands of hectares of almond orchards in Central Valley. Buzzing from flower to flower, they play an essential role in pollinating the almond trees. Those orchards produce about 80% of the world almonds and it's one of the main crop grown in the state[^almond_almanac]. The work of the honeybees in the field bring back the beekeepers **250 to 290 millions dollars** annually. But since we have shown that bees are dying *en masse*, how does this impact the almond production using [data](https://quickstats.nass.usda.gov/results/2373C039-2CFF-3744-A554-328E6A79BD39) from the USDA?

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="500" src="plot/california_almond.html"></iframe>

First, we can see that the bearing area is strictly increasing. This reinforces the idea that the industry has become more and more popular (and lucrative). Yet, the almond production doesn't always follow the trend. What's happening in those years? Are almond trees suddenly extremely unproductive or does this show environmental problems?

>California almond growers are once again being stung by a shortage of honeybees[^lack_bee]. _Los Angeles Times_, 2005

The first **plateau from 2002-2005** is then due mostly to a lack of pollinators. The beekeeping community was overwhelmed and not all almond growers could find bees to work in their fields. As the demand was high, this made the price of pollinators skyrocket. Many unconvinced beekeepers jumped on the migratory beekeeping train and new honeybee management practices were introduced[^bee_practice].

Problem solved, right? Not really, the production **dropped again in 2009** and has not been faring so well between **2011-2015**. Are the bees to blame _again_?! It turns out that weather is the main culprit this time. California was especially exposed to drought and there are many report of almond growers not being able to irrigate their orchards[^drought].

As the state will surely experience more frequent and severe droughts, there will be an impact on the almond agriculture. Almond growers need to continue working hand-in-hand with the beekeeping community and run experiments on new varieties of more resistant, less water-consuming trees to ensure its perennity[^almond_almanac].

## Bees-ness
#### World-wide honey trade

Let's now focus on the other main revenue of a beekeeper: **honey**. Often consumed locally, honey has become a raw material exported throughout the world. But how is this precious resource exported and imported around the globe? We give a look at honey trade using [data](http://www.fao.org/faostat/en/#data/TM) from the **Food and Agriculture organization of the United Nations (FAO)**.

<figure>
    <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="550" allowfullscreen="true" src="exportations_graph/main/html/honey_graph.html"></iframe>
    <figcaption>Click on countries in order to see important links between them through years.</figcaption>
</figure>

By toggling between the imports and exports we can identify a first trend. There are countries that **export a lot**: China, Argentina, Ukraine and India and those that **import a lot**: USA, Germany, Japan. Can we find a way to cluster the countries? To do so we devise a new value called the **Honey Capacity** by letting it be the total amount of available honey in a country. For each nation, the capacity is computed as the _sum between its honey production and its imported honey_. In order to compare the countries, we also compute their **import** and **export ratios with respect to their capacity**.

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="620" src="plot/beezness_plot.html"></iframe>

At the end of the animation, we can actually observe not 2 but 3 different clusters of countries:
- The countries which **export** the greater part of their honey production (such as Argentina and Ukraine)
- The countries which **import** the greater part of their honey (such as the United Kingdom, the USA and Japan)
- The countries which **use** the greater part of their honey (such as China)

This leads us to observe that the world is split between honey producers and consumers. Western countries seem to have production issues in the last decades while other countries became big exporters. This clear trend has emerged during the animation: developed countries that were able to **produce enough honey** for their own consumption **can no longer do so** and have to rely on other nations to satisfy their local demand.

## Shedding the light on dirty honey tricks
#### On the (hyper-)productivity of beehives

With such a juicy market at hand, are all countries playing fair and square or are some squeezing more out of their beehives and trading partners than they should? In order to check that we look at the production of honey using [data](http://www.fao.org/faostat/en/) from the FAO. As studies show, the **average beehive produces from 10 to 40 kg of honey annually**[^9] and this plausible range is represented in green.

<figure>
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="650" src="plot/scatterplot_beehives_production.html"></iframe>
    <figcaption>Some data points are bigger to highlight their behavior: China, India, the USA, France and Switzerland.</figcaption>
</figure>

We see that a few countries, e.g. India, are well under the average production. Indeed, India has its own kind of honeybee (the _Apis Cerana Indica_), and they do not have the same rate of production[^10]. Most other countries, like France, Switzerland or the USA, seem to have a plausible honey production. However, we note that some countries (Ukraine, Latvia, Belarus, Rwanda, etc.) are way off, and show impossible production rates. We notice that three of them were in the USSR and show these counts since their independence in 1991 (they appear in 1992 in the graph). This behavior can be explained by either dubious internal counts or non-official/missing data, especially for African countries[^africa_no_data].

<img src="img/apiscerana.jpg">

But we are still missing the elephant in the room. **China shows a strange behavior**. It starts in 1990 by being well into the plausible zone, but then slowly climbs out of it. From 2005 to 2017, the number of **beehives only increased by 10%**, whereas its **honey production jumped by more than 80%**. Something fishy is happening here... Is this _hyper_-productivity phenomenon happening in other countries as well?

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="650" src="plot/honey_productivity.html"></iframe>

<div class="withSidenote" markdown="1">

Two bright red dots appear since the beginning of the animation, in Canada and Australia. At first, we were wondering if beekeepers were feeding Maple syrup and Vegemite, respectively, to their bees to increase their productivity. It turns out that the wide meadows and longer days allow for more productive foraging and a higher yield[^beekeeping_canada].

<img src="img/vegemite.jpg">

So let's focus on what is going on in Asia. As we mentioned, their productivity boomed in the recent years to fill in the gap left by other bees around the developed world. But is it really possible to increase the productivity to this extent or did we uncover something? **Honey adulteration** is an old tale finding its root in the 70's. During the 21<sup>st</sup> century, this is has become a main concern as more than a quarter of the world honey is of questionable authenticity, rising up to 50% for Asian honey[^adulterated_honey]. The main practice consists of **cutting honey with cheap high-fructose syrup**. It is a constant struggle for food administrations as it is not only hard but expensive to detect. This lead to recent temporary bans and tariffs from the EU and the USA[^fake_honey]. But Chinese honey smugglers always found ways to flood the market with cheap, adulterated honey **using neighboring countries as proxies**.

## Don't support Winnie the Pooh[^winnie_pooh]
#### Help your local beekeepers!

As greedy industrials with no concerns for the economy keep dumping adulterated honey on the market, local beekeepers struggle to keep up[^honeygate]. Juggling with **dying bees**, **mite infections**, **unfair competition** and **migratory beekeeping** to survive, we think a way to help is to **support your local beekepers**. By buying local, you provide them the means to face those adversities and anyway you eat enough adulterated honey in processed food products.

<figure>
    <img src="img/Bee-hiding.jpg">
    <figcaption>My people need you: support me <a href="https://freethebees.ch/en/">@FREETHEBEES</a>, a Swiss charity fighting for sustainable honey culture.<br />Thank you for your engagement!</figcaption>
</figure>

## References
