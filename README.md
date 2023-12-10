# PythonProject-DSA-TimeAndSpace

Time complexity of a list comprehension vs a loop vs a map function

list comprehension - O(n) where n is the length of the list. Since the items are iterated over once.
a for loop - O(n) depending on the number of iterations and if its a nested loops or additional operations within the loop where n is the number of items being iterated over
map function - O(m*n) - where m represents the complexity (if a nested loop) of the function being used in the map and n represents the number of items being iterated over

Time and space complexity of the following list methods
insert - Time complexity is O(n) where n is the length of the list because all elements will have to be shifted to make way for the new item. Space complexity is O(1) because it modifies the original list without creating any memory. It may be O(n) if the total number of elements in the list exceeds the allocated memory capacity and python needs to copy the list to a new location in memory.

extend - O(m)  where m is the number of elements to be added to the existing list. Space complexity is O(m) since it allocates memory for m new elements.

pop - O(n) where n is the length of the list because all elements will have to be shifted. Space complexity is O(1) because it modifies the original list without creating any memory for any new item.

remove - O(n) where n is the length of the list because it iterates over the list to find the position of the item to remove. Space complexity is O(1) because it modifies the original list without creating any memory for any new item.
