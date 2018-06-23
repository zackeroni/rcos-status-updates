# Week 03 Status Update

I am now working on completing the installation for all of the required software. Being the only person I know that has done this is giving me some trouble. I have to figure out 
many problems myself since few people on the MaNGOS discord feel obliged to help out every internet person's problems. I will list the problems I have encountered so far and how I
have solved them. 

First, the guide to using the software was never updated for Visual Studio 2017 and therefore only has 2015 instructions. In order to solve this I asked Adrian Collado for assistance.
With his help I was able to obtain the correct packages in order to use Visual Studio 2017 for everything that the installation guide says I should need while using MaNGOS.

The second problem I came across was more of a learning experience than a real problem. There wre several files that the MaNGOS download came with that had the file extension .conf.dist
This was screwing me up because I could not figure out how to open these files. It turns out you can add .dist to a file (I'm guessing it stands for distribution) in order to create a 
backup that exists in the same folder. So if you ever need the original version of the .conf file that came with the download, you or a program you have written can take the .conf.dist file
and copy it whereever you like and just drop the .dist from the name in order to reobtain the original .conf file.

The final problem I came across I figuring out what different folders are. For example, I have dbZero, serverZero, serverZero_build, and serverZero_install. It took seveal iterations of trial
and error of putting files in different folders and attempting to compile the code in order to discern that the serverZero_build folder contains the code I'll be modifying for my project. 
The serverZero_install seems to contain a lot of extraction tools for editing the code for the WoW client as well as backups? of several files that had to be copied to serverZero_build. I 
still do not a have full understanding on the purpose of dbZero and severZero.