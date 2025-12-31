=== Saddam Hossen WebP Optimizer ===
Contributors: saddamweb
Tags: webp, image optimization, performance, compression, core web vitals
Requires at least: 5.0
Tested up to: 6.9
Requires PHP: 7.4
Stable tag: 1.1.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html
Donate link: https://www.buymeacoffee.com/iamsaddamhossen

High-performance, zero-cost image optimization. Converts images to WebP locally without external APIs.

== Description ==

**Stop paying for image optimization services.** This plugin converts your images to WebP format entirely on your server – no API keys, no monthly fees, no limits.

= Why This Plugin? =

Most image optimization plugins send your images to external servers, raising privacy concerns and subscription costs. This plugin:

* ✅ Runs entirely on your server (100% privacy)
* ✅ Zero ongoing costs (no API subscriptions)
* ✅ Unlimited conversions
* ✅ Faster processing (no external API calls)

= Features =

* **Auto-Convert on Upload** – Automatically converts JPG, PNG, and GIF to WebP
* **Smart Resizing** – Reduces oversized images to web-friendly dimensions (default 1920px)
* **Manual Conversion Tool** – Bulk convert existing images from Media Library
* **EXIF Auto-Rotation** – Fixes incorrectly rotated mobile photos
* **Intelligent Fallback** – Only replaces original if WebP is smaller
* **Quality Control** – Adjustable compression settings (1-100%)

= Performance Benefits =

* 🚀 Improves Core Web Vitals scores
* 📈 Passes Google's "next-gen formats" audit
* 💾 Reduces storage by up to 80%
* ⚡ Faster page loads (especially mobile)
* 💰 Lower hosting and backup costs

= System Requirements =

* PHP 7.4 or higher
* PHP Imagick extension enabled
* WordPress 5.0 or higher

= Privacy & Data =

This plugin processes all images locally. Nothing is sent to external servers. Your images stay on your server.

== Installation ==

1. Upload the plugin files to `/wp-content/plugins/sh-webp-optimizer`
2. Activate the plugin through the 'Plugins' screen
3. Go to Settings > Media to configure quality and dimensions
4. Upload new images or use the bulk converter for existing images

== Frequently Asked Questions ==

= Does this require an API key? =

No. Everything runs on your server using PHP Imagick.

= Will this work on shared hosting? =

Yes, if your host has Imagick enabled. Most quality hosts include it.

= What if Imagick is not installed? =

The plugin will display an admin notice with instructions for your host.

= Can I convert existing images? =

Yes. Each image in the Media Library gets a "Convert to WebP" button.

= What if WebP is larger than the original? =

The plugin keeps the original and skips conversion automatically.

= Does this work with multisite? =

Yes, it's multisite compatible.

== Screenshots ==

1. Settings panel in Media settings
2. Manual conversion button in Media Library
3. Before/After file size comparison
4. Core Web Vitals improvement

== Changelog ==

= 1.0.0 =
* Initial release
* Auto-convert on upload
* Manual bulk conversion
* Smart resizing
* EXIF auto-rotation
* Quality settings

== Upgrade Notice ==

= 1.0.0 =
Initial release.

== Developer Notes ==

This plugin uses PHP Imagick for high-quality, fast conversions. For development or contributions, visit:
https://github.com/iamsaddamhossen/sh-webp-optimizer

**Developed by [Saddam Hossen](https://saddamhossen.dev)**

== Donations ==

If you find this plugin useful and want to support its development, you can buy me a coffee!
Donate here: https://www.buymeacoffee.com/iamsaddamhossen