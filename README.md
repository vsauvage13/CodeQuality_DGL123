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
