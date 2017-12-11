# JavaScript brackets validator

You're new to JavaScript and you're always massing up your code because of the braces, brackets and parentheses. To save your time, you decided to write a braces/brackets/parentheses validator.

Let's say:
* '(', '{', '[' are called **openers**.
* ')', '}', ']' are called **closers**.

Examples:
* "{ [ ] ( ) }" should return `true`
* "{ [ ( ] ) }" should return `false`
* "{ [ }" should return `false`