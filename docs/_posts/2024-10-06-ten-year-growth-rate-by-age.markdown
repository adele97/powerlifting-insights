---
layout: post
sitemap: true
title:  "Growth of Power<wbr>lifting by Age Group"
date:   2024-10-06 12:59:23 +0200
categories: posts
seo_title: Powerlifting age demographics by decade and growth trends by year
description: This data analysis uses the openpowerlifting database to find that 50% of powerlifters are under 25. This is relatively constant across time. Powerlifting may trend younger as those age groups are also the fastest growing
---

It's been really great to see in recent years powerlifting totals being pushed in all age divisions, especially in the juniors.
It really feels like there is a lot of young talent entering powerlifting, and consequentially pushing the sport to new heights
(some current world open records are even held by junior lifters!).

So I thought it would be fun to put that feeling to the test. What is the distribution of powerlifters by age on a global scale?

For these charts, I used the IPF-affiliate data set of [open powerlifting](https://www.openpowerlifting.org), and included all events,
for which the bulk are made up of Bench and SBD. All equipment types (eg: Equipped and Raw) are included.

Firstly, I wanted to know what the distribution of age groups participating in powerlifting meets, and to see if this has changed at all over the decades.

Visualising data is part art and part science as you want to tell something useful, but at the same time not overwhelm with too many details. So I hope I have got the mix right here.

In the last article we established that global powerlifting participation is growing rapidly. So I wanted to take that noise out of the equation, and just look at the overall breakdown of participation by age group.

What we can see if we stack age groups from youngest to oldest, is that competing in powerlifting is largely a young person's game. Across the decades, approximately 50% of those participating in meets are 25 or younger (the range is 46% to 53%).
We also see that roughly 80% of competing powerlifters are 40 or younger.

<div class="custom-chart">
  <div class="html-content">
    {% include charts/participation-by-decade.html %}
  </div>
  <div class="svg-content">
    <img src="/assets/charts/participation-by-decade.svg" alt="growth of powerlifting by age group 1970 to 2023">
  </div>
</div>

Let's drill down now into the latest data, and try to get a feel for how powerlifting is currently growing. The limitation of the visualisation we just saw, is that given that the sport is growing overall, 
the growth of the larger group can obscure the growth of the smaller groups and make it appear that these smaller groups are not growing at all (which we will see is absolutely not the case!).

Further it includes all meet nominations, so all meets from an individual lifter are included. If we are interested in growth of the sport,
it makes sense to include a lifter's first meets only (as this is a better measure of people entering the sport).

The chart below shows the average annual growth rate of powerlifting meet participation over the last 10 years, by age group. We can clearly see that for all age groups between 15 and 70 years*, the sport is growing.
The age group of 21-25 is growing the fastest with an average annual growth rate over the last 10 years of 8.8%. 
The purple dotted line is the average annual growth rate across all groups in that period which comes in at 5.9%.

<div class="custom-chart">
  <div class="html-content">
    {% include charts/growth-by-age-2013-2023.html %}
  </div>
  <div class="svg-content">
    <img src="/assets/charts/growth-by-age-2013-2023.svg" alt="average annual growth rate of powerlifting by age group 2013 to 2023">
  </div>
</div>

If we consider that age groups 16-20, 21-25 and 26-30 are above the average growth across all groups, in conjunction with the fact that they make up the bulk of current powerlifters, 
then we might see it play out that powerlifting competitions as a whole will trend younger. However, that will also depend on the longevity of this new wave of lifters in the sport.

In the next article, we will take a look at the trends of participation in powerlifting meets by gender.

<br>
<p style="font-size: 10px;">*The 71+ age group had exactly the same count of meet participants in 2013 and 2023, so the average annual growth rate really is 0.0%!</p>