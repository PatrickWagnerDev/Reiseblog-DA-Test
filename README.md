# World Travel Blog — Patrick Branch

A contributor branch of the World Travel Blog frontend bootcamp group project.

This branch contains the travel article developed by PatrickWagnerDev. The implemented page focuses on Pattaya, Thailand and presents the destination in a responsive travel-blog article layout.

The repository is part of a frontend development bootcamp group exercise designed to simulate collaborative development practices similar to those used in real software and open-source projects.

## Branch Scope

`Patrick-branch` is the personal development branch assigned to [PatrickWagnerDev](https://github.com/PatrickWagnerDev).

Patrick's primary responsibility in this branch is:

* `Patrick.html`
* `styles/style_patrick.css`

The shared `index.html` and `style.css` remain collaborative team files.

At the current stage, Patrick's individual article is substantially implemented while the shared landing page and the other contributors' personal pages are not implemented in this branch.

## Current Implementation

The main implementation in this branch is `Patrick.html`, a travel article about Pattaya, Thailand.

The page currently includes:

* A branded header
* Navigation back to sections of the shared landing page
* A hero/article introduction
* Article metadata
* An author profile
* Responsive article content
* A rain-period graphic
* Beach activity statistics
* Accommodation expense statistics
* A sharing section
* External LinkedIn and WhatsApp sharing links
* A footer with external social-media links
* A dedicated mobile navigation bar
* Responsive layouts for multiple viewport sizes

The article headline currently presents Pattaya under the title:

`Pattaya Pulse: Food, Sun and Neon Nights`

## Content Status

The page combines implemented interface content with placeholder copy.

Several structural sections, headings, graphics, navigation elements, and UI components are already present. Some body-text sections still contain `Lorem ipsum` placeholder content and should therefore be considered unfinished editorial content.

The footer also contains placeholder links for:

* Imprint
* Cookie Preferences

These currently point to `#` rather than dedicated pages.

The social-media footer links point to the public homepages of the respective services rather than project-specific social profiles.

## Responsive Design

`styles/style_patrick.css` contains an extensive responsive implementation.

The layout adapts across several screen-size ranges, including desktop, tablet, and mobile widths.

Responsive behavior includes:

* Reorganizing multi-column areas into vertical layouts
* Resizing typography
* Adjusting content padding
* Resizing statistics and graph elements
* Moving the author section into a full-width layout on smaller screens
* Replacing the regular navigation with a mobile navigation bar
* Displaying the mobile navigation as a sticky bar at the bottom of the viewport
* Switching between alternative metadata and sharing layouts

The stylesheet includes dedicated media queries covering multiple ranges down to mobile widths beginning at 320px.

## Page Structure

The implemented `Patrick.html` page can be summarized as:

```text
Patrick.html
├── Header
│   ├── Travel Blog logo
│   └── Desktop navigation
├── Main
│   ├── Hero
│   │   ├── Article introduction
│   │   ├── Article metadata
│   │   └── Author card
│   ├── Article text
│   ├── Rain periods graphic
│   ├── Article text
│   ├── Statistics
│   │   ├── Popular beach activities
│   │   └── Accommodation expenses
│   ├── Article text
│   └── Follow and share section
├── Small-screen fallback element
├── Footer
│   ├── Copyright and legal navigation
│   └── Social-media links
└── Mobile navigation
```

## Technology

The implementation uses:

* HTML5
* CSS3
* CSS custom properties
* CSS media queries
* Responsive layouts
* Local image assets
* Local icon assets
* Local font assets
* Git
* GitHub

The branch does not rely on a JavaScript framework, CSS framework, package manager, or build system.

## Project Structure

```text
Reiseblog-DA-Test/
├── assets/
│   ├── fonts/
│   ├── icon/
│   └── image/
├── styles/
│   ├── fonts.css
│   ├── standard.css
│   ├── style_patrick.css
│   └── variables.css
├── index.html
├── Patrick.html
├── Neelima.html
├── Jin.html
├── style.css
└── README.md
```

## Important Files

### `Patrick.html`

Contains Patrick's implemented Pattaya travel article and its semantic page structure.

It references shared styling resources as well as the dedicated Patrick stylesheet.

### `styles/style_patrick.css`

Contains the page-specific styling and responsive behavior for `Patrick.html`.

The stylesheet is significantly more developed than the shared `style.css` currently present in this branch and includes dedicated breakpoint handling for desktop, tablet, and mobile layouts.

### `assets/`

Contains the local resources used by the Pattaya page.

The directory is separated into:

```text
assets/
├── fonts/
├── icon/
└── image/
```

The article uses these assets for elements such as:

* Travel Blog branding
* Article metadata
* Author imagery
* Statistical graphics
* Sharing controls
* Footer links
* Mobile navigation

### `index.html`

The shared landing page currently contains only the basic HTML document structure and stylesheet references. Its `<body>` is still empty in this branch.

### `style.css`

The shared landing-page stylesheet is currently empty in this branch.

### `Neelima.html` and `Jin.html`

These belong to the other project contributors and are not implemented as part of Patrick's responsibility in this branch.

## Team Responsibilities

| Contributor                                             | Responsibility                             | Working Branch   |
| ------------------------------------------------------- | ------------------------------------------ | ---------------- |
| [PatrickWagnerDev](https://github.com/PatrickWagnerDev) | `Patrick.html`, `styles/style_patrick.css` | `Patrick-branch` |
| [Neelimarani-git](https://github.com/Neelimarani-git)   | `Neelima.html` and its associated CSS      | `Neelima`        |
| [JinSooJang-DA](https://github.com/JinSooJang-DA)       | `Jin.html` and its associated CSS          | `Jin-branch`     |
| All contributors                                        | `index.html`, `style.css`                  | Collaborative    |

Some shared visual elements may also originate from collaboration between team members. For example, the header markup in `Patrick.html` contains an attribution indicating that part of the header design was created by Jin Soo Jang.

## Branch Workflow

The project separates individual development from integration and publication.

```text
Patrick-branch ─┐
Neelima ────────┼──> dev ──> main
Jin-branch ─────┘
```

### `Patrick-branch`

Used by PatrickWagnerDev to develop and maintain Patrick's individual travel page.

### `Neelima`

Used by Neelimarani-git for Neelima's individual page.

### `Jin-branch`

Used by JinSooJang-DA for Jin's individual page.

### `dev`

Acts as the integration branch where the contributors' work can be merged before publication.

### `main`

Represents the consolidated or published state after integrated changes are ready.

## Current Limitations

The following items are visible in the current branch and should not yet be considered finished production functionality:

* Parts of the article still use placeholder text.
* The shared landing page is still empty.
* The shared `style.css` is still empty.
* Other contributor pages are not implemented in this branch.
* Imprint and cookie-preference links are placeholders.
* Social links lead to general third-party websites.
* Read and share counts are static page content rather than dynamically tracked data.
* No JavaScript-based sharing, analytics, backend, or content-management functionality is present.

## Project Context

World Travel Blog is an educational group project created during a frontend development bootcamp.

The repository intentionally follows a collaborative branch structure similar to a real development project, while the application itself remains a learning exercise rather than a production travel platform.

This README documents the actual implementation present in `Patrick-branch` and does not treat planned or unmerged work from other branches as completed functionality.
