# Nikita Hramyka - Personal Page

This repository contains a personal "About Me" page for Nikita Hramyka, designed to be a minimalist and modern hub linking to his resume, projects, and contact information.

## Project Structure

- `index.html`: The main "About Me" page, serving as a central hub.
- `resume.html`: A detailed CV/resume page, linked from `index.html`.
- `style.css`: Custom CSS for styling both `index.html` and `resume.html` (though `resume.html` has its own embedded styles).
- `favicon.ico`: Website favicon.

## How to View

To view the page, simply open `index.html` in your web browser.
For local development, you can use a simple HTTP server (e.g., `python -m http.server` or `npx http-server`).

## Instructions for AI Agents

This section outlines the preferred conventions and guidelines for future modifications to this project.

### General Principles

- **Language**: All user-facing text and comments should be in **English**.
- **Design Philosophy**: Maintain a **minimalist, clean, and modern** aesthetic. Focus on good typography, ample white space, and subtle animations. Avoid overly flashy or complex designs.
- **Consistency**: Ensure design elements (e.g., button styles, typography, spacing) are consistent across all pages.
- **No Bootstrap Classes for Styling**: While Bootstrap might be linked for basic structural elements, avoid using Bootstrap utility classes directly for styling (e.g., `btn btn-primary`). All custom styling should be in `style.css`.

### File Specific Guidelines

- **`index.html` (Main Page)**:
    - Should act as a hub.
    - Content: Profile picture, name, brief tagline/introduction, links to resume, projects, and contact information.
    - **No direct social media icons on this page.** Social links should be handled via a "Socials" link if desired, or directly within the "Contact Info" section.
    - **No copyright notice in the footer.**
- **`resume.html` (Resume Page)**:
    - Should contain the detailed CV.
    - Must include a "Return to Main Page" button, styled consistently with other buttons on that page.
- **`style.css`**:
    - All custom styling for `index.html` and `resume.html` (where not embedded) should reside here.
    - Use Google Fonts (Poppins for headings, Open Sans for body) and Font Awesome for icons.

### Specific Content Guidelines

- **Tagline**: Keep it concise and professional, highlighting key skills (e.g., ".NET Full-Stack Developer | React & Angular Expertise").
- **About Section**: Provide a brief, professional summary of experience and passion.
- **Contact Information**: Display clearly with appropriate icons (location, phone, email).
- **Project Links**: Link to external project pages (e.g., GitHub repositories).
- **Social Links**: If included, use clear icons and link to relevant profiles.
