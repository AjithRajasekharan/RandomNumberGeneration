# RandomNumberGeneration
Generate random numbers with probability distribution.



This is a C# solution to th below problem.

Implement discrete integer random number generator with a given distribution. The distribution is provided as real weights of indices. Provide unit tests to check the correctness of the solution.

Examples:

1.Input: [1.0, 2.0]

Output: 0 with probability 1⁄3 and 1 with probability 2⁄3

2.Input: [1.0, 1.0, 1.0, 1.0, 1.0]

Output: a number between 0 and 4 with equal probabilities

3.Input: [2.0, 0.0, 2.0]

Output: 0 with probability 1⁄2 and 2 with probability 1⁄2. 1 should not be generated.

The solution is developed in C# with Visual studi 2015
This contains a RandomGenerator class library which has the code to generate random number accoring to input distribution , a console application to test it and unit test project.

This works up to two decimal places distribution.
