---
title: Solving for Customer Health
date: 2021-01-27
author: wbhamilton
layout: post
permalink: /solving-for-customer-health/
categories:
  - Technology
tags:
  - health
  - CS
---
As I [mentioned](https://1twentyeight.com/on-customer-health/), I see two issues in how we in CS think about customer health:
1. Over complication
2. No link to the customer journey

## Over Complication
I read an article that framed this particular topic (customer health) as four categories to measure *customer success performance*. One of the categories within the four was Customer Health (that’s confusing). Each of the four categories had its own top five metrics. That is **20** metrics to get to a *performance* score. This is overkill. One category was financial metrics. My encouragement to you would be to not use a financial category. Financial metrics are not an indicator of a healthy customer. You could have a customer who’s engineering team isn’t using your product, but they don’t communicate with procurement who keeps paying the renewal invoice each year. You get a 100% renewal rate, but they aren’t even close to being a healthy customer.

Another metric we add to the never-ending list of health metrics, and was listed in the article I referenced, is the Net Promoter Score (NPS). Stop using NPS to measure health. Even better, stop using NPS altogether. NPS is not actionable. Unless you have an active and engaged customer that you speak with all the time, you have no idea what it will take you and your team to move a customer from a six to a seven, or an eight to a nine. It is an absolute waste of your time.

Instead, pick four to six (no more than eight) key metrics. Set your algorithms to measure these key metrics from one to 100. Then set a red, amber/yellow, and green range within each metric. These individual metrics can be grouped, if appropriate, with the individual metrics rolling up to a group or category score, and the category scores rolling up to an overall score.

Perfect is the enemy of good. You don’t have to nail this on your first try. When you’ve established this baseline health score, you should find that you have an even distribution of customers across red, amber, and green. If you find that a majority of your customers are green (or red) you will have no clue what to do to improve their scores. That is, it will be too large of a sample size and not actionable.

The goal is to move those at the top end of the amber range to green and those at the top end of the red range to amber. After some time look at adjusting your ranges and/or algorithms. Consider adding and/or removing metrics. Your health score should evolve with your business.

### An Example
Three categories. Each category rolls up the metrics under it. The three categories roll up to an overall score.
1. Category One - Product
	1. Monthly Active Users - this could be a month over month trend, or active users against purchased users
	2. Data Amount Ingested - GB trend month over month
	3. Product specific usage - a month over month percentage trend against a number of features in your product
2. Category Two - Engagement
	1. Outreach - number of monthly emails & calls against a target
	2. Business Review attendance - could be monthly or quarterly
	3. Support Engagement - pick your poison…it could be number of open/closed tickets against a monthly target
3. Category Three - Sentiment
	1. CSM Sentiment - red, amber, green. That’s it.

That’s seven metrics (remember, no more than eight). Each with a 1-100 score and color. Each rolling up to the category, and the categories rolling up to an overall score.

It really can be this simple. 

## Where’s the Journey?
Customer health scores should then be tied to the customer journey you’ve established for your customers. Wait a second, what do I mean by “customer journey”? If you’re reading this and you don’t know what a customer journey is, or the process of creating customer journey maps, then there are a couple places to start - check the links at the bottom. Otherwise, I’ll assume you know that a customer journey is a map representing the stages, key milestones, and internal responsibilities related to the strategic path you desire to lead your customers. A properly scoped and mapped out customer journey leads to healthy customers meeting and exceeding *their* business values and goals with *your* product.

Let’s say your customer journey (for year one) has four stages (post-sale):
1. Onboard
2. Adopt
3. Optimize
4. Renew

A customer health score should be actionable by journey stage. That is, our field teams should be able to evaluate their customers at each journey stage against a benchmark. If Customer A has an overall health score of 65 at the end of the Onboard stage the team should know what to do next based on benchmarks established across the broader customer base. If the benchmark states that a customer should be at a 75 at the end of Onboard, then a playbook establishes the actions that a CSM should take for Customer A that is currently sitting at a 65.  And based on the fact that our score is really a roll-up of four to six KPIs, then our CSM is able to drill down to the actual metric(s) that is/are impacting the score.

You could also take this one step further. Let’s assume you segment your customers. The segmentation type doesn’t matter (e.g. high-touch / low touch; ARR band; industry). You should be able to set benchmarks, by segment, by journey stage. Doing so gives you a library of playbooks that your field teams can utilize to ensure the success of your customers. It takes the guess work out of what your CSMs are doing each day. It’s simple. It’s focused.

Some might say this is over-simplified. You are right! It is! And it is totally doable. You do not need to over-engineer this. I’m not saying that it does not take time to get your journey maps, benchmarks, and health scores established. It does, but not because it’s complicated. 

### Customer Journey Mapping Resources
* [Atlassian - Customer Journey Mapping](https://www.atlassian.com/team-playbook/plays/customer-journey-mapping)
* [Using Journey Maps to Improve CX](https://customerthink.com/6-ways-to-make-sure-your-journey-maps-improve-customer-experience/)
* [Six Steps to Creating Journey Maps](https://www.invespcro.com/blog/customer-journey-maps/)
