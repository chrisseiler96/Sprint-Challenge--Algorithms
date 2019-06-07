Add your answers to the Algorithms exercises here.

## 1)

a)O(n)


b) O(n^4)


c) O(n)

## 2)
I believe a binary search styled algorithm is applicable here. The floors are in sorted order (higher floors will be more likely to break the egg). We can start by droppinh the egg off of the middle floor, if the egg breaks we must move down to the floor halfway between our current floor and the ground and repeat this process. This algorithm runs in logarithmic time, we could find floor _f_ with a dozen eggs for any amount of floors 4096 or lower.