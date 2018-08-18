# Week 09 Status Update

So a lot of the code is difficult to parse. There are comments many most blocks of code that give a 1 line description of what it does. However, I still have to really try
to figure out what the different blocks do. Additionally, I have recently had some help from the communuty discord in locating where different pieces of code are such as the level3.cpp.
Apparently, each level of account (at the moment 1-3) has it's own file with the commands that it can call (as well as the levels below it) from the in game chat or server console. 
I have been exploring these because I believe the easiest way to implement flying is through the in game console. I would not know how to create some sort of listener that looks for 
two sapcesbar presses like in minecraft. Another possibility I have explored is making a spell you select from you action bar that would be located in spell.cpp mostly; many files reference
other ones. For example I have already made edits to chathandler.cpp and opcodes.cpp that I know I will need no matter which approach I use (as far as I know). I was also considering 
using an alternate implementatoin for flight. Instead of swimming what if I locked the character's Z axis. This will mean they cannot rise or fall. I got this idea from a forum discussing
implementing "flying" for another game but I do not see why it wouldn't work for WoW.