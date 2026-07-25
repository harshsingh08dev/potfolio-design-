# Developer Systems Portfolio

A modern, animated developer portfolio built with plain HTML, CSS, and JavaScript. The design uses a dark technical interface style with smooth scrolling, animated metrics, interactive cards, a custom cursor, responsive layouts, and editable content stored in one configuration file.

## Preview

This project is ready to run as a static website. Open `index.html` in a browser to view the portfolio locally.

## Features

- Responsive portfolio layout for desktop, tablet, and mobile screens
- Animated hero section with rotating visual panels
- Sticky navigation with smooth section links
- Scroll progress indicator and timeline progress animation
- Interactive project cards, gallery cards, and magnetic skill cells
- Animated metrics counter section
- Config-driven page content through `portfolio-config.js`
- Contact section with editable social/profile links
- No framework, package manager, or build process required

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts
- Unsplash image assets

## Project Structure

```text
.
+-- index.html              # Publish-ready homepage
+-- portfolio 2 .html       # Main portfolio page
+-- portfolio.css           # Complete styling, layout, and responsive design
+-- portfolio-config.js     # Editable portfolio text, links, sections, and labels
+-- robots.txt              # Search engine crawling rules
+-- README.md               # Project documentation
```

## Getting Started

1. Download or clone the repository.

```bash
git clone https://github.com/your-username/your-repository-name.git
```

2. Open the project folder.

```bash
cd your-repository-name
```

3. Open `index.html` in your browser.

No installation is needed because this is a static frontend project.

## Customization

Most visible text can be changed from `portfolio-config.js`.

Update this file to edit:

- Page title and navigation links
- Hero heading and description
- Project cards
- Skills and services
- Timeline entries
- Metric values
- Gallery labels
- Contact and social links

To change colors, spacing, fonts, animations, or responsive behavior, edit `portfolio.css`. The main design variables are defined near the top of the CSS file inside `:root`.

## Publishing on GitHub Pages

1. Push the project to GitHub.
2. Open the repository settings.
3. Go to **Pages**.
4. Set the source branch to `main` and the folder to `/ (root)`.
5. Save the settings and wait for GitHub to generate the live URL.
6. Share the generated GitHub Pages URL or submit it to Google Search Console for faster indexing.

## Before Uploading

Before making the repository public, update the placeholder content:

- Replace `architecture@dev.engine` with your real email address.
- Replace `#` links in the contact section with your real GitHub, LinkedIn, and social URLs.
- Replace sample project names with your real projects.
- After publishing, search engines may take time to index the site. Use Google Search Console if you want to request indexing sooner.

## License

This project is open for personal portfolio use. Add a license file if you want to define reuse rules clearly for other developers.
