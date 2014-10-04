
# What I am trying

This will just be a simple program to test an idea I had for using RBMs in search problems. The search problem will be finding the max of a funcition from a string of bits to the reals. The algorithm I will test goes as follows,

```
x = vector of 1 and 0s of size n
y = vector of 1 and 0s of size m < n
f(x) = function to the reals
RBM(y) = one layer Restricted Bolzman Machine that goes from y to x

do untill good solution found\
    y = random
    fittness = f(RBM(y))
    if fittness is good 
        train RBM on y
repeat
```
basically I will conduct a random search that has some direction given by the RBM. There is some rational as to why this might be good but its hard to describe. I will just test it and see.

# What I will test
I will see if this algorithm performes any better then a normal random search. If it does that would acually be very suprising


