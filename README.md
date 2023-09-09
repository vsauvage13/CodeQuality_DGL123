# CodeQuality_DGL123
## Vienna May Sauvage

https://github.com/vsauvage13/CodeQuality_DGL123

## What Makes Quality Code

### Article 1: Clean Code in PHP: Best Practices and Principles
https://medium.com/@teal33t/clean-code-in-php-best-practices-and-principles-8ccf2f1673a7

1. Code is easy to read:
    a. Meaningful variable and function names are used.
    b. Code is properly indented and formatted.

2. Code is DRY (Don't Repeat Yourself):
    a. Redundant code is removed.
    b. Copied and pasted code is refactored into reusable functions or classes.

3. Code is modular:
    a. Code is broken into smaller, reusable pieces like modules and functions.
        i. Modules have single responsibilities and are independent.

4. Code is efficient:
    a. The cost of operations is understood.
        b. Unnecessary calculations are avoided.
    c. The correct data structures and algorithms are used.
    d. Optimization is not performed until a proven bottleneck exists.

5. Code is robust and handles errors gracefully:
    a. Inputs are validated.
    b. Exceptions are handled properly.
    c. Meaningful error messages are provided.

6. Code is testable:
    a. Code is designed for easy testing.
        i. Functions and classes have clear inputs and outputs.
        ii. There are no hidden dependencies.
        iii. Each piece of code does one thing well.

7. Code follows a coding standard:
    a. For PHP, follow PSR-2

8. Code is well-documented:
    a. Comments explain why something is done in an easy-to-understand way. 
    b. PHPDoc blocks are used for classes, methods, and variables when needed.


### Article 2: Clean Code: Why HTML/CSS Essentials Still Matter
https://www.toptal.com/front-end/frontend-clean-code-guide

1. Validate your HTML and CSS
2. Make your code accessible:
    a. Use alt tags for images
    b. Think of contrast when designing colours and layout
    c. Use descriptive URL's
3. Use kebab-case for names
4. Make names meaningful, short, and easy to understand
5. When using HTML5, dont write type attributes for both:
    a. stylesheets
    b. script
6. Make CSS selectors as specific as possible, only selecting the elements you need.
7. Keep units off of zero values
8. Use the hr tag in your HTML instead of adding border styles in CSS
9. Use A>B Selectors
10. Code should be markup-based
11. Avoid unnecessary wrappers in HTML
12. Use atomic classes for styling
13. Make use of semantic elements
14. Use HTML5 tags if needed
15. Use Frameworks for HTML and preprocessors for CSS
    a. For HTML Frameworks like Bootstrap:
        i. Use classes as much as possible
        ii. Customize your framework. 
    b. For CSS Preprocessors like SASS: 
        i. Group your selectors
        ii. Use the parent item just once
16. Use rem units instead of pixels in CSS
    a. Make sure em's are used for line-height
17. Avoid fixed height and width in CSS - try adding padding on top and bottom instead
18. Be mindful of which elements will be affected when writing CSS rules and use preexisting ones before creating new ones
19. Make rules specific
20. Use shorthand properties and values

### Article 3: 10 Tips for writing clean and efficient PHP code
https://skytechbot.com/10-tips-for-writing-clean-and-efficient-php-code/

1. Use descriptive and consistent naming conventions:
   a. Use descriptive names
   b. Follow the same case
   c. Use meaningful prefixes
   d. Avoid abbreviations
   e. Follow PHP naming convensions
2. Write modular and reusable code:
    a. Use functions and classes
    b. Follow the single responsibility principle
    c. Use dependency injections
    d. Use namespaces
    e. Write unit tests if needed
    f. Prioritize design patterns
    g. Document your code by leaving comments
3. Keep your Code DRY (Don't Repeat Yourself):
   a. Use functions, classes and other constructs for repeating logic
   b. Use constants, loops, and configuration files
   c. Use inheritance if applicable
   d. Use templates if applicable
4. Use proper indentation and formatting in PHP:
   a. Use consistent indentation style, brace placement, and capitalization
   b. Avoid long lines
   c. Use whitespace to separate blocks
   d. Comment
   e. Use formatting tools
5. Optimize your PHP code for performance
   a. Use caching, efficient algorithms, and data structures
   b. Optimize your code for the specific environment
   c. Minimize database queries
   d. Use a profiler
   e. Minimize memory usage
   f. Avoid unnecessary function calls
6. Write Comments!
   a. Use clear, concise, and descriptive language
   b. Comment whats necessary
   c. Keep them up to date
   d. Use a consistent style
   e. Use commenting tools like PHPDoc or Doxygen
7. Test your Code
   a. Run them frequently
   b. Use a testing framework
   c. Document your tests
8. Use PHP frameworks and libraries
9. Continuously improve your code


### Article 4: Top 10 Tips To Write Clean Code
https://www.nilebits.com/blog/2023/01/top-10-tips-to-write-clean-code/

1. Follow a consistent coding style.
2. Use descriptive and meaningful names for variables, functions, and other identifiers.
3. Keep your code simple and avoid using complex solutions unless they are absolutely necessary.
4. Use comments to explain the purpose and function of your code
5. Avoid using global variables where possible.
6. Avoid writing code that is prone to errors.
7. Keep your code up-to-date and refactor it as needed.
8. Keep your Code DRY (Don't Repeat Yourself)
9. Avoid using magic numbers and strings and use constants or enums instead.
10. Use design patterns and best practices


Overall List: 

Coding Best Practices: 
1. Code Quality
    a. Maintain readability with meaningful names and proper formatting
    b. Apply DRY principle (Don't Repeat Yourself) to remove redundancy
    c. Promote modularity by breaking code into smaller, independent pieces
    d. Optimize for efficiency with the right data structures and algorithms
    e. Using SASS Parent selectors to nest styles where applicable - make sure to never nest more than three layers deep for readability.
    f. Concise Comments

3. Error Handling & Design
    a. Ensure robust error handling by validating inputs, handling exceptions, and providing meaningful error messages
    b. Design code for testability, keeping clear inputs and outputs, and avoiding hidden dependencies
    c. Follow coding standards and document code with comments
   
HTML and CSS Best Practices:
1. Code Quality:
    a. Validate HTML and CSS
    b. Enhance accessibility and design with alt tags, contrast, and descriptive URLs
    c. Use kebab-case
    d. Keep names meaningful, short, and easy to understand.
3. CSS Styling:
    a. Write specific CSS selectors
    b. Utilize rem units, avoid fixed dimensions, and use padding for height
    c. Follow best practices for CSS frameworks and preprocessors
    d. Avoid unnecessary wrappers and divs in HTML when possible
    e. Try to look for existing rules and variables before writing new ones
    f. Think about which elements will be affected before writing a CSS rule - can I use Bootstrap or SASS?
    g. Use A > B selectors

PHP Coding Best Practices:
1. Code Quality:
    a. Adopt consistent naming conventions and create modular, reusable code
    b. Keep code DRY, use constants, and optimize formatting
    c. Document code and apply testing practices
    d. Optimize for performance and continuously improve
