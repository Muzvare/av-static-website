---
title: AV EcoSystem Review Bounce Drop
date: 2017-08-25
tags: 
author: Sam Joseph
---

![bounce rate](/images/bounce_rate.jpg)

Right, time to work out the difference between "bounce rate" and "drop off".  Maybe it's the jetlag or just me getting old, but reading [this article](http://www.rankraiser.com/rankraiser/difference-between-google-bounce-rate-and-drop-offs/) I'm not immediately getting it.  Let's dig in:

Bounce Rate is apparently the percentage of total visitors to a specific page in our site that saw only that page during their visit to our site.  Our getting started bounce rate was ~57% in July, and 80% in June, so that tells us that since we made the change at the beginning of July people have been hanging around a bit longer after visiting this page - at least more of them have been visiting at least one more page in our site.

Drop off (which gets shown in the Google Analytics visitor flow) is a combination of people leaving the site after having visited 1 or more pages.  In July we saw 37.3% of total traffic to the "Getting Started" page drop off there, compared to 40.8% in June.  

Hmmm. So of the, say, 100 folks (sessions?) who loaded the "Getting Started" page in June, 80 only saw that single page.  While just over 40% of all sessions (that included "Getting Started"?) ended there, while just under 60% carried on browsing.  All sessions must also be those 100 folks, and 40 ended there, but 60 went on ... that does not make sense.  I must be missing something, unless the drop-off is exluding the bounces, which on reflection it looks like it is.  That would imply that of the 20 folks who browsed through the "Getting Started" page, 8 ended their browsing journey there, while 12 of them carried on browsing ...

We can hypothesize that removing the links to GitHub, Pivotal Tracker and Google+ from the start of the "Getting Started" page could have had this sort of effect, but this all seems pretty inconclusive so far.  What we really want to be looking at is the numbers of people getting set up and contributing to projects, which the analytics is not telling us about.

The other thing to look at is how our latest change to the Premium page wording has affected things ... I can't seem to pull the pricing or Premium pages up in the behaviour flow graph since they are not showing up there (too few clicks perhaps?), although I notice the exit rate is shown in the plugin (but that's different again from dropoff?).  The bounce rate as reported by the chrome plugin has dropped from 50% to 20%, which makes it seem like that's a helpful change in terms of making the Premium page stickier ... Conversely for the same time period the bounce rate has increased from 20% to 50% on the Premium Mob page where we didn't make any changes.  So that's a reasonable argument for adjusting the language on the Premium Mob page too ... looks like I have more reading to do on what makes exit rate different from bounce rate ...

* [https://www.axzm.com/google-analytics-exit-percentage/](https://www.axzm.com/google-analytics-exit-percentage/)
* [http://onlineoptimizers.eu/the-important-difference-between-exit-rate-and-bounce-rate/](http://onlineoptimizers.eu/the-important-difference-between-exit-rate-and-bounce-rate/)
