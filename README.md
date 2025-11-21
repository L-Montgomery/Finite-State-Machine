# Number Theory: Addition

In this lab, you’ve learned about One Hot and Binary state machines and how to build them.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Questions
## Summary
In this lab we made a final state machine using both binary and one hot code. Showed how different state encodings changed the hardware structure while still having the same sequence and output behavior.
### Compare and contrast One Hot and Binary encodings
Binary contains all the logic that tells the system to move to the next state. Whereas one hot has one flip flop for each of the states telling it to reset to state A.
### Which method did your team find easier, and why?
One hot was easier because it just has everything using the d flip flop and doesn't have as much boolean logic telling it what to do next.
### In what conditions would you have to use one over the other? Think about resource utilization on the FPGA.
You would choose one hot when there are a bunch of states and binary when you have few states or when you want the smallest possible register size.

