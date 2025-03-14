# MDP REPRESENTATION

## AIM:
Whether to fish salmons this year or not 

## PROBLEM STATEMENT:
fishing salmons in wrong time will leeds to loss


### Problem Description
We need to decide what proportion of salmons to catch in a year in a specific area maximizing the longer term return. Each salmon generates a fixed amount of dollar. But if a large proportion of salmons are caught then the yield of the next year will be lower. We need to find the optimum portion of salmons to catch to maximize the return over a long time period.

Here we consider a simplified version of the above problem; whether to fish a certain portion of salmon or not. This problem can be expressed as an MDP as follows

### State Space
Boat
fishing net
compass
weather

### Sample State
Empty -> no salmons are available;
low -> available number of salmons are below a certain threshold t1;
medium -> available number of salmons are between t1and t2;
high -> available number of salmons are more than t2
S={Empty,Low,Medium,High}

### Action Space
fish 
not to fish
A={Fish,Not to Fish}

### Sample Action
fish

### Reward Function
R(Low,Fish)=5K
𝑅(Medium,Fish)=50𝐾

R(High,Fish)=100𝐾

If fishing leads to Empty, a penalty of -200K applies.
​
 


### Graphical Representation


![image](https://github.com/user-attachments/assets/9ad9b8a8-8141-4758-a9d2-4e4055dc210e)




## PYTHON REPRESENTATION:
transition_probabilities = {
    0: {
        1: {1: 1.0},  
    },
    1: {
        0: {0: 0.7, 1: 0.3},
        1: {2: 0.8, 1: 0.2},
    },
    2: {
        0: {1: 0.6, 2: 0.4},
        1: {3: 0.7, 2: 0.3},
    },
    3: {
        0: {2: 0.5, 3: 0.5},
        1: {3: 1.0},
    },
}

## OUTPUT:
Write your Python output here

## RESULT:
Write your output here

