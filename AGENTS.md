This project adheres to the following development rules and principles to maintain code consistency and quality. Please keep them in mind when suggesting or generating code.

1. Technology Stack
Avoid external libraries and frameworks: The code must be 100% native. Third-party libraries such as jQuery, Bootstrap, or React should not be used.

Allowed technologies: Use only HTML5, CSS3, and JavaScript (ES6+) for the application logic.

2. Project Organization
The code should be well-structured in the following folders to facilitate navigation and maintenance:

src/: Contains the main source code.

js/: For all JavaScript files.

css/: For all stylesheets.

assets/: For resources such as images, fonts, and videos.

index.html: Main file at the project root.

3. Code Principles
SOLID: As much as possible, JavaScript code should follow SOLID principles for modular and maintainable design.

S (Single Responsibility Principle): Each module or function should have a single responsibility.

O (Open/Closed Principle): Entities should be open for extension, but closed for modification.

L (Liskov Substitution Principle): Objects of a subtype should be able to be substituted for objects of their supertype without altering the program's correctness.

I (Interface Segregation Principle): Clients should not be forced to depend on interfaces they do not use.

D (Dependency Inversion Principle): High-level modules should not depend on low-level modules. Both should depend on abstractions.

Comments and Documentation: Add clear and concise comments in the most complex parts of the code to explain the logic.

Naming Conventions: Use descriptive and consistent names for variables and functions. Prefer camelCase for JavaScript and kebab-case for CSS classes.

