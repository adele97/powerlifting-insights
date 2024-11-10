---
layout: post
sitemap: true
title:  "Am I Strong Enough To Compete? Women's Edition"
date:   2024-11-10 11:20:00 +0100
categories: posts
seo_title: "Am I Strong Enough To Compete? Distribution of lift performance in first meets by weight class"
description: "This data analysis plots the distribution of women's lift performance in first meets by weight class. The data comes from the openpowerlifting database."
---

Am I strong enough to compete? It's a question that many new powerlifters ask themselves. We are human after all, and it is a very human desire to want to belong and fit in. Being "strong enough" on the platform says "hey, I belong here!".

That's very understandable, but it's very wrong.

Powerlifting has a strong track record of welcoming new lifters of all strength levels. And here is the data to prove it.

I plotted the distribution of the best lift for powerlifters at their first meet using [box plots](https://www.jmp.com/en_nl/statistics-knowledge-portal/exploratory-data-analysis/box-plot.html). I included all lifters under 40 whose first meet was after 1st January 2010. This time period struck the right balance between having enough data, and it being relevant to today's lifters.

All active women's weight classes over the period are included, even the 72kg (which was split into 69kg and 76kg in 2021), and the 43kg (which is limited to Juniors and Sub Juniors). Men, you're going to have to wait until next week 😉

On each plot, the yellow boxes show the performance of the middle 50% of all lifters in the sample. So if your current PR is in that range then you're in good company.

Above the top edge of the yellow box to the line is the top 25% of lifts, and below the bottom edge of the yellow box to the line is the bottom 25% of lifts. The dots outside the lines are the outliers.
That means that those lifts don't really fit the general distribution of the data. But they do represent real people that showed up on the platform. And that's the real win, right?

Taking a look at these plots, you can see that the range of strength on the platform for all weight classes is very large. Let's look a little closer at the 57kg class

- 50% of best squats are between 78kg* and 105kg, the non-outlier range is 38kg to 145kg
- 50% of best bench presses are between 43kg and 60kg, the non-outlier range is 18kg to 86kg
- 50% of best deadlifts are between 100kg and 130kg, the non-outlier range is 55kg to 175kg

Tip! View these plots on your laptop and hover over the yellow boxes to see easily see the values.

What does this mean for you? Stop putting off your first meet. You are already strong enough. You already belong. And we are waiting for you to show us what you got 💪

<br>

<p style="text-align:center">Distribution of best of each lift at powerlifters' first meets (Women, 2010 - present)</p>

<div class="custom-chart-grid">
  <div class="html-content-grid">
    {% include charts/distribution-lifts-first-meet-women.html %}
  </div>
  <div class="svg-content-grid">
    <img src="/assets/charts/box-plot-first-meet-43-women.svg" alt="box plot showing distribution of first meet attempts for 43kg women">
    <img src="/assets/charts/box-plot-first-meet-47-women.svg" alt="box plot showing distribution of first meet attempts for 47kg women">
    <img src="/assets/charts/box-plot-first-meet-53-women.svg" alt="box plot showing distribution of first meet attempts for 52kg women">
    <img src="/assets/charts/box-plot-first-meet-57-women.svg" alt="box plot showing distribution of first meet attempts for 57kg women">
    <img src="/assets/charts/box-plot-first-meet-63-women.svg" alt="box plot showing distribution of first meet attempts for 63kg women">
    <img src="/assets/charts/box-plot-first-meet-69-women.svg" alt="box plot showing distribution of first meet attempts for 69kg women">
    <img src="/assets/charts/box-plot-first-meet-72-women.svg" alt="box plot showing distribution of first meet attempts for 72kg women">
    <img src="/assets/charts/box-plot-first-meet-76-women.svg" alt="box plot showing distribution of first meet attempts for 76kg women">
    <img src="/assets/charts/box-plot-first-meet-84-women.svg" alt="box plot showing distribution of first meet attempts for 84kg women">
    <img src="/assets/charts/box-plot-first-meet-84plus-women.svg" alt="box plot showing distribution of first meet attempts women over 84kg">
  </div>
</div>



<br>
<p style="font-size: 10px;">*Values not in increments of 2.5kg are usually conversions from pounds (most likely in this case) or a record attempt.</p>