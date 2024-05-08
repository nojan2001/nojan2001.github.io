---
layout: custom_post
title:  "Did Covid-19 have an impact on Chicago's issue with crimes of domestic violence?"
date:   2024-03-26 23:50:39 +0100
categories: jekyll update
custom_css: styles
---
<head>
  {% if page.custom_css %}
    {% for stylesheet in page.custom_css %}
    <link rel="stylesheet" href="{{ site.baseurl }}/assets/css/{{ stylesheet }}.css">
    {% endfor %}
  {% endif %}

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<div class='ex1'>
            <a href="https://github.com/nojan2001/nojan2001.github.io/blob/main/final_project/final_notebook%20FINAL.ipynb">Link to GITHUB notebook </a> 
            <h2>Introduction</h2>
            <p>
                In late March of 2020, a significant shift was made to the everyday lives of people across the world. The spread of Covid-19 was in it's early stages, but still spreading at a rapid rate. Many countries decided to implement a series of actions in order to prevent any further infection, and one of the most widely used preventative actions was that of isolation. This was because of the nature of how the virus was able to spread from person to person. Therefore, states were issuing different social distancing actions, also known as stay-at-home orders. This meant that governments required all individuals to stay at home, with the exception of essential activities, essential government functions and essential businesses and operations, meaning that all non-essential business and operations must cease (1).
                <br>
                However, with these stay-at-home orders being issued across different states, a growing concern was also raised by researchers and victim service providers regarding a potential increase in the amount and/or severity of domestic violence cases (2). 
                <br>
                So, with this dichotomy in mind, the article will set out to investigate the impact that the nation-wide "stay-at-home" order had on the development of domestic violence related crimes in Chicago. It will have its main focus on Chicago in the state of Illinois, as the estimate of domestic violence towards men (1 in 4, or 25.9%) and women (1 in 3, or 41.5%) were on the higher end of the spectrum, when comparing with the general trend in the U.S (3)(4).
            </p>
        <div class="facts">
            <h3>Relevant Facts</h3>
            <h4>What is domestic violence?</h4>
            <p>
                Domestic violence in the state of Illinois includes the following; (i) Physical abuse, (ii) Harassment, (iii) Intimidation of a dependent person, (iiii) Interference with personal liberty and (iiiii) Willful deprivation. (5)
                <br>
                The definition for what makes a crime specifically constitute as a crime of domestic violence, is when the aggressor and the victim of the crime are either family or members of the same household (6).
            </p>
            <h4>What is the meaning of a "stay-at-home" order in Illinois?</h4>
            <p>
                These types of orders have different meanings across different states in the U.S. Specifically in Illinois, it is defined as such:
                <br>
                <blockquote>
                STAY AT HOME — All individuals must stay at home, with exceptions for essential activities, essential government functions, and essential businesses and operations. All non-essential business and operations must cease, aside from Minimum Basic Operations. Business can continue with employees working from home. Local government units across the state must halt all evictions, and gatherings of more than 10 people are prohibited (7)
                </blockquote>
            </p>
        </div>
            <h2>The development of domestic violence in Chicago</h2>
            <figure>
                <iframe src="\final_project\introduction-dv-plot.html" width="200%" height="450px"></iframe>
                <figcaption>Figure 1: The yearly development of reported crimes regarded as domestic violence offences in Chicago</figcaption>
            </figure>
            <p>
                As can be seen in figure 1, the year with the highest number of registered domestic violence cases was in 2013, after which it experienced a decrease, only to remain relatively stable until the shift from 2019 to 2020. During this timeperiod, a pretty noticable drop occured, of nearly 4000 less domestic violence cases in 2020 compared to the previous year. That level furthermore pertained the following years. While this decrease in 2020 showed to directly oppose the initial worries of an increase in domestic violence due to the stay-at-home order, the numbers don't appear to return to their pre-pandemic level. Therefore, it was worth to investigate further, to see whether this change could in fact be connected to the Covid-19 outbreak.
            </p>
            <figure>
                <iframe src="\final_project\dv-quarter-plot.html" width="200%" height="450px"></iframe>
                <figcaption>Figure 2: The quarterly development of reported crimes regarded as domestic violence offences in Chicago</figcaption>
            </figure>
            <p>
                From figure 2, it is evident that the general trend showed an overall increase from Q1 to Q2. The degree to how much it would increase does vary depending on the year. However, the only year where this trend is broken, and we instead see a very small decrease, is in 2020 from the first to the second quarters. The years both before and after 2020 follow the general trend of seeing an increase in domestic violence crimes between those two quarters. One can also identify that figure 1 showed only a decrease in domestic violence reports from 2020 and in the years that followed. While in figure 2, it appears as though the distribution of reportings was not similar during the whole timeframe. This is furtheron visible in figure 3, which actually shows that the drop in reportings is primarily centered around the first two months of the second quarter (i.e. April and May). One could argue that the decrease begins already during March, but the main thing to note from the 2019 and 2020 comparison, is that after the sudden drop around April, the number of domestic violence cases never reach back to its prior level. 
            </p>
            <figure>
                <iframe src="\final_project\dv-monthly-plot.html" width="200%" height="450px"></iframe>
                <figcaption>Figure 3: The monthly development of reported crimes regarded as domestic violence offences in Chicago from 2019 to 2020</figcaption>
            </figure>
            <p>
                When considering these patterns of the development of reports on domestic violence, there could be an indication of some kind of correlation to the implementation of the stay-at-home order that went into effect on March 21st (9). However, this continuous decreasing trend that can be observed in figure 3, is a clear contrast to the experiences for those working at e.g. the Illinois Domestic Violence Hotline. The hotline experienced a stark 16% increase in calls for help from 2019 to 2020, along with an increase in texts received, which in 2019 laid at only 37 when comparing it to the total of 936 texts that the hotline received in 2020 only (10).
                <br>
                <br>
                Therefore, some other factors must have had an effect on this outcome that started with the issuing of a stay-at-home order. To this end, it made sense to look at the potential area-wise differences, to understand whether there might've been a disproportionate distribution of the domestic violence related crime rate.
            </p>
            <h2>The monthly difference between the Sides of Chicago</h2>
            <figure>
                <iframe src="\final_project\Choropleth.html" width="200%" height="450px"></iframe>
                <figcaption>Figure 4: Monthly development of Domestic violence crimes, by Sides in Chicago. Hover over areas for detail. Each month in 2020 is compared percent difference wise to the same month in 2019, per the relevant Side. </figcaption>
            </figure>
               <p>
                Figure 4 shows the monthly data from January to December in 2020, divided between the Sides of Chicago (8), with a look at comparing it to the same timeperiod in 2019.
                <br>
                Generally, there does not seem to be a large deviation from January to March, although there are some small jumps in the Domestic violence counts. 
                All of the Sides end up having a slight decline in March of 2020 comparatively; The only exception here is the Central side, which ends with a slight increase.
                <br><br>
                From April to June however, 3 trends seem to be observed in the data.
                The first trend can be exemplified by observing the south-grouped sides, which reveals a initial significant jump in comparative decline for the month of April 2020.
                The decline is slightly lessened by May, and then largely tapered off by June.
                The only exception is Far Southwest side, which starts off with a rather large decline of -0.40 % in April comparatively, but falls down just as quickly the next month, ending in June 2020 with an tapered off decline of -0.25%.
                The general south-grouped trend seems to hold true for West Side and Far Noth Side as well. 
                <br>
                The second trend is seen in the North Side and Northwest Side; Almost no decline is observed in April 2020, then a sudden sharp decline in May, which already wears off in June, bringing them largely back to baseline.
                <br>
                The final third trend hold true for the Central Side only, which has an initial significant decline at -0.32% in April 2020, declining steadily by an additional -0.10% in May, and again in June.
                This is the only side which ends June 2020 with an significant difference comparatively to 2019.
                <br><br>
                The data from July to December 2020 for the Sides is observed to contain much more variance than before, with no immediate pattern emerging. Some of the Sides, such as Southwest side, deviate significantly for a single monthly period, before returning to baseline the following month(s).The sides generally end December with a decline between -0.10% and -0.30%.
                The only exceptions here is  South side, which ends at a near 0% difference, and the Central side and North Side, which deviate rather largely negatively and positively, respectively.
                <br><br>
                It seems that April through June is the timeperiod with the most pattern like deviation, with the Domestic violence counts of some Sides changing different than others.
            </p>
            <h2>Summary</h2>
            <p>
                With the lockdown initiated in March of 2020 due to the rapid spread of Covid-19, there was also a growing concern for particularly vulnerable households, and how they would respond to an imposed stay-at-home order (2). 
From our findings, it appears that there is a decline in reported crimes during the initial stages of the pandemic, which can be traced more specificly to the period of April to June of 2020, that seems to line up with the date of the stay-at-home order being issued (cite). Therefore, it seems as though Covid-19 to some extent could have had an impact on domestic abuse/violence.
<br><br>
One might be inclined to believe, that Covid-19 had a possitive effect on Chicago's domestic violence issue. However, an alternative explanation for our findings, is that the decline was simply due to under-reporting and/or resources for victims being lessened immediately in the wake of Covid-19. This article (11) support the claims of scarce resources and fear of reporting their abuser due to lack of privacy. 
It was in fact estimated that 25% of the total resources available, became unavailable as a consequence of the Covid-19 restrictions, with the majority of this reduction seen in the South-side of Chicago.
<br><br>
This relates to other sources saying that some areas seem to be impacted more severily by Covid-19, in relation to Domestic violence. This study (12) explored that idea, revealing findings that link a more significant decline in areas of predominantly black communities, mostly the South sides of Chicago. While Figure 4 depicted some significant decline in the South Sides, atleast initially, it is hard to discern whether Figure 4 has enough support to come to the same conclusion unassisted. The difference in significance, when comparing their data to ours, can be due to various factors; Perhaps they had access to more data, or looked into additional crime categories that also relates to Domestic violence. 
            </p>
</div>

<div>
    <div>
    <h2>References</h2>
    <p>
        (1) <cite> https://www2.illinois.gov/sites/coronavirus/Resources/Pages/ExecutiveOrders </cite>
        <br>
        <br>
        (2) <cite> https://icjia.illinois.gov/researchhub/articles/a-short-term-analysis-of-domestic-violence-and-sexual-assault-victim-services-following-the-illinois-covid-19-stay-at-home-order/ </cite>
        <br>
        <br>
        (3) <cite> https://ncadv.org/state-by-state </cite>
        <br>
        <br>
        (4) <cite> https://worldpopulationreview.com/state-rankings/domestic-violence-by-state</cite>
        <br>
        <br>
        (5) <cite> https://www.womenslaw.org/laws/il/restraining-orders/orders-protection/basic-info/what-legal-definition-domestic-violence </cite>
        <br>
        <br>
        (6) <cite> https://www.criminaldefenselawyer.com/resources/criminal-defense/domestic-violence/domestic-violence-illinois-penalties-defense </cite>
        <br>
        <br>
        (7) <cite> https://www.illinois.gov/government/executive-orders/executive-order.executive-order-number-10.2020.html </cite>
        <br>
        <br>
        (8) <cite> https://commons.wikimedia.org/wiki/File:Chicago_community_areas_map.svg#/media/File:Chicago_community_areas_map.svg </cite>
        <br>
        <br>
        (9) <cite> https://medium.com/gdgf/timeline-how-covid-19-unfolded-in-illinois-fc8d124ae033 </cite>
        <br>
        <br>
        (10) <cite> https://abc7chicago.com/domestic-violence-covid-statistics-2020-coronavirus/10381318/ </cite>
        <br>
        <br>
        (11) <cite>  https://www.verywellhealth.com/domestic-violence-reports-5200838 </cite>
        <br>
        <br>
        (12) <cite>  https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8414190/ </cite>
    </p>
  </div>
</div>
</body>
</html>


