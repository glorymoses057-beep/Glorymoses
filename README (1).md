# Glory Moses Website

This repository holds the live website for glorymoses.co.

## What is in this repo

- `index.html`, the entire site (one page, with Home, About, Ventures, Values, and Contact sections)
- `glory-photo.jpeg`, the photo used in the hero section and referenced by the site's meta tags
- `sitemap.xml`, tells search engines about this page
- `robots.txt`, tells search engines they are allowed to crawl the site

## How the site is hosted

This repo is connected to GitHub Pages, deploying from the `main` branch, root folder.
The custom domain glorymoses.co points here through DNS records set at the domain registrar.

Any time you upload a new `index.html` to this repo and commit the change, the live site updates automatically within a minute or two. No separate deploy step needed.

## How to update content

1. Open `index.html` in this repo (or edit a local copy and re-upload it).
2. Find the text you want to change and edit it directly, it is plain HTML, the visible text sits between tags like `<h2>` and `</h2>`.
3. Commit the change. GitHub Pages redeploys automatically.

If you are not comfortable editing the HTML directly, it is easiest to describe the change you want and have it built as a new version of the file, then just replace the old `index.html` with the new one here.

## Things still marked as placeholders

Search `index.html` for `REPLACE-WITH-HANDLE`, currently used for the LinkedIn link (appears twice, once in the structured data near the top, once in the Contact section). Replace both with her real LinkedIn URL once that profile is set up.

## Contact form

The contact form on the site is visual only right now, it does not send messages. To make it functional, connect it to a form service such as Formspree, then update the form's action in `index.html` accordingly.

## Search Console

glorymoses.co is verified in Google Search Console. The sitemap above should be submitted there under Sitemaps, using `sitemap.xml` as the value.
