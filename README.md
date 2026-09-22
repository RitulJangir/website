# Ritul Jangir — Research Portfolio

A responsive, static HTML/CSS/JavaScript portfolio. No build step or framework is required.

## Files
- `index.html` — complete website
- `papers/OphEdit.pdf` — OphEdit paper
- `papers/SynCrash.pdf` — SynCrash paper

## Preview locally
Open `index.html` in a browser. For a local server, run:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Add your CV
Copy your latest resume PDF into this folder and name it exactly:
`resume.pdf`

The site automatically reveals the CV buttons when `resume.pdf` is present.

## Deploy to GitHub + Vercel
1. Create a GitHub repository (for example, `ritul-research-portfolio`).
2. Upload the contents of this folder to the repository root (keep `index.html` at root).
3. In Vercel, choose **Add New → Project**, import the GitHub repository.
4. For a static HTML site, use **Other** as the framework preset. Leave build command and output directory empty/default (root).
5. Deploy. Vercel will serve `index.html` at the project URL.

## Update links/content
Edit `index.html`. Google Scholar, LinkedIn, and GitHub links are already configured.
The CLARIF submission PDF is intentionally not included because the uploaded manuscript is marked confidential / not for distribution. Keep its project description/status only until a public version is available.
