# CDN Creating

This repository is used for practicing and testing CDN-hosted static files through jsDelivr.

## GitHub Repository

Repository:

```text
https://github.com/Khan-Fazal-sys/cdn_creating
```

## CDN URL

The CSS file is publicly available through jsDelivr CDN:

```text
https://cdn.jsdelivr.net/gh/Khan-Fazal-sys/cdn_creating@main/style.css
```

## Purpose

* Practice creating CDN-hosted assets.
* Test Content Security Policy (CSP) configurations.
* Test Subresource Integrity (SRI).
* Serve static CSS files through a globally distributed CDN.
* Learn GitHub and jsDelivr integration.

## Notes

* The content of `style.css` is currently based on Bootstrap CSS and is used for learning and testing purposes.
* jsDelivr automatically serves files directly from the GitHub repository.
* The CDN remains available even when the GitHub website or jsDelivr website is closed in the browser.
* For production use, versioned tags are recommended instead of the `main` branch.

Example versioned URL:

```text
https://cdn.jsdelivr.net/gh/Khan-Fazal-sys/cdn_creating@v1.0.0/style.css
```
