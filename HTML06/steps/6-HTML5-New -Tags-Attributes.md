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

Replace your name input with this:
<input type="text" id="name" name="name" required minlength="3" placeholder="Enter full name">

<input type="email" id="email" name="email" placeholder="Enter email address" required>

What changed?
required
Browser blocks submission if empty
No JS needed

minlength
Forces minimum characters
Built-in validation
Try submitting empty → browser stops you

HTML5 Placeholder Attribute

Why?
Shows hint text
Improves UX
Disappears when typing

4️⃣ HTML5 Browser Validation (magic ✨)
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

HTML is case-insensitive for attribute values like utf-8, so UTF-8 and utf-8 are treated the same.
Best Practice
Use <meta charset="UTF-8"> (uppercase) because it’s the most common convention and clearer to read.
Place it as the first line inside <head> so the browser knows how to interpret characters right away.

🔹 Viewport = the visible area of the webpage on the user’s device
🔹 width=device-width
Set the page width equal to the device screen width
Without this → mobile browsers pretend the page is ~980px wide and shrink it → layout breaks.
🔹 initial-scale=1.0
Page zoom level when first loaded = 100%

Test (optional)
Right Click → Inspect
Click this icon in DevTools:
📱🖥 Toggle Device Toolbar

Ctrl + Shift + M (Windows)
Cmd + Shift + M (Mac)

Choose Device
At the top, select:

iPhone SE
iPhone 14
Pixel
Galaxy
Responsive

Try, with and without that line.
