---
layout:     post
title:      Five WordPress Plugins We Love
date:       2013-06-13
summary:    We build many sites in WordPress. Plugins are little third-party WordPress applications that can provide a quick and inexpensive way to solve problems and provide complex functionality without incurring the cost of custom programming. While it can slow a site down and cause problems to have too many plugins installed there are a number of plugins that provide some really neat effects and functionality, and almost always work great.
categories: wordpress-resource
---

By <a href="https://plus.google.com/u/1/105617426521194863864?rel=author">Benjamin Robinson</a>

***

We build many sites in WordPress. Plugins are little third-party WordPress applications that can provide a quick and inexpensive way to solve problems and provide complex functionality without incurring the cost of custom programming. While it can slow a site down and cause problems to have too many plugins installed (plugins are all built by different authors at different times -- conflicts between them are common) there are a **number of plugins that provide some really neat effects and functionality,** and almost always work great.

These are our top five plugins:
## 5. <a title="Responsive Select Menu" href="http://wordpress.org/plugins/responsive-select-menu/" target="\_blank">Responsive Select Menu</a>

<a href="http://wordpress.org/plugins/responsive-select-menu/" target="_blank"><img class="aligncenter" alt="ResponsiveSelectMenu" src="/images/ResponsiveSelectMenu.png" /></a>

It's not too difficult to set this up yourself using media queries, but this saves a little work (especially if you're starting with somebody else's theme) and functions perfectly!

**Quirks**: The per-menu selection doesn't always seem to work. Using it on all menus works fine, but selecting only individual menus sometimes seems to fail.

**UPDATE (6/18/2013):** Chris Mavricos at <a title="Sevenspark" href="http://sevenspark.com" target="_blank">Sevenspark</a> reports that this issue is probably caused by incorrect assignment of "theme_location" in the wp_nav_menu() function, wherever it's called in the active theme. Making sure that each menu included in the theme properly specifies "theme_location" will most likely resolve the issue. More information about using wp_nav_menu() at the <a title="wp_nav_menu() Reference" href="http://codex.wordpress.org/Function_Reference/wp_nav_menu" target="_blank">Wordpress Codex.</a>

## 4. <a title="Lightbox Plus Colorbox" href="http://wordpress.org/plugins/lightbox-plus/" target="\_blank">Lightbox Plus Colorbox</a>

<a href="http://wordpress.org/plugins/lightbox-plus/" target="_blank"><img class="aligncenter" alt="LightboxPlusColorbox" src="/images/LightboxPlusColorbox.png" /></a>

There are lots of lightbox/colorbox/thickbox plugins out there, so this is up for debate, but as far as options, variety of styles and consistency, Lightbox Plus Colorbox has never let us down. It very rarely runs into conflicts with other plugins, and it almost always works the way it should right out of the box.

**Quirks**: Right after first installing, sometimes it needs to be reset/reinitialized so that all of the default settings (which usually work fine) take effect. It's quicker to do this than to enter custom settings manually right away.

## 3. <a title="Display Posts Shortcode" href="http://wordpress.org/plugins/display-posts-shortcode/" target="\_blank">Display Posts Shortcode</a>

<a href="http://wordpress.org/plugins/display-posts-shortcode/" target="_blank"><img class="aligncenter" alt="DisplayPostShortcode" src="/images/DisplayPostShortcode.png" /></a>

Again, there are lots of plugins to list posts/custom posts on other pages, but we've found Display Posts to be very solidly written and full of options. Almost anything you could think of doing with a post list is possible with this shortcode plugin. One feature I especially like is the ability to change not only the ID/class of the container for each item, but the ability to change the type of container from a list-item to a div, etc. It makes styling the posts really easy, and in a lot of cases, this plugin can be a quick way to bypass the need to write custom page templates for post lists.

**Quirks**: In some cases, it seems that putting "include_excerpt=false" into the shortcode actually causes the excerpt to appear, whereas just leaving "include_excerpt" out of the shortcode entirely correctly causes the excerpt not to appear. Easy to avoid once you're aware of it. Otherwise, a great plugin by <a title="Bill Erickson" href="http://www.billerickson.net/" target="_blank">Bill Erickson</a>!

**UPDATE (6/14/2013):** Bill looked into the small issue above and just posted <a title="Display Posts Shortcode Update" href="https://github.com/billerickson/Display-Posts-Shortcode" target="_blank">a new version</a> to github which resolves it. Thanks again for an awesome plugin, Bill!

## 2. <a title="Responsive Slider" href="http://wordpress.org/plugins/responsive-slider/" target="\_blank">Responsive Slider</a></h2>

<a href="http://wordpress.org/plugins/responsive-slider/" target="_blank"><img class="aligncenter" alt="ResponsiveSlider" src="/images/ResponsiveSlider.png" /></a>

This is a great plugin -- always works, never conflicts except with poorly-written themes/plugins. Simple and easy to incorporate on a theme or page level via the shortcode "responsive_slider." With the addition of the code by <a title="Hal Gatewood" href="http://halgatewood.com/" target="_blank">Hal Gatewood</a>, here: <a title="Responsive Slider -- Multiple Sliders" href="http://wordpress.org/support/topic/plugin-responsive-slider-create-more-than-1-slider" target="_blank">http://wordpress.org/support/topic/plugin-responsive-slider-create-more-than-1-slider</a> (and a little tweaking of your own to name your slider IDs) it supports multiple sliders on the same site beautifully. Easy to style and modify. Not the "fanciest" slider, but tasteful and effective in almost any case.

**Quirks**: Almost none. Since it's jQuery based, it does occasionally conflict, but only with more poorly written plugins.

## 1. <a href="http://www.gravityforms.com/" target="\_blank">Gravity Forms</a>

<a href="http://www.gravityforms.com/" target="_blank"><img class="aligncenter" alt="GravityForms" src="/images/GravityForms.png" /></a>

This is definitely my favorite plugin. It is so solidly written that it almost never has a problem working well with others. If you can think of something that you'd like to be able to do with forms, you can probably do it in half the time with Gravity Forms, and be sure that it will continue to work well. Flexible, expandable, easy to use.

It *is* a premium, paid plugin, but the price is very reasonable for the functionality and quality provided.

**Quirks**: The only quirk I've come across is that sometimes installing add-ons through "Add-ons" under forms fails to work, so instead I usually install add-ons as I would any stand-alone plugin. Overall: Fantastic plugin, well worth the price.