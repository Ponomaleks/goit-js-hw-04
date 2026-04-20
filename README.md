# goit-js-hw-04

## Topic 6: Objects and Object Methods

This section focuses on object iteration and using built-in methods to process structured data.

---

### Task 1: Product Packing (Object Values)
**File:** `task-1.js`

Create a function `isEnoughCapacity(products, containerSize)` that determines if all products can fit into a shipping container.
- **Logic:**
  - Extracts all values from the `products` object using `Object.values()`.
  - Calculates the sum of all item quantities.
  - Compares the total quantity with the `containerSize` limit.
- **Returns:** `true` if the total is within the limit, otherwise `false`.

### Task 2: Average Calorie Calculator
**File:** `task-2.js`

Write a function `calcAverageCalories(days)` that calculates the average daily calorie intake based on an array of objects.
- **Input:** An array of objects, where each object contains a `day` (string) and `calories` (number).
- **Logic:**
  - Sums up the `calories` property from each object in the array.
  - Divides the total sum by the number of elements in the array.
  - Handles empty arrays by returning `0`.
- **Goal:** Practice accessing object properties within an array iteration.

### Task 3: Game Profile (Object Methods & `this`)
**File:** `task-3.js`

Enhance a `profile` object by adding methods that manage user data using the `this` keyword.
- **Properties:**
  - `username`: String representing the player's name.
  - `playTime`: Number representing active hours.
- **Methods:**
  - `changeUsername(newName)`: Updates the `username` property.
  - `updatePlayTime(hours)`: Adds the specified number of hours to `playTime`.
  - `getInfo()`: Returns a template string: `"<Username> has <amount> active hours!"`.
- **Key Concept:** Practicing the use of `this` to access and modify an object's internal state.