# BattleDot-Game
This is a BattleDot, an unpopular networked spinoff of the popular Battleship game. Rather than having two players oppose each other directly, any player will be attacked by one opponent and in turn will attack a different opponent.     Players are connected in a ring: A is bombing B who is bombing C, ... who is bombing Z who is bombing A.  
Each player has a 10x10 grid of "dots" where one "single-dot ship" is positioned randomly. 
A player loses if this ship is bombed. Players cannot see each other's grids directly. Each player randomly selects a dot location on the enemy grid to bomb, and sends the bomb to the enemy. If the bomb lands in the enemy's dot-ship, the enemy dies; otherwise, it lives. When a player dies, relevant neighbors are matched up so that their unfinished games can continue. For example: A is bombing B is bombing C is bombing D is bombing A. If B hits C's ship, B wins, C loses/dies. B is now bombing D.   

The program is implemented in Python and it runs on Jupyter Notebook

Steps to loading and running the program

1. Download the file on your computer. 
2. Launch jupyter notebook
3. From jupyter notebook, go to your download folder and click the on the file you download
4. After file loaded itself onto jupyter notebook, click on "Cell" and select "Run All"
5. After the program complete running, result will printed below  
