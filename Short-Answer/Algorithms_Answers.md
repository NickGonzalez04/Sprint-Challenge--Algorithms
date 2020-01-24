#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Runtime of 0(n). One loop.


b) Runtime of 0(n^2). Nested for loop 


c) Runtime of 0(n). Runtime is based of the n

## Exercise II

Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.


I believe the best way to apporach this is a runtime complexity of o(n).

Start with the egg not being broken
Start with floor 1
if dropped from floor 1 and the egg does not break then increment 1 and go to the next floor and drop again until we find the n floor that causes the egg to break. 



