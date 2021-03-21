# Script ofr Random Encounter in dnd (roll20)

I used information from XANATHAR and some description found on the web to create a script that generate random encounter.
This is the logic in the file:

1. roll 1d6, if 1 there is an encounter
2. test if this is a *location* encounter or a *moonster* encounter. Location are web found monster are xanathar found.
3. if location roll location on appropriate table (arctic, forest etc...)
4. if monster check: you fount monster tracks? or encounter monster lair?
5. if no tracks and no lair you found the monster
6. enjoy the encoutner

All encounter are send to the game master with wisperer.
I've added a little information like help but i'm not good at this.
If you want to use this in a easy wy create thi macro:
**!encx ?{Choose Terrain|arctic|coastal|desert|forest|grassland|hills|mountain|openwater|swamp|underdark|underkdwater|urban} ?{Chose Level|1-4|5-10|11-16|17-20}**

Enjoy the ancounter


