# JS Debugging
![fjs](https://developers.google.com/web/tools/chrome-devtools/javascript/imgs/scope-pane.png)

> #### Definition and Usage
*The debugger statement stops the execution of JavaScript, and calls (if available) the debugging function.
Using the debugger statement has the same function as setting a breakpoint in the code.
Normally, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.
Note: If no debugging is available, the debugger statement has no effect.*

> #### Syntax
`debugger;`

>Example
*With the debugger turned on, this code should stop executing before it executes the third line:*

`var x = 15 * 5;`

`debugger;`

`document.getElementbyId("demo").innerHTML = x;`

