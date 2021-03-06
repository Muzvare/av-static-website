---
title: AV Website Review Part 4
date: 2017-07-10
tags: 
author: Sam Joseph
---

![conflicted](/images/conflicted.jpg)

I'm conflicted about what to review on the website next.  Part of me wants to start breaking the "Getting Started" page up into pieces, and showing animated gifs for each.  There's also the "About Us" page and the need for privacy statement pages.  We've also got all the text in the "Learn", "Code", "Pair", "Grow" sections, but I can also sense many other strands of the web attached there.  The presense of the "Email Registrations are temporarily disabled" on the "Sign up" page kind of bothers me.  It feels like it's a bit of a running sore.  That said, no one has complained about it explicitly.  

We disabled the email registrations a couple of years ago when we were experiencing heavy spam sign ups.  In my "simplest first" doctrine I suggested just turning it off.  Others did suggest adding captchas and I wasn't enthusiastic because I felt it was a kind of arms race and that we would be adding more functionality that we would have to maintain.  Maybe that was a mistake and I should have encouraged whoever was suggesting the captcha to implement one.  Recently my opinion is evolving. The other day I turned on a [captcha system](https://www.google.com/recaptcha/intro/) to protect our NHS HLP wiki from spambot sign ups.  It was a pretty straightforward configuration and it seems to have been completely successful in blocking the spam bots.

The other thought I have for the sign up page is that by forcing people to sign up via either GitHub or Google, we ensure that more members have already completed the "Getting Started" step 1 (sign up for GitHub) that I recently removed from the "Getting Started" page.  Ironically the Google sign up is now sort of redundant since the main reason we wanted to offer that was to enable us to connect people's Google profiles to the data coming back from the Google Hangout plugin.  Since Google retired the API for that plugin 3 months ago we're not getting any telemetry on who starts or joins Hangouts, and we're in the process of looking at how to move over to Jitsi, which uses Gravatar rather than Google Plus.  So what direction does that push us in?

Should we drop the Google sign up?  Re-enable the email signup?  From a user point of view we should be providing the sign up options that are most convenient to the user.  We could be providing Twitter and Facebook login; it doesn't feel like a priority, but having user accounts attached to their various social media identities might be useful.

The most glaring issue on the Sign up page is the reference to the "Privacy statement" when we don't actually have one.  I think the priority has to be that privacy statement and then linking it up.  I'm also tempted to work on the captcha component so we can remove the increasingly erroneous "temporarily disabled" - apparently there's a [gem](https://github.com/plataformatec/devise/wiki/How-To:-Use-Recaptcha-with-Devise) that would allow us to integrate recaptcha with Devise.  Of course that's all part of training Google's AIs, but can we really fight that flow?  There's also the concern that we're not pushing people to get GitHub accounts, but I guess it's better to get as many signed up as possible ...

So I've created a [privacy policy page](https://www.agileventures.org/privacy) based on the one we have for the NHS wiki.  Now I just need a pull request to link that into the footer and the Sign Up page ...
