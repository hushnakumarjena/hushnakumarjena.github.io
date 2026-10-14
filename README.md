# Personal scientific website (GitHub Pages)

This is a multi-page static website starter. It uses plain HTML, CSS, SVG illustrations, and a small JavaScript simulation. It does not require a build step.

## Before publishing
1. Search the files for `YOUR NAME` and replace it with the name you want displayed.
2. Replace the About text with a short accurate introduction.
3. Check each page and edit the starter notes; they are examples to develop, not a claim that these are completed research outputs.
4. Upload the files and folders to the root of your existing GitHub Pages repository.

## File map
- `index.html`: homepage
- `about.html`: personal introduction
- `research.html`: four research themes
- `maths.html`: maths index
- `writing.html`: writing index
- `resources.html`: resource index
- `themes/*.html`: individual theme pages
- `notes/*.html`: sample article pages
- `lab/index.html`: interactive leaky integrate-and-fire demonstration
- `style.css`: shared styles and navigation
- `images/*.svg`: original vector illustrations created for this starter

## Add a new note
1. Create `notes/new-topic.html`.
2. Copy the structure from an existing note such as `notes/dynamical-systems.html`.
3. Update the title and the article body.
4. Add a link to it in `maths.html`, `writing.html`, and/or the relevant `themes/*.html` page.
5. Commit changes. No code build is required.

## Add a new research theme
1. Copy a file from `themes/` and rename it.
2. Change the title, description, image, and related-note links.
3. Add a theme card pointing to the new page in `index.html` and `research.html`.
4. Keep using the shared `style.css` so the look remains consistent.

## GitHub Pages
If your repository is named `username.github.io`, the site usually publishes from the repository root. If it is a project repository, enable Pages in Settings and select the branch/folder you're using. Use relative links as provided in this project; they work on both user sites and project sites.
