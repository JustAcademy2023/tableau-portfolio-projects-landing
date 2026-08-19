# Tableau Portfolio Projects Landing Page

A single page, fully responsive landing page for **"10 Tableau Dashboard Projects for Beginners to Build a Strong Portfolio."** The page is designed to look and feel like an actual analytics dashboard, hero window with a live style chart, KPI stat strip, and a bento grid of ten project widgets, each with a custom hand drawn chart icon matching its topic (bar, gantt, map, funnel, and so on).

Built as one self contained `index.html` file with no build step and no dependencies beyond Google Fonts, so it is ready to publish on GitHub Pages as is.

## Preview

Open `index.html` in any browser, or publish it through GitHub Pages (steps below) to see it live.

## Features

- Dashboard styled hero section with an animated sample chart
- KPI stat strip summarising the project set
- Ten project cards in an asymmetric bento grid, each with a unique inline SVG icon, short description, and skill tags
- Dedicated blog callout banner linking to the full written breakdown
- Four course and bootcamp cards linking directly to the relevant training pages
- Fully responsive layout, down to small mobile screens
- Accessible focus states and `prefers-reduced-motion` support
- Sticky navigation bar with smooth scroll anchor links

## Tech stack

- Plain HTML5 and CSS3, no framework
- Google Fonts: Space Grotesk, Inter, IBM Plex Mono
- No JavaScript build tooling required

## File structure

```
.
├── index.html      # the entire landing page, markup + styles + MIT license notice
└── README.md        # this file
```

## Running locally

Clone the repository and open the file directly in a browser.

```bash
git clone https://github.com/your-username/tableau-portfolio-projects-landing.git
cd tableau-portfolio-projects-landing
open index.html   # or double click the file, or use a local server
```

Optional local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Deploying on GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set the source to **Deploy from a branch**.
4. Choose the `main` branch and the `/root` folder, then save.
5. GitHub will publish the page at `https://your-username.github.io/tableau-portfolio-projects-landing/` within a minute or two.

## Links used on this page

- [Tableau training in Mumbai](https://www.justacademy.co/course-detail/mumbai/tableau-training-in-mumbai)
- [Microsoft Power BI training in Mumbai](https://www.justacademy.co/course-detail/mumbai/microsoft-power-bi-training-in-mumbai)
- [Python training in Mumbai](https://www.justacademy.co/course-detail/mumbai/python-training-in-mumbai)
- [Data analytics bootcamp in Mumbai](https://www.justacademy.co/job-bootcamp-detail/mumbai/data-analytics-bootcamp-in-mumbai-classroom-training-with-real-world-projects)
- [Tableau tutorials blog](https://www.justacademy.co/blog-detail/tableau-tutorials)

## License

Released under the MIT License. The full license text is included as a comment at the bottom of `index.html`, and the footer of the page also credits it.
