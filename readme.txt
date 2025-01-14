=== Photocopier ===
Contributors: kjellr
Tags: photocopy, Gutenberg, blocks, filter, block style
Requires at least: 5.0
Tested up to: 5.8
Requires PHP: 5.2.4
Stable tag: trunk
License: GPL v2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Make your blocks look like photocopies.

== Description ==

This plugin adds a block style called "Photocopy" to the Image, Gallery, and Media & Text blocks. When applied, it roughly emulates the look of a high-contrast photocopy. 

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the "Plugins" screen in WordPress
3. Select an Image, Gallery, or Media & Text block. 
4. Using either the block switcher or the block settings, choose the \"Photocopy\" block style. 

== Frequently Asked Questions ==

= How does this work? =

The block style applies a handful of CSS filters to your images or text. It looks kind of like a photocopy. 

= Why are the text styles labeled experimental? =

These filters are a little unpredictable — different browsers render them in different ways. But hey, photocopiers are a little unpredictable too! It's more lifelike this way. 

= Are there any known issues? =

- The effect doesn't play great with Image block captions at the moment. The overlay pattern sometimes shows up behind the caption. 
- The warped styles cut off the resize drag handles.

= Can I contribute to this plugin? =

- Of course! It's open source. Visit the [GitHub repository](https://github.com/kjellr/photocopier) to browse the code or submit ideas. 

== Changelog ==
= 1.3 =
* Adds warped text effects for paragraph and header blocks. 

= 1.2 =
* Adds an experimental "Warped" block style.
* Improved rendering of the pattern on different screen resolutions. 

= 1.1 =
* Improved Pattern
* Fix the way the pattern maps to the image. 

= 1.0 =
* Initial Release
