# 🧱 HTML Document Structure (Core Foundation)

## 📌 Key Concepts Introduced

- Project setup using folders and files (`index.html`)
- Base HTML document structure
- Purpose of `<!DOCTYPE html>`
- Root and nested tags: `<html>`, `<head>`, `<title>`, `<body>`
- Importance of indentation for readability
- How to preview your HTML in a browser

---

## 🗂 Project Setup

- Create a folder like `code-magazine`
- Inside it, create a file named `index.html`
- This becomes your homepage

---

## 💡 Why `index.html`?

Browsers auto-load this file first in any folder — it's the homepage.

---

## 🧾 HTML Boilerplate (Manual Version)

```html
<!DOCTYPE html>
<!-- Declare this is an HTML5 document -->
<html>
  <head>
    <title>The Basic Language of the Web: HTML</title>
  </head>
  <body>
    <h1>The Basic Language of the Web: HTML</h1>
  </body>
</html>
```

🧠 Explanation of Each Part
🧾 <!DOCTYPE html>
Declares the document type

Tells the browser to use HTML5

Not a tag, just an instruction

Must be at the top of every HTML file

🌐 <html>
The root element of your webpage

Everything goes inside it: <head> and <body>

🧠 <head>
Holds invisible content (not rendered in browser window):

Page title

Metadata

Links to stylesheets or scripts

🏷️ <title>
Sets the text in the browser tab

Helps with SEO and bookmarking

📄 <body>
All visible content lives here

Paragraphs, headings, images, buttons — all go inside the body

✨ Why Indentation Matters (Even if Browser Ignores It)
Helps you (the developer) read and manage code better

Shows which elements are nested inside others

Good for teams and debugging

Example:

<html>
  <head>
    <title>My Website</title>
  </head>
  <body>
    <h1>Hello World!</h1>
  </body>
</html>
✅ Use tab or 2 spaces for indentation consistently

✅ Structure Summary Table
Tag Purpose

<!DOCTYPE>	Declares HTML5 usage
<html>	Root of all HTML content
<head>	Contains meta info, title, links
<title>	Sets browser tab name
<body>	Holds everything visible on the page

🔜 Coming Next:
You'll learn how to add:

Paragraphs (<p>)

Links (<a>)

Lists (<ul>, <ol>, <li>)

Emphasis (<strong>, <em>)

Images (<img>)

All placed inside the <body> tag.

---

Let me know if you want this version saved as a **PDF**, or want help creating a folder structure like `01_HTML/`, `02_CSS/` for your repo!
