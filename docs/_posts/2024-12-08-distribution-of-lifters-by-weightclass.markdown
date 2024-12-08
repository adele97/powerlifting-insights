---
layout: post
sitemap: true
title:  "Distribution of Power<wbr>lifters by Weight Class"
title_rss:  "Distribution of Powerlifters by Weight Class"
date:   2024-12-08 12:00:00 +0100
categories: posts
seo_title: "Distribution of Power<wbr>lifters by Weight Class"
description: "This article answers the question: Which weight classes in powerlifting contain the most lifters? The data for this analysis comes from the openpowerlifting database."
---


Take yourself to a powerlifting meet, and you get a pretty strong impression of the most popular weight classes. The 83kg and 93kg men can have multiple platforms each, while the 47kg, 52kg, 84kg and 84+kg women are often squeezed on to one. 

In this article we put that observation to the test by showing the actual distribution of powerlifters by weight class.

In order to make these charts, I queried the [openpowerlifting.org database](https://www.openpowerlifting.org/) for: 

- IPF-affiliate meets held from 1st January to 30th November 2024
- Unique lifters per weight class
- Data NOT split by division (junior, masters etc.)
- All equipment and event types included

Where weight class value was not present in the database, the weight class was inferred from the lifter's recorded weigh-in weight. Further, lifters that competed in two weight classes are counted twice: once per weight class.


### Distribution as a percentage of all lifters

As seen in a [previous post]({{ "/posts/2024/10/13/growth-by-gender-and-age.html" | relative_url }}), powerlifting is a sport dominated by men, but growing rapidly among women.

So in the first instance I wanted to show the distribution of weight classes as a proportion of all lifters, to give an impression of the sport overall.

The two largest weight classes are the 93kg and 83kg men, with 15.2% and 14.5% of lifters respectively. This is followed by 105kg men with 11.2% and 74kg men with 9.8%.

The largest women's weight class, the 69kg class, comes in at position number 5 with just 6.6% of lifters.

Interestingly, the heaviest women's class, the 84kg+, is larger than the equivalent class in the men, the 120kg+, with 3.6% of lifters compared to 3.2%. 
This perhaps lends a bit of support to the addition of a women's weight class at the heavier end. This is an idea I find very interesting, and will explore in more detail in an upcoming post.


##### Tip! View the charts in this post on your laptop and hover over them to see easily see the values.

<br>

<div class="custom-chart-grid">
  <div class="html-content-grid">
    {% include charts/distribution-lifters-weightclass-sex-all.html %}
  </div>
  <div class="svg-content-grid">
    <img src="/assets/charts/distribution-lifters-weightclass-Women-all.svg" alt="bar chart showing the distribution of female powerlifters by weight class as a percentage of all lifters">
    <img src="/assets/charts/distribution-lifters-weightclass-Men-all.svg" alt="bar chart showing the distribution of male powerlifters by weight class as a percentage of all lifters">
  </div>
</div>


### Distribution as a percentage of lifters of the same sex

We get a slightly different impression of the demographics of powerlifting if we look at the distribution of lifters as a percentage of lifters of the same sex.

For both men and women, the top four weight classes contain a generous majority of lifters (75.4% for men, 67.1% for women). 

At the lighter end, we see almost the same distribution with 3.0% and 7.5% for the 47kg and 52kg women, and 3.1% and 7.3% for the equivalent classes of 59kg and 66kg men.

The heavier end is where things get interesting. As mentioned, the 84kg+ class is slightly larger than the 120kg+ class. 
But when we look at this distribution by gender, we see that 22% of women are in the heaviest two classes, whereas for men this figure is 13.4%.


<div class="custom-chart-grid">
  <div class="html-content-grid">
    {% include charts/distribution-lifters-weightclass-sex.html %}
  </div>
  <div class="svg-content-grid">
    <img src="/assets/charts/distribution-lifters-weightclass-Women.svg" alt="bar chart showing the distribution of female powerlifters by weight class as a percentage of all female lifters">
    <img src="/assets/charts/distribution-lifters-weightclass-Men.svg" alt="bar chart showing the distribution of male powerlifters by weight class as a percentage of all male lifters">
  </div>
</div>

In the next post, we will look at the distribution of weight classes by region. Stay tuned!

<br>

### Got something else you'd like to see?

Then you can [send an email](mailto:info@powerliftingindata.com), or [DM me on instagram](https://www.instagram.com/powerliftingindata/).