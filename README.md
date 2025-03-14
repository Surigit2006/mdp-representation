![image](https://github.com/user-attachments/assets/c7428c16-1c59-4ddd-960c-db7a8184b49f)# MDP REPRESENTATION

## AIM:
The aim of this experiment is to create a Markov Decision Process (MDP) representation and implement it in Python to model the decision-making process in optimize the movement of a warehouse robot .
## PROBLEM STATEMENT:

### Problem Description
Design an RL agent to optimize the movement of a warehouse robot to efficiently pick up and deliver items while avoiding obstacles, minimizing time, and conserving energy.

### State Space
![image](https://github.com/user-attachments/assets/fd1ff3f6-5c1b-41b1-bda1-d068e0f75520)



### Sample State
![image](https://github.com/user-attachments/assets/6285bd9d-68e3-431b-930a-6c6863d73f86)



### Action Space
![image](https://github.com/user-attachments/assets/4d21bd0b-612f-49a9-84b2-9e176e42bdaa)



### Sample Action

![image](https://github.com/user-attachments/assets/ac4002b3-b2b2-45c4-8d10-07bc7540c766)

### Reward Function
![image](https://github.com/user-attachments/assets/fb02cffa-8b4e-484e-bc54-f1587b4fb392)



### Graphical Representation
![image](https://github.com/user-attachments/assets/bb66f936-2ea3-4df6-b6d4-42abaf940312)



## PYTHON REPRESENTATION:

mdp={
    
    1:
     {
    0:[(1,0,0,False)],
    1:[(1,0,0,False)],
    2:[(0.7,3,-5,False),(0.3,2,1,True)],
    3:[(0.3,2,1,True),(0.7,3,-5,False)],
    4:[(1,0,0,False)]},

    2:
     {
       0:[(1,2,0,True)],
       1:[(1,2,0,True)],
       2:[(1,2,0,True)],
       3:[(1,2,0,True)],
       4:[(1,2,0,True)]}, 
    
    3:
     {
       0:[(1,3,0,False)],
       1:[(1,3,0,False)],
       2:[(1,3,0,False)],
       3:[(0.95,4,10,True),(0.05,1,0,False)],
       4:[(0.05,1,0,False),(0.95,4,10,True)]}, 
    
    4:
     {
       0:[(1,4,0,True)],
       1:[(1,4,0,True)],
       2:[(1,4,0,True)],
       3:[(1,4,0,True)],
       4:[(1,4,0,True)]} 
    
     
}


## OUTPUT:
![image](https://github.com/user-attachments/assets/c8a98b4c-db4c-46fc-bf1a-387181baebd3)





## RESULT:
Thus, The MDP Represntation of reaching a college from home without any traffic is successfully executed.

