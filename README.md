# Ian Bouche — personal website

A plain HTML site hosted on GitHub Pages. No build step: whatever files are in
this repository are what the site shows.

## What's here

| File / folder        | What it is                                   |
|----------------------|----------------------------------------------|
| `index.html`         | Home page                                    |
| `research.html`      | Papers and projects                          |
| `blog.html`          | List of blog posts                           |
| `photography.html`   | Photo grid                                   |
| `posts/`             | One file per blog post                       |
| `photos/`            | Your image files                             |
| `papers/`            | PDFs of your papers                          |
| `style.css`          | Colors, fonts and layout for every page      |

Anything you need to change is marked with an `EDIT:` comment in the file.

## Editing a page on GitHub

Open the file in your repository, click the pencil icon (top right of the
file), make your change, then click **Commit changes**. The live site updates
within a minute or two.

## Adding a blog post

1. Open `posts/hello-world.html`, click the **…** menu, and copy its contents.
2. In the `posts` folder, click **Add file → Create new file**. Name it
   something short with dashes, e.g. `my-second-post.html`. Paste, then edit
   the title, date and paragraphs. Commit.
3. Open `blog.html`, copy one `<li>…</li>` block, paste it at the **top** of
   the list, and change the link to `posts/my-second-post.html` along with the
   title, date and summary. Commit.

## Adding a photo

1. Go into the `photos` folder (or, the first time, click **Add file → Upload
   files** and drag in your image — GitHub creates the folder if you type
   `photos/` in front of the name, or you can drag in the whole folder).
2. In `photography.html`, copy the commented example `<figure>` block, remove
   the `<!--` and `-->` around it, and set `src="photos/your-file.jpg"` to the
   exact file name. Delete the grey placeholder boxes when you're done.

Tip: shrink photos to around 2000 pixels on the long side before uploading so
the page loads quickly.

## Adding a paper

Upload the PDF into `papers/`, then in `research.html` copy one `<li>` block
under **Papers** and point its link at `papers/your-file.pdf`. Until you do,
the example paper links lead nowhere — that's expected.

## Changing the look

All colors and fonts are at the top of `style.css`. Change `--accent` to pick
a different highlight color, for example.
