---
layout: post
sitemap: true
title:  "New Year, New Weight class? Two Proposals Beyond 84kg"
title_rss:  "New Year, New Weight class? Two Proposals Beyond 84kg"
date:   2025-01-05 12:00:00 +0100
categories: posts
seo_title: "New Year, New Weight class? Two Proposals Beyond 84kg"
description: "This article makes two proposals to increase the limit of the super heavy weight class for women in IPF powerlifting. The data for this analysis comes from the openpowerlifting database."
---

This article extends the work of the last two which looked at the distribution of female powerlifters by weight class (you can find them [here]({{ "/posts/2024/12/08/distribution-of-lifters-by-weightclass.html" | relative_url }}) and [here]({{ "/posts/2024/12/15/distribution-women-weightclass-region-time.html" | relative_url }})).

I think these articles provided enough evidence to at least start the conversation at the IPF about adding another women's weight class. This week, I want to provide a little assistance for those discussions, by providing two options that will make the IPF more inclusive for heavier women.

Why two proposals? Well the IPF has a choice. They can simply add a heavier weight class beyond 84kg. The advantage of this approach is that it is the least disruptive in the short run. The goals, records and plans of lifters below 84kg remains unchanged. The main objection to this is that there will be an uneven number of weight classes for each sex*.

The other option, is to keep the same number of weight classes, but redistribute them so that we end with a higher classification for the unlimited class. The advantage of this approach is we can basically start-over and set the classes at levels that best reflect the current (and hopefully future) lifting population. The downside of this approach I hope is obvious: this would basically turn the women's division of the sport on it's head, and many lifters may find themselves in limbo as they revisit their goals and strategies for the sport. Existing records would also be essentially thrown out (although lifters holding those records will technically have them forever).

In order to make these proposals - add a class or redistribute the existing - I queried the [openpowerlifting.org database](https://www.openpowerlifting.org/) for: 

- IPF-affiliate meets held in 2024 
- Unique lifters per weight class (inferred from weigh-in weight)
- Data NOT split by division (junior, masters etc.)
- All equipment and event types included


### Proposal 1: Add a 98kg weight class, push 84kg out to 86kg

This proposal comes from looking at the weigh-in weights of women above 84kg in 2024. We can see that after 98kg, there is a significant drop off. Up until 98kg it is somewhat flat with a peak at 98kg.

<br>

<div class="custom-chart">
  <div class="html-content">
    {% include charts/bw-histo-2024-above-84.html %}
  </div>
  <div class="svg-content">
    <img src="/assets/charts/bw-histo-2024-above-84.svg" alt="distribution of weigh-in weights on women in IPF-affiliate meets in 2024">
  </div>
</div>

So let's look what the distribution of lifters per weight class would look like if we add the 98kg class. But first it's important to consider that the jump from 84 to 98 is much larger than the jump from 76 to 84 (10.5% vs 16.7%). So how about we shift the 84 up to 86? That would give us the following:

<p style="text-align:center">Distribution of female powerlifters by adding a weight class</p>

<div class="custom-chart">
  <div class="html-content">
    {% include charts/new-wc-2024-global-addition.html %}
  </div>
  <div class="svg-content">
    <img src="/assets/charts/new-wc-2024-global-addition.svg" alt="distribution of weigh-in weights on women in IPF-affiliate meets in 2024">
  </div>
</div>

This puts 10.7% of female powerlifters in the top two weight classes, 22% in the top three (currently 22% of women are in the top two classes). As time moves on we will no doubt see some current 84kg lifters bulk into the 98s.

### Proposal 2: Redistribute so the middle classes are the same as the men's

Again, I looked at the distribution of weigh-in weights, but this time for all female lifters. As expected, there are very large peaks at the limits of the existing weight classes.

<br>

<div class="custom-chart">
  <div class="html-content">
    {% include charts/bw-histo-2024-all.html %}
  </div>
  <div class="svg-content">
    <img src="/assets/charts/bw-histo-2024-all.svg" alt="distribution of weigh-in weights on women in IPF-affiliate meets in 2024">
  </div>
</div>

These peaks add a bit of noise which make it difficult to really see a natural split in the data. I played around with different histogram options, before it dawned on me (with the help of a discussion on instagram), why not just use the same classes as the men's? Women tend to be smaller overall than men (as is normal for most female mammals), so the extremes would need adjusting. But there's no real reason for the middle classes to be any different. They've also had significant field-testing.

Including the (sub)-junior-only men's class of 53kg, we have candidate classes 53kg, 59kg, 66kg, 74kg, 83kg, 93kg. As we saw earlier, 98kg seems to be the drop off point for women, so I wouldn't want to go too much lower than that for the start of the unlimited class. But we also don't want the jump from 83kg to be too much. We can space out the top two classes a little more.

Let's take a look at 48kg, 53kg, 59kg, 66kg, 74kg, 84kg and 96kg.

<p style="text-align:center">Distribution of female powerlifters with a weight class redistribution</p>


<div class="custom-chart">
  <div class="html-content">
    {% include charts/new-wc-2024-global-redistribution.html %}
  </div>
  <div class="svg-content">
    <img src="/assets/charts/new-wc-2024-global-redistribution.svg" alt="distribution of weigh-in weights on women in IPF-affiliate meets in 2024">
  </div>
</div>

This puts 11.5% of female lifters in the top two weight classes, and 30% in the top three (remember the [equivalent numbers for men]({{ "/posts/2024/12/08/distribution-of-lifters-by-weightclass.html" | relative_url }}) are 13.4% and 30% respectively). I'd also expect that the size of 96+kg would shrink below that of the 96kg as women up to the low 100s consider cutting down to be more competitive. We'll no doubt also see bulking of some current 84s, especially the taller ones, as they fill out a class that's a more appropriate size for them. 

### What do you think?

In a perfect world we would see equal competitiveness (i.e. cohort size) in every class, but humans are just not made like that. Assuming a competitive body composition, you could argue that weight classes are height classes in disguise. Human heights are normally distributed so it makes sense we would see a similar pattern in weight classes. Keeping in mind, that since they are discrete categories, they can never be fully Gaussian.

It's also important to me that no matter what step the IPF takes, that lighter lifters aren't penalised (whether that be a real or perceived penalty) in order to benefit the heavier lifters. So we have to careful with options like "shifting all the weight classes up", or "dropping the 47s".


<br>
<p style="font-size: 10px;">*although there's nothing stopping the IPF adding a men's class between 74 and 105kg (eg: 74, 81, 89, 97, 105), since those four classes are all stacked, and contain 50% of all powerlifters</p>

### Got something else you'd like to see?

Then you can [send an email](mailto:info@powerliftingindata.com), or [DM me on instagram](https://www.instagram.com/powerliftingindata/).