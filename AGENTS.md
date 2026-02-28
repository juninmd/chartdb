```markdown
# AGENTS.md File Guidelines

These guidelines outline the principles and rules for development of the AGENTS.md repository. Adherence to these guidelines is crucial for ensuring a robust, maintainable, and high-quality codebase.

## 1. DRY (Don't Repeat Yourself)

*   **Code Reuse:**  Strive to create reusable components and functions across multiple files. Avoid duplicating logic.
*   **Abstraction:**  Define abstract interfaces for components.  Components should have a clear, well-defined purpose.
*   **Standardized Components:** Create standard components with documented usage patterns.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimize Complexity:**  Keep functions and classes as small and focused as possible.
*   **Readability:** Prioritize clear, understandable code. Use meaningful variable and function names.
*   **Avoid Over-Engineering:**  Don't introduce unnecessary complexity for the sake of it.  Prioritize simplicity over optimization where possible.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one and only one reason to change.
*   **Open/Closed Principle:**  The system should be open for extension but closed for modification.  (New functionality should be added without altering existing code).
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Client code should not be required to know the result of operations on an object, which might result in over-specificity.
*   **Dependency Inversion Principle:** High-level modules should not depend on low-level modules.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Code:**  Don't add functionality or code just because it *might* be useful in the future.
*   **Focus on Current Requirements:**  Prioritize implementation based on the current task at hand.

## 5. Development Workflow

*   **Version Control (Git):** All code must be committed to a Git repository.  Use descriptive commit messages.
*   **Code Reviews:** Mandatory code reviews for all new code changes.
*   **Unit Testing:** All new code must have comprehensive unit tests.  Focus on testing individual functions and classes.
*   **Regression Testing:** After each code change, run regression tests to ensure no existing functionality is broken.
*   **Static Analysis:** Use a static analysis tool (e.g., linters) to identify potential issues and style violations.  Automated code analysis should be incorporated.
*   **Documentation:** All functions, classes, and components should have clear documentation explaining their purpose and usage.

## 6. Code Length Constraints

*   **Maximum Code Lines:**  Each file's maximum allowed code lines is 180 lines.
*   **Code Complexity Metrics:** Utilize a code complexity tool (e.g., pylint) to ensure complexity doesn’t exceed the limit.

## 7. Test Coverage Requirements

*   **Minimum Test Coverage:**  80% of the code must be covered by tests.  This is a baseline requirement.
*   **Test Suite Structure:** A well-defined test suite with modular and well-documented tests should be created.
*   **Test Case Design:**  Test cases must be designed to cover all relevant scenarios and edge cases.

## 8.  File Structure

*   **Modular Design:**  Organize code into logical modules/components.
*   **Clear Naming Conventions:** Use consistent and descriptive naming conventions for files and functions.
*   **Comments:**  Provide clear and concise comments explaining complex logic and design choices.


## 9.  Special Considerations

*   **Error Handling:** Implement robust error handling and logging.
*   **Data Validation:**  Include data validation to ensure data quality.
*   **Security:** Address potential security vulnerabilities, keeping in mind security best practices.



These guidelines are intended as a reference and may be updated as the project evolves.  Regular review and adaptation are encouraged.
```