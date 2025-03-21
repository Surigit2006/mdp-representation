# MDP REPRESENTATION

## AIM:
The aim of this experiment is to create a Markov Decision Process (MDP) representation and implement it in Python to model the decision-making process to wheater to fish or npt
## PROBLEM STATEMENT:
Whether to fish salmons this year

### Problem Description
We need to decide what proportion of salmons to catch in a year in a specific area maximizing the longer term return. Each salmon generates a fixed amount of dollar. But if a large proportion of salmons are caught then the yield of the next year will be lower. We need to find the optimum portion of salmons to catch to maximize the return over a long time period.

### State Space
Empty -> no salmons are available; 


low -> available number of salmons are below a certain threshold t1; 


medium -> available number of salmons are between t1and t2; 


high -> available number of salmons are more than t2



### Sample State
low -> available number of salmons are below a certain threshold t1; 



### Action Space
 fish and not_to_fish


 
 Fish means catching certain proportions of salmon. 

 
 For the state empty the only possible action is not_to_fish.



### Sample Action

fish

### Reward Function
Fishing at certain state generates rewards, let’s assume the rewards of fishing at state low, medium and high are $5K, $50K and $100k respectively. If an action takes to empty state then the reward is very low -$200K as it require re-breeding new salmons which takes time and money.



### Graphical Representation
![image](https://github.com/user-attachments/assets/0d84ec59-bd65-4d32-a41a-4a1370a176fd)




## PYTHON REPRESENTATION:
```
mdp={
    
    1:
 {
0:[(1.0,2,0.0,True)],



2:
 {
   0:[(0.7,3,0.0,True)],[(0.3,2,0.0.True)]
   1:[(0.75,1,1.0,True)],[(0.25,2,0.0,True)]
   

3:
 {
   0:[(0.75,4,0.0,True)],[(0.25,3,0.0,True)]
   1:[(0.75,2,1.0,True)],[0.25,3,0.0,True)]
  

4:
 {
   0:[(0.95,4,0.0,True)],[(0.05,3,0.0,True)]
   1:[(0.6,3,0.0,True)],[(0.6,4,1.0,True)]
   }
```
## OUTPUT:


![image](https://github.com/user-attachments/assets/63234399-2284-429e-a0cc-5a78f67c5260)





## RESULT:
Thus, The MDP Represntation of reaching a college from home without any traffic is successfully executed.

