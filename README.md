# Fiona Tang portfolio

A static, deliberately ugly and animated portfolio for Fiona Tang. It uses the LinkedIn headline and location supplied by the owner, a verified Pocket CFO project, and links to her LinkedIn and GitHub profiles. The neon colors, floating coins, moving ticker, and construction tape intentionally match the Pocket CFO site's aesthetic.

Open `index.html` directly, or run `python -m http.server 8765` in this folder and visit `http://127.0.0.1:8765`.

LinkedIn blocks automated access to the profile. The owner pasted the visible headline "Finance Intern @ Venu YC W21" and location "Oakville, Ontario, Canada"; these are reflected in the site. The profile text did not include an About section, education, or role responsibilities. The introductory and About copy is an editable draft based on the owner's expressed finance and AI interests, not a quote from LinkedIn. Add verified details to `index.html` if the owner supplies them. No contact email, degree, school, headshot, dates, or internship responsibilities have been guessed.

Published site: <https://fiona-t728.github.io/fiona-portfolio/>. GitHub Pages serves the root of the `main` branch; a push updates the website.

The site has no dependencies or analytics. `styles.css` contains the base layout; `ugly.css` supplies the requested theme and reduced-motion support. External links open in a new tab with `rel="noopener noreferrer"`.
