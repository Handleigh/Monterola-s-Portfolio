# Portfolio Tasks

## Planning

- [x] Record the owner's confirmed name, professional title, email, GitHub, and
  LinkedIn details in `requirements.md`.
- [x] Specify exactly two featured projects consistently across the planning
  documents, with confirmed descriptions and status labels.
- [x] Make project links optional and avoid exposing or inventing unavailable
  project URLs.
- [x] Preserve the approved Creative Modern direction and the single-file
  `index.html` implementation requirement.
- [x] Review and correct `design.md`, `requirements.md`, and `tasks.md` for
  consistency.
- [x] Get owner approval for the Vortex & Tunnel integration and its Three.js
  r0.143.0 CDN dependency.

## Implementation

- [x] Integrate the Vortex & Tunnel scene as a fixed background behind the
  existing one-page portfolio without replacing its content or layout.
- [x] Keep all CSS in an inline `<style>` block and all JavaScript in an inline
  `<script>` block; use vanilla JavaScript and only the approved Three.js CDN
  dependency for the scene.
- [x] Preserve the Creative Modern design, responsive and accessibility
  requirements, and optional-project-link policy.
- [x] Do not expose private project source or invent personal information,
  project details, or URLs.

## Testing (after implementation)

- [x] Test responsive layouts, mobile navigation, and scene behavior.
- [ ] Check reduced-motion and WebGL fallbacks, accessibility, required content,
  links, HTML validity, horizontal overflow, and mobile performance.