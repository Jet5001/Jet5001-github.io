# Portfolio

Welcome to my portfolio The following projects are my favourite works and include a variety of personal projects and university work

## Consent Detective
Consent Detective is my latest group project I completed at university
For this project I took the lead on development designing and implementing the VR framework including interactions and affordances using Unity's XR toolkit.
I also implemented the dialogue trees using a Dialogue Editor package in unity along with implementing a dynamic pronoun switching system used to mitigate gender biases when playing the game

<iframe width="420" height="315"
src="https://youtu.be/KNkQrM1zvbw"
</iframe> 

## Quest Plotter
Quest plotter is a tool I created for my 3rd year university project designed to aid in the design and development of quests and narratives in video games
The system used to model quests was designed from the ground up after extensive research and mimics the nature of paper prototyping and whiteboards while still retaining the convenience of easily shareable and editable digital files. The code for the editor interface was built from scratch using python's Tkinter library. I also ran a study to evaluate the effectiveness of the system and I received positive feedback throughout, and some participants requested I continue the project beyond its original scope.

The source code for this project can be found at: https://github.com/Jet5001/QuestPlotter

## RunnerMod
RunnerMod is a mod I am currently developing for Slay the Spire which will include a new character, at least 75 new cards and several other miscellaneous additions. The mod has not been in development for long but already includes 16 cards and several supporting mechanics. The mod builds off of the BaseMod built by DavisCook477 and BasicMod built by Alchyr.

The mod can be found at: https://github.com/Jet5001/RunnerMod

![RunnerModScreenshot](/Assets/Images/RunnerMod.png)

## Anime Image generator
As a project to learn the Pytorch Python library I decided to build a DCGAN image generation network as an introduction to machine learning in python and generative AI as a whole. The network was trained on a dataset of images scraped from Danbooru in 2020. These were then downscaled to a resolution of 64x64 so that my local machine could train the network in a reasonable time period. After training, the network could produce serviceable 64x64 images a selection of which can be found below.

The code for this can be found at: https://github.com/Jet5001/AnimeDCGAN

## Platformer Game
Within this group coursework I created a pixel platformer using LibGDX. In this project I completed most of the implementation including the character controller, gameplay mechanics, enemy logic and the underlying engine using the inbuilt physics and rendering systems. The game did not get past the prototype stage due to cuts in our group throughout the project leaving only a small team. Despite this the prototype was still fun to play and was a great learning experience. The game also included a novel movement option which we named the pogo mechanic. This allows the player to click in a spot away from the character and propel themselves away from that point. This allowed for some very interesting platforming challenges and wide variety in pathing options.

## Miscellaneous Coursework
In this section I provide a summary of some of my more interesting coursework projects that do not have an easy visual representation to present.

### Curl Distributed Hash table
As part of my elements of distributed systems module I created a task processing system in Java using a REST API and RMI. This involved creating a browser-based task submission system that would give that task to a distributed hash table for processing and storage of results.  The communication between different sections of the system was handled with Java RMI and the DHT was implemented using a Chord Network.
The Chord Network handles the processing of each task and the storage of the results until requested by the REST API. The system was also designed to work asynchronously and implement load balancing.

### Malloc
As part of my operating systems module, I was tasked with recreating C’s malloc function for memory allocation. This involved provisioning memory from the operating system using sbrk as necessary and assigning sections of that memory as per the malloc spec. This required a clear understanding and careful usage of pointers along with knowledge of the intricacies of memory management.

### Lexical Analyser
For my Languages and Compilation module my main project was the creation of one of the major parts of a compiler, the lexical analyser. This coursework tasked me with the creation of a lexical analyser that processes files of programs to be compiled in a custom language. It checks to see if the syntax follows the rules of the language and gives an understandable error message and stack trace output if not. This involved understanding the inner workings of compilers and the structures of different programming languages.

### Encryption 
For my security and risk module I implemented some security and encryption protocols using python’s libraries the most notable of these was the Diffie Hellman key exchange. I also implemented RSA encryption using Java as part of an auction system created for my distributed systems module.

