---
layout:     post
title:      Free WordPress Plugin - Responsive Image Widget
date:       2013-07-05
summary:    Here is the first freely available plugin we've produced!
categories: wordpress-resource
---

by <a href="https://plus.google.com/u/2/105617426521194863864?rel=author">Benjamin Robinson</a>

***

Here is the first **freely available plugin** we've produced! We developed this for the new <a title="Living Litehouse blog" href="http://litehousefoods.com/livinglitehouseblog/" target="_blank">**Living Litehouse blog**</a>, but it can be useful in many WordPress deployments.

<a href="/images/responsive-image-widget-screenshot.png"><img class="alignright" src="/images/responsive-image-widget-screenshot.png" /></a>This is a very simple WordPress widget that displays a single responsive, rationally proportional image in a widget area. It **helps make adding images with accurate proportions to sidebar areas quick and easy**, and thus avoid a stretched or distorted appearance -- without requiring any knowledge of HTML or even an image editing program.

Its key feature is that it allows proportional adjustment on the fly, so the user can easily change the proportion of the image inside of WordPress, instead of needing to resize the image in an editor (a problem for many WordPress users who do not have a lot of experience resizing/cropping images, or who simply don't have image editing software available.)

It takes in a title, image URL, height to width ratio and target link URL. It outputs a rationally proportional frame ("div") with the image set as a background. The image always fills the whole horizontal space (100%) of the widget, and can be cropped from the left, right, top, bottom, or centered.

## <a title="Download the Responsive Image Widget" href="http://keokee.com/responsive-image-widget/responsive_image_widget_11.zip">Download the Widget! »</a>

## Screenshots of the widget output:

<a data-mediabox href="/images/riw-example.png"><img class="aligncenter" alt="An example of a vertically rational image (height is 200% of the width)" src="/images/riw-example.png" /></a>

<p class="center">An example of a vertically rational image; the height is 200% of the width.</p>

<a data-mediabox href="/images/riw_example_square.png"><img class="aligncenter" alt="100% -- Square" src="/images/riw_example_square.png" /></a>

<p class="center">Here it is sized at 100% but in square format.</p>

<a data-mediabox href="/images/riw_example_horizontal.png"><img class="aligncenter" alt="Very horizontal image -- the height is 40% of the width.." src="/images/riw_example_horizontal.png" /></a>

<p class="center">Here's the same image sized for a very horizontal image -- the height is 40% of the width..</p>

## Installation

  1. <a href="http://keokee.com/responsive-image-widget/responsive_image_widget_11.zip">Download the widget.</a>
  2. Go to "Plugins &gt; Add new &gt; Upload" in Wordpress, and upload "responsive_image_widget_11.zip" from your computer. Or, unzip and upload "responsive_image_widget.php" to the "/wp-content/plugins/" directory.
  3. Activate the plugin through the 'Plugins' menu in WordPress
  4. Place widget(s) in your sidebar areas through 'Appearance &gt; Widgets' in WordPress
  5. Change the settings to your desiring and save!

## (Expected) Frequently Asked Questions

- **Help! The image is gigantic and/or pixelated!** The image **always** fills 100% of the width of the containing element (widget area). In other words, if the widget/widget area where the image is placed is large, the image will be large. So if your original image is only, say 200 pixels wide but the widget is 300 pixels wide the plugin will blow the image up to fill the 300 pixels and create the pixelation.To avoid this kind of pixelation, use an image that is at least as large as the widget area, or preferably larger than the widget area you plan to use it in.

- **Can the image only be placed on the side of the WordPress site like in the screenshots?** Absolutely not! Just like all widgets, the Responsive Image Widget can be placed in any widget areas available in the active theme. In the future, we may also update it to include a shortcode feature, too.

***

**Don't hesitate to shoot us more questions in the comments!** With any luck, the widget will soon be officially available through the <a title="WordPress Plugin Directory" href="http://wordpress.org/plugins/" target="_blank">WordPress Plugin Directory</a>, in addition to <a href="http://keokee.com/responsive-image-widget/responsive_image_widget_11.zip" target="_blank">here</a>.

**UPDATE: The plugin is now officially available on the WordPress plugins directory!**
That means it can be added directly from WordPress right <a title="Responsive Image Widget" href="http://wordpress.org/plugins/responsive-image-widget/" target="_blank">here</a>!