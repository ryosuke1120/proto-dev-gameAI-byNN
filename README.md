# Prototype development of game AI using neural network

## Demo (current development situation)
![demo](https://cloud.githubusercontent.com/assets/23193177/24845297/da357b3c-1deb-11e7-9d8b-5174b803b5f2.gif)

## Effect
I am a beginner developer of game AI,  
because I started development in April 2017. :)  
In this repository, development is proceeding with personal interest.  

I am developing game AI using Python,  
because I want to use a tensor flow framework.  
However, Not going to use Python only. 
Finally, I am planning to rewrite it simply in a programming language (eg C ++) that has affinity with the game.  

Again, I am a beginner.  
And there are few samples of the game AI program.  
Therefore, if you have an expert, I would like to ask for your help at any time. :)  

As an initial goal,  
I'm trying to realize a simple simulation game using "FSM : FiniteStateMachine", "BehaviorTree", "RL :ReinforcementLearning" on the console.  

Currently, each sample program has already been developed.  
So we will show how to run the sample.  

## How to run sample programs

* **FSM**  
`$ cd sample/FSM`  
`$ pwd`  
`=>(your directory path)/proto-dev-gameAI-byNN/sample/FSM`    
Create the following paths by copy&paste, and through the Python path.  
`$ export PYTHONPATH="(your directory path)/proto-dev-gameAI-byNN/sample/FSM:$PYTHONPATH"`  
`$ python3 main_activity.py`    
When you execute it, sample FSM will start.  
Please use [ctr + c] if you want to stop.  

* **BehaviorTree**  
`$ cd sample/BehaviorTree`  
`$ python3 sample_enemy.py`    
Every time it is executed,  
Action can be taken out from the behavior tree.  

* **ReinforcementLearning**  
`$ cd sample/ReinforcementLearning`  
`$ python3 sample_rl.py`  

## MyTask
* Global state transition bug (behavior tree)  
* Reinforcement learning, how to incorporate neural network  
