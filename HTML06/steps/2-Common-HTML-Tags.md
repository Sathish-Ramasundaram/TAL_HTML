# Step 2 — Common HTML Tags
(Headings, Paragraphs, Images, Links)

What you’ll learn in this step
Headings (h1–h6)
Paragraphs (p)
Images (img)
Links (a)

1. Replace the code of body with this: 
```

<body>

  <h1>Student Registration Application</h1>

  <h2>Welcome</h2>
  <p>
    This application is used to register students and display basic information.
    It is built using only HTML.
  </p>

  <h3>About This App</h3>
  <p>
    This app demonstrates basic HTML components such as headings, paragraphs,
    images, links, lists, tables, and forms.
  </p>

  <h3>Sample Image</h3>
  <img 
    src="https://via.placeholder.com/150" 
    alt="Sample student image">

  <h3>Useful Link</h3>
  <p>
    Visit 
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank">
      HTML Documentation
    </a>
    to learn more about HTML.
  </p>

</body>

```

2. Test
Update the image tag if needed. Tree image should be put in the root folder
Update weight and height optional
<img src="Tree.png" alt="Sample Tree Image" width="50%" height="80%" />
<body style="height: 100vh;"> --> This is needed for height adjustment. 

Note: 
Absolute path tied to your PC only
Browser blocks local file access in many cases
If you are having index.html and tried this C:/Training/TAL_HTML/Tree.png
It won't work. See the console error for reference.

3. Explanation (core concepts)
🔹 Headings (h1 → h6)
<h1>Largest heading</h1>
<h6>Smallest heading</h6>

Rules:
h1 → main title (only one per page ideally)
Headings define document structure, not styling

🔹 Paragraph (p)
<p>This is a paragraph.</p>
Automatically adds spacing
Used for readable text blocks

🔹 Image (img)
<img src="URL" alt="description">

Important:
img has no closing tag
alt is mandatory (accessibility + SEO)

🔹 Link (a)
<a href="URL">Clickable text</a>
href → destination
target="_blank" → opens in new tab

