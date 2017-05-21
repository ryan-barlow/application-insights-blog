# Prologue

![The author, at a rare moment he wasn’t coding](/images/logo.png)

Its the era of the cloud. Big data is the buzzword of the moment. The ‘DevOps environment’ is the promised land, appearing on every job advert from Silicon Valley to Sutton-On-Sea (via Sicilly, Seoul, Sydney and places that don’t begin with S).

Pingdom, Google Analytics and the like are of course, long since ubiquitous in every development office around the world. However, gaps in data collection still exist.

You’ve landed that lead position you’ve had your eye on. You’re 6 months in to the role, and you’ve made a cracking start. You’ve got Continuous Integration setup, and a robust one-click release deployment process all sorted. You’re starting to think you’ve got this thing covered. Then one day, the CTO comes up to your desk and asks ‘What was the average time spent querying SQL for the payments report on Sept 27th? John in Sales was complaining earlier that it seemed a bit slow. Get it to me by yesterday.’.

A bead of sweat dribbles down your forehead. ‘****! Do I log that? Can I get the data available to answer that question?  Does our current performance logging provide enough detail of what our servers are doing? And if they do, is it easy and powerful enough to query?”

## Enter Microsoft and Application Insights.

New Relic, Stackify and other APM (Application-Performance Management) tools are some options available for server side performance monitoring. The downside, is that they are often very costly to set up. Enter Microsoft and Application Insights.

This blog is intended as a primer to Application Insights, with the hope that it pulls together from a lot of disparate sources and gets you up and running.

<style>
.page-header > a { 
  display: none
}
</style>
