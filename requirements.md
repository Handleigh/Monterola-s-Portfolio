# Portfolio Requirements

## Goal

Create a one-page personal portfolio as a single static `index.html` file,
using HTML, CSS, and JavaScript.

## Required content

- The owner's confirmed personal information, recorded exactly:
  - Name: **Vince Giane Monterola**
  - Professional title: **Aspiring Full-Stack Developer, Aspiring Web
    Developer, Aspiring Data Analyst & BSIT Student**
  - Email: [vincegianemonterola@gmail.com](mailto:vincegianemonterola@gmail.com)
  - GitHub: [https://github.com/Handleigh](https://github.com/Handleigh)
  - LinkedIn:
    [https://www.linkedin.com/in/vince-giane-monterola-a64872320/](https://www.linkedin.com/in/vince-giane-monterola-a64872320/)
  - Summary: **An aspiring Full-Stack Developer & Web Developer specialized in
    building secure systems, currently pursuing BSIT and exploring the
    intersections of data analysis and performance monitoring.**
- Exactly two featured projects:
  1. **Employee HRIS & Leave Management System** — A PHP and MySQL-based HR
     management system featuring employee records, leave applications and
     approvals, role-based access, WebSocket notifications, Docker, Terraform,
     and monitoring tools. Status: **Private Repository**. Do not expose or
     invent its private repository URL.
  2. **CareNest** — A PHP and MySQL-based caregiver recruitment and matching
     platform featuring job postings, caregiver profiles, skills, experience,
     and document management. Status: **In Development**. It is currently
     local-only, with no public repository or live demo.
- Each project card has a title, description, and status label. Project links
  are optional; show one only when a confirmed public destination is available.
  Do not invent URLs, expose the private HRIS repository, or imply that CareNest
  has a public repository or live demo.

Do not invent or replace personal details, project details, or URLs.

## Functional and technical requirements

- Put all page content directly in the HTML.
- Put CSS in an inline `<style>` block and JavaScript in an inline `<script>`
  block in `index.html`.
- Use a single static HTML page with inline CSS and vanilla JavaScript; no
  frameworks, backend, database, or build tools. The owner has approved Three.js
  r0.143.0 from unpkg.com as the sole external runtime dependency for the
  Vortex & Tunnel background scene.
- Keep the full-page background scene decorative and non-interactive to
  assistive technology, provide a static CSS fallback when reduced motion is
  preferred or WebGL is unavailable, and reduce rendering load on smaller
  devices.
- Ensure the page works on phone-sized screens and responsive desktop layouts.
- Keep the page fast to load and avoid unnecessary assets or scripts.
- Use semantic HTML, accessible contrast, keyboard-accessible navigation and
  interactions, visible focus states, and appropriate text alternatives.
- Respect reduced-motion preferences and avoid relying on motion or color alone
  to communicate information.

## Layout and visual direction

- Follow the Creative Modern direction: a dark modern background, vibrant
  gradient accents, bold modern typography, and subtle glowing effects.
- Create an attractive hero section with a greeting, oversized owner's name,
  professional title, and the confirmed summary.
- Present exactly two projects in modern cards with status labels and refined
  hover effects. Do not require a repository or demo link for either card.
- Include modern social and contact links for email, GitHub, and LinkedIn.
- Keep the interface visually balanced, professional, and easy to navigate,
  with fully responsive desktop and mobile layouts.
- Avoid excessive animations and unnecessary decoration.

## Approval gate

The owner approved integrating the Vortex & Tunnel scene and its required
Three.js CDN dependency. Keep the existing portfolio content and structure;
do not replace it with the Atelier template.
