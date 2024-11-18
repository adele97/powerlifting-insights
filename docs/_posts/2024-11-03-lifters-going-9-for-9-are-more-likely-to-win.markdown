---
layout: post
sitemap: true
title:  "Powerlifters That Go 9/9 Are 32% More Likely To Win"
title_rss:  "Powerlifters That Go 9/9 Are 32% More Likely To Win"
date:   2024-11-03 11:59:23 +0100
categories: posts
seo_title: "Powerlifters That Go 9/9 Instead Of 7/9 Are 32% More Likely To Win"
description: "This data analysis uses the openpowerlifting database to show that lifters who go 9 for 9 are 32% more likely to win than going 7 for 9. The most commonly missed lift is the third bench press"
---

Prevailing powerlifting wisdom tells us that successfully completing all lifts in a powerlifting meet, aka going "9 for 9", is the best way to have a successful meet.
Not just in terms of maximising your chances of a spot on the podium, but also for the mental benefits of achieving what you came for.

So this week, I wanted to put the first part of that assumption to the test. Is it really better to go nine for nine when chasing a win? Or is that YOLO deadlift actually a good idea?

First up, I started with a simple distribution* of winners at each number of successful attempts. And what do you know, I was surprised.
Even at the elite** level, there are more winners going 8/9 or 7/9 over 9/9. Huh?

<div class="custom-chart">
  <div class="html-content">
    {% include charts/distribution-winners-by-successful-attempts-all.html %}
  </div>
  <div class="svg-content">
    <img src="/assets/charts/distribution-winners-by-successful-attempts-all.svg" alt="bar graph showing the distribution of winners by successful attempts of all lifters in the sample. most winners go 8 for 9">
  </div>
</div>
<div class="custom-chart">
  <div class="html-content">
    {% include charts/distribution-winners-by-successful-attempts-elite.html %}
  </div>
  <div class="svg-content">
    <img src="/assets/charts/distribution-winners-by-successful-attempts-elite.svg" alt="bar graph showing the distribution of winners by successful attempts of elite lifters in the sample. most winners go 8 for 9">
  </div>
</div>

This stumped me for a few minutes until I realised that lifters that go 9/9 are a special breed, and are probably just simply out-numbered. So I did the visualisation again to answer the question:

> Out of all lifters that achieve X number of successful attempts, what percentage of those get first place?

This confirms our prevailing powerlifting wisdom

<div class="custom-chart">
  <div class="html-content">
    {% include charts/winners-by-successful-attempts-ls.html %}
  </div>
  <div class="svg-content">
    <img src="/assets/charts/winners-by-successful-attempts-ls.svg" alt="bar graph showing the percentage of winners by successful attempts. Of lifters that go 9 for 9, 28.5% take first place">
  </div>
</div>

In short, for every successful lift you add to your meet performance you increase your chance of winning. This effect is strongest when going from 8/9 to 9/9, although the jump from 7/9 to 8/9 is also significant. So we can say

> Going from 8/9 to 9/9 in a powerlifting meet increases your chance of winning by 17%. Going from 7/9 to 9/9 increases it by 32%


To round out the analysis, I asked the obvious follow-up question. Which lift is missed the most? Perhaps surprising to some, it's not the YOLO deadlift (although that came in second). It's actually the YOLO bench, and by a significant margin.

<div class="custom-chart">
  <div class="html-content">
    {% include charts/most-commonly-missed-lifts.html %}
  </div>
  <div class="svg-content">
    <img src="/assets/charts/most-commonly-missed-lifts.svg" alt="a bar chart showing that third attempt bench press is the one most often missed with a count of 16000, followed by third attempt deadlift with 9500 and third squat at 6500. The data source is IPF affiliate meets 2014-2023">
  </div>
</div>

What does that mean for you? Same as always. Make a meet day plan with your coach and stick to it. Listen to your body (not your ego) and focus on expressing on the platform 100% of what your body has on that day. 

Oh yeah, and a 2.5kg jump on your RPE 9.5 second attempt bench is probably enough 😉


<br>
<p style="font-size: 10px;">*The data used in this post is for meets held in the last 10 (complete) years, where there were at least 10 lifters competing in a weight class. This reduces the influence of chance (although it does not eliminate it), while still admitting enough data for the analysis to be useful. As always, the data set is from <a href="https://www.openpowerlifting.org">openpowerlifting.org</a></p>
<p style="font-size: 10px;">**elite are meets where the IPF runs it. This consists mostly World Championships, although there are others</p>
