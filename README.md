Download Link: https://assignmentchef.com/product/solved-cs4300-project-3-reinforcement-learning
<br>
In this project, you will design agents for the classic version of Pacman, including ghosts. Along the way, you will implement both minimax and expectimax search and try your hand at evaluation function design.

As in previous projects, this project includes an autograder for you to grade your answers on your machine. This can be run with the command:

<h2>python autograder.py</h2>

The code for this project consists of several Python files, some of which you will need to read and understand in order to complete the assignment, and some of which you can ignore. Download search.zip from here http://ai.berkeley.edu/reinforcement.html which will contain all the code and supporting files.

<h1>1            Files to edit</h1>

For this project you will edit the following files:

<ul>

 <li><strong>py: </strong>A value iteration agent for solving known MDPs.</li>

 <li><strong>py: </strong>Q-learning agents for Gridworld, Crawler and Pacman.</li>

 <li><strong>py: </strong>A file to put your answers to questions given in the project.</li>

</ul>

<h1>2            Supporting Files</h1>

The following python files would help you in understanding the problem and the get you familiar with the different data structures and games states in Pacman.

<ul>

 <li><strong>py: </strong>Defines methods on general MDPs.</li>

 <li><strong>py: </strong>Defines the base classes ValueEstimationAgent and QLearningAgent, which your agents will extend.</li>

 <li><strong>py: </strong>Utilities, including util.Counter, which is particularly useful for Q-learners.</li>

 <li><strong>py: </strong>The Gridworld implementation.</li>

 <li><strong>py: </strong>Classes for extracting features on (state,action) pairs. Used for the approximate Q-learning agent (in qlearningAgents.py).</li>

</ul>

<h1>3            Reinforcement Learning</h1>

For all the problem titles described below, please refer to the link http://ai.berkeley. edu/reinforcement.html for the problem description and what is expected of each problem. As always the autograder has different test cases against which you can run your program to check the correctness. Please ensure your code is readable and use comments in your code to make it more clear for the person reading your code.

<strong>3.1      Value Iteration </strong>

<ul>

 <li>Code implementation</li>

</ul>

<strong>3.2         Bridge Crossing Analysis </strong>

<ul>

 <li>Code implementation</li>

</ul>

<strong>3.3      Policies </strong>

<ul>

 <li>Code implementation</li>

</ul>

<strong>3.4       Q-Learning </strong>

<ul>

 <li>Code implementation</li>

</ul>

<strong>3.5       Epsilon Greedy </strong>

<ul>

 <li>Code implementation</li>

</ul>

<strong>3.6         Bridge Crossing Revisited </strong>

<ul>

 <li>Code implementation</li>

</ul>

<strong>3.7        Q-Learning and Pacman</strong>

<ul>

 <li>Code implementation</li>

</ul>

<strong>3.8        Approximate Q-Learning </strong>

<ul>

 <li>Code implementation</li>

</ul>

<h1>4            Self Analysis</h1>

<ol>

 <li>What was the hardest part of the assignment for you?</li>

 <li>What was the easiest part of the assignment for you?</li>

 <li>What problem(s) helped further your understanding of the course material?</li>

 <li>Did you feel any problems were tedious and not helpful to your understanding ofthe material?</li>

 <li>What other feedback do you have about this homework?</li>

</ol>

<h1>5            Evaluation</h1>

Your code will be autograded for technical correctness. Please do not change the names of any provided functions or classes within the code, or you will wreak havoc on the autograder. If your code passes all the test cases in the autograder you would receive full points for the implementation.

However even if your code does not necessarily pass all the test cases, we would evaluate your code and then award you partial points accordingly. In such cases it would be even more beneficial if you could give a short description of what you tried and where you had failed and that would help us in giving you better points.