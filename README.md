# Multi-Domain GitHub Pages Repository

This repository hosts multiple websites served from different domains:

- [magik.works](https://magik.works) - Main Magik Works website
- [debert.xyz](https://debert.xyz) - Arthur Debert's personal website
- [txxt.is](https://txxt.is) - Text and writing projects

## Structure

Each domain has its own directory in the repository:

- `/magik.works/` - Content for magik.works
- `/debert.xyz/` - Content for debert.xyz
- `/txxt.is/` - Content for txxt.is

## DNS Configuration

For each domain to work properly with GitHub Pages:

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
cd <domain-directory>
bundle exec jekyll serve
```

This will serve the specific domain's content on http://localhost:4000
