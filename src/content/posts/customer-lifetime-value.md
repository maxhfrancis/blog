---
title: "Stop Marketing to Everyone — Focus on Your Best Customers"
description: "Most businesses segment their markets the wrong way. Value-based segmentation — built on what customers actually do, not what they say — is a better path to growth."
date: 2026-02-23
draft: false
---

Many businesses market incorrectly. Intuitively (or formally), they know the three steps of marketing a product are **Segment–Target–Position**:

- **Segment:** Divide the market into mutually exclusive, collectively exhaustive units
- **Target:** Choose the segment your product aligns with most
- **Position:** Explain why your product is superior to the next-best alternative

Though simple in theory, this framework is clearly not foolproof, as evidenced by the countless failed products released to market. The culprit is usually the very first step: how a business defines its segments.

## The Demographic Trap

Unfortunately, many marketers fall back on demographic-based segmentation — and it's an absolute no-no.

The US rollout of Honda's small hatchback, the Fit, illustrates the problem well. Honda designed the Fit for young buyers seeking something small, affordable, safe, reliable, fuel-efficient, and *spunky*. Instead, it found a market with older buyers who happened to want the same things. Honda got lucky — the Fit survived in US dealerships for about fifteen years — but they never reached the young audience they intended.

Missing on demographics cuts the other way too. See: Bic's pink pens.

## Psychographics: Better, But Not Perfect

A respectable alternative gained popularity in the 1960s and 70s: **psychographic segmentation**. Psychographics account for buyers' beliefs, values, and motivations. These segmentations typically emerge from surveys run through a K-means cluster analysis, then handed to Marketing for naming — which is why we've all rolled our eyes at personas named "Cost-Cutting Carlos" or "Frugal Frida."

Psychographics are genuinely better than demographics. But there's one persistent problem: what people *say* in a survey and what they *do* in real life frequently diverge. Researchers even have a name for it: the **say-do gap**. The gap doesn't make psychographic research worthless, but it does demand a clear-eyed understanding of its limitations.

## Enter Value-Based Segmentation

Whereas psychographics focus on what survey respondents say, **value-based segmentation** tracks what customers actually do. Specifically, it tracks how much money a customer brings to the business — and how much it cost the business to acquire them.

A well-designed CLV model has three non-negotiable properties:

1. **It is based on margin, not revenue.** If Adam buys a $100 item with a 5% margin and Betty buys a $100 item with a 70% margin, Betty is the more valuable customer — even though they generate identical revenue.

2. **It accounts for time value of money.** If Charlie buys a $20-margin item today, and Debra buys a $20-margin item in a year, Charlie is more valuable right now — a dollar today is worth more than a dollar tomorrow.

3. **It is future-oriented.** The purpose of business isn't to reward past behavior — it's to maximize the value of future interactions. Just as the Yankees offering Babe Ruth a new contract provides no value to them today, a company rolling out the red carpet based solely on historical purchases doesn't benefit the business. History can be *indicative* of the future, but it can't be what drives decisions.

## How the Model Works

Statistical models can estimate an individual's future value based on past purchases. One such model — the **beta-gamma beta-binomial gamma-gamma** — works from a simple transaction log: customer ID, timestamp, and purchase amount.

From that log, it constructs **RFM slabs** for cohorts. RFM stands for **Recency, Frequency, Monetary Value** — a direct-marketing framework for segmenting customers on actual behavior. Customers are grouped into cohorts based on acquisition timing, since different conditions affect why someone first bought from you when they did.

The model assumes each customer has a predetermined propensity to remain "alive" (still available to purchase) and a propensity to buy during any given period. Think of it as two coins:

- A **death coin** — flipped at each buying opportunity. Land on "death," and the customer is gone forever (they moved to Monaco).
- A **purchase coin** — flipped only if alive. Determines whether they buy this period.

These probabilities are derived from past recency and frequency. Monetary value assumes that past check size will be indicative of future check size.

Crucially, the model treats a customer's death coin, purchase coin, and check size as largely intrinsic. **There is little a company can do to meaningfully extend a customer's life, increase their propensity to purchase, or grow check size.** Buying behavior is what it is.

## The Strategic Implication

If we accept that our actions can't drive meaningful changes in buying behavior, we should abandon efforts to transform average customers into great ones.

Instead, the strategy shifts to **finding as many fantastic customers as possible**.

Layer in the 80/20 rule — 20% of customers generating 80% of firm value — and it becomes clear: narrow the focus of your products to your top customers.

How do you identify them? A rigorous CLV model gives you the most granular answer. In the meantime, **recency** is a useful directional proxy. Customers with the most recent purchases are most likely to buy again — and given that purchases tend to be streaky, they may buy again very soon, preserving a high time value of money.

## So What?

I want to encourage product managers, analysts, and decision-makers who prioritize backlogs to stop including enhancements for whichever stakeholder screams loudest — and stop building features that will benefit the most users in aggregate.

**Focus on your best customers.** Identify what those with the highest future time value of money will find important, and build for them this sprint. Accept that 80% of your user base will likely miss the value — and that's fine. Reward the future behavior of your best customers, and you'll find new great customers along the way.
