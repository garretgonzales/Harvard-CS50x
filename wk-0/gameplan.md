#SCRATCH PROJECT - Harvard CS50x
 -------------------------------------------------
<i>Week-0</i> 

<b>Description:</b> MEGAMAN IS HERE IN SCRATCH! HELP HIM FEND OFF INCOMING PROJECTILES!

-------------------------------------------------

<b>Sprites:</b> Mega Man (ver.1 & ver.2), Projectile (TBD)

<b>Scripts:</b> Moving projectiles, Mega Man Reaction/State, and Contact w/Projectile

<b>Conditional:</b> If projectile is hit first, if projectile hits first

<b>Loop:</b> Moving projectiles until... TBD

<b>Variable:</b> State of Mega Man. (Activation)
  - State of Mega Man will be whether or not ver.1 or ver.2 of Mega Man Sprite is visible.
  - var activated = boolean. 

<b>Sound:</b> Smack/Punching noise on contact. 

-------------------------------------------------


<b>Projectile Contact:</b>

 if projectile is hit
   projectile vanishes
 else projectile hits
   Mega Man moves back

<b>Mega Man Reaction/State:</b>

 if Mega Man is not 'activated' (false)
   ver.1 Mega Man stays still
 else if Mega Man is 'activated' (true)
   ver.2 Mega Man is put in place

<b>Moving Projectiles:</b>

 if green flag is clicked
   projectiles move towards Mega Man
 else
   do nothing.
