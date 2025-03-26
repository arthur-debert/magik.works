# Magik Works Personal Website

This is my personal website built with Jekyll and hosted on GitHub Pages.

## Development

### Prerequisites

- Ruby (version 2.5.0 or higher)
- Bundler

You can install dependencies using Homebrew:

```bash
# Install dependencies from Brewfile
brew bundle
```

### Setup

```bash
# Install dependencies
bundle install

# Start the development server
bundle exec jekyll serve
```

The site will be [available at](http://localhost:4000)

### Adding Content

- Add or modify pages directly in the root directory with the appropriate
  frontmatter

## Deployment

The site is automatically built and deployed when changes are pushed to the main
branch.

### How GitHub Pages Works

GitHub Pages automatically generates HTML from your Jekyll site when you push to
your repository:

1. Push your changes to the main branch of your repository
2. GitHub automatically runs Jekyll to build your site
3. The generated HTML is served at your GitHub Pages URL
   (username.github.io/repository-name)

You don't need to generate the HTML yourself or commit any built files. GitHub
Pages handles the build process entirely on their servers.

### Important Note

When using GitHub Pages, make sure you're using compatible plugins and themes.
Not all Jekyll plugins are supported by GitHub Pages. See the
[GitHub Pages documentation](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll#plugins)
for more details.
