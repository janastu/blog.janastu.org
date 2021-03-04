---
layout: post
title:  "Sculpting a Webinar Pi - The Pi 4 Debacles"
excerpt: "In order to make technology accessible, you must foster transperency and care"
author: Dinesh, Sanketh and Micah
featured: true
image: https://i.imgur.com/ij8lHFO.jpg
toc: false
comments: true
---
# Sculpting a Webinar Pi - The Pi 4 Debacles

This is a semi-sarcastic take on producers of technology and their assumptions - one specifically. Sarcasm-anger will be marked in italics. 
> *Like that's all it takes to fix this hot mess*.
> 
As we argued in our article for **[A case for a Webinar Pi](https://blog.janastu.org/a-case-for-a-webinar-pi/)** - the need for a community-based local device was becoming evident to us. We needed a general purpose computer that was configured and designed for the local context. These general themes started to come from our recent project in Mirzapur, where we worked in collaboration with young girls and women to build capabilities that could lead to a local creative gig economy. During the course of the project, the specific needs that became apparent were: 
- a local device installed on site - physical site
- can be used by many people - community use
- access from Bengaluru - for tech support
- processing power that allows for creative production - music, sound, film and picture editing
- it should be friendly to users that would encounter such a device for the first time
- WiFi support so that we can connect through the mobile data network - smartphone hotspot
- locally available and repairable peripherals
- making it independant from grid power
- audio-visual communications so as to nurture systems of care and collaboration not obstructed by the boundaries of "literacy"
![](https://i.imgur.com/ij8lHFO.jpg)

Due to lockdown, the situation on the ground changed where we had to address the need of the girls that we are working with to attend online classes. Our device now had to accommodate webinars. Aamne Saamne Pi (ASPi - a webinar device built on the Raspberry Pi) was conceptualised for collectives and groups of college-going girls who have not been able to continue their vocational education and schooling because of the ongoing pandemic. This is a substantial contribution to edu-tech as it seeks to address the problems of connectivity and schooling faced by most of the households in the country. 

Generally, before we choose a device or technology to work with, we wait for it to mature. Our resources are frugal and we walk a fine line between experimenting and implementing. However, by placing our hopes in the promise of the "inclusive" design of the Pi4 and forced by the urgency of the lockdown, we started working with it as soon as it launched. The Raspberry Pi Foundation is *the Open-Source Foundation with a community of tinkerers* and we hoped that the community forums would give us the support we needed. Little did we know the loneliness, self-doubt and constant sense of colonial gaslighting that would await us during this journey. It seemed like only we were facing these problems. 




![](https://i.imgur.com/7SXWJye.jpg)
*Raspberry Pi 4 Tech Specs but after a Truth Serum*

Each issue we faced brought up one more obstacle to getting a cheap device out onto the field. *The most crippling questions we had, however, were:*

## *How do I turn this on?*

The most frustrating thing about the Pi 4 is that thunderbolt symbol that shows on the screen. This happens whenever the microcomputer has inadequate power as a supply. Most often, it was an issue of low amperage. The Pi requires a 5V 3A power supply. To use it in a remote location we needed to account for the lack of consistency in power supply. The power had to be given from a stable power source like a battery or a powerbank. 

The Arduino could accomodate a 12V 1A battery. If the Pi 4 was designed in that way, it would have made this effort a lot more easier. With all the newer peripherals, it is natural that the board would need a higher supply. But with just a USB C-type power adapter and no thought for higher wattage options. Lead-acid batteries are more ubiquitous than power from the grid in rural locations. Lead acid batteries would also have been helpful in integrating the ASPi with solar power. 

We were then forced to look for suitable powerbanks that outputs 5V 3A. These were extremely hard to find. Even when we did find some, the thunderbolt symbol would pop up and show that there was a low voltage supply to the Pi. The official power adapter would also give us the same issues. The much more difficult problem was that it was driving up the costs of the device. With each new problem that the Pi gave us, the costs rose and deploying it in a remote location became that much harder.

> not any usb cable could power it up. some eia cable only. their solution was to buy their cable

## *Why try the WiFi*
India has a lot of landscapes where the network connectors are few and far in between. The spaces for populations to function and live in are also much more spread out. In these places, the network coverage is much more limited. *How do we bring a device that functions amazingly well as a self-jammer to any of these locations?*. The Pi 4 has interference issues relating to its USB ports (power, audio), HDMI ports (display) and WiFi. This kind of interference is crippling because of how many functions it disrupts. The worst affected among these in our case was the HDMI display, the WiFi would not work if the display was connected.And lo! The Wifi would come back on after the HDMI was disconnected. *We don't understand how it passed the FCCI certifications with such a big flaw.* The device would only connect to a WiFi signal reliably when the strength is above -60 dB. This means that the Pi 4 is only meant for those with a strong signal. We also couldn't find documentation for this issue in any of the more visible forums. *How do they still claim the use of RPi 4 outside their typical urban user and their typical settings?*

## Other Issues - 
### *Raspberry Pi or Egg Fry*
The Pi 4 also had so many other issues. The processor heated up to a point that it would become unusable in hotter climes. We had to install a heatsink and even then it was difficult. 

### *Who stole our cameras?*
We also needed to make the camera separable so that it would be conducive to use by multiple people at the time and for show and tell needs. This separate camera acquisition was made especially difficult by the whole stock of cheaper cameras being sold out. We suspect that this has something to do with urban *tinkerers* in the lockdown. 

### *Micro-HDMI but Macroheadaches*
The micro-HDMI ports have been used for the display. These peripherals are not available in the locations that the ASPi was supposed to be deployed in. Further, the slots are so close to each other that mHDMI to HDMI adapters would not even fit. Adaptors also make the device heavy and can easily damage the port. How would repair or replacement work in those settings?

For all its '*Community*', the Raspberry Pi 4 still holds its Eurocentric design over our heads without talking about their flaws, caveats, exceptions. The design makes it clear what its assumptions are:
1. *Power is ubiquitously available and can be sourced through a plug and USB cable anywhere, therefore, there is no need of providing any other alternative*
2. *So what if weak Wifi is jammed by the HDMI and USB3 ports, everyone has good strong wifi signal, generally*
3. *Use of emerging peripherals without a thought of what compatibilities it would break in non-western countries is not reckless*
4. *It will be set up in safe, indoor, urban settings, where replacement if not repair is immediately possible*

In order to make technology accessible, you must foster transperency and care. When tinkerers from non-western markets pick up the device, they are expected to dig through walls of forum text written in what might be their third or fourth language. Problems that would be known by the Foundation's development team become *obscure obtuse references to indirect issues in the 234th page of a feuding forum*. 


Is it not much simpler for the "Foundation" itself to discuss these issues and make it available in multiple-media formats? [Janastu](https://janastu.org) has, for the last decade, been trying to build tools that can help bypass levels of literacy through renarrative tools. We understand the effort involved and we would be glad to help if only you would try. 

We had looked at The Pi 3 for this implementation as well. It was interesting as a microcomputer to use in this way but lacked the RAM for any intensive storytelling applications. This was important for us as we wanted to use the Webinar Pi in the context of digital literacy projects in remote locations. We needed more RAM for these audio-visual applications. We would have just been happier with the Pi3 with more RAM.

A claim of making hardware accessible doesn't just mean that you put out the design and specs into the public domain. Why can you not be open about your flaws as well? Why curate your public image if you deem yourself a foundation with community tinkering at its heart? Is it so hard to talk about the issues of localisation in a truly holistic way. The Pi 4 needs a lot more to function when put outside the four walls it was designed in. Why not acknowledge that labour and support this process of adaptation and reconfiguration? 

As an organisation working in community-based technology for 20+ years, often on very frugal resources, we have learnt a few things about choosing technology to suit our needs. We work with small contexts and resources. Experimentation with new devices and technologies too fast give us only pain. Our rate of adoption is therefore much slower than the market, so as to be sure that we have developed the capabilities needed to handle the new challenges. Well-intended advice from our friends to use different microcomputer packages, unfortunately, was something we couldn't afford. Unfamiliarity to technology, linguistic barriers that barricade the rhizomatic growth of these networks and frugal fragile movements is the reality of our work. 

Adopting the Pi 4 was a mistake that cost us a lot of money, trust and 4 months of our time. 


