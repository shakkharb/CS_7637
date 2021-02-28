
# 04 Generate & Test

## Generate & Test
Generate and test is a problem solving method. Given a problem, generate potential solutions to it, and then test the solutions for the efficiency for addressing the problem. If you had complete knowledge of the world, complete and correct knowledge of the world. If you had infinite computational resources. And if you had a method of reasoning that was guaranteed to be correct, then you can generate the correct, the optimal solution.

You don't need to test it. In general however, you do not have complete or correct knowledge of the world. You do not have infinite computational resources, and not all methods are guaranteed to be correct. In that case, you can generate potential solutions. Plausible solutions, and then test them. Estimates that will generate, and test.
## Smart testers
So suppose that we have a smarter tester, a tester which can detect when any state is identical to a previously visited state. In that case the tester may decide that this, this, and this state are identical to the initial state and therefore dismiss them. The tester also dismisses this state, as usual, because of the problem specification that one cannot have more prisoners than guards on any one bank.

You need a problem solving method that uses knowledge afforded by the knowledge representation to actually do the problem solving. Generating test is one of those problem solving methods. In general, when we do problem solving or reasoning, then there is a coupling between a knowledge representation and a problem solving method, like semantic networks and generating test.
## Smart generators
We can continue to apply this method of generate and test iteratively. So we can apply it on this state and that state and see what successor states we get.

If we do so, then we get a very large number of successor states. This is a problem of call many total explosion. While one was tasked with a small number of states, but the number of successor states keeps on increasing very rapidly.

Given a number of states, they try to find out all the potential successive states that are possible, given some simple rules of recombination. And then of a fitness function that acts as a tester. Genetic algorithms, therefore, are an effective method for a very large number of problems.

They're also a very inefficient method because neither the generator nor the testing generator algorithms are especially smart.
## Generate & Test in an unconstrained domain
Humans use generate and test as the problem-solving method all the time.

This is because we do not have complete or correct knowledge of the world.

We do not have infinite computational resources.

And we also do not always have recourse to a method of reasoning that is guaranteed to be correct.
