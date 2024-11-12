# Python-list-functions

# Initial list of cars
cars = ["bmw", "mahindra", "suzuki", "rolls royce", "bentley", "aston martin", "tata", "audi", "mustang"]

# 1. Append "ferrari" to the list
cars.append("ferrari")
print("After append:", cars)

# 2. Insert "porsche" at index 3
cars.insert(3, "porsche")
print("After insert at index 3:", cars)

# 3. Clear all elements from the list
cars.clear()
print("After clear:", cars)

# Re-initialize list after clear for remaining operations
cars = ["bmw", "mahindra", "suzuki", "rolls royce", "bentley", "aston martin", "tata", "audi", "mustang"]

# 4. Sort the original list of cars in alphabetical order and store in sorted_cars
sorted_cars = sorted(cars)  # Doesn't change the original list
print("Sorted list:", sorted_cars)

# 5. Remove "audi" from the list
cars.remove("audi")
print("After removing 'audi':", cars)

# 6. Find the index of "mustang"
index_mustang = cars.index("mustang")
print("Index of 'mustang':", index_mustang)

# 7. Extend the list with another list of cars: ["tesla", "nissan"]
cars.extend(["tesla", "nissan"])
print("After extend with ['tesla', 'nissan']:", cars)

# 8. Pop the last element from the list and print it
last_car = cars.pop()
print("Popped element:", last_car)
print("List after pop:", cars)

# 9. Count how many times "bmw" appears in the list
bmw_count = cars.count("bmw")
print("Count of 'bmw':", bmw_count)

# 10. Append multiple cars: ["jaguar", "fiat"] to the list
cars.extend(["jaguar", "fiat"])
print("After appending multiple cars ['jaguar', 'fiat']:", cars)

# 11. Insert multiple cars ["volvo", "honda"] at index 2
cars[2:2] = ["volvo", "honda"]
print("After inserting multiple cars ['volvo', 'honda'] at index 2:", cars)

# Initial list of cars for testing each task
cars = ["bmw", "mahindra", "suzuki", "rolls royce", "bentley", "aston martin", "tata", "audi", "mustang"]

# 12. Clear If Empty
# Check if the list is empty and clear it if it is
if not cars:  # Checks if the list is empty
    cars.clear()
print("After checking and clearing if empty:", cars)

# 13. Sort Descending
# Sort the original list of cars in descending order
cars.sort(reverse=True)
print("Sorted list in descending order:", cars)

# 14. Remove All Occurrences
# Remove all occurrences of "bmw" from the list
cars = [car for car in cars if car != "bmw"]
print("After removing all occurrences of 'bmw':", cars)

# 15. Find Last Index
# Find the last index of "tata"
if "tata" in cars:
    last_index_tata = len(cars) - 1 - cars[::-1].index("tata")
else:
    last_index_tata = -1  # Returns -1 if "tata" is not found
print("Last index of 'tata':", last_index_tata)

# 16. Extend with Condition
# Extend the list with ["ferrari", "lambo"] only if "bmw" is in the list
if "bmw" in cars:
    cars.extend(["ferrari", "lambo"])
print("After conditional extend:", cars)

