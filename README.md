# EduBloom — Educational Posts Website

EduBloom is a responsive, multi-page educational publishing website designed around **SDG 4: Quality Education**. It is built with plain HTML, CSS and JavaScript, so no build tools or package installation are required.

## Pages
- `index.html` — home, featured posts, topic categories and demo newsletter form
- `posts.html` — searchable post library, category filters and sorting
- `article.html` — individual article pages generated from the post data in `script.js`
- `about.html` — mission and SDG 4 explanation
- `contact.html` — validated contact form with demo confirmation
- `styles.css` — responsive visual design and accessibility-focused styles
- `script.js` — educational article data and interactions

## Run locally
1. Download and extract the ZIP.
2. Open the `learnwell_website` folder.
3. Double-click `index.html` to open it in a modern browser.

For a more reliable local development setup, open the folder in VS Code and use the **Live Server** extension, then click **Go Live**. No backend is required.

## Interactions to test
1. Click **Explore posts**.
2. Search for “AI” or “water”.
3. Filter by Technology, Science, Study skills or Careers.
4. Change the sort order.
5. Open an article, click **Yes, helpful**, and try **Copy article link** (clipboard access may depend on browser security settings).
6. Submit a valid email in the newsletter form.
7. Submit the contact form with all required fields completed.
8. Resize the browser or use a phone to check the responsive navigation and layouts.

## Important demo notes
- Search, filters, sorting, article navigation, helpful feedback, and form validation work in the browser.
- Newsletter and contact forms are front-end demonstrations. They show confirmation messages but do **not** send/store submissions. A real deployment would need a backend or a trusted form service.
- The fonts are loaded from Google Fonts when internet access is available; fallback fonts are included.
- The sample articles are educational demonstration content. Verify facts and add references where your coursework requires them.

## Design and rubric alignment
- **Concept & relevance:** educational learning journal with a clear SDG 4 mission.
- **UI & visual design:** consistent forest-green, sage and cream palette; editorial typography; clear hierarchy; responsive cards and spacing.
- **Functionality:** navigation, keyword search, category filters, sorting, article pages, helpful interaction, and validated forms.
- **Content & communication:** eight sample learning notes across four categories.
- **Presentation & finishing:** reusable styling, semantic HTML, accessible labels, empty search state, mobile navigation, page titles and meta descriptions.

## Suggested classroom demonstration
“EduBloom is a digital educational publication that supports SDG 4 by presenting approachable learning content for students and lifelong learners. The website includes a searchable library, topic filters, individual article pages and contact/newsletter form interactions. It is a front-end prototype, so forms demonstrate validation and feedback rather than saving data to a server.”
