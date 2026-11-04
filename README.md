# GitHub Pages verification host

Serves ownership verification files for Google Search Console, Bing Webmaster Tools and Yandex Webmaster, plus the host-level robots.txt.

The documentation remains at https://razdva122.github.io/clean-your-tv-lg-webos/ and is built from its own repository. Do not copy or relocate its content here. The root page is excluded from indexing to avoid a competing landing page; crawling the documentation is allowed.

Publish directly from the main branch root through GitHub Pages. Keep verification files and meta tags after successful verification. No analytics, tracking or recurring submissions are installed. The additional TXT file is the public IndexNow ownership proof.

## Initial setup — 2026-11-04

- GitHub Pages serves this host from `main` at `/`; the existing project documentation URL is unchanged.
- Google Search Console verified both the host and documentation URL-prefix properties. The existing 72-URL sitemap was submitted. Its first processing showed "Could not fetch/read" without a detailed reason; HTTP retrieval and XML parsing succeed. An indexing request for the English documentation home was accepted. Submission is not proof of indexing.
- Bing Webmaster Tools verified the host and accepted the existing sitemap; processing is pending.
- Yandex Webmaster verified the host. Its Sitemap tool is currently read-only, so manual sitemap submission is unavailable. The host robots.txt advertises the existing sitemap. A direct IndexNow POST to Yandex with 72 documentation URLs returned HTTP 202 and `success: true`; ownership-key validation and crawling are pending.
- Verified HTTP 200 for the host root, robots.txt, Google verification file, IndexNow ownership file, existing documentation root and sitemap. The sitemap has 72 unique URLs across 12 languages.

Keep these dated observations separate from current indexing coverage, which can be checked in the connected webmaster accounts. No ongoing monitor is installed.
