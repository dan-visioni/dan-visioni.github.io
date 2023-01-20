---
title: 'Intercomparisons'
date: 2023-01-20
permalink: /posts/2023-01-20-intercomparisons
tags:
  - geoengineering
  - stratospheric sulfate
  - intercomparison
---

<b>New published stuff!</b>

This week, two parts of study were published on Atmospheric Chemistry and Physics by me and Ewa Bednarz (now at NOAA).
The links to the studies are here: [Part 1](https://acp.copernicus.org/articles/23/663/2023/) and [Part 2](https://acp.copernicus.org/articles/23/687/2023/).

<b>The context</b>

The context of this is: the modeling of stratospheric aerosols in the context of climate intervention. 
Go look up on the [main page](https://dan-visioni.github.io/) for more long-winded context about what it is and why it is being studies - and why I think it's ethical for us to study it.
Anyway, here we're focusing on understanding how much and why different Earth System Models (big models that represent the interaction between land, ocean, atmosphere, chemistry, the Sun...) may give different answers to the same simulated injections of SO<sub>2</sub>. This is relevant because we would like to give confident answers to the question "What would happen if we did this?", this being putting aerosols in the stratosphere to temporarily cool the climate.
Our best tool to do this is these huge climate models. The same we use to say "Hey, climate change is kind of very bad, will get worse". Can we trust them for this purpose?
<i>What we simulate is not what we would like to see happen. It's a tool to deepen our understanding of the tools we use, with the prospect of, eventually, giving robust answers to the question above.</i>

<b>What we did</b>

In this study, we took four different climate models (three actually, but one, GISS, with two different treatment of aerosols) and simulated the injection of a fixed amount of SO<sub>2</sub> daily in the lower stratosphere (at around 22 km) for a number of years. This is obviously not new and has been done before! Correct, but many previous intercomparisons only looked at similar experiments with injections performed at the equator, or over many latitudes at the same time.

By focusing on one latitude at a time, and observing the overall response in different models, we tried to gain some insight over what exactly drives the differences we observe in these models.
Many things contribute to the fact that, if you put this gas in the stratosphere in exactly the same way, the results you obtain are different.

The SO<sub>2</sub> turns into H<sub>2</sub> SO<sub>4</sub>, which turns into aerosols, but of what size, and with which lifetime?
The larger they are, the faster they fall. The larger they are, the more they also warm the local air, something it would be best to minimize. Finally, the larger they are, the less they can reflect sunlight, something we want.

These are what we call microphysical uncertainties, and depend largely on how the microscopical physical processes are parametrized - that is, treated in the models, which turns out, is very different between models.

These aerosols are then also spread over the globe by the stratospheric circulation.
If the aerosols are too confined in the tropical pipe (close to the equator) they grow too much and fall faster. If they're spread too fast, their lifetime is reduced.

Models also show a certain spread in how the air-masses move, what we call dynamical uncertainties - which ends up feeding back on the microphysical ones. Not to be one-upped, the microphysical ones tend to interact with the dynamical ones because, if the air warms, the circulation changes. So separating the two is very difficult!

Finally, once the aerosols arrive at their (ever-changing) destination, they start reflecting sunlight and cooling the planet, which is what we want in our simulations!
How these aerosols "force" the temperature to change (which is why we call this radiative forcing) depends on their size and location.
If we had the same exact aerosol distribution in different models (we don't) we would still be other differences, due to different responses at the surface: how do clouds change, how does the land interact, how does precipitation shift.

This is what we can call the climate response uncertainty - some models cool more, some cool less; some models are more sensitive and their precipitation responds more, some less.

Using multiple models gives us an idea over the size of all these uncertainties. The "average" of the models isn't necessarily the truth, and if all models agree on something doesn't also necessarily mean they're right, but understanding and measuring the spread is useful to understand where work should be focused on in future model development, what things we need to observe, and overall how "confident" we are.

<b>What we found in brief</b>

- Models are very different, we knew this already, thank you very much.
- Aerosol microphysics is one of the main sources of uncertainties - the models "see" a much different size distribution for the aerosols they produce given the same injection. Also, too simplified aerosol treatments are just too simplified and they give unrealistic results.
- This has strong influence on the stratospheric response: ozone, stratospheric heating, dynamical changes. Biiig differences we need to narrow down ([yes we're doing more work on this as well](https://ams.confex.com/ams/103ANNUAL/meetingapp.cgi/Paper/418748)).
- We can separate quite well this source of uncertainty from the other two if we ask "ok, but what is the aerosol distribution per absolute unit of (global) AOD?"
At this point, we can look at the other two sources and see that...
-- where exactly this "tropical pipe" is located is tricky and depends on the model, so injecting at the same latitude may mean "inside" or "outside" the tropical pipe in different models
-- if we ask "how does the pattern of the response in temperature looks like per unit of cooling?" we get pretty consistent results between models, even if they are way off in other ways. Interesting! 
-- this also holds for precipitation, with some caveats. A direct consequence of the point above but still interesting!

<b>What's next</b>

As I said initially, this is not something we propose to do. You wouldn't dump stuff in one location and see where it goes and then say "Woo! We cooled the planet! Now give us money" (yes, I'm talking about those guys).
We will continue our attempts to understand how confident we can be in our models' responses. We also do this with [volcanic eruptions](https://acp.copernicus.org/articles/23/921/2023/), which are fun to study (if you're away from them).
We're using these single-point injections to better understand the response to more complex simulations that leverage multiple injection points to avoid changing the climate as much as we can, not just focusing on global mean temperatures. We already have these simulations with [one model](https://www.pnas.org/doi/10.1073/pnas.2202230119) - ok, [two](https://gmd.copernicus.org/articles/15/8221/2022/) versions of the same model. 
[Here](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2022GL100353) an example of how to use single-point behavior to understand complex strategy behavior.
Another model in the UK, which participated in the runs for these studies, is running similar simulations and we hope to diagnose the changes we see there with the changes we see here.
Comparing these two models will be a very interesting, first of its kind testbed. I am very much looking forward to those results.

