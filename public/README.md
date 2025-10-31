# Public Directory

This directory contains static assets that are served directly by Next.js.

## Usage

Files in the `public` directory are served from the root URL path (`/`).

## Common Assets

- **Images**: Logos, icons, illustrations (`/images/`)
- **Icons**: Favicons, app icons (`favicon.ico`, `icon.png`)
- **Documents**: PDFs, downloadable files
- **Manifest**: PWA manifest files (`manifest.json`)
- **Robots**: SEO files (`robots.txt`, `sitemap.xml`)

## Guidelines

- **Optimization**: Optimize images before adding them
- **Naming**: Use descriptive, kebab-case names
- **Organization**: Group related assets in subdirectories
- **Size**: Keep file sizes reasonable for web performance
- **Formats**: Use modern image formats (WebP, AVIF) when possible

## Example File Structure

```
public/
├── favicon.ico
├── icon.png
├── apple-icon.png
├── images/
│   ├── logo.svg
│   ├── hero-banner.jpg
│   └── icons/
├── documents/
│   └── user-guide.pdf
└── manifest.json
```

## Accessing Assets

```tsx
// In components
<img src="/images/logo.svg" alt="Logo" />
<link rel="icon" href="/favicon.ico" />

// Next.js Image component
import Image from 'next/image'
<Image src="/images/hero.jpg" alt="Hero" width={800} height={400} />
```
