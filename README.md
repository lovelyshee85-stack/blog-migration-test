# blog-migration-test

Static migration test for **B06 — Everyday Digital Fixes**.

Purpose:
- verify clean HTTP delivery without Blogger mobile redirects
- verify crawlability and Google indexing
- validate a lightweight static deployment workflow before migrating B02–B06

Test article:
- `/how-to-find-file-you-just-saved-on-your.html`

After Cloudflare Pages assigns the production test URL, canonical tags and sitemap.xml should be added with that final hostname.
