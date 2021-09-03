---
title: "The Premium War"
header:
  teaser: /assets/images/posts/thought3/main.png
  overlay_image: /assets/images/posts/thought3/main.png
  original: /assets/images/posts/thought3/original.png
last_modified_at: 2020-05-10
categories:
  - ThoughtPiece
tags:
  - War
  - Country Risk
author: Ryan Park
comments: true
hook: \"Is there a causal effect between war and country risk?\"
customExcerpt: A terrifying word. A terrifying thought. Yet most citizens of first-world country environments will likely never experience it.
---

## War

A terrifying word. A terrifying thought. Yet most citizens of first-world country environments will likely never experience it.

Currently we are at war with a virus, named by the World Health Organization as: Severe Acute Respiratory Syndrome Coronavirus 2, or SARS-CoV-2 for short, and more colloquially known as corona. While the pandemic causing virus is a huge problem, and other viruses and diseases will continue to be a problem in the future, we have another recurring problem: war.

There’s discussions as to whether war is part of human nature or not, and when the first act of a war occured. Whatever the real answer is, recent history has shown us quite a few wars, and we can be confident that the first war was definitely before A.D,, so it’s been at least 2,020 years since the first war.

I’m not really here to talk about wars and their reasons and all that here however. I want to conduct a brief analysis of war, and how that affects risk premium of stocks

### Risk Premium

For this analysis I will be using calculations made by Professor Aswath Damodaran of NYU Stern School of Business. His calculations, which during the time of writing, were last updated on April 1, 2020<sup>1</sup>.

Country risk is generally derived from a country’s economic growth life cycle, political risk, legal system, and reliance on a commodity. Developing countries in an early growth cycle are exposed to higher risk than a mature country. Political differences such as whether the system is a dictatorship, democratic, succession plans, etc affect risk. Less fair a country’s legal system is, higher the risk. And over-reliance on a commodity exposes the country to macroeconomic cycles which highly affect a commodity’s demand and price.

In broad terms, Professor Damodaran calculates country risk using the following steps:

1. Take the equity risk premium of a mature market of 6.01% (which he obtains by looking at the implied risk premium for the S&P 500 index on April 1, 2020, which implies the U.S. has 0% country risk premium).
2. Then he estimates default spreads of each country, derived from either local currency rating from Moody’s (or S&P when Moody’s isn’t available) or the CDS spread
3. Last, he derives country risk premium from the default spread. 

### At the Onset

The original idea was to do a simple analysis, to take a look at some countries currently at war and looking at geographically close countries and compare the difference in country risk premium to see if being at war has an increasing effect on country risk. After starting out to do so, I found that countries geographically close tend to all be involved in some way to a war.

### Revised Approach:

I will go through the countries (some small ones removed under my discretion) that Professor Damodaran analyzed country risk premia of. Then I will try my best to separate countries that have a war(s) going on in their country (so countries that simply sent troops abroad will not count) vs countries that do not have a war going on in their own territory. And then analyze the difference in country risk premia of countries at war vs those that aren’t, as defined previously.

| Number of Countries | 161        |
| ------------------- | ---------- |
| **Mean**            | **7.58%**  |
| **Median**          | **6.59%**  |
| **Max**             | **25.92%** |
| **Min**             | **0.00%**  |
| **St Dev**          | **6.57%**  |

Table 1.0: All Countries

Table 1.0 is a summary of a brief analysis conducted on 161 countries from the data list. The mean and median country risk premium is 7.58% and 6.59%, respectively, with standard deviation used to measure volatility in risk premia.

| Number of Countries | 125       |
| ------------------- | --------- |
| **Mean**            | **7.13%** |
| **Median**          | **6.59%** |
| **St Dev**          | **5.92%** |

Table 2.0: Countries without war in their own territories

| Number of Countries | 36         |
| ------------------- | ---------- |
| **Mean**            | **9.13%**  |
| **Median**          | **10.07%** |
| **St Dev**          | **6.32%**  |

Table 3.0: Countries with war in their own territories

From tables 2 and 3, there can be seen a difference in country risk premium between countries with war and countries without war. Both the mean and median country risk premium is higher for countries with war compared to those without.

### Conclusion

War is likely not the driving factor behind the difference in risk premium shown, it’s likely just a correlation, as many of the countries in war are developing nations with other macro factors driving higher risk premia.

But with over 14,000 nuclear warheads in existence today, perhaps we are disregarding the chances of a nuclear warfare a bit too much. A nuke war will make every country’s risk premium 100%! We tend to be a bunch of optimistic bunch, and will continue to be so, we disregard factors that were certain to impact the macroeconomy such as a pandemic, and will discount the probability of it reoccurring again and again.



<sup>1. http://pages.stern.nyu.edu/~adamodar/New_Home_Page/datafile/ctryprem.html</sup>