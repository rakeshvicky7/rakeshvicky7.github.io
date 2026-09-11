# Personal website — Rakesh Ranjan Vejendla

Live at **https://rakeshvicky7.github.io**

Seven pages of plain HTML. No build step, no dependencies, no internet connection needed to view
them. **Every page is self-contained** — the styling and the script live inside the file itself,
so you can double-click any file anywhere on your computer and it looks exactly right.

## Files

    index.html                 home — about, personal details, where I fit, tech stack, projects, education, experience
    project-thyroid.html       thyroid disease detection from sleeping heart rate
    project-forgery.html       scientific image forgery detection
    project-elderassist.html   ElderAssist care marketplace
    project-pipeline.html      grocery sales batch data pipeline
    project-thesis.html        M.Sc. thesis — fault diagnosis assistant (in progress)
    project-cardio.html        redirect to project-thyroid.html (keeps older links working)
    photo.jpg                  portrait used on the home page
    resume.pdf                 the CV; the CV buttons on the site link to it
    resume-source.html         the file resume.pdf is generated from
    DEPLOY.md                  how to publish this on GitHub Pages

## How the project pages work

Each project page walks through the system in stages, and each stage has a diagram drawn as inline
SVG. The diagrams reveal themselves step by step: a scene player adds an `on` class to the parts
whose `data-show` number matches the current step, and CSS animates the line drawing, the bars
growing and the packets moving. A scene starts playing when it scrolls into view and stops
auto-advancing as soon as you click a step yourself.

## Editing

The source lives in `site/` with a shared `style.css` and `app.js`; `build.py` inlines both into
every page and writes the result to `dist/`. What is published is the contents of `dist/`.
Editing a published file directly is fine for a small text change — just remember the same change
belongs in the source copy too.
