quickndirtycollisions
=====================

Animation of NYC Vehicle Collision Data using D3 and Leaflet

Forked from https://github.com/chriswhong/phillyBikeThefts

NYPD released granular collision data for the first time on 7 May 2014, I wanted to make a quick visualization out of it to see what the patterns looked like in my neighborhood.

This viz is not-so-elegant, because it's a loop that just runs forever.  It increments a unix timestamp and pulls the thefts since the last increment from a CSV, draws them, and fades them out quickly. 

See it in action at:  http://chriswhong.com/sandbox/collisions


