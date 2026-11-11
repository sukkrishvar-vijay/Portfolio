# Portfolio

Personal portfolio website of Sukkrishvar Vijay Santhana Krishnan, covering skills, internship experience, education, projects and volunteer work.

**Live site:** https://sukkrishvar-vijay.github.io/Portfolio/

## What's on the page

| Section | Contents |
| --- | --- |
| Intro | Short bio, contact buttons (email, LinkedIn, GitHub), location and a quick-facts strip |
| Skills | Programming languages, tools and operating systems |
| Internship experience | Associate Consultant and Research Associate roles at SecureITLab |
| Education | M.S. Computer Science (University of New Haven) and B.Tech (Vellore Institute of Technology) |
| Projects | Recipe Nest, Blog Site, Rain Alert via SMS, Stock Trading News Alert |
| Volunteer work | Rotary Club, Vellore Institute of Technology |

## Features

- Responsive layout that works on desktop, tablet and phone
- Light and dark themes: follows the visitor's system setting, with a toggle that remembers their choice
- Sticky navigation with smooth scrolling to each section
- Sections fade in on scroll, switched off for visitors who prefer reduced motion
- Keyboard-friendly: skip link and visible focus outlines

## Built with

Plain HTML, CSS and a small amount of JavaScript. There is no framework, build step or package to install. Fonts (Sora, Inter, JetBrains Mono) load from Google Fonts.

## Project structure

```
index.html   Page content and the small inline script (theme toggle, scroll reveal)
style.css    All styling, including colour themes and responsive rules
images/      Logos shown in the Skills section
```

## Run it locally

Clone the repository and open `index.html` in a browser:

```
git clone https://github.com/sukkrishvar-vijay/Portfolio.git
cd Portfolio
```

Then double-click `index.html`. For automatic refresh while editing, use the Live Server extension in VS Code: right-click `index.html` and choose **Open with Live Server**.

## Editing the site

- **Content:** edit the matching section in `index.html`. Each section is marked with an `id` (`skills`, `experience`, `education`, `projects`, `volunteer`).
- **Add a project:** copy an existing `<article class="card reveal">` block inside the Projects section and change its text and tags.
- **Add a skill:** put the logo in `images/` and add a `<li>` to the relevant list in the Skills section.
- **Colours:** change the variables at the top of `style.css`. The light values are under `:root`; the dark values appear twice (system setting and manual toggle), so update both.

## Deployment

The site is hosted on GitHub Pages from the `main` branch (root folder). Pushing to `main` republishes it automatically, usually within a couple of minutes.
