# David LaSota — Portfolio

Personal portfolio site for David LaSota, targeting Assistant Underwriter roles in commercial insurance.

## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Landing page with headline stats and overview |
| About | `about.html` | Summary, education, certifications, and skills |
| Documents | `documents.html` | Resume display + editable cover letter area |
| Projects | `projects.html` | Project showcase (ready for future uploads) |

## How to Deploy on GitHub Pages

1. Push this folder to a GitHub repository named `portfolio` (or any name).
2. Go to **Settings → Pages**.
3. Set the source to **Deploy from a branch** → `main` → `/ (root)`.
4. Your site will be live at `https://yourusername.github.io/portfolio/`.

## Adding Projects

1. Create a `/projects/` subfolder in the repo.
2. Upload your project files (Excel workbooks, PDFs, Power BI exports, etc.) there.
3. Open `projects.html` and copy the commented-out template card.
4. Fill in the title, description, tags, and link to your file.

## Updating the Cover Letter

The cover letter on the Documents page auto-saves to your browser's local storage as you type. To pre-fill it, edit the `placeholder` attribute in the `<textarea>` tag inside `documents.html`.

## File Structure

```
portfolio/
├── index.html        # Home
├── about.html        # About
├── documents.html    # Resume + Cover Letter
├── projects.html     # Projects
├── style.css         # Global stylesheet
├── README.md
└── projects/         # (create this folder when adding project files)
```
