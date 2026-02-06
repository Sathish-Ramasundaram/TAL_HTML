# Step 5 — Semantic HTML (Meaningful Structure)

You will learn: 
What semantic means in HTML
Why semantic tags exist
How screen readers, SEO, and browsers benefit
Real HTML5 semantic tags

1. Semantic HTML = using tags that clearly describe the role and meaning of content.
❌ Non-semantic:
<div>Header</div>

✅ Semantic:
<header>Header</header>

Same display.
Very different meaning.

2. 🧩 Common Semantic Tags:
Tag	        Meaning
<header>	Top section / intro
<nav>	Navigation links
<main>	Main content

<section>	Grouped content - is a semantic container element used to group related content into a logical block.
Example: 
Section 1 — About App
Section 2 — Courses
Section 3 — Students Table
Section 4 — Registration Form

<article>	Independent content
<footer>	Bottom info

3. 
Replace EVERYTHING inside <body> with this:

```

<body>

  <header>
    <h1>Student Registration Application</h1>
    <p>This application is built using only HTML.</p>
  </header>

  <main>

    <section>
      <h2>About This App</h2>
      <p>
        This app demonstrates basic HTML components such as headings, paragraphs,
        images, links, lists, tables, forms, and semantic elements.
      </p>
    </section>

    <section>
      <h2>Available Courses</h2>
      <ul>
        <li>HTML Basics</li>
        <li>CSS Fundamentals</li>
        <li>JavaScript Introduction</li>
        <li>React Basics</li>
      </ul>
    </section>

    <section>
      <h2>Student List</h2>

      <table border="1">
        <tr>
          <th>ID</th>
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
      </table>
    </section>

    <section>
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

        <p>Gender:<br />
          <input type="radio" id="male" name="gender" value="male" />
          <label for="male">Male</label>
          <input type="radio" id="female" name="gender" value="female" />
          <label for="female">Female</label>
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
          <button type="submit">Register</button>
        </p>
      </form>
    </section>

  </main>

  <footer>
    <p>© 2026 Student Registration App</p>
  </footer>

</body>

```

4. Why this matters (very important)
✅ Accessibility
Screen readers understand page structure
Users with disabilities navigate easily

✅ SEO
Search engines understand what’s important

✅ Maintainability
Other devs understand the page instantly




