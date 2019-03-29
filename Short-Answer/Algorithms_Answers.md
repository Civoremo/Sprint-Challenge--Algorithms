Add your answers to the Algorithms exercises here.

## I.

a. O(n)

    - One loop that take O(n) time to run; there is one loop in the algorithm and no other major factors that would change the time complexity, hence the worst case scenario for the function is O(n).

b. O(n^4)

    - There is a FOR loop that takes O(n) time to run and within that for loop are another 3 nested FOR loops with O(n) time complexity each. O(n)*O(n)*O(n)*O(n) brings our total time complexity to O(n^4).

c. O(n)

    - Recursive loops run at an O(n) time complexity.

## II.

        - Half the number of floors of the n-story building and drop the egg to test if it would break.
        - If it doesnt break, half the floors above that point and repeat the process of dropping the egg to test if it would break.
        - If the egg does break, half the floors below that point and drop test the egg.
        - repeat until dividing floors in half is left with the one floor 'f'


    Example:
    a)
    [9]
    [8]
    [7]
    [6]
    [5] -> half, dropped; breaks
    [4]
    [3]
    [2]
    [1]

    b)
    [5]
    [4]
    [3] -> half, dropped; doesnt break
    [2]
    [1]

    c)
    [5]
    [4] -> half, dropped: breaks
    [3]

    c)
    [3] -> half, dropped: doesn break

    f = 3; it is the highest floor the egg can be dropped without breaking
