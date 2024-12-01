---
layout: post
sitemap: true
title:  "10 year Growth of Highest Totals"
title_rss:  "10 year Growth of Highest Totals"
date:   2024-12-01 08:00:00 +0100
categories: posts
seo_title: "10 year Growth of Highest Totals"
description: "This article plots the highest powerlifting totals per yer per weight class from 2015 to 2024. The data for this analysis comes from the openpowerlifting database."
---

As we established in a [previous post]({{ "/posts/2024/10/06/ten-year-growth-rate-by-age.html" | relative_url }}), powerlifting has been growing steadily over the last 10 years.

With that growth, we have seen totals being pushed at all levels, with what feels like new world records being set at every international meet.

But is this true for all weight classes?

So this week we plotted the highest totals by weight class over the last 10 years.

In order to make this plot, I queried the [openpowerlifting.org database](https://www.openpowerlifting.org/) for: 

- Raw, SBD, IPF-affiliate meets held in the last 10 years (2015-2024)
- Data split by weight class*
- Data NOT split by division (junior, masters etc.)

Where weight class value was not present in the database, the weight class was inferred from the lifter's recorded weigh-in weight

### Women's weight classes

For all women's weight classes, the highest total achieved in 2024 is greater than those achieved in 2015. The largest increase was for the 84kg class with a jump of 23.6% (523.5kg in 2015 vs 647kg in 2024).
The largest single year jump in that class was by Daniela Melo who totalled 601.5kg in the 2018 IPF World Classic Powerlifting Championship (a 10.9% jump on the highest 2017 total). Amanda Lawrence came second in that event with a total of 591kg and has gone on to dominate that class in the following years.

It is also worth noting is the rapid growth in the totals of the newest weight classes of 69kg and 76kg introduced in 2021. Which can't really be a surprise as these classes are absolutely stacked at the elite level (think the likes of Agata Sitko, Lya Bavoil, Carola Garra, Jessica Buettner and Karlina Tongotea)


##### Tip! View the charts in this post on your laptop and hover over them to see easily see the values.

<br>
<p style="text-align:center">Highest total per year per weight class Women (IPF 2015-2024)</p>


<div class="custom-chart">
  <div class="html-content">
    {% include charts/2015-2024-highest-totals-by-weightclass-women.html %}
  </div>
  <div class="svg-content">
    <img src="/assets/charts/2015-2024-highest-totals-by-weightclass-women.svg" alt="a multi line chart showing the Highest total per year in all Women's weight classes (IPF 2015-2024)">
  </div>
</div>


### Men's weight classes

In the men's classes, the growth in totals has been more moderate, although still outstanding. The largest increase was observed in the 74kg class with a jump of 17.8% (712.5kg in 2015 vs 839kg in 2024).

Interestingly, it is in the men's classes that we see the only fall in the highest total, in the 59kg class. The highest total for this class was 670kg in 2015 and in 2024 it sits at 638kg. 
However, Wascar Carpio put in a stunning performance at the World Championships this year, and I am excited to see what he can come up with at the Sheffield in January 2025.

The 120kg class has stayed relatively flat with a 3.2% jump from 2015 to 2024 (947.5kg vs 978.5kg). The highest totals for this year in this class have been set by Bobb Mathews, who is a light 120kg weighing it at 106.25 when he totalled 978.5kg at Classic Raw Open Nationals in Reno in March.
So we could be set to see totals in the 120s explode in the next few years as Mathews fills out the weight class.

<p style="text-align:center">Highest total per year per weight class Men (IPF 2015-2024)</p>


<div class="custom-chart">
  <div class="html-content">
    {% include charts/2015-2024-highest-totals-by-weightclass-men.html %}
  </div>
  <div class="svg-content">
    <img src="/assets/charts/2015-2024-highest-totals-by-weightclass-men.svg" alt="a multi line chart showing the Highest total per year in all Men's weight classes (IPF 2015-2024)">
  </div>
</div>



<br>

### Got something you'd like to see?

Then you can [send an email](mailto:info@powerliftingindata.com), or [DM me on instagram](https://www.instagram.com/powerliftingindata/).




<br>
<p style="font-size: 10px;">*Women: 47, 52, 57, 63, 69 (from 2021), 72 (until 2020), 76 (from 2021), 84, 84+kg Men: 59, 66, 74, 83, 93, 105, 120, 120+kg</p>