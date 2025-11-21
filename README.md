# UnityForDummies
This is a unity guide for bug fixing, issues and etc.
If you found another fix or something you want added, email alecleseman@gmail.com

# Creating your first project
Assuming you have [unity](https://unity.com) installed.
Create a new project, for this guide we are using 2D, so click on 2D.

# Collisions - Bug Fixing
Collisions are the most annoying things.
Let's say you have a jumping script using grounding with OnTriggerEnter2D, and the ground you made has the tag and the collider, BUT you still can't jump.
The issue is NOT the script, Try these fixes.
Create 2 Box Colliders(1 if you already have one) and set ONE of the variable "IsTrigger" to true and leave the other false.
Make sure if you are detecting tags, you created and SET the tag to the ground, Some people will create it thinking it auto set it, but it didn't and you spent hours of bug fixing.

# Common security problems
Please don't publish a game with a security issue, update your unity version to the newest.
Unity had a recent problem with security with some versions, update to the f2 version or you might encounter lots of bugs

# Unity editor bugs
I've encountered one single bug with the ui/inspector, it hides stuff and cant access giving you a bunch of errors, like you can't access the inspector with lists and stuff because its blank
This is not a skill issue, its unity being crappy.
How to fix - Go to preferences and go to editor, Then set IMGUI to true.
This usually fixes the problems.
If your having some issues with that, and you found a fix, please email me.

# Indentation
When creating scripts, and its not working, try using proper [Indentation](https://www.w3schools.com/python/gloss_python_indentation.asp) like python.


