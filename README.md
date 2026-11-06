# Kesha's Portfolio

A personal portfolio for Kesha Jane L. Ceniza, built using HTML, CSS, and JavaScript. It showcases her background, technical skills, projects, and contact information.

## Live Demo

https://martiank3jc.github.io/WebDvlpmnt/

## Features

* Responsive layout with illustrated artwork
* About, tech stack, Work & Wins, and contact sections
* Navigation highlighting as sections come into view
* Sections loaded dynamically from separate HTML files
* Education, leadership experience, and CodeChum certifications
* Projects including CertiChain, System Crash, AlphaQt, and Takapi
* CEB-i Hacks Top 10 Finalist (January 2026) and Oltek 5th Runner Up (March 2026) achievements

## Tech Stack

* HTML
* CSS
* JavaScript

## Skills Showcased

* Languages: C, C++, C#, Java, Python, JavaScript, and SQL
* Web development: HTML, CSS, Django, and Tailwind CSS
* Databases: MySQL and Supabase
* Tools: Git, GitHub, Ubuntu, VS Code, Figma, Vercel, Jupyter Notebook, and Streamlit
* Data analysis: Pandas, NumPy, and Matplotlib

## Run Locally

From the project directory, start a local web server, for example with Python 3:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000 in your browser. A local server is required because the homepage uses `fetch()` to load its sections. You can also use the Live Server extension in VS Code.

## Project Structure

```text
.
├── index.html                 # Homepage and dynamic section containers
├── about.html                 # Bio, education, leadership, certifications
├── skills.html                # Tech stack icons and additional skills
├── projects.html              # Projects and hackathon achievements
├── contact.html               # Contact information and form
└── assets/
    ├── css/styles.css         # Layout and styling
    ├── js/script.js           # Section loading and navigation
    └── images/
        ├── about/             # Portrait
        ├── achievements/      # CEB-i Hacks and Oltek photos and frames
        ├── backgrounds/       # Background illustrations
        ├── branding/          # Logo and favicon
        ├── contact/           # Contact icons and background
        ├── extras/            # Other preserved image assets
        ├── hero/              # Hero character illustration
        ├── icons/             # Tech stack and social/link icons
        └── projects/          # Project screenshots and decorative frames
```

Keep the HTML files at the site root: `script.js` fetches section files relative to
`index.html`. Asset filenames use lowercase letters and hyphens. Tech icons are
named for the logos they display (`c.svg`, `cpp.svg`, and `csharp.svg`).

## Updating Content

* Edit `about.html` for the bio, education, leadership roles, and certifications.
* Edit `skills.html` for skills, keeping icon labels and `alt` text in sync.
* Edit `projects.html` for projects and Work & Wins achievements. Store new images
  in the matching `assets/images/projects/` or `assets/images/achievements/` folder.
* Edit `contact.html` for contact details.
* Preview through a local server after changing paths so dynamic sections load correctly.
