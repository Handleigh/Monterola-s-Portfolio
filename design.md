# Portfolio Design

## Page structure

1. A centered, readable page container with a clear visual hierarchy.
2. An attractive hero section featuring a short greeting, the owner's name as
   an oversized primary heading, the professional title, a concise summary, and
   contact actions. Include the supplied profile photo in a compact identity
   card alongside the text on desktop and below it on mobile, with a subtle
   animated treatment that respects reduced-motion preferences. Use:
   **Vince Giane Monterola** and **Aspiring Full-Stack Developer, Aspiring Web
   Developer, Aspiring Data Analyst & BSIT Student**.
3. An "About me" focus section between the hero and projects, with three offset,
   long rounded cards describing data analysis, full-stack learning, and
   AI-assisted creative coding. Pair each with a relevant inline SVG icon.
4. A projects section with exactly two modern, consistently styled cards. Give
   each card a decorative, non-screenshot project banner, title, confirmed
   description, status label, and compact technology tags. Links are optional
   and shown only when a public destination is available.
5. A "Tools I Use" section between projects and contact. Show the owner's
   confirmed developer tools with recognizable inline SVG icons in one
   vertically scrolling column that moves upward. Show three cards at a time,
   with the center card clear and the top and bottom fading. Hide duplicated
   scrolling content from assistive technology; provide a static list when
   reduced motion is preferred or JavaScript is unavailable.
6. A footer or contact section with the confirmed email, GitHub, and LinkedIn
   links:
   - Email: [vincegianemonterola@gmail.com](mailto:vincegianemonterola@gmail.com)
   - GitHub: [https://github.com/Handleigh](https://github.com/Handleigh)
   - LinkedIn:
     [https://www.linkedin.com/in/vince-giane-monterola-a64872320/](https://www.linkedin.com/in/vince-giane-monterola-a64872320/)
7. A clear, responsive navigation area that remains easy to use on small screens.

## Visual treatment

- Show a brief, centered loading screen on each visit, using the portfolio's
  teal accent, owner's initial and name, and a lightweight animated progress
  indicator. Dismiss it when the page loads, with a timeout fallback and
  reduced-motion support.
- Follow the Creative Modern direction with a dark, modern background and
  high-contrast, accessible text.
- Use vibrant gradients for focused emphasis, such as links, selected headings,
  and small decorative details.
- Use subtle glow effects to support the accent colors without competing with
  content.
- Give project cards a glass-style treatment with translucent surfaces,
  restrained borders, depth, and subtle hover feedback.
- Use modern typography with a system font stack; keep text readable and project
  content central.
- Keep spacing generous and the interface attractive, balanced, professional,
  and easy to navigate.
- Place the original Vortex & Tunnel Three.js scene as a fixed, subdued
  background behind the entire existing one-page portfolio, like the supplied
  reference. Keep cards and navigation usable above it, preserve the blue, cyan,
  and teal accents, and do not use the Atelier template's replacement layout or
  branding.
- Keep the scene responsive and non-interactive, with a static CSS fallback
  when WebGL is unavailable or reduced motion is preferred.

## Featured project cards

- **Employee HRIS & Leave Management System**
  - Description: A PHP and MySQL-based HR management system featuring employee
    records, leave applications and approvals, role-based access, WebSocket
    notifications, Docker, Terraform, and monitoring tools.
  - Status label: **Private Repository**.
  - Do not expose or invent a public repository URL, or link to private source
    code.
- **CareNest**
  - Description: A PHP and MySQL-based caregiver recruitment and matching
    platform featuring job postings, caregiver profiles, skills, experience,
    and document management.
  - Status label: **In Development**.
  - It is a local project with no public repository or live demo yet; show no
    unavailable or invented link.
- Keep each status label clear and readable as text, not color alone. A card
  must remain complete and useful without a link.

## Motion and interaction

- Use smooth CSS transitions for links, buttons, navigation, and card hover
  states.
- Provide a JavaScript-powered mobile navigation menu with an accessible
  open/close control and clear expanded state.
- Use JavaScript for purposeful interactive elements only; interactions must
  remain understandable and must not hide essential content.
- Keep animations subtle, respect reduced-motion preferences, and avoid
  excessive motion or decoration.
- Preserve visible focus states and usable controls for keyboard and touch users.

## Responsive behavior

- Use a multi-column project-card layout where space allows and a single-column
  layout on narrow screens.
- Constrain the content width on larger screens and allow comfortable page
  margins on phones.
- Ensure navigation and other controls adapt to narrow viewports and are easy
  to tap.
- Ensure text does not require horizontal scrolling.
- Keep the hero, project cards, navigation, and contact links legible and
  well-spaced on desktop and mobile layouts.

## Implementation constraints

- Deliver as one `index.html` file with inline CSS in a `<style>` block and
  vanilla JavaScript in a `<script>` block.
- Use inline HTML, CSS, and vanilla JavaScript with no frameworks, build tools,
  backend, or database. Three.js r0.143.0 from unpkg.com is the owner-approved
  sole external runtime dependency for the hero scene.
- Use semantic HTML, accessible text/link contrast, keyboard-operable controls,
  and appropriate focus and expanded-state indicators.
- Preserve the owner's confirmed name, professional title, email, GitHub, and
  LinkedIn details. Do not invent personal details or project URLs.
- The existing `index.html` is an unapproved draft; do not treat it as approved
  implementation.
