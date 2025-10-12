# AI Coding Agent Instructions for CocoButts417.github.io

## Project Overview
This is a static website project for CoachFD, focused on career planning, coaching, and related services. The site is built using plain HTML and CSS, with assets organized under the `assets/` directory. There is no build system, backend, or dynamic scripting—changes are made directly to HTML and CSS files.

## Directory Structure
- `index.html` — Main landing page
- `about.html`, `contact.html`, `services.html`, etc. — Individual service/info pages
- `assets/css/styles.css` — Main stylesheet for all pages
- `assets/img/stock/` — Image assets (logos, stock images)

## Key Patterns & Conventions
- **Consistent Layout:** All pages should use the same header, navigation, and footer structure as found in `index.html`. When creating or updating a page, copy the layout from `index.html` and update only the main content area.
- **Navigation:** The navigation bar links to all major pages. Update navigation in all files if adding/removing a page.
- **Styling:** All styling is handled in `assets/css/styles.css`. Do not create additional CSS files unless absolutely necessary.
- **Images:** Store all images in `assets/img/stock/`. Reference images using relative paths.
- **Meta Tags:** Each HTML file should include basic meta tags for charset, viewport, and description.
- **Footer Year:** The footer uses a small script to display the current year. Preserve this pattern when updating the footer.

## Developer Workflow
- **Editing:** Make changes directly to HTML and CSS files. No build or test steps are required.
- **Previewing:** Use a local web server or VS Code Live Server extension to preview changes. Ensure `<head>` and `<body>` tags are present for live reload to work.
- **Version Control:** Use Git for version control. New files will show as "U" (untracked) until added with `git add <filename>`.
- **Rollback:** To revert to the latest commit, use `git reset --hard HEAD` in the terminal.

## Examples
- To create a new service page, copy `index.html`, rename, and update the `<main>` content.
- To update navigation, edit the `<nav>` section in all HTML files.
- To add an image, place it in `assets/img/stock/` and reference it with `<img src="/assets/img/stock/imagename.png">`.

## External Dependencies
- No external JS frameworks or build tools are used. All code is static and self-contained.

---

For questions or unclear patterns, review `index.html` and `assets/css/styles.css` for canonical examples. If a convention is not documented here, follow the structure and style of these files.
