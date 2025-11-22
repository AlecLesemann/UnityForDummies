# Collisions - Bug Fixing
Collisions are the most annoying things.
Let's say you have a jumping script using grounding with OnTriggerEnter2D, and the ground you made has the tag and the collider, BUT you still can't jump.
The issue is NOT the script, Try these fixes.
Create 2 Box Colliders(1 if you already have one) and set ONE of the variable "IsTrigger" to true and leave the other false.
Make sure if you are detecting tags, you created and SET the tag to the ground, Some people will create it thinking it auto set it, but it didn't and you spent hours of bug fixing.

