---
layout: post
title:      "First Project Time"
date:       2019-02-07 23:25:25 +0000
permalink:  first_project_time
---


I went into this week pretty excited – nervously optimistic – because it was finally time to build something of my own, something that I would have some actual stake in and control over. Being “from” Denver I see shows at Red Rocks Amphitheatre as much as possible. It’s an incredible venue, if you’re ever in town GO SEE IT, even if there’s not a concert happening.

I wanted my CLI gem to scrape the Red Rock’s website and return a list of shows. From there a user could select any concert and view the specifics – date, time, openers, ticket information, etc. I started out running Bundler to create a basic file tree and then used this genius [ScraperChecker](https://repl.it/@jenn_leigh_hansen/ScraperChecker?language=ruby) to target specific data (so much easier than attempting to do so from within the Learn IDE). 

Once I had the foundation and data in place it was only figuring out the logic of my CLI and how I wanted the user experience to actually flow. I did go down a rabbit hole at one point, writing a method that was needlessly complex and that shockingly didn’t work. It reminded me of that [scene](https://www.youtube.com/watch?v=4LLny5slQvE) from Contact (written by Carl Sagan!) where Jodie Foster’s character references [Occam’s Razor](https://en.wikipedia.org/wiki/Occam%27s_razor), the scientific(ish) principle that the simplest solution is more likely to be correct. Once the CLI was functioning properly I checked my formatting and added some color with the colorize gem (and made some small ASCII-ized Red Rocks). 

Here’s a local playing at Red Rocks, the real jams begin at 2:27:

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZyGgnlbDAZY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


