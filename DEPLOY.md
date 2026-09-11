# Putting this site online

End result: **https://rakeshvicky7.github.io** — free, permanent, no hosting bill, and the URL
you can print on your CV and put on LinkedIn.

Everything in `C:\Users\rakes\Documents\personal-website\` is final and ready to upload.
There is nothing left to fill in.

---

## Step 1 — create the repository (1 minute)

1. Go to **https://github.com/new** (sign in as `rakeshvicky7`).
2. Repository name — type it exactly, including the `.github.io`:

       rakeshvicky7.github.io

   The name has to match your username. That is the rule that gives you the short URL
   instead of `rakeshvicky7.github.io/some-repo`.
3. Set it to **Public**.
4. Leave "Add a README file" **unticked**. Add nothing else.
5. Click **Create repository**.

## Step 2 — upload the files (2 minutes)

1. On the empty repository page, click the link **uploading an existing file**.
2. Open `C:\Users\rakes\Documents\personal-website\` in File Explorer.
3. Press **Ctrl+A** to select everything, then drag it all into the GitHub page.
   Wait until every file name is listed.
4. Scroll down and click the green **Commit changes** button.

Upload the *contents* of the folder, not the folder itself.

## Step 3 — check Pages is switched on (1 minute)

1. In the repository, click **Settings** (top right), then **Pages** in the left sidebar.
2. Under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)**
   - Click **Save** if you had to change anything.

## Step 4 — open it

Wait one to two minutes for the first build, then open:

**https://rakeshvicky7.github.io**

If you get a 404 on the first try, wait another minute and refresh. The first deployment is
always the slowest.

---

## Updating the site later

Open the repository, click the file you want to change, click the pencil icon, edit, commit.
Or use **Add file → Upload files** and drop in a newer copy — same file name overwrites the old one.
The live site updates about a minute after each commit.

## What is in the folder

| File | What it is |
|---|---|
| `index.html` | Home page — about, details, education, experience, projects |
| `project-thyroid.html` | Thyroid disease detection |
| `project-forgery.html` | Scientific image forgery detection |
| `project-elderassist.html` | ElderAssist marketplace |
| `project-pipeline.html` | Grocery sales data pipeline |
| `project-thesis.html` | Master's thesis, in progress |
| `project-cardio.html` | Redirect to the thyroid page (keeps any old link working) |
| `photo.jpg` | Your photo |
| `resume.pdf` | The CV — the **CV** buttons on the site link to this |
| `resume-source.html` | The file the CV PDF is generated from. Harmless to upload. |
| `README.md`, `DEPLOY.md` | Notes. Not shown on the site. |

Each HTML page carries its own styles inside it, so there is no stylesheet to upload and
nothing can break by being left behind.

## Where the link goes once it is live

- **LinkedIn:** profile → *Edit intro* → **Website** → URL `https://rakeshvicky7.github.io`,
  and in *Contact info*. Turn **Share profile updates with your network** OFF before editing
  if you do not want the change announced.
- **CV:** already printed in the contact line of `resume.pdf`.
- **Applications:** paste it in the "Portfolio / Website" field German application forms usually have.
