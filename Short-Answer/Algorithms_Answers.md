#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) o(n)


b) o(n log n)


c) o(n)

## Exercise II

Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.


# start on the middle floor
# throw an egg off, if it breaks go to the middle floor between the current floor and the first floor and repeat
# if it doesnt break go up to the middle floor between the current floor and the top floor and repeat
# repeat this process until you find the flirst floor that will break the egg.. that is f

# the time complexity for this algorithm would be o(log n)


