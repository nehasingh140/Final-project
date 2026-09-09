# Millhouse Coffee Roasters — Business Website

A single-page business website for a fictional small-batch coffee roastery and café based in Jaipur, built with plain HTML, CSS, and JavaScript.

## Business details
- **Name:** Millhouse Coffee Roasters
- **Type:** Small-batch coffee roastery + café
- **Location:** Civil Lines Road, Jaipur, Rajasthan
- **Founded:** 2019

## Website goals
- Introduce the business and its story to build trust with new visitors
- Show the current menu (drinks, beans, food) with prices
- Give visitors practical info to plan a visit (address, hours, seating/Wi-Fi)
- Provide a simple contact form for questions and orders

## Design and tool decisions
- **Typography:** Fraunces (serif, for headings) paired with Work Sans (body) and IBM Plex Mono (for stamps, prices, and origin labels) — chosen to evoke a roastery/label aesthetic rather than a generic template look
- **Color palette:** warm paper tone with dark roast-brown ink and a rust/copper accent, echoing coffee packaging rather than a typical blue-and-white business site
- **Layout:** built with CSS Grid for the menu and visit sections, and Flexbox for the header/nav and form
- **Responsiveness:** media queries collapse the grid layouts and switch the nav to a mobile hamburger menu below 720px
- **Contact form:** front-end only (no backend), with JavaScript showing a confirmation message on submit
- **Accessibility:** visible keyboard focus states throughout, semantic HTML (`<header>`, `<main>`, `<footer>`, form `<label>`s)

## Running locally
Open `index.html` in any browser — no build step or dependencies required.

## Live site
Hosted via GitHub Pages — see the repository's live link in the About/Website section.
