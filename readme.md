# Blur Text Wordpress Plugin

Blur Text with a shortcode.  Unblur with a click or hover.  Specify a blur color.

## Description

Visit the [Wordpress Plugin Directory](https://wordpress.org/plugins/blur-text/screenshots/) for screenshots and to download the latest version.

Use the shortcode [blur][/blur] to blur text.

For example:
[blur]This text will be blurred[/blur]

Optionally, you can set the blur to be removed when the user clicks or hovers on it.

Here are the shortcode examples for that:

[blur toggle=click]This text will be blurred until it's clicked on[/blur]

[blur toggle=hover]This text will be blurred until it's hovered over[/blur]

Be default, the blurred text color will be black.  You can specify a different color like this:

[blur color=orange]This text will be orange, even when blurred.[/blur]

[blur color=#00FF00]This text will be green, even when blurred.[/blur]

This plugin uses the CSS3 feature "text-shadow" to create the blur and a transparent color font.

## Installation

1. Install the plugin in wp-content\plugins
2. Activate the Plugin
3. Use one of these shortcodes around your text:
[blur][/blur]
[blur toggle=click][/blur]
[blur toggle=hover][/blur]
