# CPP_CellularAutomata_pt2_Synapses
C++ OpenGL Probabilistic Hexagonal-Grid Cellular Automata Creating Snaking "Neural Network".

<img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_Synapses/assets/76754592/82f897e9-0c32-44a7-9704-cc7e8460bcbf" alt="Cornstarch <3" width="95" height="129">

Another File Dump Extension Of My Cellular Automata This One Was Very Interesting To Me And Can Change Amount Of Origin Stem Cells In Loop To Only Show One Or Many Trying To Fight Against Eachother For Space. The Code Has Some Unoptimized Points With A Lot Being In Main But Don't See Need For Optimization Just Yet As Space Complexity Isn't A Issue And Runtime Is UpHeld Because Of Some Of These Local In Main Variables.
Taught me my first sense of probabilistic calculations in these sorts of systems and how we can conceptually visualize a sort of relationship between cells for given patterns.


----------------------------------------------
<img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_Synapses/assets/76754592/b8f1331f-644d-4b71-826e-2f24b4439292" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_Synapses/assets/76754592/b8f1331f-644d-4b71-826e-2f24b4439292" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_Synapses/assets/76754592/b8f1331f-644d-4b71-826e-2f24b4439292" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_Synapses/assets/76754592/b8f1331f-644d-4b71-826e-2f24b4439292" alt="Cornstarch <3" width="55" height="49">


**The Breakdown:**

  This Program Works In C++ To Call Upon OpenGL Through A GLSL Window.

  The Window Is Visually Layed Out With a Hexagonal-Grid, Where Each The x & y Axis Are Set To A Predefined Number Of Hexagons. Each Hexagon Is Wrapped In A Object Which Represents Themselves In A 2D-Array With A Class Called Cell.

  Each Cell Is Delegated Its Inherit Capabilites In The Array, As In Ability To Draw Themselves, Override Their Color Or Buffer Data, React/Think To Their Neighboring Cells (For Game Of Life) And Die/Revive Themselves Accordingly. 

  In This Iteration Of Our Program, Our React/Think Function Has The Ruleset Of:
  
  &emsp;- If Dead, if there is 2 alive neighbors we have a 50% chance of turning on (becoming alive).
    
  &emsp;- Else If Dead, Stay Dead :/
    
  &emsp;- If Alive, if we have 2 alive neighbors we die.
    
  &emsp;- Else If Alive, Stay Alive :D

  This Program Starts By Pinging On Some Cells And Their Neighbors To Start Behaivor. Other Than That Theres No External Input Needed Or Used By The User. 

  Because Of Our Invariants For Reactions, When Inputting Multiple Neural Paths With Our Initialization We See That The Paths Will Never Connect With Another Stem Network. This Makes Some Cool Patterns As It Tries Moving And Filling In Space While Accounting For Its Neighboring Networks.

<img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_Synapses/assets/76754592/56e16e1a-56a1-40db-8851-c7edff2ac570" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_Synapses/assets/76754592/56e16e1a-56a1-40db-8851-c7edff2ac570" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_Synapses/assets/76754592/56e16e1a-56a1-40db-8851-c7edff2ac570" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_Synapses/assets/76754592/56e16e1a-56a1-40db-8851-c7edff2ac570" alt="Cornstarch <3" width="55" height="49">

----------------------------------------------


![brainFight-ezgif com-optimize](https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_Synapses/assets/76754592/e2e4d255-8cd1-456a-8eee-f19c576e7813)
![singleBrain-ezgif com-video-to-gif-converter (1)](https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_Synapses/assets/76754592/b2e1f813-8a35-42ce-b934-d3fc01324760)
