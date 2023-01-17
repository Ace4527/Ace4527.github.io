---
title: Portfolio
layout: default
description: Nathan Tucker
---

# Unsighted Agent
![Unsighted Agent Game](/assets/images/Unsighted_Agent_Warehouse.PNG "Unsighted Agent"){:class="img-responsive}
Unsighted Agent is a single-player stealth and stealing game. You play as the 'man-in-the-van' coordinating a heist, however you boots on the ground is a robot that you control through voice commands.

Unsighted Agent was developed by a small team of artists and programmers. I served in the role of lead programmer, and my primary respsonsibilities included implenting the speech-to-text for voice commands, the character controller and camera rig, as well as a voice-controlled mini-game.

In team discussion while prototyping ideas, the concept of the integration of the player's mic into games had come up, and I was intrigued by the concept. Following the discussion I investigated the basics of such a system and pitched the prototype to the team, and as they say, the rest is history.

It was fun and interesting to explore the options for real-time voice control in a game environment, the importance of speech-to-text accuracy, reliability and speed all needed to be considered. 

We explored numerous speech-to-text engines available, and switched the one the game operated on three times during development as we further explored the available options and their limitations and trade offs. 
From the native Unity Speech-to-text with its quick and easy setup but low accuracy and reliability as well as limited access to the knobs and dials (such as swapping the input mic), through online cloud based subscription services like IBM Watson STT services and Microsoft Cognitive Speech Serives with their higher accuracy but inconsistent response time and limits on usage.
Eventually moving on to a Unity implementation of VOSK offline Speech Recognition API, while marginally less accurate than the cloud based alternatives, it provided consistent response times, offline access, and an easy ability to swap languages or models for the STT if desired (not that the game supports languages other than English).

[Download Unsighted Agent](https://drive.google.com/file/d/1Mtt5sxJ5Ogq0Zj1mK3LdLV6F_1Snb0fm/view?usp=sharing) and give it a try.

---

# Bee Survival  
![Bee Survival Game](https://img.itch.zone/aW1hZ2UvMTE2NTQyNC82NzgwOTgzLnBuZw==/original/hry7vK.png "Bee Survival"){:class="img-responsive"}  
I served as the lead programmer on the Bee Survival game, and was responsible for most of the game code from movement and interaction to the enemy AI. I also collaborated with the design team to come up with the gameplay and mechanics.  
  
We were given theme of 'Be Good' and set loose to prototype and create a game. The Bee theme was a play on the assigned theme as well as bringing attention the very real issues facing bees in the modern world.

The bee theme also resonated with me on a personal level as my Grandfather kept bees, and my dad is also a hobbyist beekeeper. I drew inspiration from the relevance of the theme in my personal life and the world at large when collaborating with the team on the mechanics and design
  
[Play Bee Survival](https://bee-survival.itch.io/bee-survival){:target="_blank_"} on itch.io  

---
  
# The Little Wizard's Prison Escape
![The Little Wizard's Prison Escape](/assets/images/Little_Wizards_Prison_Escape_Small.PNG "The Little Wizard's Prison Escape"){:class="img-responsive"}  
The Little Wizard's Prison Escape project was produced by a small team, of which I was the lead programmer and gameplay mechanic designer. My responsibilities included the design and implementation of the player character, their movement, abilities and attacks. I was also repsonible for the enemy and level logic.
  
I was excited to work on this project as it was my first time working on a game made for Playstation, and also my first cross-platform game (PC and PS4). I also had a great time collaborating with the character artist, [Isabella Matutini](https://www.linkedin.com/in/isabella-matutini/){:target="_blank_"}, working out overarching enemy themes and animation implementation.
  
[Download The Little Wizard's Prison Escape](https://drive.google.com/file/d/13OMbXVnps7QuEbjBbX1k3kzKuC1fbEro/view?usp=sharing) and try it.  
  
---
  
# Racer Prototype
![Racer Prototype](/assets/images/Racer_Prototype.PNG "Racer Prototype"){:class="img-responsive"}
Racer prototype was a proof of concept project undertaken to implement physics based player movment and AI pathfinding in a game scenario. The AI car utilises A* pathfinding to navigate the racetrack by simulating inputs to control the vehicle.
  
It was interesting to explore a physics based movement system in this project. The movement of the cars needed to feel realistic to the player. This was also my first time creating an independent AI agent in a game environment which was enlightening and satisfying to see it racing around the track. Even if it frequently beat me...  
  
[Download Racer Prototype](/assets/downloads/Racer_Prototype_Release.zip) and try it.
