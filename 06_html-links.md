# 🔗 HTML Links (Anchor Tags)

## 📌 What Are Links?

Links (or **anchors**) are one of the **fundamental building blocks of the web**.  
They connect pages and allow users to navigate between documents, sites, or sections.

HTML uses the `<a>` element (short for **anchor**) to create links.

---

## 🧭 Types of Links

| Type             | Description                                    | Example                         |
| ---------------- | ---------------------------------------------- | ------------------------------- |
| External link    | Points to a page **outside** your website      | `https://developer.mozilla.org` |
| Internal link    | Points to another page **within** your website | `blog.html`, `about.html`       |
| Placeholder link | Link that doesn't go anywhere (`#`)            | Used as a placeholder in menus  |

---

## 🔍 Basic Syntax

```html
<a href="https://example.com">Visit Example</a>
```

🔗 External Link with New Tab Behavior
html
Copy code

<p>You can learn more at 
  <a href="https://developer.mozilla.org/en-US/" target="_blank">
    MDN Web Docs
  </a>
</p>
href = link target (URL)

target="\_blank" = opens the link in a new tab

title (optional) = shows a tooltip when hovered
🏠 Internal Link (Page in Same Folder)
html
Copy code
<a href="blog.html">Go to Blog</a>
This will navigate to blog.html in the same directory as your current HTML page.

To return back from blog page:

html
Copy code
<a href="index.html">Back to Home</a>

❓ Placeholder Link (for Menus or Future Links)
html
Copy code
<a href="#">Challenges</a>
<a href="#">Flexbox</a>
<a href="#">CSS Grid</a>
These appear as links but don’t go anywhere

Clicking them scrolls to the top of the page

📚 Reference for Future Use
🧠 You can learn more about anchor tags and other HTML features at:
👉 MDN Web Docs – HTML <a> element

Save this link — it’s the official and most trusted reference for web developers.

## ✅ Key Attributes for `<a>` Element

| Attribute  | Purpose                                  | Example                               |
| ---------- | ---------------------------------------- | ------------------------------------- |
| `href`     | Specifies the link destination           | `href="https://example.com"`          |
| `target`   | Opens link in a new tab or same tab      | `target="_blank"` or `target="_self"` |
| `title`    | Tooltip text shown on hover              | `title="Go to blog page"`             |
| `download` | Prompts file download instead of opening | `download="resume.pdf"`               |
