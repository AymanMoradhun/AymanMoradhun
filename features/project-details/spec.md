# Feature: Project Details

## Goal
implement `index.html`
## Designs
![target layout](/assets/images/ProjectDetails.png)
## Work
- Describe the UI/UX clearly and specifically
Minimalistic UI that talks about my project details.

- What elements exist? What container elements exist?
Structural/Semantic: <nav>, <header>, <main>, <footer> — semantic containers dividing the page into clear sections.
Navigation: <ul>, <li>, <a> — inside <nav> for the menu links.
Content: <h1>, <h2>, <p>, <strong> — for headings and body text.
Layout containers: <div class="logo">, <div class="project-image">, <div class="tech-stack"> — divs used for grouping specific content blocks.

- How do users interact? What is the hover behavior?
Nav links (.nav-links a:hover): Hovering a menu link transitions its color from #555 (grey) to #007bff (blue) over 0.3s — same as your homepage.
Back button (.back-btn:hover): Hovering the "← Back to Home" link shifts it left by 5px (translateX(-5px)) over 0.2s, reinforcing the backwards navigation direction visually.

## Deliverables
- What does “done” look like?
Something that is user-friendly with no bugs.
- Be concrete and testable
