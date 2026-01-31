# Step 3 — Creating Lists and Tables

We’ll add:
A list of courses
A table of registered students

1. What we will learn

Ordered lists (ol)
Unordered lists (ul)
List items (li)
Tables (table, tr, th, td)
How data is structured in HTML

2. Add the following code below your existing content inside <body>:

  <h2>Available Courses</h2>

  <p>Below is the list of courses offered:</p>

  <ul>
    <li>HTML Basics</li>
    <li>CSS Fundamentals</li>
    <li>JavaScript Introduction</li>
    <li>React Basics</li>
  </ul>

  <h2>Student List</h2>

  <p>Registered students information:</p>

  <table border="1">
    <tr>
      <th>Student ID</th>
      <th>Name</th>
      <th>Course</th>
      <th>Email</th>
    </tr>

    <tr>
      <td>1</td>
      <td>Arun</td>
      <td>HTML Basics</td>
      <td>arun@example.com</td>
    </tr>

    <tr>
      <td>2</td>
      <td>Sneha</td>
      <td>CSS Fundamentals</td>
      <td>sneha@example.com</td>
    </tr>

    <tr>
      <td>3</td>
      <td>Rahul</td>
      <td>JavaScript Introduction</td>
      <td>rahul@example.com</td>
    </tr>
  </table>

3. 

4. 
Update list to visually see the difference from unordered to ordered. 
From: 
  <ul>
    <li>HTML Basics</li>
    <li>CSS Fundamentals</li>
    <li>JavaScript Introduction</li>
    <li>React Basics</li>
  </ul>

To: 

  <ol>
    <li>HTML Basics</li>
    <li>CSS Fundamentals</li>
    <li>JavaScript Introduction</li>
    <li>React Basics</li>
  </ol>

5. Explanation: 
tr → row
th → heading cell
td → normal cell

🔹 border="1"
Old-school HTML attribute
Used here only because CSS is not allowed
Makes table visible
