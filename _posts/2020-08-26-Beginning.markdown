---
layout: post
title:  "The Beginning"
date:   2020-08-27 01:32:09 -0400
categories: ACI, BCI, paper writing, blog
---

I'm honestly just going to jump right in because I'm avoiding the writing of multiple papers and I think this is a great way to wrap up the day. Honestly, I meant to post this earlier today, but life got in the way. Apologies, but for now this might be a mashup of a to-do list and documentation.

There's a little background on some of the completed items: My team participated in the student design challenge for the Animal Centered Computing Summer School hosted by LETI University in St. Petersburg and WE WON! As part of the win, we were invited to write an extended abstract / demo paper on "technologies for monitoring the welfare of bears in captivity" for the ACI conference. I will probably post more about it later once it's closer to the conference.

Secondly, I work on in-ear methods for detecting EEG and we're analyzing the data that we've collected this past summer. Again, if it gets accepted to the conference, I'll post more about it.

<h5>Things I completed today: </h5>
- Worked on the ACI submission
- Got the BCI data split out by trial and converted to .mat files for the EEG study that we’re working on.
- Got this blog working!

<h5>To prep for tomorrow: </h5>
- 7a discussion of the ACI submission with team members from around the globe.
- Interview with Triplebyte on Animal Communication and Machine Learning. I'm really excited to learn more about the article.

<h5>Notes on how I feel about life, PhD, and everything related to 42:</h5>
There were lots of thoughts today. First, I keep doing this shit where some of my data preprocessing is automated and the other half is manual. I could probably figure it out, but that takes more time that just automating it sometimes. And time isn’t really something I can afford to do at the moment. 

Also, not all days are tough days, but today was especially rough. I'm building a new board to put in the Smart Toys and for some reason (e.g. possible shorting, temperature issues (thermistor), possible damage due to thermal cycling from multiple attempts to surface mount solder the components to the board) the LTC4124 isn't routing power from BATT to VIN. After multiple attempts to understand what is going on (e.g. trying to re-seat the component, trying to remove solder because maybe it's shorting somewhere, checking for strange temperature drops through resistance, etc), well I've decided that I'll try some of the things below first, but then if that doesn't work I'm just going to decide to start from scratch and build this board forward (starting from the LTC4124 and moving towards the buck boost converter, etc). 

<h6>Things to try tomorrow (per Scott's suggestion): </h6>
- jumper the NTC pin to VCC and bypass the temperature protection
- it's possible that the buck boost converter is shorting something so the starting from scratch isn't a terrible idea
- I checked the thermistor to see if the resistance was dropping significantly when turned on -> need to check to see if the voltage is dropping and if so, by how much


OK. This got more technical than I expected. After banging my head against the table for an hour or so, I walked home while talking to my mom and then ended up watching a couple of episodes of *Terrace House: Opening New Doors*. I really hope Tsubasa and Shion end up together.

