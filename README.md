# HW_2024_Test

## Assignment: Doofus Adventure Game

## Backstory:
Meet our character Doofus, a cube that loves exploring green platforms called Pulpits. The catch? Pulpits don't last long and disappear within seconds. Doofus has set a challenge to walk on at least 50 Pulpits. 

### Characters/Props:
1. Doofus: The main character (a simple cube will work too).
2. Pulpit: A green metallic 9x9 platform where Doofus walks.
		
### Goal:
Guide Doofus to walk on as many Pulpits as possible. Be cautious! If Doofus walks off the edge, he falls and the game ends.

### Challenges:
Each Pulpit has a timer. When it runs out, the Pulpit is destroyed, and Doofus falls. You can check out the gameplay here: [Link](https://youtu.be/NOgrwo1dWxQ)

### Controls:
Use arrow keys or WASD to move Doofus left, right, forward, or backward. The speed of Doofus is specified in the Doofus Diary (found [here](https://s3.ap-south-1.amazonaws.com/superstars.assetbundles.testbuild/doofus_game/doofus_diary.json)).

### Pulpit Appearance:
Only two Pulpits can exist simultaneously. A new Pulpit appears when the timer of the previous one reaches a certain time (x seconds). Pulpits last for a random time between y and z seconds. They appear adjacent to the previous one, but not in the same position.

### Scoring:
Doofus's score is based on how many Pulpits he successfully walks on.


## Dofus Adventure Game
Welcome to the thrilling and visually stunning Doofus Adventure Game! Immerse yourself in the world of Doofus, a cube on a quest to explore vibrant green platforms called Pulpits. Navigate through disappearing platforms, challenge your agility, and aim for a high score.

### Introduction
Embark on an exciting journey with Doofus, a cube with an insatiable curiosity for exploration. Pulpits, the green metallic platforms, pose both a challenge and an opportunity. Can you guide Doofus to walk on at least 50 Pulpits and achieve greatness?

### Gameplay
1. Platform Exploration: Use arrow keys or WASD to move Doofus in all directions. Navigate across dynamically appearing and disappearing Pulpits.
2. Scoring: Successfully walking on a Pulpit adds to your score. Strive for a high score by chaining multiple successful walks.
3. Challenges: Be mindful of the Pulpit timers. Each platform has a limited lifespan, and if the timer runs out, the Pulpit disappears. Falling off the edge ends the game.

### Controls
1. Movement: Arrow Keys or WASD or JoyStick
2. Quit: Press Q to exit the game

### Setup
1. Unity Project: Open the Unity project.
2. Import Standard Assets: Ensure Unity Standard Assets are imported.
3. Doofus Configuration: Attach the "FirstPersonController" script to the Doofus cube.
4. Pulpit Setup: Create a "PulpitPrefab" object with the "PulpitController" script attached.

### Visual Enhancement
1. Customization: Personalize the appearance of Doofus and Pulpits using materials and textures.
2. Environment: Craft an immersive environment with a ground plane, skybox, and visually appealing surroundings.
3. Animation: Consider adding animations (like rabbits, animals, etc.) or particle effects to elevate the overall visual experience.

<img width="245" alt="image" src="https://github.com/mohdmohsin0403/HW_2024_Test/assets/78999231/f5e1c554-bcc6-4769-b0b0-8a17014713f0">

### Scoring System
1. User Interface: Implement a scoring system with a user interface (UI) to display the current score.
2. Achievements: Consider incorporating achievements for reaching specific score milestones or completing challenges.

### Additional Features
1. Power-Ups: Introduce power-ups that provide temporary benefits such as extended Pulpit duration or increased Doofus speed.
2. Obstacles: Spice up gameplay with occasional obstacles that challenge Doofus's journey.
3. Dynamic Environments: Experiment with dynamically changing environments, adding variety and unpredictability.

### Some snapshots from the Adventure game
![WhatsApp Image 2024-01-22 at 22 24 56_f20966f9](https://github.com/mohdmohsin0403/HW_2024_Test/assets/78999231/d5bd8828-69a0-458d-874b-a9e33e56e457)

![WhatsApp Image 2024-01-22 at 23 43 04_cf81cd2b](https://github.com/mohdmohsin0403/HW_2024_Test/assets/78999231/089d1f8d-693f-4f43-a508-e3a6ac3dc948)

![WhatsApp Image 2024-01-22 at 23 45 44_dbec5083](https://github.com/mohdmohsin0403/HW_2024_Test/assets/78999231/dce71438-f417-4600-ba11-8fffe25b9499)

![WhatsApp Image 2024-01-22 at 23 59 36_902e1f3e](https://github.com/mohdmohsin0403/HW_2024_Test/assets/78999231/d529548f-5203-4593-baa1-82f29d87599d)


### Evaluation Criteria :
Your assignment will be evaluated based on the levels completed. It's recommended to commit after completing each level. 

- [x] (Level 1: Character Movement and Platform placements)
- [ ] (Level 2: Score update after every successful move to a different pulpit)
- [ ] (Level 3: “Start” Screen and “Game Over” Screen)

**Key Expectations:** Few things that will be important for us and will help us evaluate your submission would be


- [x] (Modular and robust code)
- [x] Code structuring, readability and adaptability
- [ ] Levels completed
- [x] Handling the specified exceptions and edge cases gracefully


# Thank You!!
