---
layout: post
sitemap: true
title:  "Squat Contributes More to Total for Heavier and Elite Lifters"
title_rss:  "Squat Contributes More to Total for Heavier and Elite Lifters"
date:   2024-11-24 11:20:00 +0100
categories: posts
seo_title: "Squat Contributes More to Total for Heavier and Elite Lifters"
description: "This powerlifting data analysis shows the contribution of each lift by gender, weight class and experience. On average, the heavier and more elite you are, the more the squat contributes to your total. The data comes from the openpowerlifting database."
---

This article marks a milestone for Powerlifting in Data. This is the first crowd-sourced analysis (yes, I [take requests!](mailto:info@powerliftingindata.com)). So big thanks to Sean at [Three Paths Powerlifting](https://www.instagram.com/threepathspowerlifting) for your idea 🫶

As an experienced powerlifting coach, Sean had a hypothesis: 

<p style="font-style: italic;">For elite lifters, the squat contributes more to the total</p>

Sean also thought it would be interesting to see if there is any trend across weight classes. And I agree!

So to investigate this, I queried the [openpowerlifting.org database](https://www.openpowerlifting.org/) for: 

- Raw, SBD, IPF-affiliate meets held in the last 10 complete years (2014-2023)
- Unique by lifter and meet date
- No shows (NS) and did not qualify (DQ) excluded
- Weight class data available* and filtered by the official IPF weight classes**

### Lift Contributions for Non-Elite and Elite Lifters

Lift contribution was calculated as an average percentage of total for all meet participants that fit the above criteria.

Elite was defined as international events. So any meet where the federation was IPF, AfricanPF, EPF, AsianPF, FESUPO, NAPF, ORPF, CommonwealthPF or NordicPF. Non-elite events were not run by these federations. Indeed, there would be some elite lifters in the non-elite meets (think nationals, where elite lifters qualify for international events), but this is a sound enough distinction of the purposes of this analysis***.

As you can see, there is very little difference in the average lift contribution between Non-Elite and Elite lifters. However, for both men and women, the squat contributes slightly more to the total for elite vs non-elite lifters (0.6% for women and 0.8% for men).

Interestingly, there is a small increase in bench contribution for women (0.4%), whereas for men it's the same. In the deadlift, for elite women it contributes 1.0% less to the total than non-elite women. For elite men deadlift contributes 0.8% less than for non-elite men.

However, these differences are likely too small to be really meaningful.

##### Tip! View the charts in this post on your laptop and hover over them to see easily see the values.

<br>

<p style="text-align:center">Percentage Contribution of Each Lift to Total by Gender and Experience (2014 - 2023)</p>

<div class="custom-chart-grid">
  <div class="html-content-grid">
    {% include charts/lift-contribution-total.html %}
  </div>
  <div class="svg-content-grid">
    <img src="/assets/charts/lift-contribution-total-women-elite-non-elite.svg" alt="stacked bar chart showing average lift contribution to total for women and elite women powerlifters">
    <img src="/assets/charts/lift-contribution-total-men-elite-non-elite.svg" alt="stacked bar chart showing average lift contribution to total for men and elite men powerlifters">
  </div>
</div>

A table makes the differences a little clearer

| Group       | Squat (%) | Bench (%) | Deadlift (%) |
|-------------|-----------|-----------|--------------|
| Women       | 36.0      | 20.3      | 43.7         |
| Elite Women | 36.6      | 20.7      | 42.7         |
| Men         | 35.3      | 23.6      | 41.1         |
| Elite Men   | 36.1      | 23.6      | 40.3         |

<br>

### Lift Contributions by weight class

Things get a little bit more interesting if we break things down by weight class. While again the differences are small, they are noticeable if we plot them out. 

> There is a distinct trend upwards for squat contribution as we move up through the weight classes. 

This is true for both men and women, but the effect is the most pronounced in elite women (3.3% difference between lowest and highest weight classes), followed by elite men (2.4%), men (2.1%) and women (1.9%).

Another interesting thing we can highlight is that 

> For men, bench press contributes more to the total in heavier weight classes.

The jump is highest in elite men (1.8%). For women, bench press contribution to total is relatively constant (max 0.2% difference).

Then it follows that the biggest change we see is

> For elite men, deadlift contribution to total drops 4.2% as we move from 59kg to 120+kg weight classes

<p style="text-align:center">Percentage Contribution of Each Lift to Total by Weight Class and Experience (2014 - 2023)</p>

<div class="custom-chart-grid">
  <div class="html-content-grid">
    {% include charts/lift-contribution-total-weight-class.html %}
  </div>
  <div class="svg-content-grid">
    <img src="/assets/charts/lift-contribution-total-women-WC-non-elite.svg" alt="stacked bar chart showing average lift contribution to total for non elite women powerlifters by weight class">
    <img src="/assets/charts/lift-contribution-total-women-WC-elite.svg" alt="stacked bar chart showing average lift contribution to total for elite women powerlifters by weight class">
    <img src="/assets/charts/lift-contribution-total-men-WC-non-elite.svg" alt="stacked bar chart showing average lift contribution to total for non elite men powerlifters by weight class">
    <img src="/assets/charts/lift-contribution-total-men-WC-elite.svg" alt="stacked bar chart showing average lift contribution to total for elite men powerlifters by weight class">
  </div>
</div>

Again, a table makes the differences a little clearer. Remember you can inspect the charts and see the values if you are using a laptop (or flip a larger phone sideways). Then hover on/tap the weight class you're interested in.

| Weight class     | Squat (%) | Bench (%) | Deadlift (%) |
|------------------|-----------|-----------|--------------|
| 47kg Women       | 35.0      | 20.5      | 44.6         |
| 47kg Elite Women | 35.4      | 20.6      | 43.9         |
| 84+ Women        | 36.9      | 20.4      | 42.7         |
| 84+ Elite Women  | 38.7      | 20.8      | 40.5         |
| 59kg Men         | 34.4      | 22.9      | 42.7         |
| 59kg Elite Men   | 35.3      | 22.8      | 42.0         |
| 120+kg Men       | 36.5      | 24.5      | 39.0         |
| 120+kg Elite Men | 37.7      | 24.6      | 37.8         |

<br>

### So what does this mean for you? 
From a coaching or training perspective, likely not a lot. However, it might help you spot an opportunity to bring up a lagging lift. 
I would tread very carefully here, as there are many other factors that determine lift contribution for an individual lifter (for example relative limb and torso lengths). 

It's also worth keeping in mind that the information presented here are just averages. Lifter-specific data is, and always will be, king when it comes to coaching decisions.

It is interesting though, right? 🤓



<br>
<p style="font-size: 10px;">*Most notably with this criterion, points-based meets are excluded (for example The Sheffield). </p>
<p style="font-size: 10px;">**Women: 47, 52, 57, 63, 69, 76, 84, 84+kg Men: 59, 66, 74, 83, 93, 105, 120, 120+kg</p>
<p style="font-size: 10px;">***In the future, it could be useful to define Elite as a total per weight class. Maybe that would amplify the small effect we see here. Using a weighted average for by weight class for the aggregation could also amplify the effect</p>