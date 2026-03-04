# GDIM32 In Class Activities
## W1
### Activity 1
Submit homework on thime and it's very important to check the itcho link after uploaded (check if the link is set on public) start to do the mini game before deadline come up.

### Activity 2
	1.10
	2.2
	3.show "hello world" every frame
	4.MonoBehaviour
	5.show "x = 10"
	6. method arugment and parameter
	7.translate called on object and tranform is a class
	8. use translate

### Activity 3
[W1 Activity 3](https://docs.google.com/document/d/1k-sXYZ-8W-76zU_AhOm0KkVi5w6dVbUOzbarCw8tWbU/edit?usp=sharing)

## W2
### Activity 1
<img width="913" height="690" alt="a graphic breakdown of MG2" src="https://github.com/user-attachments/assets/34430d45-cd34-49c7-9a7f-85f3f7c6efc6">

### Activity 2
[W2 Activity 2](https://github.com/UCI-GDIM32-W25/mg2-oop-review-ZiyingHuang3/commit/9d18b9e82b6f0a1890c714c193b6de24e6da0b36) I added ground and player in the scence. Added player script allow player to jump by pressing space and make sure the player can't double jump.

## W3
### Activity 0-2
Evelina Wang

### Activity 3
<img width="913" height="690" alt="a graphic breakdown of MG3" src="https://github.com/user-attachments/assets/5df13eea-e924-4854-a815-c031e2c684f9">

## W4
### Activity 0
Evelina

### Activity 1
Only one Locator remains, all other destroy automatically.

### Activity 2
<img width="913" height="690" alt="a graphic breakdown of MG4" src="https://github.com/user-attachments/assets/6178172e-8a0b-42f3-9380-b1c5f8228e38">


### Activity 3
[W4 Activity 3](https://github.com/ZiyingHuang3/HW4/commit/d3d8c3911d5f76480c7a5757b438211e5e857a52) I creaated the scene and added bird and pipe sprites.

## W5
### Acitivity 1
I think interfaces and abstract classes are clear and effective. The abstract class defines shared Use() behavior. Each item can implements own version Use(). I would keep it in my project because it is easy to change and extend.

### Activity 2
Model: PlayerW5Demo2
View: InventoryUI : MonoBehaviour
Controller: Enemy Stats

### Activity 3

#### Scenario 1
There are sprites (prefeb) ScriptableObjects to show where to click or show the beat system.
#### Scenario 2
Finite State Machine with C# enums shows action constenly moving from state to state. MVC pattern can be used M: gun's ability (data) V: UI to show point.. C: player able to shoot
#### Scenario 3
Parent class from farmobject shared by all farm objects. Use interfaces to sepearte functionality.

### Activity 4
Attendance: Ziying Huang, Evelina Wang, Nicole Yang
[W5 Activity 4](https://docs.google.com/document/d/10HReV1LS2bKpFumSkCfVwM0uvrhOadVoLUmLjYf7iTk/edit?usp=sharing)

## W6
### Acitivity 1
Gizmos is really helpful to check the player's facing direaction in the Scence, like if NPC changes state based on player distance. Profiling can be used to check CPU and GPU if the game feels laggy. Breakpoints is helpful debugging tool like when the score is not updating.

### Acitivity 2
Attendance: Ziying Huang, Evelina Wang, Nicole Yang [W6 Activity 2](https://docs.google.com/document/d/10HReV1LS2bKpFumSkCfVwM0uvrhOadVoLUmLjYf7iTk/edit?tab=t.0)

## W7
### Activity 1
Check whether the player is detected through Raycast and based on that to switch state and behavior.

### Acitivity 2
Attendance: Ziying Huang, Evelina Wang, Nicole Yang

### Activity 3
<img width="2360" height="1640" alt="unnamed" src="https://github.com/user-attachments/assets/3fb6d7e3-50fe-48e9-936a-3e34c3f34342" />

### Acitvity 4
[W7 Activity 4](https://docs.google.com/document/d/14oNVjOULok9GKOuAMz6FifVQNZexjDqA_J2JGHLxH9M/edit?tab=t.0)

### Activity 5
[W7 Activity 5](https://github.com/ZiyingHuang3/GDIM32-Final/commit/e8be940b50f0184b89248e28ec6631dddef4493c) I added art and enviroment the scene

## W8
### Activity 1
Post-process effect can make the scene look more polish.Free effect can be found in Unity asset store.

### Acitivity 2
Attendance: Ziying Huang, Evelina Wang, Nicole Yang

### Activity 3
Buddy team: Great question
The feedback that we got on our game is that the button to pick up items is not clear, movement might be a little fast, player can still move after they die, 
animations still move after you die (they said they enjoyed seeing it and that it adds onto the fun), you can go through a specific wall in the map,
we should have indication of losing health like audio or flashing red, we should have indication of picking up item like audio, you can go through the mushroom NPC, 
if you're behind Freddy, you do not take damage but the animation still plays. You can lose health multiple times near Freddy even when you're somewhat away.
You do not take damage in front of the blue guy but only when touching (the animation plays but does not take damage), Camera spins randomly sometimes, and 
camera spins after the game ends.

### Activity 4
I will add audio, import door animation and add UI to make interaction more obvious.

### Activity 5
I changed the NPC's collider to make alert zone smaller. [W8 Activity 5](https://github.com/ZiyingHuang3/GDIM32-Final/commit/6aff4c52463fa69a209f4923cbe8e592dcfc891d#diff-f494ac502950b7beeaa5a379cb6488828adba99fcb2c8e162e020614f5776728)\

## W9
### Activity 1
 It is important to know how the system will work when the data become larger and more complex. System may function when the game only have some 
 dialogue lines but as content grows, the issues of maintainability and data manage may happen. 

 ### Acitivity 2
Attendance: Ziying Huang, Evelina Wang, Nicole Yang

### Activity 3
Our goal is to check if the player can move smoothly and interact to the items corectly.
From our playtesting, we found out that it is not clear what controls are used for moving, the dialogue with the NPC needs to be clicked twice initially to start the conversation, the dialogue never ends unless the player completes the full conversation, the rotation sensitivity is a little too high, and there is a spot where Freddy's animation plays but the player never takes damage.

### Activity 4
We finished most of the game mechanics and coding. We still have some small issues from player feedback and need to have small adjustment to the
environment like the table is too high.

### Activity 5
[W9 Activity 5](https://github.com/ZiyingHuang3/GDIM32-Final/commit/e73e86c46233bcfedc02e798737c36ed624536e4) I fix the NPC damage area and the issue of item's rotation speed.
