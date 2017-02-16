# Path Walking

The goal of this program is to determine the number of paths to end on an array.  There will be obstacles in the way at some of the locations ending your journey prematurely.

### Function buildPath()
This function will accept two inputs, p which stands for the percentage of traps, and n which represents the length of the array.
  +  Inside the function declare a new variable path and assign it an empty array.
  +  Write a for-loop that will fill the array of size n with the booleans true or false.
    -  Inside the loop declare a random number r.
    -  If r is less than or equal to p, assign the path false.
    -  Otherwise, assign the path true.
  +  Make sure that the last array entry is true.
  +  Finally return your path.

### Function stroll()
This function accepts two inputs, an array named path, and an index representing your current location.
  +  This function should be a recursive function that only moves one step at a time.
    -  If you reach the end, return 1;
    -  If you reach a false-location, return 0.
    -  Otherwise, return the next step.

### Function rsj - Run, Skip, Jump
This function accepts two inputs, an array named path, and an index representing your current location.
  +  This should be a recursive function that moves one step, two steps, or five steps.
  +  The same requirements hold as before.
  +  In addition, think about what you will add to the code to prevent over shooting.
