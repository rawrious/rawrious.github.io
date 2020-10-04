---
layout: post
title:  "Everything is Going Terribly Wrong"
date:   2020-09-01 05:11:00 -0400
categories: ACI
---


Working on the dissertation today :/. You're not going to get a whole lot out of me. 

Catalina basically bricked my machine. While I've been able to keep all my data (I back up regularly), I've lost a lot of time today attempting to drop down to Mojave. :(

However before everything bricked itself, I was able to try: 
<h4>Things to try from the last time:</h4>
- jumper the NTC pin to VCC and bypass the temperature protection >>> this didn't change anything. I'm really worried now.
- it’s possible that the buck boost converter is shorting something so the starting from scratch isn’t a terrible idea >>> I built the board from scratch only using the LTC4124 and its components. It's still not outputting the right voltage.
- I checked the thermistor to see if the resistance was dropping significantly when turned on -> need to check to see if the voltage is dropping and if so, by how much >>> voltage isn’t dropping. resistance is about the same