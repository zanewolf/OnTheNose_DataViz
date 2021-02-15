# On The Nose

## Overview

This is a data visualization I have made as part of my #100DaysOfCode challenge. It reinforced previously-learned d3.js skills and forced me to acquire new ones (specifically d3 force simulations). I manually scraped the data from Hans Florine's book, and the only code borrowed was from Jim's example setting up the force simulations. Everything else I coded by hand. 

I went with a minimalistic design, choosing to use color sparingly as a way to emphasize the record-setting climbs, in addition to the increased opacity/stroke size over the non-recording setting climbs. +1 for encoding redundancy

### Project Planning 
In Appendix B, Hans Florine has a log of the date, partners' names, the time each climb took, and if the climb set any records. 

I decided to visualize this data project first because I have several climbing-focused projects on my idea list, and this is the only one where the data came to me (the book was a gift), and all I had to do was transcribe it to excel. 

At this point, the format of the datavis is a bubble chart, a la [Jim Vallandinghma's 'Creating Bubble Charts with D3V4'](https://vallandingham.me/bubble_charts_with_d3v4.html). I've never made this type of vis before and I'm looking forward to the challenge. 

- Background and Motivation
	- Pure curiosity and interest in making a bubble chart. 
- Related Work or Inspiration
	- see Jim's example above
- Audience
	- What do they know? What are their interests? What visualization literacy do they have? etc.
		- This work is intended for a climbing audience that is familiar with the race for the nose record and Hans Florine. 
		- to augment the understanding for non-climbers, I'll make the overview page more informative with some backgorund
- Questions
	- How many climbs of the 100+ recorded in the book were record-setting, and of what record? 
	- Is there a correlation between time and number of partners? 
  	- When did the record-setting climbs occur, year/month? 
- Data
	- Hand-collected from the appendix in On The Nose
- Data Cleanup 
	- Date formats vary between simply Month/Year and specific Day/Month/Year, so I won't be able to show data beyond the month level of detail. 
  	- Timing reports likewise vary between specific Hours:Minutes:Seconds to "About 3 days". In the circumstances where time is not given in hours, I will round to the closest interval of 24 (e.g. 'about 3 days' = 72:00:00)
- What is the final product? 
	- A bubble chart that the viewer can step through, which will sort the climbs (individual bubbles) according to whatever factor the user has chosen (year/month/number of partners/ record-setting/etc). 


### Post-Mortem

Things I would do better/refactor if I wanted to spend more time on this project: a more stylistic tooltip, a more effecient/less repetitive way to create the labels in the first place - including farming it out affinity and then just including an image-, and maybe try to make it mobile-friendly, which is something I've never prioritized before. 

In the beta testing, the original version of the Nose vector graphic was hard for non-climbers to interpret at first glance, so I added trees to hopefully give it better context. It was hard to test whether this change elicited an improvement because at that point all the beta-testers knew what they were looking at, lol. 

A friend also suggested I look into material design and try to style it using the most modern stylistic guidelines (e.g. using cards, different fonts and color choices), and that is something I think I'll implement on the next project. 

Overall, I'm really happy with this. However, I will **always** be accepting feedback, so feel free to email/tweet me your thoughts. 



