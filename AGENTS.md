# Repository Guidelines

## Project Structure & Module Organization

This repository is currently a small content workspace with two top-level deliverables:

- `AIRUUN_Microsite_Findings_and_TWF_Actions.md` contains the written findings and action recommendations.
- `AIRUUN_Storytelling_Presentation_TWF_Refined.html` contains the presentation-ready microsite deck in a single self-contained HTML file with inline CSS.

Keep related assets near the file that uses them, or add an `assets/` directory if images, fonts, or exports start to grow.

## Build, Test, and Development Commands

There is no checked-in build system or test runner. Use lightweight local validation:

- `open AIRUUN_Storytelling_Presentation_TWF_Refined.html` to review the presentation in a browser.
- `python3 -m http.server 8000` to preview the HTML over a local server if browser restrictions affect fonts or media.
- `npx prettier --check "*.md" "*.html"` to verify formatting if Prettier is available locally.

If new tooling is introduced, document the exact install and run commands here.

## Coding Style & Naming Conventions

Use clear, descriptive filenames in `PascalCase` or underscore-separated title form, matching the existing files. For Markdown, keep headings short and structure content with nested sections rather than long paragraphs. For HTML and CSS:

- Use 2-space indentation.
- Prefer semantic HTML elements and grouped CSS custom properties in `:root`.
- Keep inline styles and one-off overrides to a minimum.

## Testing Guidelines

No automated tests are present. Before submitting changes:

- Re-open the HTML presentation and check layout, typography, scroll behavior, and mobile responsiveness.
- Re-read Markdown for heading order, broken lists, and bilingual copy accuracy where applicable.
- If adding JavaScript or reusable assets, include a minimal validation workflow and note it in this file.

## Commit & Pull Request Guidelines

Git history is not available in the current working directory, so no repository-specific commit convention can be inferred. Use short imperative commit messages such as `Refine presentation typography` or `Update microsite findings`. Pull requests should include:

- A concise summary of content or design changes.
- Screenshots or exported previews for presentation changes.
- Notes on any manual review performed, especially browser and mobile checks.

## Content & Review Notes

Treat presentation copy, Thai text, and brand terminology as source material that requires exact review. Avoid broad rewrites unless requested, and verify tone consistency across both the Markdown brief and the HTML presentation.
