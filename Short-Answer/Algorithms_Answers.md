#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n) - As n increases by one, the while loop will run one iteration. It is directly proportional to the input size of n. Linear time complexity.

b) O(n log n) - As n gradually increases, the first loop will run a directly proportional number of times, but the inner loop will run more and more times. As the variable j is being multiplied by 2 each time though it is not as bad as O(n^2).

c) O(n) - As n increases by one, the function is called recursively one time. Any loops in a set up like this would be exponentially worse, but as this is a simple function performing one basic calculation it increarses proportionally to the

## Exercise II

The most efficient way to discover the highest floor you can safely drop an egg from would be to utilize the idea of a binary search.

Begin at the middle floor of the building and drop an egg. From there, based on the results, proceed through the following tasks:

- If it does not break, move halfway up the remaining consecutive unchecked floors and try again.
- If it does break, move halfway down the remaining consecutive unchecked floors and try again

Eventually you will find the exact floor that consistently will not break an egg when dropped.
