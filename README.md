# robots.txt and llms.txt Generator

A single-file browser tool that generates a robots.txt naming the major AI crawlers and an llms.txt skeleton that points AI answer engines at your key pages.

**Live demo:** https://0xelitesystem.github.io/robots-llms-txt-generator/

## What it does

Enter your site URL, choose which named AI crawlers to allow, set your disallow paths, and provide a brand name and description. The tool produces two files. The robots.txt lists the sitemap at the top, sets site-wide rules with a wildcard block, and allows each named AI crawler explicitly. The llms.txt follows the standard skeleton: an H1 brand name, a one-line blockquote, a short summary paragraph, and sectioned link lists you fill in with your real pages.

## Why name the crawlers

A wildcard rule alone leaves AI crawler access ambiguous. Naming each crawler and allowing it explicitly states your intent clearly, and every crawler you do not name is a surface where your brand may not be readable. The default is to allow the named AI crawlers unless you have a specific reason to block one.

## How to use it

Open `index.html` in any browser, or use the hosted GitHub Pages version. Adjust the inputs, switch between the robots.txt and llms.txt tabs, and copy each file to your site root. Replace the example llms.txt links with your real pages and write each description specific to what that page answers.

## Privacy

Runs entirely in your browser. No network calls, no analytics, no data stored.

## License

MIT. Copyright 0xelitesystem 2026.
