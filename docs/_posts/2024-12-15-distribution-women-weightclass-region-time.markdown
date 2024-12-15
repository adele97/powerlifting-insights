---
layout: post
sitemap: true
title:  "Regional Differences in Weight Class Distribution of Female Power<wbr>lifters"
title_rss:  "Regional Differences in Weight Class Distribution of Female Powerlifters"
date:   2024-12-15 12:00:00 +0100
categories: posts
seo_title: "Regional Differences in Weight Class Distribution of Female Power<wbr>lifters"
description: "This article answers the question: Which weight classes in powerlifting contain the most lifters? The data for this analysis comes from the openpowerlifting database."
---

In [last week's article]({{ "/posts/2024/12/08/docs/distribution-of-lifters-by-weightclass.html" | relative_url }}), we looked at the current distribution of powerlifters by weight class.

In the case of the men, it was roughly as you would expect, with the middle weight classes the post popular, and reducing participation as you approach the lightest and heaviest classes.

For the women, that trend wasn't as clear-cut, and we saw more participation in the heavier classes (22% of female powerlifters are in the heaviest two classes, for men the figure is 13%).
This observation lends support to the introduction of a heavier women's weight class, however it does not paint the full picture.

For example, is the story the same for every region? Casual observation may lead us to suspect that in Asia, the lighter weight classes have higher representation than the heavier ones.

Further, is this over-representation in the heavier classes consistent or becoming more pronounced over time? If the IPF were to consider adding an additional class, you would want to see that the over-representation is something structural that needs correcting and is not simply a one-off.

So in this article we will attempt to answer these questions by plotting the distribution of the women's weight classes by region in different time periods.

In order to make these charts, I queried the [openpowerlifting.org database](https://www.openpowerlifting.org/) for: 

- IPF-affiliate meets held in 2014, 2019 and from 1st January to 30th November 2024 
- Unique lifters per weight class (inferred from weigh-in weight)
- Data NOT split by division (junior, masters etc.)
- All equipment and event types included
- Region classification done by meet location (lifter country is often missing from the data set)
- Meets where the Federation is the IPF are excluded (eg: World Championships), so we can say with more confidence that the participating lifters are from that region

Region is not a field in the open powerlifting database, so I have used the country and region mapping [from the UN](https://unstats.un.org/unsd/methodology/m49/)


### Distribution by Year and Region

The first thing I'd like to highlight is that in 2024, Europe seems to dominate powerlifting participation amongst women. Part of this is due to the [removal of USAPL as an IPF-affiliate](https://www.powerlifting.sport/about-ipf/news/news-detail/ipf-votes-to-expel-usapl) at the end of 2021. The reduction in participation in the Americas between 2019 and 2024 is hard to miss!

Another reason for Europe's apparent domination, and this probably the biggest limitation of this analysis, is that data for the other regions is simply less complete (coordinating global meet result submission is no easy task!)

That said, I do think the sample is large enough in Asia, to say that the region certainly trends lighter than Europe and the Americas. However, I would not put any exact numbers on it. Same in reverse for Oceania. The region tends to trend a little heavier, but we have insufficient data to put an exact number on it. 

It is interesting to note in Asia that participation in the 84kg and 84+kg classes is very close. As we saw last week, the heaviest men's class is about half the size of the second heaviest, and I think it's reasonable to expect a similar split for the women. So even in a region where we see an overall trend lighter, we still see the 84+ class over-represented.

For Africa I would draw zero conclusions. The data is too incomplete. The big jump we see in participation in 2024 is from the Commonwealth Championships. So a majority of lifters from that meet would not be from the region.


##### Tip! View the charts in this post on your laptop to see each region's charts side-by-side

<br>

<div class="custom-chart-grid">
  <div class="html-content-grid">
    {% include charts/lifter-count-by-region-time-women.html %}
  </div>
  <div class="svg-content-grid">
    <img src="/assets/charts/lifter-count-wc-2014-Africa.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in Africa in 2014">
    <img src="/assets/charts/lifter-count-wc-2019-Africa.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in Africa in 2019">
    <img src="/assets/charts/lifter-count-wc-2024-Africa.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in Africa in 2024">
    <img src="/assets/charts/lifter-count-wc-2014-Americas.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in the Americas in 2014">
    <img src="/assets/charts/lifter-count-wc-2019-Americas.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in the Americas in 2019">
    <img src="/assets/charts/lifter-count-wc-2024-Americas.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in the Americas in 2024">
    <img src="/assets/charts/lifter-count-wc-2014-Asia.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in Asia in 2014">
    <img src="/assets/charts/lifter-count-wc-2019-Asia.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in Asia in 2019">
    <img src="/assets/charts/lifter-count-wc-2024-Asia.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in Asia in 2024">
    <img src="/assets/charts/lifter-count-wc-2014-Europe.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in Europe in 2014">
    <img src="/assets/charts/lifter-count-wc-2019-Europe.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in Europe in 2019">
    <img src="/assets/charts/lifter-count-wc-2024-Europe.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in Europe in 2024">
    <img src="/assets/charts/lifter-count-wc-2014-Oceania.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in Oceania in 2014">
    <img src="/assets/charts/lifter-count-wc-2019-Oceania.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in Oceania in 2019">
    <img src="/assets/charts/lifter-count-wc-2024-Oceania.svg" alt="bar chart showing the unique lifter count of female powerlifters by weight class in Oceania in 2024">
  </div>
</div>


### So Should the IPF Add a Women's Weight Class?

I think the last two articles have provided enough evidence to at least start the conversation at the IPF about adding another women's weight class. In addition, and anecdotally, when I shared the results of last week's analysis on social media I had a lot of comments from both men and women in support of a heavier class.
It is not unreasonable to expect that a tall athletic woman weighs 90 or 95kg. Her two options should not be aggressive cutting or putting on significant weight in order to be competitive.

The powerlifting community likes to claim that we are a sport for all. And on the whole, I believe this to be true. But taller women deserve better.

In the next article I will use the data to put a proposal together for the new weight class or classes.


<br>

### Got something else you'd like to see?

Then you can [send an email](mailto:info@powerliftingindata.com), or [DM me on instagram](https://www.instagram.com/powerliftingindata/).