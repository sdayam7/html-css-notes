# 🖼️ HTML Attributes & Images

## 📌 What are Attributes?

- Attributes are **extra information** added to HTML elements
- They are written **inside the opening tag**
- Usually appear in the form: `name="value"`

Example:

```html
<img src="image.jpg" alt="Descriptive text" />
```

## 🧠 Commonly Used HTML Attributes

| Attribute | Description                                                  |
| --------- | ------------------------------------------------------------ |
| `src`     | Path to the image or media file (used in `<img>`, `<video>`) |
| `alt`     | Alternate text for image if it cannot be displayed           |
| `href`    | URL used in hyperlinks `<a>`                                 |
| `width`   | Width of element (in pixels by default)                      |
| `height`  | Height of element                                            |
| `lang`    | Declares language of the page                                |
| `charset` | Specifies character encoding (commonly UTF-8)                |
| `id`      | Unique identifier for styling or JavaScript                  |
| `class`   | Groups elements for CSS styling                              |
| `title`   | Tooltip text shown on hover                                  |
| `type`    | Input type (`text`, `submit`, etc.)                          |
| `name`    | Form input or metadata name identifier                       |
| `value`   | Predefined value for form inputs or buttons                  |
| `target`  | How to open linked documents (`_blank`, `_self`, etc.)       |

🧾 Syntax Example: Image Tag with Multiple Attributes
<img 
  src="post-img.jpg" 
  alt="HTML code on a screen" 
  width="500" 
  height="200">

✅ No closing tag for <img> — it's self-closing

❓ What Happens If You Don’t Specify px?
You asked: "If I write width="50" without px, does it still mean 50 pixels?"

✅ Yes, it defaults to pixels in HTML!
For width and height in <img>, the default unit is always pixels (px) unless styled differently in CSS.

Example:
<img src="pic.jpg" width="100"> <!-- Interpreted as 100px -->

🌐 Language Codes for lang Attribute
Used in:

<html lang="en">
## 🌐 Language Codes for `lang` Attribute

| Language | Code |
| -------- | ---- |
| English  | en   |
| German   | de   |
| French   | fr   |
| Korean   | ko   |
| Japanese | ja   |
| Hindi    | hi   |
| Telugu   | te   |
| Chinese  | zh   |
| Spanish  | es   |

🧬 What is <meta charset="UTF-8">?
meta = metadata (information about your document)

charset="UTF-8" tells the browser how to read characters

✅ UTF-8:
Most widely used encoding

Supports English + other international characters

Prevents weird character display (like � or Ã©)

<head>
  <meta charset="UTF-8">
</head>

✨ Real-World Examples of 14 Key Attributes
html
Copy code

<!-- Image with attributes -->
<img src="author.jpg" alt="Headshot of Laura Jones" width="50" height="50">

<!-- Anchor link with attributes -->

<a href="https://example.com" target="_blank" title="Visit Example">Click here</a>

<!-- Input form -->
<input type="text" name="username" value="shruti123">

<!-- Meta data in head -->
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- Button -->

<button class="btn" id="submitBtn">Submit</button>

<!-- Paragraph with title -->
<p title="This is tooltip text">Hover over me</p>
