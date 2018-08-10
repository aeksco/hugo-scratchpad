---
title: "Why Not Change Your Clothes?"
github: "wncyc"
website: "https://github.com/jcolekaplan/WNCYC"
---

Have you ever wanted to know whether or not there were any washers or dryers available in your residence hall, without needing to walk all the way to the laundry room? Is finding the laundry website too much effort? Well, now you’ll be able to ask Alexa!

There's already laundryview.com, but that requires you to: 

1) Remember a URL, or bookmark it
2) Have access to a web browser

This project aims to make it easier to know the status of laundry machines in your building. You'll be able to check if any machines are available, check how much longer until a machine is available, and check how much longer your machine will be running. Maybe more!

The project has 2 parts: An Alexa skill and an API. The API is in development first. It will do the hard work of scraping the laundryview website in the background, as well as serving the information the user wants. The benefit of making an API is that other projects will be able to use the information to make their own interface, such as for people who don't have echos. 

The Alexa skill will serve as an initial basic interface for a user to interact with the API.
