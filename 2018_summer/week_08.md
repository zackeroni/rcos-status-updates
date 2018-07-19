# Week 08 Status Update

RPI's network strikes again! It turns out I can connect to my server from the client just fine. MySQL, which I am using to host the server on my computer, does not like that my 
IP and local IP adresses are thesame while connected to RPI's network (I think this is the problem but either way I cannot connect to my own server on RPI's network). At home or 
when I host a mobile hotspot on my phone I can connect perfectly fine. After logging in I created a gamemaster account and an administrator account and experimented with many of
the tools and commands that I have never seen before because they are not available to players. Through my testing I discovered that flying was not available. It turns out flying 
was not an option for gamemasters/admins until the first expansion. This is likely because the first expansion is when flying animals were introduced to be able to be used as mounts
by players and the developers just took the code created for flying and made it avaible to gamemasters/admins with the use of a flag in the client chat console rather than a mount.
This has inspired me to alter my milestones. I wish to implement flying for gamemasters/admins in vanilla World of Warcraft. I believe I can do it by basing it off of the code for 
swimming since it is also movement in 3 dimentions. The animation will likely end up being swimming though air since I do not yet know how which animation to use is decided.