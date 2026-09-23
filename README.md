# Best Final Year Engineering Projects

**Engineering Project Hub (EPG)** is a lightweight static GitHub Pages website for engineering students. Tagline: **Explore. Build. Learn.**

## Contents

- 300 numbered project records in [data/projects.json](data/projects.json), from EP-001 through EP-300.
- 128 keyword-focused guides plus project, category, and department directories.
- Responsive HTML/CSS with a small search script; no framework or build dependency is needed.
- SVG logo and favicon in [assets](assets).

## Architecture

Guides cover general engineering projects, CSE, AI/ML, Python, IoT, IEEE, web development, data science, cybersecurity, computer vision, cloud/DevOps, embedded systems, smart agriculture, healthcare, and sustainability. Every guide has unique SEO metadata, a canonical URL, an H1, student-focused introduction, project shortlist, implementation checkpoints, difficulty and department context, related internal links, FAQs, and one relevant CodeSelf Projects contextual link.

The project database fields are id, title, category, departments, difficulty, summary, problem, solution, technologies, modules, implementation, expected_output, future_scope, and keywords.

## GitHub Pages

The site uses the repository-safe base URL https://codeselfinfotech.github.io/best-final-year-engineering-projects/. In GitHub, open **Settings > Pages**, select **Deploy from a branch**, choose the default branch and / (root), then wait for Pages to publish. Regenerate with node generate-site.js.

## Extending

Add a concept to concepts to create the next complete project record. Add a category to domains with a slug, display name, technologies, departments, and verified CodeSelf destination. Add a high-intent guide to special, or add a new intent to intents. Run node validate-site.js after changes.

## External link policy

CodeSelf Projects URLs are kept in the external map and used contextually by topic. The site does not create sitewide promotional blocks or invent destination URLs.
