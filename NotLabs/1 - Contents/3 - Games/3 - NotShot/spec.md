# NotShot

## 1 - Abstract

NotShot is a game where the optimal situation that the player can find themselves in is one in which they have not been shot.

## 2 - Contents

### 2.1 - Gameplay

Faced with an endless horde of murderous, brainwashed geese, your only objective is to
survive as long as possible without getting shot or touched by the geese, taking as many
with you as you can. 
        
You can move left or right using arrow keys, but are restricted to the bottom of the screen.
Geese spawn from the top and move down toward you. If they reach the bottom, the geese will 
stop shooting, turn towards you, and proceed towards you laterally, restricting your movement
but also rendering themselves easy targets. Each bullet from a goose does one damage but if a
goose touches you, you are still instakilled. Don't be like Doug and never mess with geese.
        
Your handgun fires 1 bullet every 0.5 seconds when you click the left mouse button
in their direction. (I forgot to add autofire sorry. Cry about it.)
Enemies include the normal goose which fires a single bullet at the 
player every 4-7 seconds and the Depleted Uranium Armored goose, which fires 5 shotgun pellets
at the player every 4-7 seconds and take 5 hits before dying. That's all I had time to code lmao.

### 2.2 - Implementation

The game will be programmed in python using pygame. There's a class for the player and the enemies, as well as the projectiles fired by both of them. There is also a class which records the gamestate, and another class that updates the game every frame. There will also be a class for the main menu and a class for the game over popup.

### 2.3 - Presentation

The game is displayed on a 800 by 800 window by default, but it should scale if the player chooses to adjust the size. The player and enemies will appear as images, while the projectiles are yellow triangles. The game will have background music. A diagram of the UI can be accessed in ui_prototype.png.

### 2.4 - Lore

Lore: 
On June 26, 2023, a 23 year old man, Alexander Uleyev Ushlyopak Yeban, aka Doug went missing. 
Many of his friends and family knew that Doug was irrationally afraid of geese and getting shot
to the point that he'd make deals with criminal organizations to obtain unregistered IKEA kettles 
in order to craft his own makeshift body armor causing him to frequently get in trouble with the law.
On June 22, 4 days prior to his disappearance, Doug's house as robbed by a disgruntled
IKEA kettle registry worker, and Doug missed a payment to the local mafia boss,
Valeriy Samogonov Ulvrik A.B. IV, as a result. Doug's dead body was recovered on June 28
in an abandoned ammunition factory, along with a gun, numerous used and unused magazines,
multiple damaged IKEA kettles (which Doug had evidently scavenged from the factory), and the 
corpses of numerous geese, which, according to the local police chief, Radimir Trofimovich 
Pereprigun-Zaborov, possessed psychokinetic powers. The factory was quickly secured by police
and government investigators were called in; They determined that Doug was kidnapped
by Ulvrik A.B. IV's subordinates, deprived of all but two IKEA kettle armor plates, and brought 
to the factory. There, Ulvrik A.B. IV negotiated a deal with a private military corporation,
which is currently under investigation, to test out the psychokinetic geese on Doug.
Upon waking up the next morning, Doug was assaulted by the geese, who used telekinesis
to 'shoot' unused bullets scattered around the factory at Doug. Doug managed to find a gun 
and proceeded to kill numerous geese before eventually dying. The following recording was 
recovered, and depicts Doug's heroic last stand against the goose army that eventually shot him.

RIP Alexander "Doug" Uleyev Ushlyopak Yeban (February 29, 2000 -- June 27 2023), a man who, 
in his efforts to avoid getting shot, ended up sealing his own fate.



        
