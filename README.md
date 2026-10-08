# RobotsTxtSurvey

If you found this page through the `RobotsTxtSurvey` User-Agent in your server logs, here is what happened.

- **What it fetched:** `/robots.txt` only, once, following at most 5 redirects. It never requests any other page and never reads page content.
- **Why:** a research survey of how websites use robots.txt (sitemap declarations, crawler rules). Your domain came from the public Tranco top-sites list or from public Certificate Transparency logs.
- **How fast:** at most one connection to your site at a time, with low overall request rates.

## Opt out

Open an issue on this repository with your domain name. It goes on the exclusion list, and future runs will never contact that domain or any of its subdomains.
