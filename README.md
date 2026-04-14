# Innovation_Studio_Module1_Quizzes

## Python Quiz (11/13)

1. Which statement correctly assigns the integer 10 to a variable named 'count'?

A) count = 10

B) int count = 10

C) let count := 10

D) var count = 10

Answer: A) count = 10


2. Which of the following is a valid Python list?

A) [1, 2, 3]

B) (1, 2, 3)

C) {1, 2, 3}

D) 1, 2, 3

Answer: A) [1, 2, 3]


3. What keyword starts a loop that iterates over items in a list?

A) for

B) while

C) loop

D) repeat

Answer: A) for


4. Which keyword exits a loop early?

A) exit

B) stop

C) break

D) skip

Answer: C) break


5. How do you define a function in Python?

A) function greet():

B) def greet():

C) func greet()

D) define greet():

Answer: B) def greet():


6. What is the correct way to call a function named 'calculate' with argument 5?

A) calculate(5)

B) call calculate 5

C) calculate = 5

D) function calculate(5)

Answer: A) calculate(5)


7. What does the 'return' keyword do in a function?

A) exits the program

B) outputs text to console

C) sends back a value to the caller

D) skips to the next iteration

Answer: C) sends back a value to the caller


8. Which operator checks equality between two values?

A) =

B) ==

C) ===

D) !=

Answer: B) ==


9. By convention, how many spaces should each indentation level be?

A) 2 spaces

B) 4 spaces

C) Tabs only

D) No indentation needed

Answer: C) Tabs only

Correct Answer: B) 4 spaces


Why I got it wrong: I have only ever used tabs for python indentation, but it is helpful to know that 4 spaces and tabs are the same distance visually.


11. Which statement skips the rest of the current loop iteration and continues with the next?

A) break

B) skip

C) continue

D) pass

Answer: D) pass

correct answer: C) continue

Why I got it wrong: I have yet to use continue in my scripts, however this makes sense for multiple loop situations.


12. How do you start a single-line comment in Python?

A) //

B) #

C) --

D) /*

Answer: B) #


13. Which built-in function outputs text to the console?

A) print()

B) echo()

C) console.log()

D) write()

Answer: A) print()












## SQL Quiz (10/12)
Testing out a different Markdown Method here


### 1. Which SQL command retrieves rows from a table?
- [x] **SELECT** (Correct)
- [ ] INSERT (Incorrect)
- [ ] UPDATE (Incorrect)
- [ ] DELETE (Incorrect)

### 2. What does the WHERE clause do in a query?
- [ ] Sorts the results (Incorrect)
- [ ] Limits how many rows return (Incorrect)
- [x] **Filters rows based on a condition** (Correct)
- [ ] Creates a new table (Incorrect)

### 3. Which command would you use to add a new employee record?
- [x] **INSERT INTO employees** (Correct)
- [ ] UPDATE employees (Incorrect)
- [ ] SELECT * FROM employees (Incorrect)
- [ ] DELETE FROM employees (Incorrect)

My answer - UPDATE employees

Why I got this wrong: My SQL class went deep into querrying and the nuances of that, but we did little work on adding or updating data. This will be something I will have to pay special attention to in the future.

### 4. Which statement modifies data that already exists?
- [ ] SELECT (Incorrect)
- [ ] INSERT (Incorrect)
- [x] **UPDATE** (Correct)
- [ ] CREATE (Incorrect)

### 5. Why should you include a WHERE clause with UPDATE or DELETE?
- [ ] To change the table's name (Incorrect)
- [x] **To avoid affecting every row** (Correct)
- [ ] To sort the output (Incorrect)
- [ ] To increase query speed (Incorrect)

### 6. Which keyword sorts query results by salary from highest to lowest?
- [ ] GROUP BY (Incorrect)
- [x] **ORDER BY salary DESC** (Correct)
- [ ] LIMIT (Incorrect)
- [ ] BETWEEN (Incorrect)

### 7. The LIKE operator is used to...
- [ ] Calculate totals (Incorrect)
- [x] **Search for a text pattern** (Correct)
- [ ] Delete rows (Incorrect)
- [ ] Grant permissions (Incorrect)

### 8. Which aggregate function returns the average salary?
- [ ] SUM (Incorrect)
- [ ] COUNT (Incorrect)
- [x] **AVG** (Correct)
- [ ] MIN (Incorrect)

### 9. To count employees in each role, which clause pairs with COUNT(*)?
- [ ] ORDER BY (Incorrect)
- [x] **GROUP BY** (Correct)
- [ ] HAVING (Incorrect)
- [ ] JOIN (Incorrect)

### 10. What does the PRIMARY KEY constraint guarantee?
- [x] **Values are unique and identify each row** (Correct)
- [ ] Column cannot be empty (Incorrect)
- [ ] Values are always positive (Incorrect)
- [ ] Rows are sorted by ID (Incorrect)

### 11. Which command permanently removes rows matching a condition?
- [ ] UPDATE (Incorrect)
- [x] **DELETE** (Correct)
- [ ] DROP (Incorrect)
- [ ] ALTER (Incorrect)

### 12. Starting a transaction begins with which statement?
- [x] **BEGIN TRANSACTION** (Correct)
- [ ] SAVEPOINT (Incorrect)
- [ ] ROLLBACK (Incorrect)
- [ ] COMMIT (Incorrect)

My Answer - Commit

Why I got it wrong: I am confused on the syntax for transactions. I will play around with this in a seperate submission.












## OOP Algorithims Quiz (9/12)

### 1. Which keyword is used to define a new class in Python?
- [ ] def (Incorrect)
- [x] **class** (Correct)
- [ ] struct (Incorrect)
- [ ] new (Incorrect)

### 2. Which special method initializes object state when a class instance is created?
- [ ] \_\_start\_\_ (Incorrect)
- [x] **\_\_init\_\_** (Correct)
- [ ] begin (Incorrect)
- [ ] constructor (Incorrect)

### 3. A subclass providing its own version of a parent method is an example of...
- [ ] overloading (Incorrect)
- [x] **overriding** (Correct)
- [ ] encapsulation (Incorrect)
- [ ] abstraction (Incorrect)

My Answer: abstraction

Why I got it wrong: I thought abstraction meant blurring the parent method, but apparently it is the covering up of complex details

### 4. What is a primary benefit of using inheritance in object-oriented design?
- [ ] Forcing static methods (Incorrect)
- [ ] Avoiding objects (Incorrect)
- [x] **Reusing existing code** (Correct)
- [ ] Increasing code duplication (Incorrect)

### 5. Which sorting algorithm generally has the best average time complexity?
- [ ] Bubble Sort (Incorrect)
- [ ] Insertion Sort (Incorrect)
- [x] **Merge Sort** (Correct)
- [ ] Selection Sort (Incorrect)

### 6. Big O notation describes...
- [ ] exact runtime in seconds (Incorrect)
- [x] **the worst-case growth rate of an algorithm** (Correct)
- [ ] how many lines of code you wrote (Incorrect)
- [ ] the precise memory address (Incorrect)

### 7. When searching a sorted list, which algorithm is more efficient than linear search?
- [ ] Depth-first search (Incorrect)
- [ ] Random search (Incorrect)
- [x] **Binary search** (Correct)
- [ ] Breadth-first search (Incorrect)

### 8. What is the worst-case time complexity of Bubble Sort?
- [ ] O(n) (Incorrect)
- [ ] O(n log n) (Incorrect)
- [ ] O(log n) (Incorrect)
- [x] **O(n^2)** (Correct)

### 9. Which data structure is typically used to implement breadth-first search (BFS)?
- [ ] Stack (Incorrect)
- [x] **Queue** (Correct)
- [ ] Priority Queue (Incorrect)
- [ ] Dictionary (Incorrect)

My Answer: Dictionary

Why I got it wrong: I have yet to utilize Queue so I was confused with how it worked.

### 10. Adding an item to the end of a Python list takes which amount of time on average?
- [ ] O(log n) (Incorrect)
- [ ] O(n) (Incorrect)
- [x] **O(1)** (Correct)
- [ ] O(n^2) (Incorrect)

### 11. Which algorithm is considered stable and efficient for nearly sorted data?
- [ ] Quick Sort (Incorrect)
- [ ] Heap Sort (Incorrect)
- [x] **Insertion Sort** (Correct)
- [ ] Selection Sort (Incorrect)

My Answer: Quick Sort

Why I got it wrong: I saw "efficient" and instinctively went with Quick Sort

### 12. What is the time complexity of binary search?
- [ ] O(n) (Incorrect)
- [ ] O(n^2) (Incorrect)
- [x] **O(log n)** (Correct)
- [ ] O(n log n) (Incorrect)












## SOLID Principals Quiz (4/5)

### 1. What does the 'S' in SOLID stand for?
- [ ] Standardization
- [x] Single Responsibility
- [ ] System Design
- [ ] Simple Integration

### 2. Which principle encourages extending code behavior without modifying existing classes?
- [x] Open/Closed
- [ ] Interface Segregation
- [ ] Dependency Inversion
- [ ] Liskov Substitution

### 3. Violating the Liskov Substitution Principle often results in...
- [x] Fragile inheritance hierarchies
- [ ] Duplicate interfaces
- [ ] Loose coupling
- [ ] Simpler code

### 4. The Interface Segregation Principle suggests that...
- [ ] one large interface is better than many small ones
- [x] clients should depend on interfaces they use
- [ ] interfaces must have default implementations
- [ ] inheritance should be avoided

### 5. Dependency Inversion promotes...
- [ ] depending on concrete classes
- [ ] separating data from behavior
- [x] relying on abstractions
- [ ] always using inheritance

What I put: "always using inheritance"

Why I got it wrong: I forgot what dependency inversion was

