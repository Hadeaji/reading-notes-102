# Dynamic web pages with JavaScript
In Order to add Dynamic components to yout page you have to start sing and learnning the **Java Script**

## Java Script:
It is a coding language that can be used for front and back ends
Jaca Scripts can be writtren on the same page of the HTML but it is more recommanded to 
keep it in a differant file then link the HTML page to it, you can do it by typing:

`<script src="nameofthefile.js"></script>`

and the rusalt of the Java Script will appeare wherever the command is

the Java Script conssit of:

- VARIABLE: which can be any kind of information or Dara suchs as numeric or string or boolen "true or false"
- STATEMENTS: which are the rules or the instructions
- it may consist of comments or quotes

 You give value to Variables and add rules.
 The Variables goes thought the rules you assingned and the output depends on it

 *exapmle:*
`var today= new Date();`
 `var hourNow = today.getHours();`
 `var greeting;` 
`if (hourNow > 18) {`
        `greeting= 'Good evening!';}`
          ` else if (hourNow > 12) `
        `{ greeting = ' Good afternoon!';}`
         `else if (hourNow > 0)` 
        `{ greeting = 'Good morni ng!';}`   
        `else { greeting = 'Welcome!' ; }`
`document .write( ``<h3>${greeting} </h3>``);`
***this example from the website that accompanies the book: www.javascriptbook.com***

