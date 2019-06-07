Add your answers to the Algorithms exercises here.

a) The time-complexity is linear O(n) & the space-complexity is O(1)
We are only storing one variable and we aren't allocating space for any additional data structures so the memory costs don't scale with the size of n.
The time-complexity is linear because the multiplicative step in each iteration of the while loop brings `a` closer to n^3 and n^3 remains constant so the size of `n` doesn't have any affect on how our algorithm scales over time.

b) the time-complexity is O(n^4) because we have 3 nested loops. The space-complexity is O(1) We are only storing one variable and we aren't allocating space for any additional data structures so the memory costs don't scale with the size of n. As n grows our algorithm slows down dramatically which makes this a very inefficient algorithm.

c) the time-complexity is O(n + 1) but we can just write that as O(n). It's O(n) because we make `n` recursive calls. The space-complexity is also O(n) because each recursive call adds a function to our call stack.

Exercise II

pseudocode

run modified binary search on input
choose middle element
if egg is broken at this element then we know that any element higher than our current element will also break the egg
if not broken take all the elements to the left and split them into two lists. repeat previous step

time-complexity - O(lg n) or O(n lg n) if our input is not sorted.
space-complexity O(1)
