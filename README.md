ExpNo 5 : Implement Simple Hill Climbing Algorithm
Name: ABINAYA T
Register Number: 212224060006
Aim:
Implement Simple Hill Climbing Algorithm and Generate a String by Mutating a Single Character at each iteration

Theory:
Hill climbing is a variant of Generate and test in which feedback from test procedure is used to help the generator decide which direction to move in search space. Feedback is provided in terms of heuristic function

Algorithm:

Evaluate the initial state.If it is a goal state then return it and quit. Otherwise, continue with initial state as current state.
Loop until a solution is found or there are no new operators left to be applied in current state:
Select an operator that has not yet been applied to the current state and apply it to produce a new state
Evaluate the new state:
if it is a goal state, then return it and quit
if it is not a goal state but better than current state then make new state as current state
if it is not better than current state then continue in the loop
Steps Applied:
Step-1
Generate Random String of the length equal to the given String

Step-2
Mutate the randomized string each character at a time

Step-3
Evaluate the fitness function or Heuristic Function

Step-4:
Lopp Step -2 and Step-3 until we achieve the score to be Zero to achieve Global Minima.

Sample Input and Output
Sample String:
Artificial Intelligence
Output:
Score: 643 Solution : 8RzF:oG ]%;CPORRMe!zGvk
Score: 609 Solution : 8RzF:oG ]%;CPqRRMe!zGvk
Score: 604 Solution : 8RzF:oG ]%;CPqRRMe!zGqk
Score: 594 Solution : 8RzF:oG ]%;CPqRRWe!zGqk
Score: 551 Solution : 8RzF:oGK]%;CPqRRWe!zGqk
Score: 551 Solution : 8RzF:oGK]%;CPqRRWe!zGqk
Score: 551 Solution : 8RzF:oGK]%;CPqRRWe!zGqk
Score: 551 Solution : 8RzF:oGK]%;CPqRRWe!zGqk
Score: 551 Solution : 8RzF:oGK]%;CPqRRWe!zGqk
....................................................
..................................................
................................................
Score: 1 Solution : Artificial Intelligencf
Score: 1 Solution : Artificial Intelligencf
Score: 1 Solution : Artificial Intelligencf
Score: 1 Solution : Artificial Intelligencf
Score: 0 Solution : Artificial Intelligence
