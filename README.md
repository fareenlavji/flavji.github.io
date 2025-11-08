# flavji.github.io — Personal Brand Site

Welcome to the source repository for [flavji.github.io](https://github.com/flavji.github.io), the personal and professional website of **Fareen. Lavji**.

## 🎯 Purpose

This site serves as a central hub for:

- Showcasing personal projects, CV, and creative work
- Hosting the **Floidity** brand documentation and policy bundle
- Publishing accessible, standards-compliant content via GitHub Pages

## 📁 Repository Structure

### Root
- `index.html`, `CV.html`, `projects.html`, `misc.html`: Public-facing pages
- `assets/`, `vendor/`, `hackerthemes-neon-glow/`: Theme and styling resources
- `create_labels.py`, `create_repo_project.sh`: Automation scripts for GitHub Projects
- `.github/workflows/`: GitHub Actions for label creation and CSV task import
- `CNAME`: Custom domain configuration (`www.floidity.ca`)

### `docs/` — Floidity Documentation Hub
Contains all brand, policy, and launch documentation for the Floidity initiative.

Subdirectories:
- `branding/`: Brand guidelines, logo usage, typography, color palette
- `policy/`: Privacy, accessibility, security, licensing
- `content/`: YAML templates for projects, publications, resources
- `requirements/`: Scope, data models, governance, traceability
- `latex/`: LaTeX sources for PDF generation
- `outputs/pdfs/`: Generated PDFs
- `floidity_launch_tasks.csv`: GitHub Projects task import file
- `floidity_launch_checklist.md`: Markdown checklist for launch planning

### `floidity/` — Floidity Site Starter
A minimalist, accessible Bootstrap-based site for showcasing Floidity’s brand and policies.

- `index.html`: Floidity landing page
- `assets/`: Theme-specific CSS, JS, and image assets

## 🚀 Getting Started

To build and deploy:
1. Clone the repo and navigate to the root directory.
2. Run `make all` to generate PDFs from LaTeX sources.
3. Use GitHub Actions to automate label creation and task import.
4. Customize content in `docs/` and `floidity/` as needed.
5. Push changes to `main` to update GitHub Pages.

## 📬 Contact

For questions or contributions, reach out via GitHub or connect on [LinkedIn](https://www.linkedin.com/in/fareenlavji).

---

© 2025 Fareen. Lavji — All content and assets are protected under applicable copyright and trademark laws. Version November.08.2025

## Nitpicks
- [ ] Had to create a seperate `footer.css` to center all footage content
- [ ] Can't figure out how to reformat `hal-9000`

## Resources
- [x] Theme: [Neon Glow Hacker Bootstrap Theme](https://hackerthemes.com/bootstrap-themes/demo/neon-glow/)
