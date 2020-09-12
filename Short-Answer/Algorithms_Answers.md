#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) This is O(n) because the while loop runtime will increase. it will equal n \* n. linear run time

b) This is O(n log (n)). This is because of the nested while loopp in the for loop. The for loop will run n times and while loop will run O(log n) times because j is incrementing by doubling its value with each loop.

c) This is also O(n). This is because it is just reducing number of bunnies by one with each recursive call

## Exercise II

I feel like this would be a binary search because linear would start at the ground and go up to nth floor. Drop the egg from the middle floor and middle floor + 1. if lower of the 2 does not break, but high does, f is middle floor + 1

if both eggs break, we could go half way to ground level and repeat process. if both eggs do not break, we would go half way to top level and drop from 2 adjancent floors

keep this going, halving the number of floors we are looking at until we found floor

runtime would be O(log n)
