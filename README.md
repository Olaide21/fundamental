HTML Form Elements Documentation
This HTML code demonstrates various form elements, including input types, fieldsets, legends, and labels. Here's a breakdown of the code:

Document Structure
<!DOCTYPE html>: This is the document type declaration, which tells the browser that the document is written in HTML5.
<html>: This is the root element of the HTML document, which contains all the other elements.
<head>: This element contains metadata about the document, such as the title, charset, and links to external stylesheets or scripts.
<title>basic.html.com</title>: This sets the title of the page, which appears in the browser's title bar and in search engine results.
<body>: This element contains the content of the HTML document.
Form Elements
First Form
<form action="action.php" method="GET">: This is a form element, which sends data to the server when submitted. The action attribute specifies the URL to send the data to, and the method attribute specifies the HTTP method to use (in this case, GET).
<fieldset>: This element groups related form elements together, providing a visual border and a legend.
<legend>login Details</legend>: This is a legend element, which provides a caption for the fieldset.
<input type="text" name="matric number" placeholder="Matric Number">: This is a text input element, which allows the user to enter a single line of text. The name attribute specifies the name of the input field, and the placeholder attribute provides a hint to the user.
<input type="email" name="" placeholder="Email">: This is an email input element, which allows the user to enter an email address.
<input type="password" name="">: This is a password input element, which allows the user to enter a password.
<input type="radio" name="gender" value="male" checked> I am male: This is a radio input element, which allows the user to select one of several options. The checked attribute specifies that this option is selected by default.
<input type="submit" name="" value="submit">: This is a submit input element, which sends the form data to the server when clicked.
Second Form
<form action="">: This is an empty form element, which does not send data to the server when submitted.
<input type="password" name="">: This is a password input element, which allows the user to enter a password.
<input type="checkbox" name="color" value="red"><label for="">Red</label>: This is a checkbox input element, which allows the user to select multiple options. The label element provides a text description for the checkbox.
<input type="button" name="" value="My Button" onclick="alert('you press the button!');">: This is a button input element, which triggers a JavaScript event when clicked.
New to HTML5
<input type="number" name="" min="1" max="10">: This is a number input element, which allows the user to enter a numerical value within a specified range.
<input type="date" name="" min="2001-01-01">: This is a date input element, which allows the user to enter a date.
<input type="color" name="">: This is a color input element, which allows the user to select a color.
<input type="range" name="" min="1" max="100">: This is a range input element, which allows the user to select a value within a specified range.
<input type="month" name="">: This is a month input element, which allows the user to enter a month and year.
<input type="week" name="">: This is a week input element, which allows the user to enter a week and year.
<input type="time" name="">: This is a time input element, which allows the user to enter a time.
<input type="datetime" name="">: This is a datetime input element, which allows the user to enter a date and time.
<input type="datetime-local" name="">: This is a datetime-local input element, which allows the user to enter a date and time in the local timezone.
<input type="url" name="">: This is a URL input element, which allows the user to enter a URL.
<input type="search" name="">: This is a search input element, which allows the user to enter a search query.
<input type="tel" name="">: This is a telephone input element, which allows the user to enter a phone number.
