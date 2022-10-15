# Sherlock 13 Project

The goal of this project was to code (C) the Sherlock 13 gamen in multi-players. It involved a network part (TCP servers, sockets), an UML diagram, and a graphical interface using the SDL library.

ATTENTION : Le projet requiert l'installation de la librairie SDL_mixer de SDL2. Pour l'installer sur Linux avec apt : 
This project require the installation of the SDL_mixer library as it contains sounds. To install it, use ```sudo apt-get install libsdl2-mixer-dev```


The test.sh test allows you to test the project quickly without having to open multiple terminals by initiating the main server and the 4 customers.
WARNING : This command opens 5 terminals at once and 4 SDL windows! It also requires the use of the terminal-gnome.

The cmd.sh file allows the compilation of the sources files, i.e sh13.c and server.c

To run the game, please refer to the report (page 15)

Please consider that if the game is executed on the same machine then the sound may seem unpleasant to hear because the different sounds simulated by the terminals will overlap between each others. For a better experience, run the game on differents machines or mute the sound.


The images, sounds, and fonts folders contains the necessary files to the display.
