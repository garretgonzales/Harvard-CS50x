#SCRATCH PROJECT - Harvard CS50x
 -------------------------------------------------
<i>Week-0</i> 

<b>Description:</b> KIRBY IS HERE IN SCRATCH! HELP HIM FEND OFF INCOMING PROJECTILES!

-------------------------------------------------

<b>Sprites:</b> Kirby (ver.1 & ver.2), Projectile (TBD)

<b>Scripts:</b> Moving projectiles, Kirby Reaction/State, and Contact w/Projectile

<b>Conditional:</b> If projectile is hit first, if projectile hits first

<b>Loop:</b> Moving projectiles until... TBD

<b>Variable:</b> State of Kirby. (Activation)
  - State of Kirby will be whether or not ver.1 or ver.2 of Kirby Sprite is visible.
  - var activated = boolean. 

<b>Sound:</b> Smack/Punching noise on contact. 

-------------------------------------------------


<b>Projectile Contact:</b>

 if projectile is hit
   projectile vanishes
 else projectile hits
   kirby moves back

<b>Kirby Reaction/State:</b>

 if Kirby is not 'activated' (false)
   ver.1 Kirby stays still
 else if Kirby is 'activated' (true)
   ver.2 Kirby is put in place

<b>Moving Projectiles:</b>

 if green flag is clicked
   projectiles move towards Kirby
 else
   do nothing.
