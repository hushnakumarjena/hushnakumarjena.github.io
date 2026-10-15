# Hushna Kumar Jena — personal scientific website

This is a multi-page GitHub Pages website built with plain HTML, CSS, original SVG illustrations, and a small JavaScript neuron simulation.

## IMPORTANT: upload the contents to the repository root

After extracting the ZIP, you should see `index.html`, `style.css`, `about.html`, `research.html`, and folders such as `images/`, `themes/`, `notes/`, and `lab/` immediately. Upload those files and folders to the **top level** of your GitHub repository. Do not upload the ZIP itself, and do not place everything inside an extra folder.

Your repository root should look like:

```
index.html
about.html
research.html
maths.html
writing.html
resources.html
style.css
images/
themes/
notes/
lab/
```

## Edit descriptions

- Homepage introduction and theme-card descriptions: `index.html`
- About paragraph: `about.html`
- The four theme cards: `research.html`
- Individual theme introductions and lists: `themes/physics.html`, `themes/statistical-physics.html`, `themes/machine-learning.html`, and `themes/neuroscience.html`
- Maths page list: `maths.html`
- Writing list: `writing.html`

Text usually appears inside tags such as `<p>...</p>`; replace only the words between the tags and leave the HTML tags intact. Commit the changes to publish them.

## Use your own images

1. Prepare a JPG, PNG, or WebP image. Descriptive filenames with no spaces are easiest, e.g. `quantum-wave.jpg`.
2. In GitHub, open the `images` folder, choose **Add file → Upload files**, upload the image, and commit it.
3. Find the image you want to replace in the HTML. On the homepage, for example:

   `<img class="card-image" src="images/physics.svg" alt="Wave patterns representing mathematical physics">`

   Change the `src` to `images/quantum-wave.jpg` and update the `alt` description. On pages inside `themes/`, use `../images/quantum-wave.jpg` because those pages are one folder deeper.
4. The CSS sets card images to a consistent aspect ratio. Images around 1200 × 600 pixels work well. Use images you created or are allowed to publish; check licences for images found online.

The hero background is set in `style.css` at the `.hero` rule: `url("images/hero.svg")`. Replace `hero.svg` with your own filename to change it.

## Add a new note

1. Create a new file such as `notes/new-topic.html`.
2. Copy the structure from `notes/dynamical-systems.html` and replace the title and article text.
3. Add a link to that page in `maths.html`, `writing.html`, and/or the relevant theme page. Links from `notes/` to a root page use `../maths.html` and links to another note use the appropriate `note-name.html` path.
4. Commit changes.

## GitHub Pages settings

Open repository **Settings → Pages**. For a standard branch-based setup, choose **Deploy from a branch**, select your main branch (often `main`), and select `/(root)` as the folder. This should be the folder containing the root `index.html`. After committing, give Pages a minute to deploy and then hard-refresh the site.

If your repository is a project site, links in this template are relative so they work under the repository subpath too.
