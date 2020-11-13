# Proposal

## What will (likely) be the title of your project?
Bone Sword
TODO

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")
A character collects fragments of a bone sword and throws it at a boss.

TODO

I plan on using the template that will be created from the Mario video. I would really like to possibly create some custom assets, but I think that may 
just be something to do in the future when I have more time and experience. My main objective is to have the user collect 2-3 bone fragments, hopefully each being
in their own seperate room. The user will have to do some sort of simple act to be able to obtain the fragments, possibly something such as jumping at a certain
place or reading a scroll. Once the user collects the bone fragments they have to press a button to forge the Bone Sword. The player will then face the final 
boss, which I will have be a set number of pixels away. I would want to somehow just attatch the boss to the user's movements as to avoid having to make a complex AI,
so the boss would be a set number of pixels away from the play, it will be floating and possibly shooting projectiles. If the player moves forward 10 pixels then so does the boss,
to defeat the boss the player has to push a button to throw their sword at the boss.

TODO

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

I am a Geology major and while this is not part of a class, I have been speaking with a professor once a week who has shown me a free software called QGIS. 
QGIS uses python and has a python console. Seemingly there is a way to use QGIS modules in an external environment such as pycharm. I would get these modules to
work outside of QGIS and then create a program using them that allows the user to build a virtual raster using .TIF files in some sort of input. I have been having
an extremely difficult time doing this though because I can't get QGIS's modules and version of python to work in an external text editor, I am doing this on my
PC and every time it just says pycharm has no python interpreter, so I will keep playing with that and maybe it will be an option if I can finish it in time 
and it is final project worthy. 

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

TODO, if applicable

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

The player is spawned in, can pick up at least one bone fragment that they then throw at the boss.

TODO

I have not started the Mario videos yet but I hope to this weekend. I think that I can hopefully do what I said above, but additionally I would like to make it multiple
bone fragments that you combine, and that you have to go into seperate rooms to get. 

TODO

A best outcome will be having the player able to enter different rooms that have different scenarios that you must complete to be able to unlock the bone fragments
. Also having death would be good. Custom assets, character creation, hints hidden throughout gesturing the user to do specific things but never explicitly stating them
, the boss shoots projectiles that if the player gets hit by once they die, but the player is able to jump to avoid them (maybe I could do something like the progressively
more unfair pong game where if the player takes too long the boss just locks on and defeats the player with ease). Also, for the scenarios to unlock the bone
fragments, ideally it would be little puzzles and combat scenarios, I think very simple puzzles may be realistic, but I am not sure so I'll put it here.

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

Obviously I need to learn all of the skills in Mario, I need to add the ability to add death using Lua in Love, since the project will be built off of the Mario video
I need to learn how to add a second character model since I don't think the Mario video shows that, I would need to learn how to make some sort of inventory system, even
if it is not a UI, but just an internal tracking of the character's current bone fragments, I would need to learn how to animate the throw, but I think it would be very
similar to the steps used to get the ball originally moving in the pong video. I would need to learn how to lock the boss character model to the player's movements
and only have this happen when the player is within vicinity of the boss. This is just an overall summary of the skills I may need, but at a bare minimum
I would need to learn how to pick up a bone fragment, and throw it at a boss that stays a certain distance away. To do this I will use the Mario and Pong code
as a strong basis to understand what the code does, I would use the LUA documentation, as well as looking for previous forums posts on things such as stack overflow if allowed.
Finally, one other thing I just thought of that I could learn, an easy way to do hints could be when the user picks up
the item by pushing a button, then if that item is a bone fragment there will be a little dialog box with a seer speaking
and giving a hint to the player that they have to connect the bones.
