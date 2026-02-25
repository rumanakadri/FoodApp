# Copilot Instructions for FoodApp Homepage Workspace

## Overview
This workspace is a static web project for a food-related application, containing multiple HTML pages and a shared CSS file. There are no build tools, frameworks, or backend integrations present.

## Project Structure
- `homepage.html`: Main landing page for the app.
- `aboutpage.html`: Information about the app or business.
- `loginpage.html`: User authentication entry point.
- `style.css`: Shared stylesheet for all pages.
- `Images/`: Directory for image assets used across pages.

## Key Patterns & Conventions
- All HTML files reference `style.css` for consistent styling.
- Images are stored in the `Images/` folder and referenced with relative paths (e.g., `Images/food.jpg`).
- Navigation between pages is handled via `<a href="...">` links; no JavaScript routing.
- Keep page layouts consistent: use similar header/footer structures across HTML files.
- Use semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<footer>`) for accessibility and maintainability.

## Developer Workflows
- No build or test commands: edit HTML/CSS directly and refresh in browser to view changes.
- Debug by opening HTML files in browser and using browser dev tools.
- To add new pages, create a new `.html` file, link `style.css`, and add navigation links in all relevant pages.
- To update styles globally, edit `style.css`.

## Integration Points
- No external dependencies or scripts are present.
- All assets are local; ensure new images are placed in `Images/` and referenced correctly.

## Examples
- To add a new menu page:
  1. Create `menupage.html`.
  2. Link `style.css` in the `<head>`.
  3. Add navigation links in `homepage.html`, `aboutpage.html`, etc.
  4. Place menu images in `Images/`.

## References
- See `homepage.html` for main layout and navigation structure.
- See `style.css` for styling conventions.
- See `Images/` for asset organization.

---

If any section is unclear or missing important project-specific details, please provide feedback to improve these instructions.