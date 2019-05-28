# READ RAW--NOT THIS

# HTML
HTML FILE 1-->
Let’s review what you’ve learned so far:

HTML stands for HyperText Markup Language and is used to create the structure and content of a webpage.

Most HTML elements contain opening and closing tags with raw text or other HTML tags between them.

HTML elements can be nested inside other elements. The enclosed element is the child of the enclosing parent element.

Any visible content should be placed within the opening and closing <body> tags .
  
Headings and sub-headings,<h1> to <h6> tags, are used to enlarge text.
  
<p>, <span> and <div> tags specify text or blocks.
  
The <em> and <strong> tags are used to emphasize text.
  
Line breaks are created with the <br> tag.

Ordered lists (<ol>) are numbered and unordered lists (<ul>) are bulleted.

Images (<img>) and videos (<video>) can be added by linking to an existing source.



# Table-
he <table> element creates a table.
The <tr> element adds rows to a table.
To add data to a row, you can use the <td> element.
Table headings clarify the meaning of data. Headings are added with the <th> element.
Table data can span columns using the colspan attribute.
Table data can span rows using the rowspan attribute.
Tables can be split into three main sections: a head, a body, and a footer.
A table’s head is created with the <thead> element.
A table’s body is created with the <tbody> element.
A table’s footer is created with the <tfoot> element.
All the CSS properties you learned about in this course can be applied to tables and their data.


# FORM-
The purpose of a <form> is to allow users to input information and send it.
The <form>‘s action attribute determines where the form’s information goes.
The <form>‘s method attribute determines how the information is sent and processed.
To add fields for users to input information we use the <input> element and set the type attribute to a field of our choosing:
Setting type to "text" creates a single row field for text input.
Setting type to "password" creates a single row field that censors text input.
Setting type to "number" creates a single row field for number input.
Setting type to "range" creates a slider to select from a range of numbers.
Setting type to "checkbox" creates a single checkbox which can be paired with other checkboxes.
Setting type to "radio" creates a radio button that can be paired with other radio buttons.
Setting type to "list" will pair the <input> with a <datalist> element.
Setting type to "submit" creates a submit button.
A <select> element is populated with <option> elements and renders a dropdown list selection.
A <datalist> element is populated with <option> elements and works with an <input> to search through choices.
A <textarea> element is a text input field that has a customizable area.
When a <form> is submitted, the name of the fields that accept input and the value of those fields are sent as name=value pairs.


# FORM Validaiton-
Client-side validations happen in the browser before information is sent to a server.
Adding the required attribute to an input related element will validate that the input field has information in it.
Assigning a value to the min attribute of a number input element will validate an acceptable minimum value.
Assigning a value to the max attribute of a number input element will validate an acceptable maximum value.
Assigning a value to the minlength attribute of a text input element will validate an acceptable minimum number of characters.
Assigning a value to the maxlength attribute of a text input element will validate an acceptable maximum number of characters.
Assigning a regex to pattern matches the input to the provided regex.
If validations on a <form> do not pass, the user gets a message explaining why and the <form> cannot be submitted.
These quick checks help ensure that input data is correct and safe for our servers. It also helps give users immediate feedback on what they need to fix instead of having to wait for a server to send back that information.
