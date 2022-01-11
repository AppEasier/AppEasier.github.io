# Easier App

![Homepage preview](./assets/images/screenshot.jpg)

## Requirements

- Ruby > 2.5
- Jekyll ~> 3.8

## Content Management


Any changes you make in Forestry is commited back to the repository and automatically deployed.

## Local development

```bash
# clone your imported repository
# cd in the project directory
# install dependencies
bundle
# Start local dev server
bundle exec jekyll serve --livereload --drafts
```

## Deployment and hosting

### GitHub Pages

Go to your repository settings and activate GitHub Pages in the root folder.

### Vercel

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/git)

Copy-paste your Git repository URL, accept default settings and click deploy ✨.

### Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/forestryio/jekyll-mundana-forestry)

1. Set the build command to: `jekyll build`
2. Set the publish directory to: `site`

That's it, now your site gets deployed automatically on `git push` or when saving documents from Forestry.

## Feedback

## LICENSE

[MIT](LICENSE)
