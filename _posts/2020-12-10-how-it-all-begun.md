---
layout: post
title: How it all begun..
excerpt_separator: <!--more-->
---
{% if page.title == "Home" %}
  ![Confused AI](../images/confused_ai.jpg)
{% else %}
  ![Confused AI](/images/confused_ai.jpg)
{% endif %}

A long, long time ago, in the far land of... 

It wasn't a far land but while I was renovating the apartment I bought for my mother, I decide to fill up my breaks seriously playing stock trading on a paper account, choosing companies I liked and using my intuition and a bit of arbitrary sentiment analysis. However, I quickly realized that:
<ul>
  <li>Though successful (9% monthly returns), my performance was as good as my daily time commitment and analysis to preparing for market open</li>
  <li>90% of my losses where due to FOMO or the hope that a losing trade would bounce back</li>
</ul>

And so I wondered whether there could be a way to automate entering and exiting trades through a predetermined strategy, removing so also the major cause of money loss, i.e. the human fear factor.
<!--more-->
I first came across with TradingView.com and its own programming language(Pine Script). I experimented for a while, studying the fundamentals of technical analysis until I realized that if I wanted to insightfully find out the most effective technical indicator/s, their best parameters levels and combinations tha would produce the best trading strategies with the most consistent high positive returns and the lowest drawdowns, I had to tab the different results of each combination in excel. 

Said and masochistically done it, I begun a manual forward test on eToro.com paper account. Yippie!!! Finally the model will make me rich!! ..or so I though! Though the model with the best overfit and then normalized strategy was making money on Tradingview.com, the reality is that by the time that I: a) received the notifications on my phone; b) saw them; c) took action, the momentum , if not the trade, was already over, and eToro being eToro, their very large spread did not allowed for the gains I was seeing on TradingView.com (note: TradingView does not allow for directly trading a strategy with a connected broker, though they now have some escamotage to achieve this result).

So, back to the drawing table, the main issue now was still the human factor, i.e. my responsiveness to the signals, and the large bid/offer spread I had to overcome each time I placed a trade.

Looking around on the net, I discovered that InteractiveBrokers was one of the main routes to implement algorithmic trading and so I studied their API, learnt Python and iBridgePy from scratch and now I forward-test and improve this algo both through their API as well as through Blueshift (Quantopian just closed) with Alpaca and FXCM.

These blog and repositories are mostly for personal reference as blog of what I do, ideas and archive. If you enconted these repositories and would like to contribute to the projects with some advice, feel free to drop me a line.

Bye for now.
d.
