# WeDrink Static Website

Static marketing and policy website for WeDrink, a cocktail app by Creative Star.

## Pages

- `/` - Home
- `/privacy/` - Privacy Policy
- `/terms/` - Terms of Service
- `/support/` - Support and FAQ

## Project Structure

```text
.
├── index.html
├── styles.css
├── app.js
├── server.js
├── privacy/
│   └── index.html
├── terms/
│   └── index.html
└── support/
    └── index.html
```

## Local Preview

This project does not require a build step. You can open `index.html` directly in a browser.

For cleaner local routing, run:

```bash
node server.js
```

Then open:

```text
http://127.0.0.1:5173/
```

## Deploy to Cloudflare Pages

1. Create a new Cloudflare Pages project.
2. Connect the Git repository that contains this folder.
3. Use the following build settings:

```text
Framework preset: None
Build command: leave blank or use exit 0
Output directory: /
```

4. Deploy the site.

## Before Publishing

Replace the placeholder support email everywhere:

```text
support@YOUR_DOMAIN.com
```

Recommended replacement example:

```text
support@wedrink.app
```
