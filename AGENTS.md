```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines define the principles and rules for development of AGENTS.md, a repository for AI coding agents. Adherence to these principles is critical for maintaining code quality, consistency, and maintainability.

## 1. DRY (Don't Repeat Yourself)

*   All functionality and logic must be encapsulated within individual, well-documented files.
*   Avoid duplication of code across multiple files.
*   When a component needs to be reused, create a reusable component or module.
*   Document all reusable components thoroughly.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize simplicity and readability in code design.
*   Strive for the simplest solution that meets the requirements.
*   Avoid unnecessary complexity.
*   Focus on clear and concise expressions.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module/agent should have one and only one reason to change.
*   **Open/Closed Principle:**  The system should be extensible through mechanisms like modules, plugins, or interfaces, without modifying the core code.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Each class should have only the interface it needs, and no other.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement features that are currently required for the intended purpose.
*   Avoid adding unnecessary code that might be obsolete or redundant later.
*   Refactor and remove code that has become outdated or irrelevant.

## 5. Code Structure & File Management

*   **File Limit:** Each file must contain a maximum of 180 lines of code.
*   **Naming Conventions:** Use descriptive filenames and consistent naming conventions.
*   **Comments:** Provide clear and concise comments within the code explaining complex logic or design decisions. Comments should clearly state the purpose and rationale behind the code.
*   **Modularization:** Break down large modules into smaller, manageable units.
*   **Error Handling:** Implement robust error handling and logging for all operations.  Exceptions should be handled gracefully.
*   **Testing:** All code must be thoroughly tested.
*   **Documentation:**  Provide concise documentation within each file, detailing inputs, outputs, and potential side effects.

## 6. Testing - Mocking Only

*   All mocks and fake implementations must be generated *exclusively* during testing.
*   Tests should focus on validating the behavior of the agent, not the underlying implementation details.
*   Implement thorough unit, integration and end-to-end tests.
*   Each test should cover edge cases and boundary conditions.
*   All tests should use dependency injection to isolate components.

## 7.  Development Process

*   **Commit Frequency:**  Commit code frequently, ideally multiple times per day.
*   **Code Reviews:**  Mandatory code reviews for all changes before merging.
*   **Version Control:**  Use Git for version control.
*   **Dependencies:** Clearly define dependencies between modules and test cases.
*   **Documentation Updates:**  Keep documentation updated whenever code changes.

## 8.  Code Quality

*   Follow established coding standards.
*   Use appropriate data structures and algorithms.
*   Implement logging for debugging and monitoring.
*   Pay attention to potential performance bottlenecks.

## 9.  Specific Considerations for AI Agents

*   **State Management:**  Clearly define how states will be managed and updated.
*   **Learning/Adaptation:**  Consider how learning will be incorporated into the agent’s process.
*   **Safety & Ethics:**  Design the agent with safety and ethical considerations as primary goals.  Document these considerations.

## 10.  Testing Coverage

*   Minimum 80% code coverage.
*   Automated testing frameworks will be employed.
*   Test-Driven Development (TDD) methodology will be followed.

These guidelines aim to facilitate the creation of robust, maintainable, and well-documented AI coding agents. Failure to adhere to these principles may lead to increased maintenance costs and reduced code quality.
```