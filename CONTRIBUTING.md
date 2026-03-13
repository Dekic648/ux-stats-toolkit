# Contributing to UX Research Statistics Toolkit

Thanks for your interest in contributing! This toolkit exists because UX researchers deserve better stats tools — and it gets better with every contribution.

## Ways to contribute

### Suggest a new tool
Have a statistical method or workflow that UX researchers need but can't easily find? [Open a "New Tool Proposal" issue](../../issues/new?template=new-tool.yml) and describe the problem it solves.

### Report a bug
Found a calculation error, broken layout, or something that doesn't work on your device? [Open a "Bug Report" issue](../../issues/new?template=bug-report.yml). Include your browser and a screenshot if possible.

### Improve an existing tool
Want to make a tool clearer, more accurate, or better looking? Fork the repo, make your changes, and open a pull request.

### Fix a typo or improve copy
Even small improvements matter. If you spot awkward wording, unclear labels, or jargon that could be simpler — PRs are welcome.

---

## How each tool is built

Every tool follows the same architecture:

- **Single HTML file** — one file per tool, no build step
- **Inline CSS + vanilla JS** — no frameworks, no dependencies
- **Client-side only** — nothing is sent to a server, ever
- **Stakeholder-ready output** — tools generate sentences that can be pasted into reports

When contributing a new tool or modifying an existing one, please stick to this pattern.

## Setting up locally

```bash
git clone https://github.com/Dekic648/ux-stats-toolkit.git
cd ux-stats-toolkit
open index.html
```

That's it. No `npm install`, no build commands. Open the HTML file in your browser and you're running.

Each tool lives in its own repo under the [Dekic648](https://github.com/Dekic648) GitHub account. The landing page (this repo) links to all of them.

## Pull request guidelines

1. **Keep it simple** — match the existing style. No frameworks, no build tools.
2. **Test in both light and dark mode** — all tools support `prefers-color-scheme`.
3. **Test on mobile** — tools should work on screens as small as 360px wide.
4. **Show your math** — if your tool performs a statistical calculation, reference the method in a comment or in the tool's attribution section.
5. **One tool per PR** — makes review easier.

## Code style

- Semantic HTML, minimal nesting
- CSS custom properties for theming (see `index.html` for the variable system)
- Vanilla JS — no jQuery, no React, no TypeScript
- Accessible: proper labels, sufficient contrast, keyboard-navigable

## Questions?

Open an issue with the "Question" label. No question is too basic — this toolkit is for researchers, not engineers.
