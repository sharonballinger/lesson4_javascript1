## Project Name:  Expense Calculator Application

### Course Title:
LIS 2360:  Web Application Development

### Assignment Date:  
July 19, 2017

### Student Name:  
Sharon Ballinger

### Project Description:
An introduction in understanding and applying the characteristics of JavaScript language.

### View Project:
https://sharonballinger.github.io/lesson4_javascript1/

### Lessons Learned in the Assignment:

#### 1. How to include your JavaScript in your designs.

**Inputting straight into the HTML.**
The JavaScript code can either by placed in the head `<head></head>` section or the body `<body></body>` section, or in both together.

When placed in the head `<head></head>` section you force the browser to download the JavaScript code before it has time to load the page which might cause a slow loading time.

When placed at the bottom of your HTML before the close of the body `</body>` tag, your web page will load, then the JavaScript code will load after everything else.

**Using an external JavaScript file**

When you place a script element in the head `<head></head>` section of your website, it identifies the external file and loads the file as if it is coded in the script element.

When using this method you need to specify where the JavaScript file is located on the server:
`<script src="my_javascript.js"></script>`

If you have a large JavaScript file(s) it is beneficial to separate the file(s) from the HTML as it makes it easier to read. The only downside is that you will have to switch back and forth between the files.

**Top 5 things to remember with your JavaScript code**
- The JavaScript syntax is VERY case-sensitive. You might find that your code isn't working and it could be down to something very minor, `lessonInput` is not the same as `lessoninput`. 
- Ending a statement with a semicolon `;`.
- Always use comments. (See, *"How to write JavaScript statements."*)
- Never use one of the reserved JavaScript words.
- Keep you code to roughly 80 characters per line and only split lines after: `+, -, *, /, =, ==, >, <, {, }, [`. Never split a line after an identifier, a value, a return keyword, a closing bracket `]` or closing parenthesis `"`.


#### 2. There are three main primitive data types.
JavaScript is a computer programming language. There are instructions known as **statements**, the computer will carry out these statements. There are only three primitive data types within JavaScript:

**Number, string and boolean**.
- **Number** data type represents all types of numerical data.
- **String** data type represents character data, it also needs to be surrounded by double or single quotes `"text"` `'text'`. `""` isn't a mistake; there is no data inside the quotations also known as an *empty string*.
- **Boolean** data type has two possible outcomes either it is `true` or it is `false`.


#### 3. How to write JavaScript statements.
By using the three primitive data types, JavaScript statements are constructed using: variables, comments, operators, keywords and expressions.

**Variables** can either be a number or a string data type. A variable is a container with a given name. The container can be called upon in your code. Before using the variable (container) it has to be declared what it is. To declare the word you put `var` in front of the variable name: `var person;` `var object;` `var place;` etc. You can also declare more than one at a time: `var person, object, place;`. It only needs to be declared once in your code.

**Comments** are added to help understand your code similar as with HTML or CSS.
There is a difference in how you write your comments whether the comment is written on one line or two or more lines.
- One line: use `//`. 
  Example: `// One line comment.`

- Two lines or more: use `/* and */`. 
  Example: `/* this is a super complex statement so I am writing this comment out so you will understand what I am trying to do with my code. */`

**Operators** used in statements, make your code work. There are different operators for numeric, string or boolean data types. 
In numeric data types they consist of: ` +, -, *, /, %, ++, --, =, += etc.`
In string data types they consist of: `+, \n, \", \'`
In boolean data types they consist of: `=`
There are many more operators used in JavaScript.

**Keywords** are reserved words by JavaScript to perform an action. You cannot use a keyword as a variable name. If you do end up using a reserved word you will more than likely end up with an error message.

**Expressions** are a combination of variables, operators, and values that make another value.
`"Sharon" + " " + "Ballinger"` is `Sharon Ballinger`. This a very basic expression; a string data type with an operator. Expressions also have an order of precedence but these can be overwritten.





