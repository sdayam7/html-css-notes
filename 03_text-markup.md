# ✍️ HTML Text Markup: Headings, Paragraphs, Bold, Italics & Comments

## 🧠 Key Concepts Covered

- Headings: `<h1>` to `<h6>`
- Paragraphs: `<p>`
- Bold text: `<strong>` (not `<b>`)
- Italic text: `<em>` (not `<i>`)
- HTML Comments
- Semantic meaning in HTML

---

## 🧱 Headings in HTML

### ✅ Purpose:

- Structure the page content into **sections**
- Give **titles** to different parts of a document
- Create a **visual hierarchy**

### 🔢 Available Tags:

- `<h1>` → Primary heading (only **one** per page)
- `<h2>` → Subsection of `<h1>`
- ...
- `<h6>` → Least important, smallest size

### 🔍 Example:

```html
<h1>Main Title of the Page</h1>
<h2>Subheading</h2>
<h3>Section Title</h3>
<h4>Minor Subsection</h4>
<h5>Smaller Header</h5>
<h6>Tiny Text Heading</h6>
```

📝 Paragraphs in HTML
✅ Purpose:
Used to wrap larger blocks of text

Automatically adds spacing before/after

🔍 Syntax:

<p>This is a single paragraph of text in HTML.</p>
🔠 Bold Text: <strong>
✅ Use <strong> instead of <b>
<strong> has semantic meaning: “this is important”

<b> only styles it bold, without meaning (deprecated in modern HTML)

🔍 Example:

<p>Written by <strong>Laura Jones</strong></p>
🔤 Italic Text: <em>
✅ Use <em> instead of <i>
<em> means “emphasis” — semantic

<i> only styles it italic, no meaning

🔍 Example:

<p>HTML is a <em>fundamental</em> language of the web.</p>
💬 HTML Comments
✅ Purpose:
Add developer notes

Temporarily hide parts of code from the browser

🔍 Syntax:

<!-- This is a comment and will not appear in the browser -->

⚠️ Best Practices to Remember
Concept Do Don't
Headings Only 1 <h1> per page Don’t skip heading levels
Paragraphs Use <p> for readable text Don’t stack raw text without tags
Bold text Use <strong> Avoid <b>
Italic text Use <em> Avoid <i>
Commenting Use <!-- comment --> Don’t leave unused code active
