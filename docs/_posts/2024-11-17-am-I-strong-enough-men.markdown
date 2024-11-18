---
layout: post
sitemap: true
title:  "Am I Strong Enough To Compete? Men's Edition"
title_rss:  "Am I Strong Enough To Compete? Men's Edition"
date:   2024-11-17 11:20:00 +0100
categories: posts
seo_title: "Am I Strong Enough To Compete? Distribution of men's lift performance in first meets by weight class"
description: "This data analysis plots the distribution of men's lift performance in first meets by weight class. The data comes from the openpowerlifting database."
---

Last week, we answered the question "Am I strong enough to compete?" using data from [first meets done by women]({{ "/posts/2024/11/10/am-I-strong-enough-women.html" | relative_url }}). This week it's the men's turn.

<p style="font-style: italic;">And spoiler alert: once again the answer is yes, you are strong enough to compete.</p>

This analysis uses IPF-only data from the [openpowerlifting.org data set](https://www.openpowerlifting.org/). The event type is limited to SBD (bench only for example is excluded), and equipment type to Raw.

Using this data, I plotted the distribution of the best lift for powerlifters at their first meet using [box plots](https://www.jmp.com/en_nl/statistics-knowledge-portal/exploratory-data-analysis/box-plot.html). I included all lifters under 40 whose first meet was after 1st January 2010. This time period struck the right balance between having enough data, and it being relevant to today's lifters. 

I further limited the definition of "first meet" to lifters where their first meet where was a Raw meet. Some lifters start out in Equipped, then move to Raw, so to include their first Raw meets would be misleading, since they have already competed in Equipped.

Lastly, all men's weight classes were plotted, including the 53kg, which is limited to Juniors and Sub Juniors.

On each plot, the yellow boxes show the performance of the middle 50% of all lifters in the sample. So if your current PR is in that range then congrats you're in the middle of the pack.

Above the top edge of the yellow box to the line is the top 25% of lifts, and below the bottom edge of the yellow box to the line is the bottom 25% of lifts. The dots outside the lines are the outliers.
That means that those lifts don't really fit the general distribution of the data (but they still represent real people that stepped on the platform!)

Taking a look at these plots, you can see that the range of strength on the platform for all weight classes is very large. Let's look a little closer at the 83kg class

- 50% of best squats are between 153kg* and 195kg, the non-outlier range is 90kg to 258kg
- 50% of best bench presses are between 100kg and 130kg, the non-outlier range is 55kg to 175kg
- 50% of best deadlifts are between 185kg and 228kg, the non-outlier range is 123kg to 290kg

What does this mean for you? Stop putting off your first meet. "Am I strong enough?" is the wrong question. "What can I learn from competing?" is a better one.

##### Tip! View these plots on your laptop and hover over the yellow boxes to see easily see the values.

<br>

<p style="text-align:center">Distribution of best of each lift at powerlifters' first meets (Men, 2010 - present)</p>

<div class="custom-chart-grid">
  <div class="html-content-grid">
    {% include charts/distribution-lifts-first-meet-men.html %}
  </div>
  <div class="svg-content-grid">
    <img src="/assets/charts/box-plot-first-meet-53-men.svg" alt="box plot showing distribution of first meet attempts for 53kg men">
    <img src="/assets/charts/box-plot-first-meet-59-men.svg" alt="box plot showing distribution of first meet attempts for 59kg men">
    <img src="/assets/charts/box-plot-first-meet-66-men.svg" alt="box plot showing distribution of first meet attempts for 66kg men">
    <img src="/assets/charts/box-plot-first-meet-74-men.svg" alt="box plot showing distribution of first meet attempts for 74kg men">
    <img src="/assets/charts/box-plot-first-meet-83-men.svg" alt="box plot showing distribution of first meet attempts for 83kg men">
    <img src="/assets/charts/box-plot-first-meet-93-men.svg" alt="box plot showing distribution of first meet attempts for 93kg men">
    <img src="/assets/charts/box-plot-first-meet-105-men.svg" alt="box plot showing distribution of first meet attempts for 105kg men">
    <img src="/assets/charts/box-plot-first-meet-120-men.svg" alt="box plot showing distribution of first meet attempts for 120kg men">
    <img src="/assets/charts/box-plot-first-meet-120plus-men.svg" alt="box plot showing distribution of first meet attempts men over 120kg">
  </div>
</div>



<br>
<p style="font-size: 10px;">*Values not in increments of 2.5kg are usually conversions from pounds (most likely in this case) or a record attempt.</p>