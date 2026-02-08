## THEORY

A dictionary in Python is an unordered, mutable collection of data that stores elements in **key–value pairs**. Dictionaries are written using curly braces `{}` where each key is unique and maps to a value. Keys are generally immutable data types such as strings, numbers, or tuples, while values can be of any data type.

Dictionaries are widely used because they allow **fast lookup**, **easy modification**, and **clear representation of structured data** such as student records, product lists, and user credentials.

### Key Features of Dictionaries

* Keys must be **unique**; if a key is repeated, the **latest value overwrites the previous one**.
* Values can be modified, added, or removed after dictionary creation.
* Dictionary elements are accessed using their keys rather than index positions.
* Built-in methods like `get()`, `keys()`, `values()`, and `items()` make data handling efficient.

### Applications of Dictionaries

* Storing student marks and details
* Managing login credentials
* Representing real-world objects (cars, products, users)
* Finding maximum/minimum values based on keys

---

## ALGORITHM

### Algorithm 1: Handling Duplicate Keys in a Dictionary

1. Start
2. Create a dictionary with product names as keys and prices as values
3. Include a duplicate key intentionally
4. Print the dictionary
5. Observe that the last value of the duplicate key is retained
6. Stop

---

### Algorithm 2: Retrieving Value Using `get()` Method

1. Start
2. Create a dictionary containing student marks
3. Accept student name as input
4. Use the `get()` method to retrieve marks
5. If the key does not exist, display a default message
6. Stop

---

### Algorithm 3: Simple Username and Password Validation

1. Start
2. Create a dictionary with usernames as keys and passwords as values
3. Accept username and password from the user
4. Check if the username exists in the dictionary
5. Verify whether the entered password matches the stored password
6. Display login success or failure message
7. Stop

---

### Algorithm 4: Finding the Topper Using Dictionary

1. Start
2. Create a dictionary with student names as keys and marks as values
3. Use the `max()` function with `key=marks.get`
4. Store the key having the maximum value
5. Display the topper name and marks
6. Stop

---

## CONCLUSION

From this experiment, we learned how to create and manipulate dictionaries in Python. We understood how duplicate keys behave, how to safely retrieve values, how dictionaries can be used in authentication systems, and how to find maximum values efficiently. Dictionaries are powerful data structures that simplify real-world data representation and processing.
