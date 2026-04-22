# Feature: Home Page

## Goal

implement `index.html`

## Designs

![target layout](/assets/images/Homepage.png)

## Work

- Describe the UI/UX clearly and specifically
  It is a simple and minimalistic homepage that talks about me.

- What elements exist? What container elements exist?
  Structural/Semantic: <nav>, <header>, <main>, <footer> — these are the semantic container elements that divide the page into distinct sections.
  Navigation: <ul>, <li>, <a> — used inside <nav> to build the menu links.
  Content: <h1>, <h2>, <h3>, <p>, <strong> — for headings and text.
  Layout containers: <div class="logo">, <div class="grid">, <div class="card"> - The generic divs used for grouping and layout purposes.

- How do users interact? What is the hover behavior?
  Nav links (.nav-links a:hover): When a user hovers over a menu link, the text color transitions from #555 (grey) to #007bff (blue) smoothly over 0.3s.
  Cards (.card:hover): When a user hovers over a card, it lifts up by 5px (translateY(-5px)) and a soft shadow appears (box-shadow: 0 10px 20px rgba(0,0,0,0.1)), both animating over 0.2s. This gives a tactile, "raised" feel.

## Deliverables

- What does “done” look like?
  Something that is user-friendly with no bugs.
- Be concrete and testable
