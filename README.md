UNITY DIALOGUE SYSTEM

Unity Dialogue System is an open-source dialogue framework designed for independent Unity
game developers to help create and manage conversations between characters and the player
in their games. Dialogue systems are common in story games but implementing them from scratch
can take time away from developing the game itself despite it being something that a lot of
games have recreated over and over again. This project's main goal is to provide a reusable
foundation that developers can incorporate into their Unity projects and customize it to
fit their needs.

The main goal is to remain approachable for small indie developers whiles till providing the
flexibility for more complex dialogue options. Rather than forcing developers into one particular
type of narrative structure, this project is designed to be modular and provide the flexibility
developers will need.

Features

The project is intended to provide the following:

* Creating conversations between the player and multiple characters
* Displaying character names and dialogue text through the Unity interface
* Progressing through sequences of dialogue
* Supporting reusable dialogue data
* Allowing dialogue to be triggered during gameplay
* Providing a foundation for branching dialogue
* Making the system customizable for different type of Unity projects from 2D to 3D

Installation

This project is currently intended for the Unity Game Engine specifically
To install:

1. Clone or download this repository from GitHub
2. Open Unity Hub
3. Add the downloaded project or copy the dialogue system files into an existing project
4. Open the project using a compatible version of Unity
5. Add the provided dialogue components to the appropriate GameObjects and connect the dialogue elements

Usage

The main goal is to allow a developer to define dialogue and then have Unity display that dialogue during gameplay
For example:

NPC 1: Hey! What did you find?
Player: "Nothing" or "Something"
NPC 1 response 1: "Oh that's too bad"
NPC 1 response 2: "Oh show me!"

The developer could attach the dialogue to an NPC and trigger the conversation when the player
interacts with that NPC. The dialogue system would then display each line in order while keeping track
of the character that's currently speaking.

It's also usable between multiple NPC's with either some Player interaction or none
For example:

NPC 1: Hey! How's your day?
NPC 2: It's going pretty well.
Player: "Mine's good." or "Mine's bad"
NPC 1 Response 1: "That's great!"
NPC 1 Response 2: "That's too bad."

Roadmap

* Branching dialogue and player choices
* A visual dialogue editor
* Dialogue conditions and requirements
* Events that can be triggered from dialogue
* Character portraits
* Text animation or typewriter effects
* Localization support
* Saving and restoring conversation progress
* Improved documentation

License

Unity Dialogue System is currently available under the MIT license. This license allows the project to be used, modified, and distributed
including a part of commercial projects as long as the terms of the license are followed.
