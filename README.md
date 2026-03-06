# ManulParty
A Web Game That Has A Goal Of Being A Space For Friends And Fun Games
# Documentation
## Config
To Make ManulParty Games Your Version Must Be +2.0 (Map Update)
Make A "config" File In A Directory It Must Be Named "config" The 1st Line Of This File Is The Name Of The Game Like "My Game" 
The Second Line Is The Description And The Third Is The Max Player Count
Example
```
My Game
A Cool Game
5
```

## Objects
To Add Objects Make A Folder Named "space"
In That Folder Make Another Folder You Can Name How You Want In It Make A File Called "main.mobj"
The First Line Is The Type, We Want To Make A Object To Do That We Need To Type ManulParty:Part
In The Second Line Type The X Position In The Third The Y Position
And In The Fourth The Z Position In The Fifth The First Size Of The Object (X) The Sixth First Size (Y)
The Next 3 Lines Are Like The Other 3 But For The Second Size
Example
```
ManulParty:Part
0
1
0
8
1
8
1
1
1
```
## Spawn Point
Spawn Points Are Objects In ManulParty That Change The Default Spawn Point To Make It Make A Folder In The Directory "space" In It Make A File Called "main.mobj"
The First Line Is ManulParty:Spawn The Second Is The X Position, The Third Line Is The Y Position And The Fourth Line Is The Z Position
Example
```
ManulParty:Spawn
10
5
-20
```
