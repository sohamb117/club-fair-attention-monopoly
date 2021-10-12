# Club Fair Attention Monopoly

I built this app (inspired by [@lachlanjc](https://github.com/lachlanjc)'s own [schacks-demo](https://glitch.com/edit/#!/schacks-demo)) to advertise my [Hack Club](https://hackclub.com) at our schools' club fair, where all the incoming freshman come to sign up for clubs. My goal was simple: attract as much attention as humanly possible. That is what I did.

It's a website that has a phone number on the screen, and when someone texts that phone number with the name of a color, the screen changes to that color. It has a queueing system to make sure that every color texted gets shown on the screen & there's a live feed in the top left hand corner.

If you'd like to use this yourself, here are the steps:

- Make a Twilio account
- Load it with credit and purchase a phone number
- Host this code somewhere (heroku, Glitch, repl.it, your own server)
- Setup a webhook with Twilio to /twcolor
- Open the site
- PROFIT!

![Image of students at our booth at the club fair](club-fair-1.png)

![Another image of students at our booth at the club fair](club-fair-2.png)

# UPA Hack Club

This has been modified for use by the UPA Hack Club. All credit goes to the original creator - I'm only pushing my changes for use for future club fairs. 

#### NOTE:
This is already configured to run in replit, so just use that. 