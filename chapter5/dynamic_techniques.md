## Dynamic Techniques

### 1. Structural Techniques or White Box Techniques:
   - These techniques involve testing the internal structure, design, and implementation details of the software.
   - The focus is on analyzing the code's structure and logic to design effective tests.
   - They require knowledge of the code's internals and access to the source code.

**1.1. Statement Coverage Testing:**
   - Measures the extent to which each statement in the code has been executed during testing.
   - Aims to ensure that all statements have been tested at least once.

**1.2. Branch Coverage Testing:**
   - Measures the extent to which each decision branch or conditional statement in the code has been executed.
   - Verifies that all possible outcomes of the decision points have been tested.

**1.3. Path Coverage Testing:**
   - Aims to test all possible paths through the code, including every statement and branch.
   - Focuses on ensuring that every feasible execution path has been exercised.

**1.4. Conditional Coverage Testing:**
   - Focuses on testing the various conditions within the code, including true/false outcomes and boundary conditions.
   - Ensures that each condition has been tested with different possibilities.

**1.5. Loop Coverage Testing:**
   - Focuses on testing different scenarios related to loops, including loop entry, exit, and iterations.
   - Ensures that the loop constructs are thoroughly tested.

### 2. Black Box Techniques or Specification Based Techniques:
   - These techniques focus on testing the software without knowledge of its internal structure or implementation details.
   - The focus is on verifying the software against specified requirements or specifications.

**2.1. Boundary Value Analysis:**
   - Tests the software using values at the boundaries of input or output ranges.
   - Verifies how the software handles values at the lower and upper limits, as well as just beyond those limits.

**2.2. Equivalence Class Partition:**
   - Divides the input or output values into groups or classes based on their behavior or characteristics.
   - Selects representative values from each class to design test cases.

**2.3. State Transition Technique:**
   - Tests the software by modeling and testing its behavior as it transitions between different states.
   - Focuses on identifying valid and invalid state transitions and the associated actions or outputs.

**2.4. Decision Table:**
   - Uses a table format to define various combinations of inputs, conditions, and actions or outputs.
   - Helps identify test cases that cover all possible combinations of input conditions.

**2.5. Use Case Testing:**
   - Tests the software based on real-world user scenarios or interactions.
   - Focuses on validating the software's functionality, behavior, and user interactions.

### 3. Experienced Based Techniques:
   - These techniques rely on the tester's knowledge, intuition, and experience to design and execute tests.

**3.1. Error Guessing:**
   - Involves identifying potential errors, defects, or weak points in the software based on the tester's experience.
   - Uses past knowledge to guess and design tests that target specific areas or scenarios that are prone to errors.

**3.2. Exploratory Testing:**
   - Involves simultaneous learning, testing, and designing of test cases without predefined scripts or test cases.
   - Relies on the tester's skills, creativity, and understanding of the software to uncover defects.
   
## Examples:
### Boundary Value Analysis:

Let's consider a scenario where we have to test a form that accepts a numeric input for a user's age. The requirement states that the age must be between 18 and 65.

Using Boundary Value Analysis, we would select test cases that cover the boundaries and immediate values around them. In this case, we would consider the following test cases:

1. Test case: Minimum valid value (lower boundary)
   - Age: 18
   - Expected behavior: The form should accept the age and proceed to the next step.

2. Test case: Just below the minimum value (invalid)
   - Age: 17
   - Expected behavior: The form should display an error message indicating that the age is too young.

3. Test case: Maximum valid value (upper boundary)
   - Age: 65
   - Expected behavior: The form should accept the age and proceed to the next step.

4. Test case: Just above the maximum value (invalid)
   - Age: 66
   - Expected behavior: The form should display an error message indicating that the age is too old.

5. Test case: Typical valid value (within the range)
   - Age: 30
   - Expected behavior: The form should accept the age and proceed to the next step.

By considering these test cases, we cover the boundaries of the input range (18 and 65) and include one test case just below and above each boundary to check the behavior in those scenarios.

### Equivalence Class Partitioning:

Consider a scenario where you need to test a form that accepts a numeric input for a user's age. The requirement states that the age must be between 18 and 65.

Using Equivalence Class Partitioning, you would divide the input values into different equivalence classes or groups based on their behavior. In this case, we can identify the following equivalence classes:

1. Valid Equivalence Class: Age between 18 and 65 (inclusive)
   - Age values: 18, 25, 40, 60, 65
   - Expected behavior: The form should accept ages within this range.

2. Invalid Equivalence Class: Age below 18
   - Age values: 17, 0, -5
   - Expected behavior: The form should display an error message indicating that the age is too young.

3. Invalid Equivalence Class: Age above 65
   - Age values: 70, 100, 80
   - Expected behavior: The form should display an error message indicating that the age is too old.

By considering these equivalence classes, you can select representative values from each class to design test cases. Here are some example test cases:

1. Test case: Age within the valid equivalence class
   - Age: 40
   - Expected behavior: The form should accept the age and proceed to the next step.

2. Test case: Age below the valid range (invalid equivalence class)
   - Age: 17
   - Expected behavior: The form should display an error message indicating that the age is too young.

3. Test case: Age above the valid range (invalid equivalence class)
   - Age: 70
   - Expected behavior: The form should display an error message indicating that the age is too old.

### State Transition Technique:

Consider a scenario where you need to test the functionality of an ATM. The ATM can be in various states, such as "Idle," "Card Inserted," "PIN Entered," "Transaction Selected," "Amount Entered," and "Transaction Complete." The transitions between these states are governed by specific events and conditions.

Using the State Transition Technique, you would model and test the behavior of the ATM as it transitions between different states. Here's an example state transition diagram:

```
Initial State: Idle
State Transitions:
- Idle --(1)--> Card Inserted
- Card Inserted --(2)--> PIN Entered
- PIN Entered --(3)--> Transaction Selected
- Transaction Selected --(4)--> Amount Entered
- Amount Entered --(5)--> Transaction Complete
- Amount Entered --(6)--> Transaction Selected
```

Based on this state transition diagram, you can design test cases to cover different state transitions and validate the ATM's behavior. Here are some example test cases:

1. Test case: Successful transaction flow (valid sequence)
   - Current state: Idle
   - Trigger: (1) Card Inserted
   - Expected behavior: The ATM should transition from Idle to Card Inserted state.

   - Current state: Card Inserted
   - Trigger: (2) PIN Entered
   - Expected behavior: The ATM should transition from Card Inserted to PIN Entered state.

   - Current state: PIN Entered
   - Trigger: (3) Transaction Selected
   - Expected behavior: The ATM should transition from PIN Entered to Transaction Selected state.

   - Current state: Transaction Selected
   - Trigger: (4) Amount Entered
   - Expected behavior: The ATM should transition from Transaction Selected to Amount Entered state.

   - Current state: Amount Entered
   - Trigger: (5) Transaction Complete
   - Expected behavior: The ATM should transition from Amount Entered to Transaction Complete state.

2. Test case: Cancel transaction flow (invalid transition)
   - Current state: PIN Entered
   - Trigger: (6) Transaction Selected
   - Expected behavior: The ATM should not transition from PIN Entered to Transaction Selected. It should remain in the PIN Entered state.

3. Test case: Invalid sequence (invalid transition)
   - Current state: Idle
   - Trigger: (2) PIN Entered
   - Expected behavior: The ATM should not transition from Idle to PIN Entered without the Card Inserted event. It should remain in the Idle state.

By considering these test cases, you cover different valid and invalid state transitions of the ATM system.

### Decision Table:

Consider a scenario where you need to test a discount calculation feature in an e-commerce system. The discount calculation depends on two factors: "Membership Level" and "Purchase Amount." Let's define the following rules for the discount calculation:

1. If the Membership Level is "Silver" and the Purchase Amount is less than $100, apply a 5% discount.
2. If the Membership Level is "Silver" and the Purchase Amount is $100 or more, apply a 10% discount.
3. If the Membership Level is "Gold" and the Purchase Amount is less than $200, apply a 10% discount.
4. If the Membership Level is "Gold" and the Purchase Amount is $200 or more, apply a 15% discount.
5. If the Membership Level is "Platinum" and the Purchase Amount is less than $300, apply a 15% discount.
6. If the Membership Level is "Platinum" and the Purchase Amount is $300 or more, apply a 20% discount.
7. If the Membership Level is not specified or invalid, apply no discount.

Using a Decision Table, we can visually represent these rules and design test cases to cover different combinations. Here's an example decision table:

| Membership Level | Purchase Amount | Discount Applied |
|------------------|-----------------|------------------|
| Silver           | < $100          | 5%               |
| Silver           | >= $100         | 10%              |
| Gold             | < $200          | 10%              |
| Gold             | >= $200         | 15%              |
| Platinum         | < $300          | 15%              |
| Platinum         | >= $300         | 20%              |
| Any              | Any             | No Discount      |

Based on this decision table, you can design test cases to cover different combinations of Membership Level and Purchase Amount. Here are some example test cases:

1. Test case: Silver membership, Purchase Amount less than $100
   - Membership Level: Silver
   - Purchase Amount: $80
   - Expected Discount Applied: 5%

2. Test case: Gold membership, Purchase Amount $200 or more
   - Membership Level: Gold
   - Purchase Amount: $250
   - Expected Discount Applied: 15%

3. Test case: Platinum membership, Purchase Amount less than $300
   - Membership Level: Platinum
   - Purchase Amount: $250
   - Expected Discount Applied: 15%

4. Test case: Membership Level not specified
   - Membership Level: Not specified
   - Purchase Amount: $150
   - Expected Discount Applied: No Discount

|Membership|Purchase Amount|Discount|
|----------|---------------|--------|
|Silver|80|5%|
|Silver|110|10%|
|Gold|250|15%|
|Platinum|250|15%|
By considering these test cases, you cover different combinations of Membership Level and Purchase Amount to validate the discount calculation.

### Use Case Testing:

Consider a scenario where you need to test the functionality of a shopping cart in an e-commerce application. Let's define a specific use case for adding items to the shopping cart. The use case involves the following steps:

1. The user logs into the application.
2. The user searches for a product.
3. The user selects a product from the search results.
4. The user adds the product to the shopping cart.
5. The user views the shopping cart to verify the added product.

Using Use Case Testing, we can design test cases to cover this specific use case. Here are some example test cases:

1. Test case: Successful addition of a product to the shopping cart
   - Preconditions: The user is logged into the application and has performed a search for the desired product.
   - Steps:
     1. User selects a product from the search results.
     2. User adds the product to the shopping cart.
     3. User views the shopping cart.
   - Expected behavior: The selected product should be successfully added to the shopping cart, and the shopping cart should display the added product.

2. Test case: Adding multiple products to the shopping cart
   - Preconditions: The user is logged into the application and has performed a search for multiple products.
   - Steps:
     1. User selects multiple products from the search results.
     2. User adds the selected products to the shopping cart.
     3. User views the shopping cart.
   - Expected behavior: All the selected products should be successfully added to the shopping cart, and the shopping cart should display all the added products.

3. Test case: Adding an out-of-stock product to the shopping cart
   - Preconditions: The user is logged into the application and has performed a search for a product that is currently out of stock.
   - Steps:
     1. User selects the out-of-stock product from the search results.
     2. User attempts to add the out-of-stock product to the shopping cart.
   - Expected behavior: The system should display an appropriate error message indicating that the selected product is out of stock and cannot be added to the shopping cart.

By considering these test cases, you cover different scenarios and variations of the use case, ensuring that the functionality of adding items to the shopping cart is thoroughly tested.


