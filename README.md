# An Introduction to Computer Software Development (Level 2 to Level 3 Bridging Course)

## Exercise: The Digital CV (HTML Structure)

In this exercise, you will build the foundation of your professional  
Digital CV using HTML (Hypertext Mark-up Language).

**Remember:** HTML provides the **STRUCTURE**. We aren't worried about  
colours or fonts yet—focus on the *blueprint* of your content.

### Key Tags to Remember
- `<h1>` to `<h6>` – Headings (Hierarchy)
- `<p>` – Paragraphs
- `<ul>` and `<li>` – Unordered (Bulleted) Lists
- `<ol>` and `<li>` – Ordered (Numbered) Lists

---

## Task 1: Document Skeleton

Every HTML document needs a standard *boilerplate* to work correctly.

### TODO
1. Create a new file in your workspace named `index.html`.
2. Add the basic HTML5 structure:
   - `<!DOCTYPE html>`
   - `<html>` tags (with the `lang="en-GB"` attribute)
   - `<head>` section (containing a `<title>` with your name)
   - `<body>` section (where all your content will live)

---

## Task 2: The Professional Header

Use headings to make your name stand out and paragraphs to introduce yourself.

### TODO
1. Inside the `<body>`, add an `<h1>` tag with your full name.
2. Below your name, add a `<p>` tag that contains a short  
   professional **Personal Statement** (2–3 sentences about your goals).

---

## Task 3: Experience & Education

Use sub-headings and lists to organise your history.

### TODO
1. Add an `<h2>` heading for **Work Experience**.
2. Use a `<ul>` (unordered list) to list at least two previous  
   job titles or roles.
3. Add another `<h2>` heading for **Education**.
4. Use an `<ol>` (ordered list) to list your qualifications  
   in order of importance or date.

---

## Task 4: Technical Skills

Nesting is a key concept in programming. Let's group your skills.

### TODO
1. Add an `<h2>` heading for **Technical Skills**.
2. Create a `<ul>`. Inside the list items (`<li>`), try to  
   mention the languages you are learning (e.g. Python, HTML).

---

## Saving Your Work

Now that the basic structure is complete, save your work to GitHub.

Run the following commands in the terminal:

1. `git add index.html`
2. `git commit -m "Completed core CV structure"`
3. `git push origin main`

---

## Extension Activities

### Extension 1: Hyperlinks (Contact Me)

Use the anchor tag `<a>` to make your CV interactive.

#### TODO
1. Add an `<h2>` for **Contact Information**.
2. Create a link that points to a website (like LinkedIn or GitHub).  
   **Syntax:** `<a href="URL_HERE">Link Text</a>`
3. *(Challenge)* Create a link that opens an email:  
   `<a href="mailto:email@example.com">`

---

### Extension 2: Adding Visuals

Websites are rarely just text. Add an image to your CV.

#### TODO
1. Find a professional placeholder image or use a profile photo.
2. Use the `<img>` tag to display it.
3. Remember the `alt` attribute for accessibility!  
   **Syntax:** `<img src="image.jpg" alt="A description of the image">`

---

### Extension 3: Content Partitioning

Use horizontal rules to create visual *breaks* between your sections.

#### TODO
1. Place an `<hr>` tag between your main sections (e.g. between  
   Experience and Education).
2. Notice how this creates a thematic break in the browser.

---

## Advanced Activity (Optional)

### Semantic HTML

Modern software development uses tags that describe their purpose.

#### TODO
1. Wrap your name and personal statement inside a `<header>` tag.
2. Wrap your main content (Experience/Education) inside a `<main>` tag.
3. Create a `<footer>` tag at the bottom of the body and include  
   a **Copyright 2026** notice.

---

## Final Submission

Once you have finished your extensions, run the following commands in your terminal:

1. `git add index.html`
2. `git commit -m "Added extensions and semantic tags"`
3. `git push origin main`

---
