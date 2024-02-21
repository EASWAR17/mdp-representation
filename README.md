# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

1.Text representation

2.Graphical representation

3.Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description
To Develop an environment contain some dirt and the agent is going to detect and clean the environment using vaccum. The aim is to clean the dirty place.

### State Space
{Location A,Location B,Location C}

### Sample State
Location A

### Action Space

1.Moving Right

2.Moving Left

3.Suck Dirt

### Sample Action

Moving Right

### Reward Function
1.+1 - when an agent move to the right side and the dirt is cleaned using vaccum 

2.0 - Otherwise
### Graphical Representation

![img1](https://github.com/EASWAR17/mdp-representation/assets/94154683/9000c390-49ad-412f-b6f7-adaadc968d70)

## PYTHON REPRESENTATION:
```
# Developed by: Easwar J
# Register Number: 212221230024

P = {
    0:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,0,0.0,True)]
    },
    1:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,2,1.0,True)]
    },
    2:{
        0: [(1.0,2,0.0,True)],
        1: [(1.0,2,0.0,True)]
    }
}

```
## OUTPUT:
![image](https://github.com/EASWAR17/mdp-representation/assets/94154683/45db2831-434b-48f0-a36b-6c0843d4d417)



## RESULT:
Thus the given real world problem is successfully represented in a MDP form.

