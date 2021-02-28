# 05 Means-End Analysis

## State Spaces
So, we can imagine problem solving as occurring in a state space.

Here is the initial state, here is the goal state. And the state space consists of all of the states that could be potentially produced from the initial state by iterative application of the various operators in this micro world. I want to come up with a path in the state space, takes me from initial state to the goal state. There is one path, this is not the only path, but this is one path to go from the initial state to the goal state. The question then becomes, how might an AI agent derive this path that may take it from the initial state to the goal state.

![https://dl.dropbox.com/s/gb0l97nvo1f84up/Screenshot%202016-01-27%2001.38.07.png](https://camo.githubusercontent.com/ad65da81486288273de400cd1138ae1f3a83bc432fdfa3d900b8b74dae57404c/68747470733a2f2f646c2e64726f70626f782e636f6d2f732f6762306c39376e766f3166383475702f53637265656e73686f74253230323031362d30312d323725323030312e33382e30372e706e67)
## Means-end Analysis
We can summarize the means-ends analysis method like this.

Compare the current state and the goal state. Find the differences between them. For each difference, look at what operators might be applicable. Select that operator that gets you closest to the goal state from the current state. We did this for the blocks and worlds problem. We also did this with regards to the business problem. But throughout those states in regards to business problem, which we're not getting us close to the goal state. This is the means-ends analysis method in summary.
## Problem Solving with means-end analysis
![https://dl.dropbox.com/s/av9b73lbnmbje4d/Screenshot%202016-01-27%2001.49.04.png](https://camo.githubusercontent.com/db12ec0126c36e820722375c192076390d6a26868dac18690c0e331666210e4d/68747470733a2f2f646c2e64726f70626f782e636f6d2f732f6176396237336c626e6d626a6534642f53637265656e73686f74253230323031362d30312d323725323030312e34392e30342e706e67)
## Problem reduction
Given the hard complex problem, reduce it.

Decompose it into multiple easier, smaller, simpler problems. Consider, for example, computer programming or software design that I'm sure many of you do all the time. Given a hard part of the address, you decompose it with a series of smaller problems. How do I read the input? How do I process it?

How do I write the output? That itself is a decomposition. In fact, one of the fundamental roles that knowledge plays is it tells you how to decompose a hard problem into simpler problems.

Then once you have solutions to this simpler smaller problems.

You can think about how to compose the sub-solutions to the sub-problems into a solution of the problem as a whole. That's how problem reduction works.

![https://dl.dropbox.com/s/517xm0r04cfv1k2/Screenshot%202016-01-27%2001.55.35.png](https://camo.githubusercontent.com/1da005899e2d61d94d4a467e9274c9a5f5abd749753523d8e56320863acfeba4/68747470733a2f2f646c2e64726f70626f782e636f6d2f732f353137786d30723034636676316b322f53637265656e73686f74253230323031362d30312d323725323030312e35352e33352e706e67)
