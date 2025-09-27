## GAM_305_Project: Project CyberVirus

------------------------------------------------------------
# Team Roles:

Patrick Reardon (Team Lead & UI Developer)

Braeden Thompson (Programmer)

Chase Perez (Level Designer)

------------------------------------------------------------
# Module Two Team Project Plan:

## Scenario: First-Person Simulation

Our team's game will be a single level designed around the player being shrunk and inserted into a cybernetic body
to locate and eliminate various viruses. Additional elements for the game includes:

•	Teleporters for traversing from area to area around the level.

•	Health, Armor, and Ammo Pick-ups

•	Virus Reproduction from static spawners that spawn to a cap till destroyed.

•	Capillaries for hiding away from enemies if the player becomes overwhelmed.

## Prefered Scenario Content

Our chosen theme is Futuristic, based on the resemblance of Cyberpunk with humans that have cybernetic parts that
require constant attention from a virus threat. If the player doesn’t get the virus contamination under control, 
then it’s all over and an outbreak will occur across the population. We will be staying along the default of 20 virus
kills across the level, but more weaker ones spawn from the reproduction spawners. 

We will have three variants, one melee focused enemy, one ranged focused enemy, and one tankier enemy that is like a
mini-boss in such a way that it does quite a bit more damage and has a lot more health. Also, each variant has unique 
health and damage modifiers to them with the potential to be weaker or stronger based on the area of the level. Our 
level will have 5 different rooms designed for the player to look around for said viruses with a fully textured 
environment of the playable area. 

## Schedule

Based on the due dates outlined within the course the approximation of completion for said project will be four 
weeks with the core gameplay being roughly 5-10 minutes. By Week four, or module 4, we are to have our Alpha 
release done and before week 6, or module 6, we are to have our Beta release done for the final release submission
in week 6. With all of this in mind, before week 4 finishes we should have the Player, 3 variant viruses,  at least 
an area created in the level, and the Player’s interface completed alongside teleporter and virus reproduction 
functionality. Before the end of week 5 we should have the level fully made with 5 areas that are playable with 
texturizing, a main menu with credits, controls, quit, and play buttons, and pickups that are fully functional.

## Development goals for Stages:

Based on the due dates outlined within the course the approximation of completion for said project will be four 
weeks with the core gameplay being roughly 5-10 minutes. 

Alpha -By Week four, or module 4, we are to have our Alpha release done with having the Player, 3 variant viruses, 
at least an area created in the level, and the Player’s interface completed alongside teleporter and virus reproduction 
functionality. 

Beta - Before week 6, or module 6, we are to have our Beta release done for the final release submission in week 6 
with having a level fully made with 5 areas that are playable with texturizing, a main menu with credits, controls, 
quit, and play buttons, and pickups that are fully functional.

## Preferred Communication Method

Our team’s preferred communication method is mainly text chat through discord as it is easy and efficient for us due
to the time zone constraint based on our area of living. 

## Frequency of Communication

We will be periodically messaging each other to stay updated, talk through conflicts of code or issues of the project,
and do check ins for project deadlines. As well, additionally, I Patrick Reardon will be keeping up with the team to 
ensure that we meet every deadline and have a smooth and great playable game by the end of the course. 

## Task Assignment Methods

Our method of assigning and reporting on specific task items will be through Google Sheets with the use of a 
traceability matrix to assign work to specific group members. Alongside this, there will be extra tasks that may be 
worked on as stretch goals if extra time is found for the team.

Team Red's Traceability Matrix: 
https://docs.google.com/spreadsheets/d/1XSS3Rk1OSB4AgOmefKghWvWbpqhSpti_tmhQQzoEIo0/edit?usp=sharing

------------------------------------------------------------
# Module Three QA and Testing Plan:

## How will we Test?

We should test objects such as the Player's weapon(s), AI behavior, and the power ups to ensure they work correctly. 
For the level we should make sure everything works, such as the pathing for enemies or UV mapping is functional. For 
the game itself we should test the entire game build to ensure there is no progression blocks or accidental progression
when it isn't supposed to.

•	Play Test/Preproduction Phase - We should test core mechanics gameplay loops, and the usability of the game. This
includes Enemy remaining counter for progression, enemies that are functioning, a projectile spawn location for our
weapon, a level that we can be mobile in, and a damage/health system for the AI and Player.

•	Demo/Marketing Phase -  We should ensure that the build is stable with the least amount of bugs possible and our
team will be testing the Demo. Another thing we may do is allow friends or family to test the Demo.

•	Code Release/Public Release Phase - We should conduct rigorous testing to ensure all final features are completed and
stable with commenting including with all code to ensure readability in case of issues after release. The testing can 
be done within our team and as well with friends and family again as a sort of closed beta.

## Item Test Log

Gameplay Mechanics:
------------------------------------------------------------

•	Player Movement

•	Player Weapon

•	User Interface

•	AI Functionality

Level Design:
------------------------------------------------------------

•	No Invisible Holes or Tears

•	Accurate Collision Detection

•	The Player can't get Stuck


Stability:
------------------------------------------------------------

•	Game doesn't Crash

•	Game can be Completed from Start to Finish without Blocking Errors

•	No Memory Leaks

Visuals:
------------------------------------------------------------

•	All Textures and Assets are Loaded Correctly

•	Lighting and Shadows are Consistent

•	Smooth Animation (Basic)

Sound:
------------------------------------------------------------

•	All Sound Effects are Correct and Present if Needed

•	Music is Seamless if Needed

•	Audio is Balanced Correctly

Compatibility:
------------------------------------------------------------

•	Input Methods as Intended without Errors

## How to Update & Report Test Plan

We will be updating the test plan from within Team Red's Traceability Matrix where we have added the test plan. This
will be done frequently to ensure testing is being done as we progress to avoid major bugs or errors. As well, bugs 
will be reported inside the Test Plan and the Discord in order to ensure smooth fixing of the bug or errors to stay
on track for submission. Essentially a title of the Bug with a description, severity of the bug, and then updates or
resolutions on the bug.

## How Bugs will be Tracked

For Bug tracking I will be adding another category into the Matrix for Bug Tracking. This will be done to show when
it popped up, when it was closed as solved, if it showed back up, and any other conflictions linked to the bug. This
will also be labeled as who discovered it and what asset or object it is attached to.

------------------------------------------------------------
# Module Four Team Reflection and Alpha Release:

## What parts of the testing process did the team perceive to go well

I believe that quite a few parts went pretty well as the upgrades were as simple as just adding some code logic to 
allow it to work on the player to restore armor and health. The Player Movement and Dashing was as simple as it just 
took a bit of extra code to fix the movement and then some adjusting for dash speed. The Melee Enemy does well with 
attacking the Player and dealing correct damage and the Level Design has come out great with the layout.

## How were bugs identified and corrected

Most bugs were identified via the testing process, such as player movement not allowing movement when looking down 
or up and then fixing it was simple with some additional rotation code to the movement. However, for the Enemy Spawner
we had some pretty bad bugs such as accidentally causing an infinite loop that crashed Unreal Engine 5, which was then
fixed by adding limits and delay to the code. Another way that bugs were identified was via the output log where it 
gave important information on runtime errors that were occurring in the program. Here, fixing it was as simple as 
clicking the location of the error and then looking for ways to fix it. Such as with the Enemy Spawner, it was throwing
this error every time the spawner was destroyed and then the enemy spawned from it was hit. Fixing it was as simple as 
adding if statements to prevent it from occurring and doing the correct action.

## In terms of QA and testing process, what would you do differently to improve the process

I believe what we are doing for the QA and testing process is great already. However, most things can always be improved 
on, and I believe more frequent testing between minor or major additions to the game is a great addition to improving 
the process. This can be done by adding for an example the ammo pool and ammo Pickup and after adding the pool for the 
first time it needs to be tested. After this we find what is wrong and then fix that and then test again. With this we 
can improve the process to ensure each game mechanic is almost 100% bug free.

## What tools (Chosen in Module Two) did you find successful in the development of your Alpha Project? Why?

We found that the Traceability Matrix and Test Plan Document in Google Sheets worked great with organizing progression 
for pieces of the game’s development. The Test Plan was used to help document Bugs or Runtime Errors alongside the 
resolution to ensure we know how it was fixed in case it comes back. The Traceability Matrix was used to organize tasks
for the team to ensure pieces of the game were completed in time for the Alpha phase. Discord also played a part in our
communication tool to stay in contact with each other in case someone ran into an issue, wasn’t going to be present for 
a while, or what was completed or updated.

## Were there any tools or techniques that you did not find helpful in the success of your project development? Why?

I believe that all the tools and techniques that we used for our project development were helpful as it helped the team
stay organized, on task of development completion, and was easy for us to stay in contact with each other. Discord 
helped with sharing information, staying organized with development progression, and assignment completion. Google Sheets
helped with task organization, test planning, and bug/error resolution handling.

## How did the team approach to the initial analysis of the game design document contribute to the decision to use these tools and techniques?

We approached an initial analysis of the game design document due to what we previously used in other courses throughout 
our time at SNHU. 
