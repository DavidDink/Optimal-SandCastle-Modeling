# MCM Project

So far I've only uploaded the radioactive decay file from my last year simulation course. I took an object oriented approach so it might be slightly confusing to read through at first, but I believe it's gonna be really useful for us to keep this approach, since we'll have to run the same simulation for various types of sandcastles (thus the object oriented approach)

Tonight, I'm gonna spend some time studying water waves and try to model them in a code file. So far, I believe I'll use 3 parameters as random variables under normal distributions. They will be: frequency of waves (how often one comes), height of waves and speed of waves.

(btw note: I accidentally came upon python's 3D plotting options, and I found some really cool ways to visualise our 3D geometric shapes. I spent some time on it and I created cubic and pyramidal castles so far; I even imagine that I could create animations of the castles breaking over time (if we have spare time towards the end) to make pretty visualisations)

(31 May):
I uploaded the 'master' file called "Sandcastles_v2", which contains the code for creating and visualizing the castles, creating the waves, and hitting the castle with each wave. The methods that need refinement are: the collapsing of the castle after each wave hit (tetris-like so far), the force function for each wave, and more realistic wave parameters.

(4 June):
I uploaded some new changes (in "Sandcastles_v4") which include comments to explain what each method does and how the code "flows". The code is ready to include the tides and the force function as we discussed in yesterday's meeting. I'll probably include these in the next few days and upload the updated version.
