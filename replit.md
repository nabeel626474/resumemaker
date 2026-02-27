# resumemaker

A static HTML resume maker website.

## Project Structure

- `index.html` - Main landing page
- `about.html` - About page
- `contact.html` - Contact page
- `privacy.html` - Privacy policy page
- `terms.html` - Terms of service page
- `sitemap.xml` - Sitemap for SEO
- `favicon.ico` - Site favicon

## Running the Project

The site is served via Python's built-in HTTP server on port 5000:

```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment

Configured as a static site deployment with the root directory as the public directory.
