#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) - 
The while will run n * n * n times so as n gets bigger, the operations increase - that reduces to just n.  Inside of the while loop is multiplication, which doesn't increase based on n.

b) O(n log(n))
Classic nested loop
for loop runs "n" times, incrementing the index by 1 for each iteration through the loop. The while loop doubleds "j" every iteration, giving us the run time of O(n log (n))

c) O(n)
Because it recurses upon itself, it is a loop, the reason is because bunnies increase the number of recursions increase which puts the recursive loop at O(n). (Despite the recursion, all the operations are done in constant time)

## Exercise II

floor = 0

drop egg from floor: if egg does not break increment floor call drop egg from floor else if egg breaks, stop, as eggs from this floor onward will break.

The runtime complexity of this would be O(n) as we only have one loop, assuming that the floor the eggs break from changes.

If the floor the eggs break from were a constant it would be O(1) since it would only go to the same floor every single time, making it constant.


