#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) n

The loop will run n number of times. You can almost cancel out two of the n's since they're within the while loop condition and the loop itself. So froma runtime perspective it's basically a < n

b) n log n

The first loop has a run time of n, the second loop has a runtime of log n since j is multiplied by 2 during each loop (meaninng it will more quicklly approach n than a traditional for loop incrementing by 1).

c) n

This will recurse n times until it hits the base case.

## Exercise II

# Step 1 determin a top and bottom floor

# Step 2 start at the middle floor(top_floor + bottom_floor//2)and

# Step 3 drop off an egg

#Step 4a if that egg breaks and you have already visited the floor below and the egg did not break, this is floor f. Otherwise # Step 5a move halfway down between floors # Step 6a reassign top to your current floor, bottom remains the same # Step 7a go back to Step 3
#Step 4b if that egg does not break, and you have already visited the floor above and the egg did break, the floor above is f. Otherwise # Step 5b move halfway up floors # Step 6b reassign bottom to your current floor, top remains the same # Step 7b go back to Step 3

#runtime complexity on average would be log n (similar to binary search)

# If we wanted to minimize just for broken eggs

#begin throwing one egg off of the lowest floor
#if the egg does not break move one floor up
#continue until 1 egg is broken
#the floor below where 1 egg is broken would be the value of f
