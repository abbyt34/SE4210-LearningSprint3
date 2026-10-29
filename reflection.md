# Sprint 3 - Problem 5 Reflection

## Overview of our Experience
For this problem, we utilized ChatGPT to develop the visualization tool. This tool helps provide us with insight into the algorithmic complexity and side-channel problems in multiple ways: 
1. **Input Size Complexity**: the input size for the complexity tool is adjustable, therefore you can see the differences between different masses of input
2. **Linear v. Logarithmic Growth Curves**: both types have different ways to view the algorithm function, and the growth of it
3. **Growth Functions**: we can visual the different growth functions and the amount of time used for different n (input) values
4. **Leaky-Function for Side Channel**: the function here finds the first non-match and then exits the function with an error, not going through the rest of the work and using up more search units. We visualize this by letting the user adjust the secret, the guess, and it calculates how many units it uses and visualizes it
5. **Constant Work Function for Side Channels**: the constant work function goes through the whole guess, not just the first non-match and returns the parts in which it is matched. The tool visuals this in the same way it does for the leaky function.

The experience as a whole was very smooth and understanding, with the tool being able to develop a great visualization tool that can help provide better understanding for tough topics. 

## Development Workflow
For the beginning of development, we began by prompting the A.I. with the problem description and let it run to figure out the baseline tool it developed. The baseline tool was good, but after testing edge cases, it was a little non-user friendly with the bigger things. We went back to the tool and refined our prompt, getting more niche with the visualization description where the second prototype was our final. The use of sliders, adjustable aspects, and the refinement of user's being able to customize their experience by choosing their custom secret to test against, turning on and off different aspects of the complexity tool, and overall being able to use it in Google Chrome without needing to run it in an IDE. 
