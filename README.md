
1. append()
- Description: Adds an item to the end of the list.

Example:
fruits = ["apple", "banana"]
fruits.append("cherry")
print(fruits)  # Output: ["apple", "banana", "cherry"]


2. extend()
-Description: Adds multiple items from another list or iterable to the end of the list.

Example:
fruits = ["apple", "banana"]
fruits.extend(["cherry", "date"])
print(fruits)  # Output: ["apple", "banana", "cherry", "date"]


3. insert()
- Description: Inserts an item at a specified position.

Example:
fruits = ["apple", "cherry"]
fruits.insert(1, "banana")
print(fruits)  # Output: ["apple", "banana", "cherry"]


4. remove()
-Description: Removes the first occurrence of a specified item.

Example:
fruits = ["apple", "banana", "cherry"]
fruits.remove("banana")
print(fruits)  # Output: ["apple", "cherry"]

5. pop()
- Description: Removes and returns the item at the specified position. If no index is specified, it removes the last item.

Example:
fruits = ["apple", "banana", "cherry"]
item = fruits.pop(1)
print(item)  # Output: "banana"
print(fruits)  # Output: ["apple", "cherry"]


6. clear()
- Description: Removes all items from the list, making it empty.

Example:
fruits = ["apple", "banana", "cherry"]
fruits.clear()
print(fruits)  # Output: []


7. index()
- Description: Returns the index of the first occurrence of a specified item.

Example:
fruits = ["apple", "banana", "cherry"]
index = fruits.index("banana")
print(index)  # Output: 1


8. count()
- Description: Returns the number of occurrences of a specified item in the list.

Example:
fruits = ["apple", "banana", "cherry", "banana"]
count = fruits.count("banana")
print(count)  # Output: 2


9. sort()
- Description: Sorts the items of the list in ascending or descending order.

Example:
numbers = [3, 1, 4, 1, 5]
numbers.sort()
print(numbers)  # Output: [1, 1, 3, 4, 5]


10. reverse()
- Description: Reverses the order of the items in the list.

Example:
fruits = ["apple", "banana", "cherry"]
fruits.reverse()
print(fruits)  # Output: ["cherry", "banana", "apple"]


11. copy()
- Description: Returns a shallow copy of the list.

Example:
fruits = ["apple", "banana", "cherry"]
fruits_copy = fruits.copy()
print(fruits_copy)  # Output: ["apple", "banana", "cherry"]


12. len()
- Description: Although not a method, len() is a built-in function that returns the number of items in the list.

Example:
fruits = ["apple", "banana", "cherry"]
print(len(fruits))  # Output: 3
