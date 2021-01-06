# Forms and JS Events
![fjs](https://cdn.educba.com/academy/wp-content/uploads/2020/04/JavaScript-Form-Events.jpg)

> #### JavaScript Form Event
*A form event is fired when a form control receive or loses focus or when the user modify a form control value such as by typing text in a text input, select any option in a select box etc. Here're some most important form events and their event handler.*

> #### The Focus Event (onfocus)
*This event occurs when an element gets focused on a web page. The `onfocus` event handler is used to handle this event. The following example will highlight the background of text input in green color when it receives the focus.*

>Example

`<script>
function highlightInput(elm){`
`elm.style.background = "lightgreen";`
` }`    
`</script>`
`<input type="text" onfocus="highlightInput(this)">`
`<button type="button">Button</button>`

        