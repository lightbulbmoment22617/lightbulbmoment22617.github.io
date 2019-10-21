---
classes: wide
header:
  overlay_image: /assets/images/oxford.jpg
  caption: "Presenting at the Oxford Hackathon"
permalink: /portfolio/index.html
date: 2019-10-21
---
# Projects

Here are a few examples of projects I have worked on in the past. 

## IoTea: Oxford Hack 2017
<img src="{{ "/assets/images/iotea.png" | absolute_url }}" width="30%" hspace="20" align="left">
At the Oxford Hackathon 2017 my team and I used an old kettle, a valve stolen from
a dishwasher, a tea brewing vessel and a box built in the freezing cold at 4am out of scrap wood 
to create 'IoTea'. IoTea is a tea brewing machine controlled by a Raspberry Pi: automating the process 
of brewing loose-leaf tea. We produced a short video summarising the project - you can watch it [here][2]. 
Our slightly unhealthy commitment to this project (there was no sleep involved) as well as its successful 
end result earned us prizes from both Microsoft and Facebook. 

## SkyShots: Oxford Hack 2018
<img src="{{ "/assets/images/skyshots.jpg" | absolute_url }}" width="30%" hspace="20" align="left">
Returning to the Oxford Hackathon in 2018 my team and I were eager to take IoTea to the next level. Our
idea was 'SkyShots' - the bartender on a turret. This smart bartender would be able to locate your face
and fire your drink directly into your mouth (saving you the considerable time and effort it takes to 
drink from a glass). We built a small wooden platform which could rotate on two axes thanks to some servos 
(controlled by a Raspberry Pi using PWM) upon which we could mount a sawed-off electric watergun. At the 
front of the platform we attached a USB webcam and by using Microsoft Azure's face recognition API along 
with a bit of maths we could point the watergun directly at the user's mouth to deliver a refreshing drink! 

## HexLedger: Hack Harvard
<img src="{{ "/assets/images/harvard.jpg" | absolute_url }}" width="30%" hspace="20" align="left">
My team and I expanded our horizons by spending a few days in Cambridge, Massachusetts to explore
and attend the Harvard Hackathon. Here we created 'HexLedger', a blockchain-based hacker profile.
We used the [multichain][1] architecture to build a decentralised database of hacker projects and 
the prizes they had won. This worked by creating ledgers to store data on both users and hackathons,
with each hackathon having its own token (essentially a cryptocurrency). Hackathon organisers could 
then issue these tokens to users as proof of attendance or prizes won. On our web interface, one could
visit a specific user's profile to see the hackathons they had attended and read about their projects. 
As winners of the "Most Useless Hack" award, we left Boston proud and successful. You can view the source
code over [here][3].

## Analysis of my Google Location Data
To practise some data analysis I decided to have a look at my Google location history. This was 
a really interesting project for me and helped me brush up on some key skills. You can have a look
at the analysis (in two jupyter notebooks) [here][4].

## gba-forever
I still have my Gameboy Advance safe at home and I intend to keep things that way. My friends and I all 
have fond memories of playing with this handheld console so we decided to spend a weekend learning how
to develop for it. This involved working very close to the metal with limited specs and we learned a huge 
amount in a short space of time. While we didn't end up with a fully fleshed out game, this project is 
certainly something we would all like to return to at some point. However you can view the source code
for what we worked on [here][5]

## deliver.ai : System Design Project
<img src="{{ "/assets/images/deliverai.jpg" | absolute_url }}" width="30%" hspace="20" align="left">
The System Design Project is a group project all Computer Science students at the University of Edinburgh
take part in. It involved working with 8-10 other students to build an assistive robot. We had access to a
Raspberry Pi as well as the LEGO EV3 and EV3 development kit. I was project manager of 'deliver.ai', a secure 
delivery robot for an office environment. This was essentially a locked box on wheels - users could log 
into our web app where they could send / receive deliveries from other users. We envisioned a fleet of 
such robots handling all the office-mail delivery for a particular floor within a building.

## orient-golf
As part of my internship at the [Centre for Speckled Computing][6] at the University of Edinburgh, I created
an Android app to allow golfers to analyse their golf swing. The centre develops small wireless sensors called
'specks' which are able to process and transmit a lot of useful information through components such as a 3-axis 
accelerometer, gyroscope and magnetometer. I used a stream of quaternion data from one of these sensors worn on
the wrist to model the golfer's swing plane, allowing them to use my app and check they were on the correct plane.

<!------------------------------- FOOTER --------------------------------->

[1]: https://www.multichain.com/
[2]: https://www.youtube.com/watch?v=qtW3_EyxSd8
[3]: https://gitlab.com/teambrewlabs/cryptohexes
[4]: https://github.com/lightbulbmoment22617/google_location_data
[5]: https://gitlab.com/teambrewlabs/gba-forever
[6]: http://www.specknet.uk/