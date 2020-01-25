#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) because there's only one loop


b) O(n^2) because of the two nested loops


c) O(n) becuase it runs once for each bunny

## Exercise II

I'd calculate the middle floor and start there. If it breaks, f is below that floor. Otherwise, it's above. Then I'd calculate the middle of that floor and the top/bottom and repeat. Time complexity is O(log n) because as n increases, we'll likely cut the building in half more times.
