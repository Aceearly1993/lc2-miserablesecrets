THIS IS A COMMUNITY PROJECT

### Summary ###

This project is a community mod aiming to create an Alucard main mode in freeware fan game "Castlevania: The Lecarde Chronicles 2" using both custom and pre-existed assets.
Because the lost of exact original design document, there's no reference to such mode so we have no choice but to add a bit of customized events, as such it may or may not fit the initial intention of original design idea of a possible Alucard main mode.

More extensive details are shared with the main branch so I won't bring more words here unless really necessary: 
https://github.com/katriellucas/lecarde-2  
We recommend play the main version (Efrain's game) before in order to avoid potential spoilers of the main game, if you care about that. 


Some of the bugfixes are also shared with the main branch.

### Q&A corner ###

<img width="689" height="497" alt="RHX`$FJZ{3G%T9%GJAG$2PA" src="https://github.com/user-attachments/assets/99103865-fb22-40a4-a962-2f4dd2284749" />


Q: What's the purpose of this project?  
A: The Alucard main campaign mode is missing from the vanilla version. As LC2 is open sourced in 2023-2024, we (the rework team) received quite a lot of request, so we want to create our own vision to describe the Alucard main mode, fulfill the previously missed opportunity.  


Q: Will there be Valmanway/Crissaegrim in the game?  
A: Our fear included: 
1) It's possible but it's not something without technical difficulties so we cannot guarantee they will be in the game (in an ideal way).  
2) We fear they will break the vanilla design or the direction goes against the original game's developers' intention badly.

Despite these, we can at least try to include it as a secret well hidden, without hindering the majority of the game.


Q: How about a super jump or a bat transform ability?  
A: It's possible, but the rework team is against the idea and it will look weird if using pre-existed events.  

### Rules on Submitting a Translation error ###

The text script is well established in 2 years and not really a subject to be dispatched again and again; Please submit a translation error only when the errors are serious and inconsistency is huge enough. Hope we can earn your understandings. 



Discuss the reworked version of Lecarde 1 and Lecarde 2:   
https://discord.gg/yuS7VjPfYM 


Discuss more Migami games works (mainly their works AFTER their transition into a commercial studio): 
https://discord.gg/uAVxVqmZXx  



#### Credit Goes For ####
Migami Games  
Konami  
Robert Belgrade  
palmymkgames  
Aceearly1993  
DragonX24  
mashedpotatoes312  
theplottwist  
Jorge. D. Fuentes  
jdbuenol  
Exorion Hagen  
狼王之2型 (https://space.bilibili.com/936194/dynamic) (Japanese re-translation)  
ACC (a.k.a."得枫.德广")(https://space.bilibili.com/1471923), Astral "Bozo" Clocktower (Alucard animation enhance)    
浅野川 (https://space.bilibili.com/101496) (Testplay)  

Translations to enemy description/extra texts:  
English/Portuguese/Simplified Chinese - The Lecarde 2 rework project team (Aceearly1993, Katriel, ThePlotTwist, Jeffrey Montoya)  
French - Chernabogue  
Spanish - Jorge Fuentes  
German - Exorion Hagen  
Italian - TheCarsEdge  
Japanese - 狼王之2型  



... and all the people in the game's original credits and reworked edition credits.  

Thank you; Your contributions occupied a great session in this community mod and helped us break through the constant backs-and-forths in the directions of this community mod. 


### Update History ###


#### 2026/9/3 #### 

 - The joystick 2 object just received a sudden update out of nowhere. I cannot resist the temptation of any possible chance on improvements and will test the new version right in this release. (new version of object updated by NaitorStudios)  

 - Fixed one text error at the drop item list in monster bestiary. 


#### 2026/7/3 #### 

 - Main hitbox: Main character Hurtbox fully separated from main collision box; Added a new collision box and shrink down the size of main character hurtbox.
 - L'Auberge rouge Inn: A hidden bonus changed to not disappear too soon, following the logic of other hidden bonus spots throughout the game.
 - Servigny earldom>Albemont Ruins: Due to hurtbox capable to change individually without touching the main collision box, there's no need to resize the spotlight object; 
They're now reverted to the same size as in the vanilla game for the sake of authority visual-wise, optimization and compatibility.  
- Garden of the deads: Fixed a bug which after the Anna V.V boss fight, the wind bell's return function will not work even after leaving Garden of the deads.
- Boss Rush: Fixed an issue which will cause the damage of Lucifer's lasers being abnormally higher than usual.
- Boss Rush (Efrain): Fixed a bug in the temporary fix of Issue 43 (related to Air Dash) in the main branch where a second air dash will sometimes be lost when executed the first air dash, 
and slash in mid air before landing, then jump again and attempt to do double air dash after the next jumping. 



#### 2026/6/13 #### 

- Game start: Added a text string so that it's more clear that players are playing as Alucard in this branch.
- Albaret earldom, Garden of Deads, Chamber of illusions, Princely Room: Several exploits adjusted.
- Castle entrance: reduced the total amount of grip ring objects the game loads at once.
- Main character movement: Very slightly adjusted movement speed to be less vulunerable to exploits.
- Double jump/triple jump: Added several pre-input frames so that they can be performed after an air dash much easier than before. 
- Fixed An oversight in the vanilla which will cause the bones skeleton type enemies thrown to stack in object counter and not properly erased when they flied beyond the camera. 
- Fixed a bug in the reworked support of Xbox triggers so that Whirlwind, air dash and air float will now be able to pull out properly with Xbox triggers. 



#### 2026/6/3 #### 

- Garden of the Dead: Fixed a irregular behavior if for some reason you get 2 chalices before triggering the first statue's activation zone for the first time. 
- Altar: Always return a variable to 0 so that the final boss trigger zone will always be possible to trigger, overriding the whatever saved variable in the save file. 



#### 2026/5/30 #### 

Initial release of the sub branch.
