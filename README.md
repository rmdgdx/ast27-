# Chapter 1: Unlocking SciComm — Interactive OER

An interactive, single-file open educational resource (OER) on **science communication** — covering the deficit vs. engagement models, visual analytics and scrollytelling, misinformation and cognitive biases, and the ethics of communicating uncertain science. Built for the *Seminar in Astronomy*.

**➡️ Live demo:** once published, your page will be at
`https://<your-username>.github.io/<repo-name>/`

## Features

- **Five modules** of expanded academic content, from "What is SciComm?" to the ethics of the astronomer's voice.
- **Astronomy case studies** — Galaxy Zoo citizen science, JWST first-image rollout, the phosphine-on-Venus caution tale, and more.
- **Interactive chartjunk sandbox** — toggle a cluttered chart against a clean, high data-ink-ratio version.
- **40-item self-assessment** (HOTS + reinforcement) plus four essay prompts, with a reveal-answer tracker and Reveal All / Reset controls.
- **Key-terms glossary** and an APA-adjacent **references** list for further reading.
- **Reading UX:** dark/light theme toggle, scroll progress bar, sticky table of contents, back-to-top, and print-friendly styles.
- **Zero dependencies** — pure HTML, CSS, and vanilla JavaScript in one file. No build step, no tracking, works offline.

## Repository contents

```
index.html     The entire interactive chapter (open it directly in any browser)
README.md      This file
LICENSE        MIT License
.gitignore     Common ignore rules
```

## View locally

Just open `index.html` in any modern browser — no server required. To serve it locally instead:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Publish with GitHub Pages

1. Create a new GitHub repository and push these files to the `main` branch:

   ```bash
   git init
   git add .
   git commit -m "Add interactive SciComm chapter"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Set the branch to **main** and the folder to **/ (root)**, then **Save**.
5. Wait about a minute, then visit `https://<your-username>.github.io/<repo-name>/`.

Because the file is named `index.html` and sits at the repository root, GitHub Pages serves it automatically as the site's home page.

## License

Released under the [MIT License](LICENSE) — free to use, adapt, and share for educational purposes.
