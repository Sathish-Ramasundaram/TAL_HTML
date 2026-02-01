1. Using HTML Forms for User Input
you’ll learn
What a form is
form, input, label, select, option, textarea, button
How browsers collect user data
How HTML alone handles input

2. 
What is a Form?
A form is how a user sends data from the UI to somewhere else
(server, backend, or just a URL)
Even without JS, forms still work.

3. Add this BELOW your table (inside <body>)

  <h2>Student Registration Form</h2>

  <form>

    <p>
      <label for="name">Full Name:</label><br>
      <input type="text" id="name" name="name">
    </p>

    <p>
      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email">
    </p>

    <p>
      <label for="course">Select Course:</label><br>
      <select id="course" name="course">
        <option value="html">HTML Basics</option>
        <option value="css">CSS Fundamentals</option>
        <option value="js">JavaScript Introduction</option>
        <option value="react">React Basics</option>
      </select>
    </p>

    <p>
      <label for="message">Additional Notes:</label><br>
      <textarea id="message" name="message" rows="4" cols="30"></textarea>
    </p>

    <p>
      <button type="submit">Register</button>
    </p>

  </form>

  ```

4. Explanation

<form>
Groups input fields
Browser knows: this data belongs together

<label for="name">Full Name:</label>
Improves accessibility
Clicking label focuses input

for must match input id

input name → used when form data is submitted
When the form is submitted, the browser sends data like this:
name=abc
email=abc@gmail.com


<input type="text">
Common types
text → normal input
email → browser validates email format

<select>
  <option>HTML</option>
</select>
Dropdown selection
Only one option selected at a time

<textarea></textarea>
Multi-line text input
Used for comments, messages

rows="4"
Shows space for 4 lines of text
Controls the vertical height
User can still type more — scrollbar will appear

cols="30"
Shows space for about 30 characters in one line
Controls the horizontal width
Based on average character width (not pixel-perfect)

<button type="submit">
Submits the form
Browser sends data automatically

Note: 
submit button sends the form data; button type only triggers JavaScript logic.

Use submit
Form submission
Login / Register / Save buttons
When sending data

Use button
Open popup
Validate fields manually
Increment counter
Show/hide content
React / JS handlers

Example: 

<form action="/save">
  <input name="email">
  <button type="submit">Submit</button>
</form>


<button type="button" onclick="alert('Hello')">
  Click Me
</button>


5. What happens when you click “Register”?

Page reloads
Form data is prepared for sending
Since no action is given → reloads same page
✔️ This is correct behavior

6. Note: 
HTML collects data
JavaScript processes data
Backend stores data

Right now, HTML is doing its job perfectly.


