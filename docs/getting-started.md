# Getting Started

This guide will help you get the Stellar template up and running.

## Local Development

Since this template uses standard HTML/CSS/JS, you can run it locally using any basic HTTP server.

For example, if you have Python installed:
```bash
python -m http.server
```

Or using Node.js:
```bash
npx serve
```

## GitHub Pages Deployment

The repository includes a pre-configured GitHub Actions workflow (`.github/workflows/deploy.yml`) that automatically deploys the `main` branch to GitHub Pages.

### Enabling GitHub Pages

1. Navigate to your repository on GitHub.
2. Go to **Settings** > **Pages**.
3. Under **Build and deployment**, change the **Source** to **GitHub Actions**.
4. Push any change to the `main` branch, and the action will automatically build and publish your site!
