# Welcome

Hello! My name is Matthew Stollery and I am a recent graduate from the University of Bristol with an MEng Computer Science degree. Below you may find my portfolio of projects I have worked on both for university and in my own time, along with a short descripion of each. Thank you for your time!

---

# Portfolio
---

## Personal Projects

### [FootballSimv2](https://github.com/stollaz/FootballSimv2)
This project was my first attempt at making something from scratch. Inspired by the Football Manager games, as well as my general love of football, this project aimed to be a basic football simulator with little to no interaction, but that could however simulate football games with real-world player data. It can simulate individual matches as well as full league seasons with both real player data and randomised players. This first version is written in C#, and runs in the terminal.

### [FootballSimC++](https://github.com/stollaz/FootballSimCpp)
This project is a C++ port of FootballSimv2. There are three reasons for doing this: to refresh my knowledge of programming in C++, the standard language for many game development studios, to clean up much of the C# code that was written without readability or performance in mind, and to further the project for use in a portfolio such as this one. At the point of writing, this project has less functionality than the original C# version, however much of the code is refactored into header files and many functions are cleaned up and commented properly.

### [FootballSImGui](https://github.com/stollaz/FootballSImGUI)
This is the most recent version of the project, aimed to help me learn how to use GUI frameworks. Prior to this, the only visuals in my projects have been either terminal art or in a game engine such as Unity, where visuals were an integral part of the development environment. For this however, I wanted to still build something from scratch however with the help of a GUI to make both debugging and usability easier. I use the C++ GUI framework ImGui, supported with a Vulkan backend (provided by the [Walnut framework by TheCherno](https://github.com/TheCherno/Walnut/)), and this helps massively with development, however much of the functionality from FootballSimC++ is yet to be ported across. The aim for this proejct is to implement a more sophisticated 2D match engine, as opposed to the probabilistic events in the prior two versions.

---

## University Projects

### [RPGen](https://gitlab.com/bristolgamesproj/deepdungeonsndragons)
[Video](https://www.youtube.com/watch?v=VyuJAoaVRS8)
This project was for the 40 credit "Team Project" unit in third year MEng, the goal of which was to make a web game with two key technologies present. We chose to make a simple RPG game with speech transcription and AI generated text. We recieved a 63% for the unit, however were hampered by two of our six team members being unavailable for the final six weeks of the project. As a result, while playable, the game lacks fleshed out technologies (however they are present). The speech transcription is driven by Google Cloud, while the AI text generation is driven by GPT-2. The game is made in Unity. Please see the video for more information.

### [Scaleable Fault Tolerant Chess](https://github.com/ccdb-uob/CW21-29)
This project was done for the "Cloud Computing and Big Data" coursework unit in fourth year MEng, as part of a group of three. We recieved 80% for this project, with the coursework prompt to construct "an elastically scalable and fault-tolerant big data cloud system that performs a parallelisable task on streaming data". We chose to create a simple chess site that takes streams of games, processes the move using Stockfish, and responds to said move. This used Kubernetes, MongoDB, MinIO, Google Cloud and Redis. I was personally primarily responsible for writing the worker and healer scripts, as well as the final project write-up.

### [Dissertation](files/Dissertation_jo18163.pdf)

// TODO

---

## Gamejam Projects

// TODO
