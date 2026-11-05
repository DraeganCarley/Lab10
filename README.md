# Lab10
# Sequential Circuits: Latches


In this lab, you’ve learned about edge sensitive circuits and explored some of the power therein.


## Rubric


|Item|Description|Value|
|-|-|-|
|Summary Answers|Your writings about what you learned in this lab.|25%|
|Question 1|Your answers to the question|25%|
|Question 2|Your answers to the question|25%|
|Question 3|Your answers to the question|25%|


## Names
Group 7 - Aaron Ray and Draegan Carley

## Summary
In this lab, we learned more about sequential circuits and how to use flip-flops to store information. We learned the difference between level sensitive and edge sensitive circuits and how they respond to different signals. We also created D, JK, and T flip-flops using Verilog and tested how they respond to clock signals. This helped us understand how we can use clock signals to control when a circuit changes its output and how these circuits can be used to create more complex systems like counters and memory.

## Lab Questions

### What is the difference between edge and level sensitive circuits?
Level sensitive circuits can change their output as long as their enable signal is active, while edge sensitive circuits only change their output when the clock signal changes from low to high or high to low, depending on the circuit. This means a level sensitive circuit can continue following its input while enabled, but an edge sensitive circuit only stores the input at the clock edge.
### Why is it important to declare the initial state?
Declaring an initial state is important because it gives the circuit a known starting value. Without an initial state, we would not know what value the circuit is storing when it first starts. This could cause unexpected behavior, especially when using circuits like counters that depend on their previous value. By setting an initial state, we can make sure the circuit starts at a known value and behaves the way we expect it to.
### What do edge sensitive circuits let us build?
Edge sensitive circuits allow us to build things like flip-flops, counters, registers, and more complex memory systems. Since they only update their outputs on a clock edge, we can control exactly when the stored information changes. For example, we can create a counter that increases by one each time the clock signal triggers instead of continuously increasing while the signal is high. This allows us to build more complex digital circuits that operate in a controlled sequence.
