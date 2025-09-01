🎯 What this is

This repository contains a beginner-friendly portfolio created using pure HTML. It’s ideal for:

Practicing semantic HTML5 structure.

Learning forms, tables, and multimedia embedding.

Publishing a lightweight portfolio quickly (for example via GitHub Pages).

📂 What's in this repo

FinalProject.html — the full portfolio page (header, nav, about, skills, projects, contact, footer).
The page demonstrates:

Semantic sections (<header>, <nav>, <section>, <footer>)

Forms with inputs (text, email, textarea, radio, select, color, file)

<table>, <details>/<summary>

Embedding media via <iframe> and external links

🚀 How to view locally

Clone the repo:

git clone <your-repo-url>
cd <your-repo-folder>


Open the HTML file in your browser:

Double-click FinalProject.html, or

From terminal:

# macOS / Linux
xdg-open FinalProject.html

# macOS (alternate)
open FinalProject.html

# Windows (PowerShell)
start FinalProject.html

📤 How to publish on GitHub Pages

Push your code to a GitHub repo (if not already).

In the repository settings → Pages:

Source: choose branch main (or gh-pages) and / (root).

Save — GitHub will host FinalProject.html at https://<username>.github.io/<repo>/FinalProject.html (or at root if you rename to index.html).

Tip: Rename FinalProject.html to index.html if you want it to load automatically at the repo site root.

✍️ How to customize (quick guide)

Change the name & headline in the <header>.

Update navigation anchors to match section ids.

Add or remove <section> blocks for new content (e.g., blog, testimonials).

Replace the YouTube iframe src with your video ID:

<iframe src="https://www.youtube.com/embed/your-video-id" ...></iframe>


Update contact form action to your email handler or form service (Netlify forms, Formspree, etc.) if you want real submissions.

♿ Accessibility & usability checklist

Even without CSS/JS you can be accessible:

Use semantic elements (<main>, <nav>, <header>, <footer>, <section>).

Provide alt text for images (<img alt="...">).

Ensure form inputs have <label for="...">.

Maintain readable structure with headings (<h1> → <h2> → ...).

Use meaningful link text (avoid “click here”).

✅ Nice-to-have next steps (after HTML)

When you’re ready to expand:

Add a small CSS file (external or inline) to improve typography and layout.

Introduce responsive design with media queries.

Add light JavaScript for interactivity (form validation, analytics).

Break sections into separate HTML pages if the portfolio grows large.

Example snippets from this project

Semantic section

<section id="about">
  <h2>About Me</h2>
  <p>Hi — I'm Youssef, a junior web developer...</p>
</section>


Simple contact form

<form action="#" method="get">
  <label for="name">Name:</label>
  <input id="name" name="name" type="text" required>
  ...
  <input type="submit" value="Send Message">
</form>
