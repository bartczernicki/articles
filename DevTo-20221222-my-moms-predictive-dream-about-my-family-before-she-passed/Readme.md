
![Calculate Probability - Header](https://raw.githubusercontent.com/bartczernicki/Articles/main/DevTo-20221222-my-moms-predictive-dream-about-my-family-before-she-passed/CalculatingProbability-Header.webp)

In 2017, a few months before my mom passed away, my mom had a dream that in the future my wife and I would have a family consisting of three daughters. I thought this dream prediction an interesting study on "predictive life events", so I decided to write about it and synthesize this with some math & statistical modeling.

In this article, I will cover:
- How to craft simple statistical models using basic statistical rules, to quantify (put math labels on) life events that you may think are hard to measure. You will see how easily these models can be crafted (even in your head!) and applied to forecasts, predictions and future decision making
- You don't need Artificial Intelligence, Machine Learning, Neural Nets for everything; old-school statistical foundations still apply to a lot of use cases
- Creating statistical models is an exercise in knowledge about the environment. Secondly, it is almost an "art" as much it is about the math and statistics
- How "predictive" my mom's dream forecast actually was and what causal conclusions we can draw from these types of life events. For example, does the "supernatural" exist?

## Background Story

Going back several years to one day in early 2017; I received a call from my parents that my mom had a dream the night prior, that I would have a family with my wife consisting of three daughters. At that time of my mom's predictive dream, my wife and I had been married for 2 years and we had no kids together. We were just starting family planning. My mom had not been well, so I thought this was just one of those "comfort" dreams where my mom was connecting with my "future family" via dreams. Having said that, that day in 2017 I didn't think much of my mom's dream. Fast forward seven years to the end of 2022...I am blessed with a bigger family and **YES, we have three little daughters!!!** Our first daughter was born in 2018, second in 2020 and our third in 2022. Immediately when we found out the gender of our third baby in 2022, I started to think back to my mom's dream and prediction of three daughters. How strange was this? Was this in fact a prediction from the supernatural?

## Calculating the Probability of Three Daughters - Part 1 - Naive Approach

Let's tackle the first question. How strange was my mom's predictive dream? Can we put a number on it and in effect measure the probability of my mom being correct? Therefore, what is the probability for having a family of three daughters? In order to calculate this, we can utilize one of the foundational rules of statistics: **"The Statistical Multiplication Rule"**. The statistical multiplication rule, also known as the "rule of product," is a principle in probability that helps to calculate the probability of several events occurring together. It states that the probability of several independent events occurring simultaneously is the product of the probabilities of each event occurring individually.

For example, consider the probability of rolling a "4" on a six-sided die and flipping a coin that lands on heads. The probability of rolling a 4 is 1/6 (one of the six sides of the dice) and the probability of flipping a coin to show heads is 1/2 (50%). Using the statistical multiplication rule, the calculated probability of both of these events occurring together is 1/6 x 1/2 = 1/12 (8.3%). Simple, right? The statistical multiplication rule can be used to calculate the probability of complex events that are composed of multiple independent events. 
![Calculate Probability](https://raw.githubusercontent.com/bartczernicki/Articles/main/DevTo-20221222-my-moms-predictive-dream-about-my-family-before-she-passed/CalculateProbability-DiceCoin.png)

Using this multiplication rule, we can apply this concept to my mom's dream predicting three daughters to calculate a numeric probability. To keep it simple, let's assume the probability of having a baby daughter [P(Baby Daughter)] is 1/2 (50%). Furthermore, let's assume having each specific baby gender is an independent event, which means having a prior daughter has no impact on the gender of the future baby. This means that the total probability of having three daughters can simply be calculated by multiplying the independent probability of having a daughter three times. This equates to 1/2 * 1/2 * 1/2 = 1/8 (or 12.5%).
![Calculate Probability Daughters](https://raw.githubusercontent.com/bartczernicki/Articles/main/DevTo-20221222-my-moms-predictive-dream-about-my-family-before-she-passed/CalculateProbability-Daughters.png)

So, is this it? Well this is a very naive model of the prediction, but a good start. There are several key problems with this simple model, but to highlight a couple issues:
1. The model is already assuming there will be three children. The correct probability statement of the model above should be "Given there are three children, what is the probability that all three would be girls".
2. We are missing a great deal of other various independent information that can influence the model of starting a family from scratch. As you can imagine, a mny biologicial/environmental/family events have to "go right" to have a baby.

## Calculating the Probability of Three Daughters - Part 2 - Including Independent Environment Events
It turns out the model that we calculated above is quite simple, actually overly optimistic and frankly not quite correct. While it is "roughly true" the probability of a baby daughter is roughly 1/2 (50%), life is much more complex. There is much more information to be added. Going back to my mom's prediction of having a family of three daughters, we should consider the probability (chance) of:
- What if my wife or myself couldn't have kids?
- What if we had one baby, and had "enough" or couldn't handle more than one baby?
- What if our marriage failed (before or during the family process) and ended in divorce?
- What if one of us lost our job and we couldn't afford more children?
- Going more out of the box...What if WW3 started, an asteroid was going to destroy the planet or the universe abruptly ends?

There are almost infinite scenarios to list! This is where the process of **crafting statistical models becomes an exercise in understanding our environment and somewhat of an "art"**!
- Which events should we consider in our model to make proper inferences, claims or forecasts? Events such as WW3 happening or a black hole swallowing up earth will definitely impact family planning, however probably not enough to impact in our statistical model
- More importantly, which of these events are independent? Which ones can we use in our model applying the earlier introduced "the statistical multiplication rule"?

Some of these are more likely to happen on average (i.e, a divorce, infertility) versus an asteroid/comet impact. All of these events do have a non-zero (>0%) probability of happening even if the probability is super low. The good news is that many of these events have been studied, include many years of empirical data and can simply be looked up. For example, scientists claim an asteroid/comet hitting Earth causing catastrophic impact in a given year is 1 in 300,000 (or 0.0003%). Stating it another way: a 299,999 in 300,000 (or 99.9967%) chance of an asteroid/comet NOT having catastrophic impact in a given year. However, a lot of these event probably shouldn't be taken into consideration into our "statistical family model of three daughters". It is generally accepted to exclude inprobable events from models (i.e, large asteroid/comet hitting Earth) as they do not change the overall "spirit" of the model nor do they change the overall pobability meaningfully. Excluding these events does potentially leave our statistical model susceptible not able to predict "black swan" events. For example, how many business/sales/inventory supply chain/stock market forecasts predicted a global pandemic (black swan event) in 2020? As it turned out, not many at all.

## Why my Mom didn't Predict Supernatural Existence
If this had been set up a frequentist inference hypothesis experiment, then one could conclude something called **statistical significance**. This is because my mom's prediction was so unlikely, it was under a commonly used statistical threshold (5%). Basically, because my mom's Not going into detail, but statistical significance does not mean practical/environment significance. While this experiment could be looked at very highly unlikely to happen just by chance, we cannot claim anything about the environment, 
You have probably heard the term "correlation does not imply causation".


John Allen Paulos is a mathematician and author who has written about the role of probability and statistics in everyday life, including the topic of dreams and their potential relationship to the future. In his book _"A Mathematician Plays the Stock Market"_, Paulos discusses the idea that some people believe dreams can be predictive, offering an example of someone who dreams about a specific stock and then sees that stock rise in value the next day. Paulos notes that while this may seem like a coincidence, it is actually an example of the "law of truly large numbers," which states that with a large enough sample size, any outcome is possible. Paulos goes on to explain that it is natural for people to look for patterns and connections in the world around them, including in their dreams, and that this can lead to the illusion of causality when there is none. In other words, while it may seem like a dream was predictive of a future event, the reality is that the event was likely to happen anyway and the dream was simply a coincidence. In the Appendix section of this post, I discuss John Allen's deriving of a probabilistic model around "predictive dreams".
