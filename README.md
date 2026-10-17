# bicss

### A Modular CSS Library for Everyone

**bicss** is a lightweight, modular CSS library designed to make web development simpler, more flexible, and easier to maintain.

Use only the modules you need. Combine them to build your own styling system without relying on a large, monolithic framework.

## Features

- **Modular** — Use each CSS file independently.
- **Lightweight** — Include only what your project needs.
- **Flexible** — Combine utility classes and components.
- **Easy to use** — Simple, consistent class names.
- **Customizable** — Adapt the styles to your project's needs.
- **Framework-independent** — Use with any HTML-based project.

## Installation

You can include individual modules directly from GitHub using raw CSS URLs.

For example, add the following to your HTML document:

```html
<link
    rel="stylesheet"
    href="https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/reset.css"
>
```

You can include additional modules in the same way.

## Available Modules

Each module has a specific purpose and can be used independently.

| Module | Description |
| --- | --- |
| [Reset](https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/reset.css) | Provides a consistent baseline for browser styles. |
| [Colors](https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/colors.css) | Provides color-related classes and theme styles. |
| [Layout](https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/layout.css) | Provides layout, display, flexbox, and grid utilities. |
| [Spacing](https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/spacing.css) | Provides margin, padding, and spacing utilities. |
| [Typography](https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/typography.css) | Provides text styling and typography utilities. |
| [Utilities](https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/utilities.css) | Provides general-purpose utility classes. |
| [Transitions](https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/transitions.css) | Provides transition properties, durations, and easing utilities. |
| [Components](https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/components.css) | Provides reusable UI component styles. |

## Usage

Include the modules you need in your HTML document.

```html
<head>
    <link
        rel="stylesheet"
        href="https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/reset.css"
    >
    <link
        rel="stylesheet"
        href="https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/colors.css"
    >
    <link
        rel="stylesheet"
        href="https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/layout.css"
    >
    <link
        rel="stylesheet"
        href="https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/spacing.css"
    >
    <link
        rel="stylesheet"
        href="https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/typography.css"
    >
    <link
        rel="stylesheet"
        href="https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/utilities.css"
    >
    <link
        rel="stylesheet"
        href="https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/transitions.css"
    >
    <link
        rel="stylesheet"
        href="https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/components.css"
    >
</head>
```

```
1. https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/reset.css
2. https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/colors.css
3. https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/layout.css
4. https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/spacing.css
5. https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/typography.css
6. https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/utilities.css
7. https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/transitions.css
8. https://raw.githubusercontent.com/bimaden/bicss/refs/heads/main/components.css
```

You do not need to include every module. Choose the files that fit your project.

## Design Philosophy

bicss follows a simple principle: **use what you need, keep what you use.**

The library is designed around modularity and composability. Layout, spacing, typography, colors, transitions, and components are organized into separate files so you can build a styling system that fits your workflow.

## Contributing

Contributions, suggestions, and bug reports are welcome.

If you have ideas for improvements, feel free to open an issue or submit a pull request.

## License

See the repository for license information.

---

**bicss** — Simple CSS. Modular by design.
