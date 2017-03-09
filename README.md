# AI-Assignment-2
Create a self playing AI game



**Question - 1** 
Complete question 1, the depth-first search. Provide your solution for tinyMaze,
mediumMaze, bigMaze, and openMaze.

**Solution:**     
***Output for tinyMaze***    


C:\AI\AI-Assignment-2>python pacman.py -l tinyMaze -p SearchAgent -a fn=dfs      
[SearchAgent] using function dfs     
[SearchAgent] using problem type PositionSearchProblem    

Path found with total cost of 10 in 0.0 seconds    
Search nodes expanded: 15    
Pacman emerges victorious! Score: 500    
Average Score: 500.0    
Scores:        500.0    
Win Rate:      1/1 (1.00)   
Record:        Win    

C:\AI\AI-Assignment-2>    


***Output for mediumMaze***    


C:\AI\AI-Assignment-2>python pacman.py -l mediumMaze -p SearchAgent -a fn=dfs    
[SearchAgent] using function dfs    
[SearchAgent] using problem type PositionSearchProblem    
Path found with total cost of 130 in 0.0 seconds    
Search nodes expanded: 146    
Pacman emerges victorious! Score: 380    
Average Score: 380.0    
Scores:        380.0    
Win Rate:      1/1 (1.00)    
Record:        Win    

C:\AI\AI-Assignment-2>    


***Output of bigMaze***


C:\AI\AI-Assignment-2>python pacman.py -l bigMaze -p SearchAgent -a fn=dfs    
[SearchAgent] using function dfs    
[SearchAgent] using problem type PositionSearchProblem    
Path found with total cost of 210 in 0.0 seconds    
Search nodes expanded: 390    
Pacman emerges victorious! Score: 300    
Average Score: 300.0    
Scores:        300.0   
Win Rate:      1/1 (1.00)    
Record:        Win    

C:\AI\AI-Assignment-2>   

***Output for openMaze****


C:\AI\AI-Assignment-2>python pacman.py -l openMaze -p SearchAgent -a fn=dfs    
[SearchAgent] using function dfs     
[SearchAgent] using problem type PositionSearchProblem    
Path found with total cost of 298 in 0.0 seconds    
Search nodes expanded: 576    
Pacman emerges victorious! Score: 212    
Average Score: 212.0    
Scores:        212.0    
Win Rate:      1/1 (1.00)    
Record:        Win    
  
C:\AI\AI-Assignment-2>    

