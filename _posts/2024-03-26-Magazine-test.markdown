---
layout: post
title:  "A deeper look at San Francisco's drug problem"
date:   2024-03-26 23:50:39 +0100
categories: jekyll update
---
<html>
<head>
    <style>
        .some-page-wrapper {
        }
        .row {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        width: 100%;
        }
        .column {
        display: flex;
        flex-direction: column;
        flex-basis: 100%;
        flex: 1;
        }
    </style>
</head>
<body>
<div class='some-page-wrapper'>
  <div class='row'>
    <div class='column'>
            <h2>Introduction</h2>
            <p>
                In San Francisco, it is evident from the crime data, that drug related crimes was a consistent problem throughout the early 2000's. However, what made this particular category of crimes in San Francisco interesting, was the sudden drop around 2009/2010. When conducting a bit of research, this drop appears even more peculiar, when considering the fact that the US have a growing drug crisis in terms of an epidemic in drug overdoses (4). 
                Therefore, we set on to investigate what might have caused this sudden drop in drug related crimes, by both investigating the different types of arrests made within this umbrella category, as well as looking at the locations of the different hot-spots through the years, but in particular around 2009 and 2010.
            </p>
            <h2>The yearly development of drug-related crimes</h2>
            <p>
                As can be seen from the bar-graph, for the first two years (2003 - 2004) the number of crimes laid relatively steady around 10k, from which it began to slowly rise from 2005 until 2009 with an approximate total increase in crimes of 3k. However, in the span of just two years (2010 - 2011) this peak of about 12k suddenly declines to nearly half, which does appear to be quite drastic. 
                <br>
                Another drastic drop worth that should be adressed is the one in 2017 - 2018, where it also decreases from about 3k to a little less than half. We believe this is due to the fact that the dataset only consists of data from about half of 2018, and therefore won't look further into why this might've occurred.
            </p>
            <figure>
                <iframe src="/intro-bar-chart.html" width="100%" height="400px"></iframe>
                <figcaption>Figure 1: Yearly development of drug-related crimes, y axis is crimes commited per year. Hover over bars for more detail  </figcaption>
            </figure>
            <h2>Development of drug crimes by district</h2>
            <p>
                When looking at the crime frequency by district throughout the years, we see that the changes are not equal for each district. <br>
                In areas like Ingleside, Bayview and Richmond, the decline since 2009 is much more gradual and varies quite a bit throughout time; its crime frequency even jumps above the 2009 peak in some years. An interesting thing to note here is that the percent difference from 2019 for a lot of these districts start to significantly decrease at year 2015, with decreases of minimum 50% and greater. 
                <br>
                <br>
                Another example is the Northern district, which declines a bit from 2009 - 2012, recovers to near peak status in 2013, and finally declines again. 
                Its percentage wise difference finally lands at a decrease of 36%, which is smaller than the other ones mentioned. <br>
                The biggest contributors to the total crime frequency decline, as seen in absolute values, are the districts; Mission, Southern and Tenderloin. Their numbers, in 2009 are; 1484, 2022 and 4795. The next biggest contributor is Nothern at 794.
                Interestingly, these already begin to decrease significantly, percentage wise, at year 2011. Some variance is again observed, and there also seems to be some kind of larger decrease around year 2015, although less dominant than in the previous districts. <br><br>
                The years 2009-2011 and around 2015 seem to be worth looking at in further detail.
            </p>
            <figure>
                <iframe src="/choropleth-map.html" width="100%" height="400px"></iframe>
                <figcaption>Figure 2: Yearly development of drug-related crimes, by district. Hover over areas for detail
                </figcaption>
            </figure>
      <h2>Development of drug crimes by drug</h2>
            <p>
                Figure 3 depicts the yearly development in the drug/narcotics category, but this time, it is categorized by drug type. It can quickly be seen that the significant contributors are Heroin, Meth, Marijuana, Base "crack" Cocaine and Cocaine. Of these drug types, "Crack" Cocaine is by the far the biggest contributor in terms of arrests from 2003 to 2010. Right after 2009, a significant drop can be seen. This, coupled with a smaller decrease of Marijuana at the same time, could explain the big drop that is seen in figure 1 and 2 during that same time.
                The only drug which seems to not be affected by 2009 is Meth, which actually trends upwards until about year 2014.<br> <br> 
                The 5 drugs mentioned beforehand all experience some sort of drop around 2015, except Heroin, which would explain the other decreases seen in figure 2. Cocaine is especially affected, as it plummets to near 0. 
            </p>
            <figure>
                <iframe src="/Bokeh_plot.html" width="100%" height="400px"></iframe>
                <figcaption>Figure 3: Yearly development of drug-related crimes. y axis for each year depicts the sum of crimes, categorized by the specific drug in the arrest description. Click on the drug labels to add/remove data from plot </figcaption>
            </figure>
            <h2>Reasons behind changes</h2>
            <p>
                At a first glance, the data shows a general downtrend of drug-related crime arrests. Sorting by district and drug type, various trends shows up, but the major downtrend seems to occur after 2009. One important thing to keep in mind however, is that the data does not necessarily explain the reason behind these trends. For instance, we can see that "Crack" Cocaine decreases drastically, but not why that might've happened? A reason could be that the supply had simply dwindled, meaning there would be less users to arrest. This would, however, contradict the general trend overall in the US, as per this article (2), which shows an overall increase in drug-related deaths. <br><br>
                An alternative explanation could also be that less arrests are made, for various reasons. As per this article (1), a new police chief was appointed in 2011. This change brought about both a downsizing of the previous narcotics department, and a prioritization of drug user treatment coupled with leniency on arrests. Although this change was in 2011, another article points towards a general change in how to approach drug-related issues. This article (3) speeks about an overall change in mentality in order to destigmatize addiction, by arguing for how "body-autonomy" should apply for all people including drug-users. 
            </p>
    </div>
  </div>
  <div class='row'>
    <div class='column'>
    <h2>References</h2>
    <p>
        (1) <cite> https://www.sfexaminer.com/news/san-francisco-drug-arrests-tumble-as-police-focus-on-serious-and-violent-crime/article_770e3b20-d694-59c4-a95d-6c3656906c40.html </cite>
        <br>
        <br>
        (2) <cite> https://www.aic.gov.au/sites/default/files/2020-05/ti578_the_opioid_epidemic_in_north_america-v2.pdf </cite>
        <br>
        <br>
        (3) <cite> https://www.nytimes.com/2024/01/31/briefing/san-francisco-addiction.html </cite>
        <br>
        <br>
        (4)
        <cite> Spencer MR, Garnett MF, Miniño AM. Drug overdose deaths in the United States, 2002–2022. NCHS Data Brief, no 491. Hyattsville, MD: National Center for Health Statistics. 2024. DOI: https://dx.doi.org/10.15620/cdc:135849 </cite>
    </p>
  </div>
</div>
</body>
</html>
