# NOCTURNE LIBRARY

A responsive dark-academia literature website for VS Code.

## Run locally
1. Extract the ZIP.
2. Open the `nocturne_library` folder in VS Code.
3. Open `index.html` in a browser. Recommended: install the VS Code extension **Live Server**, right-click `index.html`, choose **Open with Live Server**.
4. No npm, framework, external API, or `.txt` files are needed for the built-in reading experience.

## What's included
- 30 real classic works with correct author credits, genre, year/period, synopsis, and external full-text search links.
- 30 locally stored SVG cover designs and a local SVG library hero image.
- Search by title, author, genre, and synopsis; genre filter; sorting.
- Responsive dark library layout, light/dark toggle, likes, bookmarks, reading progress, previous/next navigation.
- Each classic record opens an original complete short story (one chapter with a beginning, development, and ending) written for this student project.

## Important content note
The original stories shown on each reading page are original companion fiction, NOT the full text of the named classic and NOT written by the credited classic author. Use the "Find a full-text edition" link to locate editions of the actual classic. Check the status of each edition and translation before reproducing its full text. Some titles or translations may remain copyrighted in your jurisdiction.

## Replace a cover image
Open the `images` folder. Each SVG file is a local vector cover, e.g. `cover-01.svg`.
- To use your own cover, copy it into `images/` and rename it, e.g. `cover-01.jpg`.
- Then in `script.js`, find the matching book's `cover` property and change it to `images/cover-01.jpg`.
- Keep the file extension exactly the same as the actual image.
- For your own original SVG/JPG/PNG cover, make sure you have permission to use the artwork.

## Files
- `index.html` = page structure
- `style.css` = all design and responsive layout
- `script.js` = book catalog, complete companion stories, search, buttons, reader
- `images/` = 30 cover images + hero image
