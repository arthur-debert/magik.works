# magik.works

Main Magik Works website, hosted on GitHub Pages.

## Structure

This repository contains the content for the [magik.works](https://magik.works) website.

## DNS Configuration

For the domain to work properly with GitHub Pages:

1. Add the custom domain in GitHub Pages settings
2. Configure your DNS provider with the following records:
   - A Records pointing to GitHub Pages IP addresses:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - CNAME record with name `www` pointing to `<username>.github.io`

## Local Development

To test locally:

```bash
bundle exec jekyll serve
```

This will serve the website on [http://localhost:4000](http://localhost:4000)
