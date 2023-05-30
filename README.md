# Codingg-Standards-Backend-Php
Every company follows a different coding standard based on their best practices. Coding standards are required because there may be many developers working on different modules so if they will start inventing their own standards then source will become very un-manageable and it will become difficult to maintain that source code in future.

# There are multiple reasons to use coding standards:

## 1. Enhanced Code Readability: 
Coding standards serve as a blueprint for all team members, ensuring that your code is easily understood by your peers. Consistency in coding style and formatting promotes clarity and simplifies comprehension.

## 2. Prevention of Common Mistakes: 
Following a coding standard helps you avoid common errors. By adhering to consistent coding practices, you reduce the likelihood of introducing bugs or making mistakes due to inconsistent or ambiguous code.

## 3. Improved Maintainability: 
When you revisit and revise your code after some time, a well-defined coding standard makes it easier to understand and modify the code. Clear and consistent code structure and naming conventions aid in maintaining and updating the software.

## 4. Industry Best Practices: 
Following a coding standard aligns with industry best practices. Adhering to recognized standards and guidelines promotes quality in software development and ensures compatibility and interoperability with other systems and libraries.

# Coding standards at Namibra
## File Convention
  + All files should have their appropriate extensions.
  + Single  ***`line comments`*** for a block code should be aligned with the code they are meant for. 
  + There should be comments for all major variables explaining what they represent.
  + Use CAPITAL letters for comments ``(e.g //CHECK IF ALL USER INPUTS ARE SELECTED)``
  + Our Project Must contain this file called [auxiliaries.php,](https://github.com/Namibra-Devs/AuxilliariesPHP.git) :+1: which contains all the custom functions/methods and should be required_once in the necessary files.
  + In a case of code reusabilty, use `required_once` over the others.

# Naming Convention
  + Package names should be ***lowercase***
  + Variable names should be noun and should start with ***Lowercase*** (`e,g userpassword, useremail, etc`)
  + All SQL Statements should be a verb and in CAPS and variable should be in Camel Casing
    `Example: $createUser = “INSERT INTO tablename(col1,col2) VALUES(:col1, :col2);
    $getAllUsers = “SELECT * FROM users WHERE id = 1”`
  + Constant names should all be ***uppercase***
  + Method/Function names should be a verb following ***Camel Casing*** 
   ` Example:  createUers(arg1, arg2), checkUserLoggedIn(userID);`
