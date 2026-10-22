# BRUTAL-JOHN-2-VR
VR Mod for BRUTAL JOHN 2

<img width="448" height="442" alt="Adobe" src="https://github.com/user-attachments/assets/e9a790b9-a52c-473c-81b5-149531cf32e4" />

BRUTAL JOHN 2 VR  v0.1.21 (test on quest 3 VDXR)
========================

Install
-------
1. unzip into the game folder (next to the game .exe).
2. Start SteamVR / Oculus / Virtual Desktop (as the OpenXR runtime), then the game.

Controls
--------
Menus, vehicles, cut-scenes, mini games (arcade machines, air hockey): a normal Xbox gamepad (no laser pointer)
  triggers = LT / RT, grips = LB / RB, A B X Y, both sticks, stick clicks = L3 / R3

In a vehicle (otherwise the normal gamepad):
-
  L3 ....................... 1st person (driver's seat) / 3rd person
  
  Hold X (0.6 s) ... gun laser on / off (vehicles with a gun)
  
  Vehicle gun ............. aims where your right controller points
  
  1st person ............... right stick left / right steers (like the left stick)
  
  Normal play (on foot):
  Right trigger ............ RT (fire) 
  
  Left trigger ....... LT (kick)
  
  Right stick left/right ... turn (snap\smooth
  
  Right stick up ........... LT (kick)

  Left grip (tap) .......... RB (grenade)
  
  Hold left grip ........... the left stick is the D-pad
  
  Right grip ............... LB (alt fire)
  
  Y ........................ Y (flashlight) 
  
  Dual weapons ............. both triggers fire (LT = the gun in your left hand),
    
  X tap .................... X (reload)
  
  Hold X (0.6 s) ... laser on / off
  
  Weapon wheel open ........ the right stick is the game's (choose a weapon)
  
  (Every one of these can be changed in the VR menu / [Controls] in the config.)

Always:
  A + B together ........... Start (pause menu and back out arcade)
  
  X + Y together ........... Back / View
  
  Tap both stick clicks .... re-centre the view
  
  Hold both stick clicks 1.2 s ... VR settings menu
    (right stick up/down = choose, left/right = change, A / trigger = select, B = close)

Weapon in your hand (6DOF)
--------------------------
Every weapon, its arms and its laser are adjusted on their own and saved per weapon:

  Hold L3, press Y ... adjust the WEAPON      - hold the LEFT grip to grab it and move / turn it

  Hold L3, press X ... adjust the WEAPON ARM  - hold the LEFT grip to grab the right hand
  
  Hold L3, press B ... adjust the FREE ARM    - hold the RIGHT grip to grab the left hand
                       (dual weapons: adjusts the SECOND GUN in your left hand)
                       
  Hold R3, press Y ... adjust the LASER       - left stick = move its start left/right/up/down
                                                (hold the right grip: forward/back), right stick = aim it
                                                
  Hold R3, press X ... adjust the SECOND GUN'S LASER (dual weapons), same sticks as above
  
  While adjusting:  A = save (for this weapon),  B = back to the default
  
  Shots and throws go from the muzzle along the laser. "Use" points where your right controller points.
  
  The arms hang from your shoulders (VR menu: shoulder position, or switch it off).

Hand HUD
--------
  Left hand: health / armour / stamina bars, the objective above them.
  Weapon: ammo to the right of the weapon, the timer below it.
  Size and positions: VR menu > Hand HUD / screen (or [UI] in the config).

  Issues
  -
  * arcade show 2 images but still playable (RB start)
  * when leaving arcade (A + B together) one screen stay for about 15 sec
  * flame thrower dual not working correctly
  *  have to turn your body on motorcycle when turning
  *  guns some time adjust a little fome where you save position but easy readjust live (Hold L3, press Y)  
  *  and more......  

