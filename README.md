# Blayne Griffin's website

A simple static HTML website hosted with GitHub Pages. The `site/` folder is the website and the only folder published by the workflow in `.github/workflows/static.yml`.

## Deployment setup

In the repository's **Settings → Pages**, enable GitHub Pages and select **GitHub Actions** as the build and deployment source. A repository administrator must do this before the workflow can deploy.

If the deploy job fails at **Setup Pages** with “Get Pages site failed” or a 404, check this setting, then re-run the workflow from the **Actions** tab. The default workflow token cannot enable Pages automatically.
