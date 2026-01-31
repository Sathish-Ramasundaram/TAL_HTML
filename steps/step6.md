# Step 6 — HTML5 New Tags & Attributes

HTML5 didn’t change what HTML is — it improved how clearly we describe content and how browsers help users.

1. you’ll learn
New HTML5 structural tags
New input types
Built-in validation
Helpful HTML5 attributes

1️⃣ HTML5 Structural Tags (you already used them)

You’re already using:
<header>
<main>
<section>
<footer>
These did not exist in old HTML.
This alone means your app is HTML5-compliant ✔️

2️⃣ New HTML5 Input Types

Replace your email input with this:
<input type="email" id="email" name="email" required>

Replace your name input with this:
<input type="text" id="name" name="name" required minlength="3" placeholder="Enter full name">

What changed?
require
Browser blocks submission if empty
No JS needed

minlength
Forces minimum characters
Built-in validation
Try submitting empty → browser stops you

3️⃣ HTML5 Placeholder Attribute

Update inputs like this:
<input type="text" id="name" name="name" required minlength="3" placeholder="Enter full name">

<input type="email" id="email" name="email" placeholder="Enter email address" required>

Why?
Shows hint text
Improves UX
Disappears when typing

4️⃣ HTML5 required + Browser Validation (magic ✨)
Try this:
Enter invalid email → browser warns you
Leave field empty → browser blocks submit
💡 HTML5 gives you free validation

5️⃣ HTML5 meta tags (head section)

Update your <head> like this:

<head>
  <title>Student Registration App</title>
  <meta charset="UTF-8">
  <meta name="description" content="A simple student registration app built using HTML only">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

Why this matters:
charset → supports all languages
description → SEO
viewport → mobile-friendly

2. 
3. 
4. 
5. 
6. 
7. 
8. 
9. 
10. 



