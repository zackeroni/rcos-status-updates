# Week 12 Status Update

So this is the end of the semester wrap up. I had a lot of fun working on this project and learned a ton. There ended up being a lot more varied content to digest 
than I thought with both the C++ code and the plethora of mySQL tables. I never did get my flying to work so that'll be on the docket for the next semester of RCOS.
Additionally, my creature worked in ALMOST every way. I was able to edit it's events and spawn location successfully. Also, I was able to make it hostile and change its
stat values. The problem was it's name. In the mySQL tables it's name is different but I cannot get the name to change in game. I further tested names by trying to change 
the name of the item "Small Shield" and the name of the merchant NPC (non-player character) "Godric Rothgar". Both did not change. After consulting the Discord it seems that 
the client caches some data that it has previously loaded in order to create faster loads for the user. Names are one of these cached items. I tried deleting every cache I 
could locate in the client in the WTF (Warcraft text file) and WDB (World Database) fodlers. However, the original names still persisted. I think this fix is just a matter of 
trial and error searching for the solution of where the correct file is. 

Goals for the future in order of difficulty: 
Print to the in game console
Check for a player/unit's flags or other statistic through the in game console
Issue a new in game console command
Implement flying through a command
Create a brand new creature that flies using my flying code. (There is already code for creature flying but this would be cool)