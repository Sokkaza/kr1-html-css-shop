# Repository Instructions

## Project Shape
- This is a static, multi-page HTML/CSS/JavaScript learning project deployed through GitHub Pages.
- Keep the site framework-free and avoid adding build tools, dependencies, or a backend unless explicitly requested.
- The pages are `index.html`, `catalog.html`, `product.html`, `order.html`, and `contacts.html`.
- Shared styles belong in `css/style.css`; the small homepage interactions belong in `js/main.js`.
- Use relative paths so the pages continue to work on GitHub Pages.

## Code Conventions
- Keep user-facing content in Russian and preserve `<html lang="ru">`.
- Use semantic HTML elements and accessible names/labels; retain keyboard focus visibility and native form validation.
- Follow the existing BEM-style class naming, such as `block__element` and `block--modifier`.
- Reuse the shared header, navigation, footer, and existing CSS variables/utilities instead of introducing duplicate patterns.
- Match the existing two-space indentation in HTML, CSS, and JavaScript.
- Keep JavaScript dependency-free and scoped to interactions already supported by the page markup.

## Validation
- There is no build or test command. For UI changes, check the affected page in a browser and verify shared navigation and responsive layout where relevant.
- For form or dialog changes, verify keyboard use, browser validation, and the success/close behavior.
- Update `README.md` when project structure, features, or usage instructions change.