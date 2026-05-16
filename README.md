# Welcome to my profile! Please browse my projects:
More to come in the future.  
Current project(s):

## Other projects (New to old):

- **Cluttered Obstacle Field Traversal ([Link](https://github.com/MRRP-lab/cluttered-navigation)):** A python simulator which simulates a swarm of robots traversing through a cluttered obstacle field for my research at university. I was the lead on this project and it was created in order to fill a gap in multi-robot systems literature between bug algorithms and random walk algorithms. It features the python simulator itself and decentralized swarm control algorithm and obstacle field generation. It includes: a data generation pipeline including a parameter sweep script, simulation database to query results from a generated index; a data analysis pipeline which generates metrics characterizing each simulation, and a plotting script with a rich interface to easily study inferences based on simulation parameters; It uses protocol buffers to invoke and integrate external swarm control algorithms for comparisons using programs in different langauges. Currently implemented is an offline centralized swarm path solver that I needed to modify from the original source to be able to invoke it via a client-server architecture spun up during the parameter sweep.
We ended up producing a paper titled "A Randomized Bug Algorithm for Swarm Navigation in Dense Obstacle Fields", submitted to DARS2026.

- **Wake on Lan ([Link](https://github.com/Mrnibblesg/WakeOnLan)):** A C program that crafts and sends a magic packet to wake up a powered off computer over LAN. It's based on AMD's "Magic Packet Technology" whitepaper viewable [here](https://www.amd.com/content/dam/amd/en/documents/archived-tech-docs/white-papers/20213.pdf).

- **Blitz OS Kernel (Private):** An OS kernel for an emulated CPU. Implements necessary system calls for any functional operating system, including process creation/spawning, spawning the first user process, virtual address translation, file I/O, fork/exec, process synchronization, as well as error handling for everything mentioned. All is written in a custom programming language called KPL (Kernel Programming Language)

- **Organelle Identification & Grouping ([Link](https://github.com/Diego-Llanes/markingcellstructures)):** A python application to streamline the workflow of a biology lab on campus. We were tasked with taking images of cell structures stained such that certain organelles glow, and forming organelle groups that identify the larger structures that the biology lab is interested in. Utilizes computer vision (opencv-python) and clustering techniques (DBSCAN) to group cell structures.

- **Unity voxel terrain engine ([Link](https://github.com/Mrnibblesg/VoxelTerrainGeneration)):** A voxel terrain generation engine built in Unity! It efficiently generates voxel-based terrain and dynamically creates meshes for them. The user can edit terrain block-by-block or in larger chunks. It's networked so you can build the app and play with friends (port 7777). It implements a custom data structure to efficiently store the voxels in each chunk, and also uses the Unity burst compiler to parallelize chunk generation and mesh building, eliminating stutters.

- **Little flowchart app ([Link](https://github.com/Mrnibblesg/FlowChart)):** A flow chart desktop app using the Windows API.

- **Protein mutation visualization site ([Link](https://github.com/Jasonl2398/Protein_Mutations)):** My senior project for CS that I worked on with two other team members. The protein mutation site aims to help researchers find protein mutants suitable to be subjects of research through visualization by various protein metrics.

- **Chess website ([Link](https://github.com/Mrnibblesg/Chess-Site)):** A project from my Web Scripting class. The chess website implemented a fully functional chess website using a MERN stack, with socket.io added for real-time chess games. Users can create accounts, queue into matchmaking, and even spectate other games. 

- **Multi-platformer ([Link](https://github.com/Mrnibblesg/Multi-Platformer)):** An OLD multiplayer game I made prior to working on evades.io as a volunteer dev. I made it as a proof of concept that I could make stuff. It's a basic platformer where you can login and see other players currently in the world with you. It has basic movement mechanics like double jumping and wall jumping, and you would respawn if you fell off the edge. It was made utilizing the HTML \<canvas\> as well as socket.io, express, nginx, and a static ip service.
