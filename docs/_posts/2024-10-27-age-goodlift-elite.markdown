---
layout: post
title:  "Elite Power<wbr>lifters Peak at Age 30"
date:   2024-10-27 08:59:23 +0100
categories: posts
seo_title: Elite IPF male and female powerlifters reach peak strength at at age 30 according to historical data
seo_description: This data analysis uses the openpowerlifting database to find the age at which elite powerlifters reach peak strength. This 30 years old for both men and women in all years studied.
---

For this week's analysis, I wanted to see if there was any relationship between a lifter's age and goodlift points.
Say what you want about the goodlift formula (or Wilks or DOTS), but this really is the best measure we have to compare lifters across gender and weightclasses and as an extension, identify broader trends in powerlifting.
(There is also some serious [statistical power](https://www.powerlifting.sport/fileadmin/ipf/data/ipf-formula/IPF_GL_Coefficients-2020.pdf) behind how these formulas are put together.)

That said, the results of this analysis shocked even me at the consistency across gender and time period.

> At the elite level, powerlifters reach their peak around age 30. This is true for both men and women.

So first, a quick definition of elite. In this analysis, I looked at meets where the federation is the IPF. So basically World Championships across all age divisions in the respective year. 
I further limited the search to Raw SBD events. I then created a scatter plot from the resulting data.

If you're not familiar with scatter plot, it's simply a way to visualise two qualities of something to see if there is any relationship between those two qualities. In this case, the age and goodlift points of a lifter. Each lifter in the sample is represented as a yellow dot.
Then, if a relationship looks like it is present, you can conduct a regression analysis to better highlight this relationship. The result of the regression* is shown by the grey line.

To verify the results, I did the same analysis for men and women for the years 2023, 2018 and 2013.

In five of the six charts below, you can see a peak in the grey line around age 30. The analysis for women in 2013 is inconclusive as there was insufficient data (read: not enough women competing at that time 🥲)

Another interesting observation which I would cautiously make, is that strength in men seems to drop off faster between the ages of 30 and 50 than it does for women, who see a more linear reduction in strength after age 30.

<div class="custom-chart-grid">
  <div class="html-content-grid">
    {% include charts/elite-age-goodlift-scatter-all.html %}
  </div>
  <div class="svg-content-grid">
    <img src="/assets/charts/elite-age-goodlift-scatter-Men2023.svg" alt="scatter plot age vs goodlift elite men 2023">
    <img src="/assets/charts/elite-age-goodlift-scatter-Men2018.svg" alt="scatter plot age vs goodlift elite men 2018">
    <img src="/assets/charts/elite-age-goodlift-scatter-Men2013.svg" alt="scatter plot age vs goodlift elite men 2013">
    <img src="/assets/charts/elite-age-goodlift-scatter-Women2023.svg" alt="scatter plot age vs goodlift elite women 2023">
    <img src="/assets/charts/elite-age-goodlift-scatter-Women2018.svg" alt="scatter plot age vs goodlift elite women 2018">
    <img src="/assets/charts/elite-age-goodlift-scatter-Women2013.svg" alt="scatter plot age vs goodlift elite women 2013">
  </div>
</div>

What does this mean for you? If you're above 30, should you just give up? Absolutely not! The benefits of powerlifting extend far beyond reaching the podium at the World Championships 😉


<br>
<p style="font-size: 10px;">*The regression method used is LOESS (locally estimated scatterplot smoothing)</p>