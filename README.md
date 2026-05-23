# Rafi — Data Science Portfolio

A single-file React + Tailwind portfolio site. No build step. Just open `index.html` in any browser.

## How to view it locally

Double-click `index.html` — it opens in your browser. That's it.

## How to edit your info

Open `index.html` in any editor (VS Code, Notepad++, even Notepad). Find the section near the top of the `<script>` block that starts with:

```js
const DATA = {
  name: "Rafi",
  title: "Data Scientist",
  ...
};
```

Everything you see on the site lives inside that `DATA` object. Just change the text inside the quotes.

### What to update

- `name`, `title`, `tagline` — top of the page
- `email`, `github`, `linkedin` — your real links
- `resumeUrl` — replace `"#"` with a link to your resume PDF (e.g., a Google Drive or GitHub link). If you leave it as `"#"`, the Download Resume button is hidden automatically.
- `about` — your bio paragraph
- `location` — your city
- `skills` — add/remove categories and tools
- `projects` — replace placeholder projects with your real data science work. Each project has:
  - `title`, `description`, `tech` (array), `link` (live demo URL or `"#"`), `github` (repo URL)
- `experience` — internships, jobs. Each has `role`, `org`, `period`, `points` (bullet list)
- `education` — your degree(s)

Save the file, refresh your browser — done.

## How to host it online (free)

### Option 1: GitHub Pages (recommended)
1. Create a new public repo on GitHub (e.g., `rafi-portfolio`).
2. Upload `index.html` to the repo.
3. Go to **Settings → Pages**.
4. Under "Source", pick the `main` branch and `/ (root)` folder.
5. Save. In ~1 minute your site will be live at `https://<your-username>.github.io/rafi-portfolio/`.

### Option 2: Netlify (drag and drop)
1. Go to https://app.netlify.com/drop
2. Drag the folder containing `index.html` onto the page.
3. Done — Netlify gives you a live URL.

### Option 3: Vercel
1. Push to GitHub, import the repo in Vercel — auto-deploys.

## Tips for recruiters

- Replace the placeholder projects with **2–4 strong, real projects** rather than many weak ones.
- For each project: explain the **problem**, **what you did**, the **result** (with numbers if possible), and link to the **code on GitHub**.
- Add a clear link to your resume (`resumeUrl`).
- Make sure your LinkedIn and GitHub are public and up-to-date.
- Consider adding screenshots or a Streamlit demo link for top projects.

Good luck with your job search!
