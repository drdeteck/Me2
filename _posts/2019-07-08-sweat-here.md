---
layout: post
title: Sweat Here - Hackathon project
---

Last March, [Amilia](https://www.amilia.com/) and [Decathlon](https://www.decathlon.ca/), the outdoor shop, organised an Hackathon about making sports more accessible through coding. GSoft was there represented by 2 teams of dev, coach, data scientists and business professionnals. Our team was formed of :
- Yohan Belval
- Étienne Labrie-Dion
- Everic Lauzière
- Francis Thibault
- Alexandre Arpin
- Me (Philippe Lavoie)

The first hour, we explored the available APIs by both Amilia and Decathlon to finally decide to make **Sweat Here**.

![Sweat Here Logo](/me/assets/images/sh-logo.png "Sweat Here Logo")

Our goals were three-fold :

1 - Be able to find an activity related to a sport around you.
------------

Our base feature was to search for a sport and find all courses and activities related to that sport around you. For that, we used Amilia’s API for the activities and the Decathlon API for the sports.

![Sweat Here Screen](/me/assets/images/sh-screen1.png "Sweat Here Screen")

2 - Have a mobile version to put directly inside the Decathlon stores.
------------

After the basic function, we decided to do a quick win and display them on a kiosk mode. Let say you are inside a Decathlon store and next to the yoga mats, there is an iPad that tell you where the yoga class are in the neighborhood! Wouldn’t that be great?

![Sweat Here Screen](/me/assets/images/sh-screen2.png "Sweat Here Screen")

3 - Gather query data to find trends and most popular sports around.
------------

Finally, every time a user makes a request, we gather that data point and make it so the admin of the platform can view a geolocation of the request. This can be super useful for under-served area and store promotions. The map assemble the data points into an heat map we can then join this with the different activities and help focus sport types where the requests are. This is an important part of the project where the service we give to user can be improve with usage.

![Sweat Here Screen](/me/assets/images/sh-screen3.png "Sweat Here Screen")

It’s super important in an Hackathon to demonstrate the value simply. This reinforce your elevator speech and demonstrate a true business awareness. This is often the extra step that makes a difference. We had a great time with Amilia’s and Decathlon’s teams and will surely repeat this exercise. 

In the end, we ended up winning the competition with **Sweat Here** !
