# Test levels

## 1. Unit Testing:
   - Tests individual units or components of code.
   - Focuses on verifying the correctness of each unit.
   - Typically, performed by **developers** using frameworks like JUnit or NUnit.
   - Helps identify defects at an early stage and facilitates code refactoring.

## 2. Integration Testing:
   - Tests the interaction between integrated components.
   - Ensures that components work together as expected.
   - Identify issues with interfaces, data communication, and dependencies.
   - Conducted after unit testing and before system testing.
   - Typically, performed by **developers**/**tester**

## 3. System Testing:
   - Tests the entire software system as a whole.
   - Verifies that the system meets specified requirements.
   - Tests functional and non-functional aspects of the system.
   - May involve both manual and automated testing techniques.
   - Typically, performed by **tester**

## 4. Acceptance Testing:
   - Ensures that the software meets user expectations.
   - Validates the system against real-world scenarios.
   - Helps determine whether the software is ready for deployment.
   - Typically, performed by **end-user**/**stack-holders**

## Key differences between different test levels in software testing:

| Test Level         | Purpose                                                    | Scope                       | Performed by         | Timing                                      | 
|--------------------|------------------------------------------------------------|------------------------------|----------------------|---------------------------------------------|
| Unit Testing       | Verify individual units of code for correctness            | Code components (modules)   | Developers           | Early stages of development                  |
| Integration Testing| Test interactions between integrated components             | Groups of integrated units  | Developers/Testers   | After unit testing and before system testing |
| System Testing     | Validate the entire software system as a whole             | Complete system             | Testers              | After integration testing and before acceptance testing |
| Acceptance Testing | Determine if the software meets user expectations          | End-to-end user scenarios   | End-users/Stakeholders | Towards the end of the development cycle |
