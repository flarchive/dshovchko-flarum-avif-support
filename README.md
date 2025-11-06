# Flarum AVIF Support

[![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Latest Stable Version](https://img.shields.io/packagist/v/dshovchko/flarum-avif-support.svg)](https://packagist.org/packages/dshovchko/flarum-avif-support)

A Flarum extension that adds support for AVIF image format in posts.

## Features

- ✅ Automatically recognizes `.avif` URLs as images
- ✅ Enables preview for AVIF images
- ✅ Works with Autoimage and Markdown
- ⚠️ Image dimensions require PHP 8.2+ (AVIF support in `getimagesize()`)

## Requirements

- Flarum ^1.0
- PHP 8.2+ (recommended for full functionality with image dimensions)

## Installation

```bash
composer require dshovchko/flarum-avif-support
```

## Usage

Once enabled, simply paste AVIF image URLs in your posts:

```
https://example.com/image.avif
```

Or use Markdown:

```markdown
![Alt text](https://example.com/image.avif)
```

## Compatibility

- Works with `dshovchko/flarum-image-dimensions` extension
- PHP 8.1: AVIF images display but dimensions may not be detected
- PHP 8.2+: Full support including automatic dimension detection

## Links

- [GitHub Repository](https://github.com/dshovchko/flarum-avif-support)
- [Packagist](https://packagist.org/packages/dshovchko/flarum-avif-support)
- [Flarum Community](https://discuss.flarum.org)

## License

[MIT](LICENSE)
