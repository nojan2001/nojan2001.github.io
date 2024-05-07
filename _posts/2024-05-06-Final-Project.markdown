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
  <div class='row'>
    <div class='column'>
            <h2>Introduction</h2>
            <p>
                In late March of 2020, a significant shift was made to the everyday lives of people across the world. The spread of Covid-19 was in it's early stages, but still spreading at a rapid rate. Many countries decided to implement a series of actions in order to prevent any further infection, and one of the most widely used preventative actions was that of isolation. This was because of the nature of how the virus was able to spread from person to person. Therefore, states were issuing different social distancing actions, also known as stay-at-home orders. This meant that governments required all individuals to stay at home, with the exception of essential activities, essential government functions and essential businesses and operations, meaning that all non-essential business and operations must cease (source: https://www2.illinois.gov/sites/coronavirus/Resources/Pages/ExecutiveOrders.aspx#:~:text=STAY%20AT%20HOME%20%E2%80%94%20All%20individuals,with%20employees%20working%20from%20home.)
                <br>
                However, with these stay-at-home orders being issued across different states, a growing concern was also raised by researchers and victim service providers regarding a potential increase in the amount and/or severity of domestic violence cases (source: https://icjia.illinois.gov/researchhub/articles/a-short-term-analysis-of-domestic-violence-and-sexual-assault-victim-services-following-the-illinois-covid-19-stay-at-home-order/). 
                <br>
                So, with this dichotomy in mind, the article will set out to investigate the impact that the nation-wide "stay-at-home" order had on the development of domestic violence related crimes in Chicago. It will have its main focus on Chicago in the state of Illinois, as the estimate of domestic violence towards men (1 in 4, or 25.9%) and women (1 in 3, or 41.5%) were on the higher end of the spectrum, when comparing with the general trend in the U.S (sources: https://ncadv.org/state-by-state and https://worldpopulationreview.com/state-rankings/domestic-violence-by-state).
            </p>
            <h3>Relevant Facts</h3>
            <h4>What is domestic violence?</h4>
            <p>
                Domestic violence in the state of Illinois includes the following; (1) Physical abuse, (2) Harassment, (3) Intimidation of a dependent person, (4) Interference with personal liberty and (5) Willful deprivation (source: https://www.womenslaw.org/laws/il/restraining-orders/orders-protection/basic-info/what-legal-definition-domestic-violence).
                <br>
                The definition for what makes a crime specifically constitute as a crime of domestic violence, is when the aggressor and the victim of the crime are either family or members of the same household (source: https://www.criminaldefenselawyer.com/resources/criminal-defense/domestic-violence/domestic-violence-illinois-penalties-defense).
            </p>
            <h4>What is the meaning of a "stay-at-home" order in Illinois?</h4>
            <p>
                These types of orders have different meanings across different states in the U.S. Specifically in Illinois, it is defined as such:
            <br>
                <blockquote cite="https://www.illinois.gov/government/executive-orders/executive-order.executive-order-number-10.2020.html">
                    STAY AT HOME — All individuals must stay at home, with exceptions for essential activities, essential government functions, and essential businesses and operations. All non-essential business and operations must cease, aside from Minimum Basic Operations. Business can continue with employees working from home. Local government units across the state must halt all evictions, and gatherings of more than 10 people are prohibited.
                </blockquote>
            </p>
            <h2>The history of domestic violence related crimes in Chicago</h2>
            <p>
                ...
                <br>
            </p>
            <figure>
                <iframe src="/intro-bar-chart.html" width="100%" height="400px"></iframe>
                <figcaption>Figure 1: Yearly development of drug-related crimes, y axis is crimes commited per year. Hover over bars for more detail  </figcaption>
            </figure>
            <h2>The 2020 positive deviation</h2>
            <p>
                When looking at the crime frequency by district throughout the years in Figure 2, we see that the changes are not equal for each district. <br>
                In areas like Ingleside, Bayview and Richmond, the decline since 2009 is much more gradual and varies quite a bit throughout time; its crime frequency even jumps above the 2009 peak in some years. An interesting thing to note here is that the percent difference compared to 2009 for a lot of these districts start to significantly change at year 2015, with decreases of minimum 50% and greater. 
                <br>
                <br>
                Another example is the Northern district, which declines a bit from 2009 - 2012, recovers to near peak status in 2013, and finally declines again. 
                Its percentage wise difference finally lands at a decrease of 36%, which is smaller than the other ones mentioned. <br>
                The biggest contributors to the total crime frequency decline, as seen in absolute values, are the districts; Mission, Southern and Tenderloin. Their numbers, in 2009 are; 1484, 2022 and 4795. The next biggest contributor is Nothern at 794.
                Interestingly, these already begin to decrease significantly, percentage wise, around year 2011. Some variance is again observed, and there also seems to be some kind of larger decrease around year 2015, although less dominant than in the previous districts. <br><br>
                The years 2009-2011 and around 2015 seem to be worth looking at in further detail.
            </p>
            <figure>
                <iframe src="/choropleth-map-2.html" width="100%" height="450px"></iframe>
                <figcaption>Figure 2: Yearly development of drug-related crimes, by district. Hover over areas for detail. Percent Difference is the difference in percent for each year compared to the value in 2009.
                </figcaption>
            </figure>
      <h2>Development of drug crimes by drug</h2>
            <p>
                Figure 3 depicts the yearly development in the drug/narcotics category, but this time, it is categorized by drug type. It can quickly be seen that the significant contributors are Heroin, Meth, Marijuana, Base/Rock Cocaine and Cocaine. Of these drug types,Base/Rock Cocaine is by the far the biggest contributor in terms of arrests from 2003 to 2010. Right after 2009, a significant drop can be seen. This, coupled with a smaller decrease of Marijuana at the same time, could explain the big drop that is seen in figure 1 and 2 during that time period.
                The only drug which seems to not be affected by 2009 is Meth, which actually trends upwards until about year 2014.<br> <br> 
                The 5 drugs mentioned beforehand all experience some sort of drop around 2015, except Heroin, which would explain the other decreases seen in figure 2.
            </p>
            <figure>
                <iframe src="/Bokeh fixed.html" width="100%" height="500px"></iframe>
                <figcaption>Figure 3: Yearly development of drug-related crimes, divided by drug type. y axis for each year depicts the sum of crimes for the specific drug in the arrest description, from category 'POSSESSION', 'SALE', 'TRANSPORTATION'. Click on the drug labels to add/remove drug data from plot </figcaption>
            </figure>
            <h2>Reasons behind changes</h2>
            <p>
                At a first glance, the data shows a general downtrend of drug-related crime arrests. Sorting by district and drug type, various trends shows up, but the major downtrend seems to occur after 2009. One important thing to keep in mind however, is that the data does not necessarily explain the reason behind these trends. For instance, we can see that Base/Rock Cocaine decreases drastically, but not why that might've happened? A reason could be that the supply had simply dwindled, meaning there would be less users to arrest. This would, however, contradict the general trend overall in the US, as per this article (2), which shows an overall increase in drug-related deaths.
                <br><br>
                An alternative explanation could be that less arrests are made, for various reasons. As per this article (1), a new police chief was appointed in 2011 for San Francisco. This change brought about both a downsizing of the previous narcotics department, and a prioritization of drug user treatment coupled with leniency on arrests. Although this change was in 2011, another article (3) also points towards a general change in how to approach drug-related issues. Article (3) speeks about an overall change in mentality in order to destigmatize addiction, by arguing for how "body-autonomy" should apply for all people including drug-users. <br><br>

                Even though some of the official changes in policy were publicized after the 2009 decline, the cultural mindset shift could perhaps have started even before 2009, permeating the public opinion, leading to a unofficial leniency on drug related crimes. This possible shift was then enhanced through official policy change, leading to further decline in possession arrests for certain drug types, coupled with some arrests seemingly being replaced with alternatives such as treatment options or possibly even no action at all as per the described "Pro-Drug Culture"

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


