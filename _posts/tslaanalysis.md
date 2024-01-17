---
layout: post
title: TSLA Stock Analysis
subtitle: So, I was asked to look at some data...
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [luca is the goat]
comments: true
---

{: .box-success}
## **Let's talk about stocks...**
1. I worked with Tesla (TSLA) stock data over the last twelve years, where I was given the date, opening price, closing price, maximum price of the day, minimum price of the day, and the volume of traded shares that day in the form of a csv. 
2. I was interested in this dataset because stocks are very frequently analyzed by looking at statistics, and thus I wanted to try some analyst work for myself to see what sort of trends I could pick up on.
3. The first trend I analyzed was just the overall trend of the stock in a plot which looked at the closing price by day. It simply mapped out how the closing price varied, and it revealed that the stock had overall been quite flat until around 2020, where there was a very, very strong rise until around 2021 or 22 where the stock strongly steadily declined to the current point. The next trend I analyzed was how day of the week played a role in the fluctuation of the stocks. Firstly, I looked at what day of the week seemed to have the greatest increase in closing price from that day to the next, and ultimately, it revealed no clear pattern. In fact, every single day of the week, the closing price decreased more often than it increased, meaning that overall, the days which the stock did increase, the average increase was greater than the average decrease. I also looked at how the opening price compared to the closing price for that given day for every day of the week using similar methods to the previous analysis. I learned that essentially, there was no correlation between the day of week and the delta price for the day. The final analysis I did was on a histogram of the weekly change in closing price. The histogram was slightly skewed right, implying that the mean is greater than the median delta. The center (looking at median because distribution is irregular) is also slightly above 0. Overall, this means that there is a greater volume of deltas which are negative (stock price goes down on the week) but the lower volume of deltas which are above 0 are closer to the mean, which is also above 0. My data analysis is obviously far from comprehensive and yielded basically nothing useful in terms of investment, but it was useful to understand the methods that could be used to preform a better analysis in the future.
4. For this lab, I worked mainly with Feingold for any help I needed.
