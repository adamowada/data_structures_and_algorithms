## Hashtable
Class that will create a hashtable.

## Challenge
Without using any builtin functionality, create a hashtable.

## Approach & Efficiency
Time: o(n) Space: o(n)
Creation of Node is o(1)

# API
Node - Builds the LinkedList Node
add - Takes in both key and value.  This method should has they key, and add the key and value 
    pair to the table, handling collisions as needed.
get - Takes in the key and returns the value from the table.
contains - takes in the key and returns a boolean, indicating if the key exists in the table.
hash - Takes in an arbitrary key and returns an index in the collection.

# Repeated Words
Will take in a length string and return the first duplicate word.
Time O(n)
Space O(n^2)

# Tree Intersection
Will take in 2 binary trees and return a set of values that are shared between the 2 trees.
Time: O(n^2)
Space O(n^2)

# Left Join
Will take 2 hash maps and merge into one, returning the left map with appended values from 
the 2nd map.
