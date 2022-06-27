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

My dissertation, titled "Using Unsupervised Deep Learning for Song Similarity Recommendations", explored the use of unsupervised neural networks for the purpose of music recommendations, without focusing on collaborative filtering-based approaches. Training a network on over one million previews of Spotify tracks allowed me to generate recommendations for tracks. Per the abstract:

*This project explores the use of unsupervised neural networks to provide music recommendations based
on song similarity. The model is trained in two phases upon a dataset of the 30-second preview clips
of over 1 million Spotify tracks. Through the use of Triplet Margin Loss and a choice of three distance
functions, recommendations can be provided for an input. Depending on the style of music used as the
input, recommendation quality ranges from vaguely within the right genre, up to very good matches
which echo the style and vibe of the track provided extremely well. Recommendations work best for
ambient music, tracks with long sustained sections, as well as more defined genres such as hip-hop, but
fall short on more high tempo music such as drum and bass.*

This dissertation project used PyTorch, the Spotify API, and a number of other Python maths and deep learning libraries.

---

## Gamejam Projects

The following gamejams were hosted by University of Bristol's Computer Science Society, often in collaboration with and with sponsorship from other companies. They run over the course of 24 hours in teams of up to 6 students, and aim to follow a particular theme.

### CSS GAMEJAM 2020
[Contest Link](https://cssbristol.co.uk/events/2020_11_14_gamejam/) | 
[Github](https://github.com/TBExtent/Onward-Maggots) | 
[Game Link](https://motehue.itch.io/onward-maggots)

The theme for this edition of the gamejam was *"keep moving forward"*. Our game, **"Onward, Maggots!"** placed 2nd place at the event. I was primarily responsible for music, level design, and playtesting.

### CSS X BOEING HACKATHON 2021
[Contest Link](https://cssbristol.co.uk/events/2021-03-20_boeing_hackathon/) | 
[Github](https://github.com/MoteHue/YESSQUID) | 
[Game Link](https://harrywiner.itch.io/yessquid)

The theme for this joint hackathon with Boeing was **"Life Under Water"**, with the task being to *"innovate in one of three areas: Exploration, Environment, Communication"*. We chose to make a simple game based on a river in USA where you must play as a fish surviving in the river.

### CSS GAMEJAM 2021
[Contest Link](https://cssbristol.co.uk/events/2021-10-30_game_jam/) | 
[Github Link](https://github.com/MoteHue/Superior-Beans)

---

## Others / Achievements

### [CIUK Cluster Challenge 2021](https://www.scd.stfc.ac.uk/Pages/CIUK-2021-Cluster-Challenge.aspx)

I was a member of the joint Bristol and Bath team that won the CIUK Cluster Challenge 2021, a series of challenges involving high performance hardware usage and optimisation.
