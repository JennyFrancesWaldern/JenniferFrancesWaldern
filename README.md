# JenniferFrancesWaldern

Personal portfolio site hosted on GitHub Pages.

## Site structure

All deployable files live in the `docs/` folder:

```
docs/
├── index.html                          ← single-page portfolio (tabbed: About / Resume / Projects / Contact)
└── assets/
    └── resume/
        ├── Jennifer_Waldern_AI_Architect_Resume.pdf
        └── Jennifer_Waldern_AI_Architect_Resume.docx
```

## Local preview

Open `docs/index.html` in a browser, or serve the `docs/` folder with any static file server:

```bash
npx serve docs
# or
python -m http.server 8080 --directory docs
```

## GitHub Pages configuration

In the repository **Settings → Pages**, set:

- **Source**: Deploy from a branch
- **Branch**: `main`
- **Folder**: `/docs`
