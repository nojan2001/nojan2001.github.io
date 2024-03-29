---
layout: post
title:  "A deeper look at San Francisco's drug problem"
date:   2024-03-26 23:50:39 +0100
categories: jekyll update
---
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
.flex-container {
  display: flex;
}

.flex-container > div {
  margin: 2px;
  padding: 2px;
}
</style>
</head>
<body>
    <div class="flex-container">
        <div class="column">
            <h2>Introduction</h2>
            <p>
                In San Francisco, it is evident from the crime data, that drug related crimes was a consistent problem throughout the early 2000's. This notion does seem to follow the overwhelming trend of drug related problems, that pertains to the whole country. However, what made this particular category of crimes in San Francisco interesting, was the sudden drop around 2009/2010. When conducting a bit of research, this drop appears even more peculiar, as it seems San Francisco is having a growing and evermore critical problem related to drug-use (especially when considering the introduction of Fentonyl in recent years). 
                Therefore, we set on to investigate what might have caused this sudden drop in drug related crimes, by both investigating the different types of arrests made within this umbrella category, as well as looking at the locations of the different hot-spots through the years, but in particular around 2009 and 2010.
            </p>
            <h3>The yearly development of drug-related crimes</h3>
            <p>
                As can be seen from the bar-graph, for the first two years (2003 - 2004) the number of crimes laid relatively steady around 10k, from which it began to slowly rise from 2005 until 2009 with an approximate total increase in crimes of 3k. However, in the span of just two years (2010 - 2011) this peak of about 12k suddenly declines to nearly half, which does appear to be quite drastic. Another drastic drop worth noticing is the one in 2017 - 2018, where it also decreases from about 3k to a little less than half, in only one year.
            </p>
            <iframe src="/intro-bar-chart.html" width="100%" height="300px"></iframe>
            <h2>Development of drug crimes by location</h2>
            <p>
                When looking at the crime frequency by district throughout the years, we see that the changes are not equal for each district.
                In areas like Ingleside, Bayview and Richmond, the decline since 2009 is much more gradual and varies quite a bit throughout time; its crime frequency even jumps above the 2009 peak in some years. An interesting thing to note here is that the percent difference from 2019 for a lot of these districts start to significantly decrease at year 2015, with decreases of minimum 50% and greater.
                Another example is the Northern district, which declines a bit from 2009 - 2012, recovers to near peak status in 2013, and finally declines again.
                Its percent difference finally lands at a decrease of 36%, smaller than the others mentioned.
                The biggest contributors to the total crime frequency decline, as seen in absolute values, are the districts; Mission, Southern and Tenderloin. Their numbers, in 2009 are; 1484, 2022 and 4795. The next biggest contributor is Nothern at 794.
                Interestingly, these already begin to decrease significantly, percentage wise, at year 2011. Some variance is again observed, and there also seems to be some kind of larger decrease around year 2015, although less dominant than in the previous districts.
            </p>
            <iframe src="/choropleth-map.html" width="100%" height="300px"></iframe>
            <h2>Development of drug crimes by location</h2>
            <p>
                DEEZ
            </p>
            <iframe src="/Bokeh_plot.html" width="100%" height="300px"></iframe>
        </div>
    </div>
</body>

