# Reusable UI Components

A growing collection of reusable, accessible UI components built while I learn and refine modern front-end engineering.

This repository begins with Vanilla HTML, CSS and JavaScript components. React and TypeScript and other tool implementations will be added as I rebuild and deepen my understanding of each pattern.

## Goals

- Build components from first principles.
- Learn the reasoning behind structure, styling, behavior, and accessibility.
- Document what each component does and what it can be adapted.
- Rebuild selected components in React and TypeScript.

## Component Library


| Component | Vanilla | React | Key concepts |
| -------- | -------- | -------- | --------- |
| Scroll-snap slider | Planned | Planned | CSS Scroll snap, responsibe layout, keyboard support | 


## Repository Structure

```text
reusable-ui-components
|- vanilla/
|   |- component-name/
|       |- index.html
|       |- styles.css
|       |- script.js
|       |- README.md
|- react.js/
|   |- component-name/
|       |- ComponentName.tsx
|       |- ComponentName.css
|       |- README.md
```

## How each component documented

Each component folder should explain:

1. **Purpose** - What problem does it solve?
2. **Preview** - A screenshot GIF, or deployed demo link.
3. **How to use** - Files to a copy and setup steps.
4. **Key concepts** - Important HTML, CSS, JavaScript, or React ideas.
5. **Accessibility** - Keyboard behavior, labels, focus, and reduced-motion support.
6. **Customization** - Colors, spacing, content breakpoints, and variants.
7. **Learning notes** - What I learned by building or auditing it.

## Engineering conventions

- Use semantic HTML before adding ARIA.
- Design for keyboard and touch input form the beginning.
- Prefer native browser features before adding dependencies.
- Keep components focused, readable, and responsive.
- Use kebab-case for folders and files.
- Create one focused branch per change.
- Write descriptive commits, such as feat: add vanilla modal dialog.

### Learning Path

1. Build the vanilla version.
2. Audit and document how it works.
3. Improve its accessibility and responsive behavior.
4. Rebuild the same component in React and TypeScript.
5. Compare the two implementations and document the trade-offs.

### Status

This is an active learning repository. Components will be added deliberately, reviewed, and improved over time.