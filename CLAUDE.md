# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a GitHub profile repository for the user `daryllundy`. It serves as the special README.md that appears on the GitHub profile page at https://github.com/daryllundy.

## Repository Structure

```
.
├── README.md          # Main profile content displayed on GitHub profile
├── img/               # Assets for the profile
│   ├── header.svg           # Current profile header image
│   └── header-with-js.svg   # Alternative header with JavaScript
└── .gitignore         # Git ignore rules
```

## Working with This Repository

### Modifying Profile Content
- The `README.md` file is what displays on the GitHub profile page
- The file currently references `./img/header.svg?v=6` as the header image
- Any changes to README.md will be reflected on the GitHub profile after pushing

### SVG Assets
- Profile header images are stored in the `img/` directory as SVG files
- The current active header is `header.svg`
- SVG files can contain embedded JavaScript (see `header-with-js.svg`)
- When referencing images in README.md, use relative paths like `./img/header.svg`
- Version parameter (`?v=6`) can be incremented to bust GitHub's image cache

### Git Workflow
- Remote repository: `git@github-daryllundy:daryllundy/daryllundy.git`
- Main branch: `main`
- Standard git commands apply: `git add`, `git commit`, `git push`
