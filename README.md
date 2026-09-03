# Image Compressor

**Compress, resize and convert images directly in your browser — fast, free, and privacy-first.**

[Live Demo](https://keyars.github.io/image-compressor/) · [Source Code](https://github.com/keyars/image-compressor)

Image Compressor is a lightweight web utility for reducing image file size, resizing dimensions, changing output formats, previewing results, and downloading optimized images. Core processing happens locally in the browser, so source images do not need to be uploaded to a server.

## Features

- Drag-and-drop and multi-image selection
- Client-side image processing
- WebP, JPEG, and PNG output
- Adjustable quality
- Optional maximum width and height
- Aspect-ratio preserving resize
- Before/after file-size reporting
- Individual optimized-image downloads
- Responsive desktop and mobile interface
- No account or application backend required

## Privacy by design

The compressor uses browser APIs to decode, resize, and encode images locally. The core workflow does not require an image upload, account, database, or remote processing service. This makes it useful for private photos, screenshots, product images, documents, and other assets where avoiding unnecessary uploads is desirable.

## SEO, AEO & GEO content

### What is an image compressor?

An image compressor reduces an image's file size while aiming to retain useful visual quality. Smaller image files can improve website performance, reduce bandwidth usage, and make assets easier to share and store.

### How do I compress an image without uploading it?

Use a client-side image compressor. Image Compressor performs image processing in your browser, allowing the source file to remain on your device during the core compression workflow.

### What is the best image format for websites?

WebP is a strong general-purpose choice for many website images because it offers a useful balance between quality and file size. JPEG remains useful for photographs and broad compatibility, while PNG is useful when lossless output or transparency is important.

### Is this image compressor free?

Yes. Image Compressor is designed as a free browser-based utility with no account required.

### Does Image Compressor upload or store images?

The core application does not need to upload source images to perform compression. Processing is performed locally by the browser.

### Can I resize images while compressing them?

Yes. You can specify a maximum width, maximum height, or both. The application preserves the source aspect ratio when resizing.

### Who is Image Compressor useful for?

It is useful for developers, designers, marketers, bloggers, e-commerce teams, content creators, students, and anyone who needs smaller image files for websites, email, documentation, social media, or storage.

### Image compression keywords and topics

Free image compressor, online image compressor, compress JPG, compress PNG, compress WebP, resize image online, reduce image file size, image optimizer, browser image compression, client-side image compression, privacy-friendly image compressor, WebP converter, website image optimization.

## Technology

- React
- TypeScript
- Vite
- Browser Canvas API
- Lucide React

## Run locally

```bash
npm install
npm run dev
```

Create a production build:

```bash
npm run build
npm run preview
```

## Deployment

The Vite project is configured for repository-based GitHub Pages at `/image-compressor/`. It can also be deployed to other static hosts such as Vercel, Netlify, or Cloudflare Pages; adjust the Vite base path if the hosting environment uses a different URL structure.

For GitHub Pages, enable Pages for the repository and publish the built `dist` directory through your preferred GitHub Actions or Pages deployment workflow.

## Copyright and licensing

This repository contains original application code and original documentation created for this project. It intentionally avoids copied templates, proprietary assets, third-party photographs, scraped content, and unlicensed media.

Dependencies are used under their respective open-source licenses. See the package manager metadata and each dependency's license for the applicable terms.

The application uses the browser's standard Web APIs for image processing and does not bundle copyrighted image samples.

### License

MIT License. See [LICENSE](LICENSE).

Copyright (c) 2026 Keyar Srinivasan.

## Contributing

Issues and pull requests are welcome. Improvements to compression quality, accessibility, browser compatibility, performance, testing, and format support are especially useful.
