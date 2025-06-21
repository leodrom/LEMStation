# LEM Station Static Site

This repository contains the exported HTML, CSS, and JavaScript files for the **LEM Station** website. The pages were generated with Tilda and can be served as a static site.

## Purpose

The project provides a snapshot of the LEM Station web presence in both Ukrainian and English. It includes landing pages, blog posts, interviews and other informational sections.

## Deployment

1. Upload the repository contents to your web server.
2. If you are using Apache, rename `htaccess` to `.htaccess` so that the rewrite rules and custom start page work.
3. When serving from GitHub Pages, `.htaccess` is ignored. Add a `.nojekyll` file so the site is served as static HTML. The provided `index.html` then redirects to `page8455448.html` so that `https://leodrom.github.io/LEMStation` opens the correct home page.
4. Ensure your server uses `page8455448.html` as the start page (either via `.htaccess` or the redirect).

## Editing

You can edit any of the HTML files directly or update them in Tilda and export again. The main pages include:

- `page8455448.html` – Ukrainian home page
- `page13543016.html` – English home page
- `page8658789.html` – About LEM
- `page8673485.html` – Blog
- `page8676746.html` – Interview
- `page14663992.html` – Проекти (Projects)

Other pages under `page*.html` correspond to additional sections such as contacts, events and timelines.

After making changes upload the updated files and `htaccess` again.
