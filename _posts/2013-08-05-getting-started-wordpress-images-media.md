---
layout:     post
title:      Getting Started with Wordpress - Images &amp; Media
date:       2013-08-05
summary:    In our first two "Getting Started with Wordpress" tutorials, we covered logging into WordPress, and working with text content in your posts and pages. In this third installment we'll tell how to add pictures, galleries and videos.
categories: ['WordPress Resource']
---

by <a title="Benjamin Robinson" href="https://plus.google.com/u/2/105617426521194863864?rel=author" target="_blank">Benjamin Robinson</a>

***

In our first two "Getting Started with Wordpress" tutorials, we covered logging into WordPress, and working with text content in your posts and pages. In this third installment we'll tell how to <strong>add pictures, galleries and videos</strong>.

Adding pictures and video is still very easy to do in WordPress, but there are a few tricky things you'll need to be aware of.

## Adding Photos: Being aware of "Float"

In WordPress, there are three primary ways an image can be placed into the content of a post or page:

  1. centered
  2. to the left of the text
  3. to the right of the text

<strong>Center alignment</strong> the simplest of the three to deal with: the picture clears the text on both sides of it, and centers itself in the middle of the content column. It is clear to see where the photo is and what comes before and after it.

<strong>Left and Right aligned</strong> images are trickier. Left and right aligned images "float" next to the text placed <em>after</em> them. That means whether you want to place an image to the left or right of some text, you need to insert the image <em>before</em> the text. You do this in the Edit Post or Edit Page window by simply placing your cursor right before the text, then clicking the "Add Media" button to add or find your picture (more on that below). Here's what the Left or Right alignment will look like:

<a data-mediabox data-title="Photo by Katie Kosaya" href="/images/drink_example.jpg"><img style="max-width: 400px;" class="alignleft" alt="Photo by Katie Kosaya" src="/images/drink_example.jpg" /></a> 

For example, the picture of the drink is <strong>floating to the left</strong> of this text...

<div style="clear: both;"></div>

<a data-mediabox href="/images/building_example.jpg"><img style="max-width: 400px;" class="alignright" src="/images/building_example.jpg" /></a>

While the picture of the building is <strong>floating to the right</strong> of this text. Both images are actually placed before the text they float next to.

<div style="clear: both;"></div>

Unlike in Microsoft Word or other word processing (or design) software, positioning images more exactly is not simple to achieve on the web, whether you are using WordPress or not. Specific positioning is possible, of course, but it certainly requires knowledge of HTML and CSS to do correctly, so it is beyond the scope of this tutorial.

Anyway, these three positioning options are usually enough.

<h3>The size of the image makes a difference!</h3>

<aside>
<h3>A Note About "Lightboxes"</h3>

Many sites have "lightboxes" installed. Lightboxes are javascript-powered popup boxes which appear to show a larger version of a clicked photo. You can try clicking on a photo on this page to see a lightbox effect.  

<a title="Five WordPress Plugins We Love" href="/wordpress-resource/2013/06/13/five-wordpress-plugins-we-love/">I wrote about our favorite lightbox plugin for WordPress here.</a>
</aside>

Your content column has a certain width. Images that are very large may fill the whole column and not appear to float, even if they are set to float right or left. Users wanting to see a larger version might click on the image to see the full size version in a <strong>Lightbox</strong> (see aside).

WordPress automatically makes additional image sizes for you when you upload a photo from your computer. The image sizes that are available by default are:

- <strong>Full</strong> (the original that you uploaded)
- <strong>Large</strong> (typically 1024px wide)
- <strong>Medium</strong> (300px wide)
- <strong>Thumbnail</strong> (150px by 150px square)

All of these reflect the original dimensions except "Thumbnail." Thumbnails are small, perfectly square versions of your image as would be used for a small preview.

It's important to select an appropriate size to allow space for text to flow around a floating image. Usually, the "medium" size option for an image works well for floating images.

<h3>Actually Adding the Photos</h3>

To add photos to a post or page:

<ol>
	<li>Open the post or page for editing in WordPress.</li>
	<li>At the top left corner of the page, click "Add Media."</li>
	<li>The media window will pop up. It looks like this:
<a data-mediabox href="/images/AddMedia.png"><img class="aligncenter" alt="Add Media" src="/images/AddMedia.png" /></a></li>
	<li>If you've already uploaded the image you need, you'll see it in the Media Library there. If you need to upload an image from your computer, click the "Upload Files" tab at the top left. You can drag an image onto the blank upload space, or click the "Select Files" button to browse for a file on your computer:
<a data-mediabox href="/images/UploadMedia.png"><img class="aligncenter" alt="Upload Media" src="/images/UploadMedia.png" /></a></li>
	<li>Once you've uploaded your image or found it in the media library, select it. Then set the insertion options on the right side of the screen -- this is where you'll set the alignment:
<a data-mediabox href="/images/Alignment.png"><img class="aligncenter" alt="Alignment" src="/images/Alignment.png" /></a></li>
	<li>You'll also set the size here -- for floating images, "Medium" is a good choice.</li>
	<li>And there are other options to be set:
<a data-mediabox href="/images/AttachmentDetails.png"><img class="aligncenter" alt="Attachment Details" src="/images/AttachmentDetails.png" /></a>
<ul>
	<li><strong>Title</strong>: the title of the image that will appear when a user holds their mouse over the image. ("Tooltip")</li>
	<li><strong>Caption</strong>: An optional caption that appears under the image.</li>
	<li><strong>Alt Text</strong>: text that would show if the image failed to load -- also read by search engines!</li>
	<li><strong>Description</strong>: Not really necessary. A description for yourself, to help you organize photos in WordPress.</li>
	<li><strong>Link to</strong>: the location where the media file links when clicked. "Media File" is usually the best option, because people clicking on an image usually expect to see the full size version. You might also consider "none" if you don't want the picture to be made into a link.</li>
</ul>
</li>
	<li>Once you've set all of the options the way you want them, click the blue "Insert into Post" button.</li>
</ol>

<strong>That's it! You've added an image.</strong> You should see it show up in your content box.

<hr />

<h2>Adding Galleries</h2>

Often, you don't want to add just a single image, but rather you want to add a large gallery of images that users can click on to see bigger versions.

WordPress lets you easily insert picture galleries through the same "Add Media" button as photos.

To add a gallery:
<ol>
	<li>In WordPress, Open the post/page you want to add the gallery(ies) to.</li>
	<li>Click the "Add Media" button at the top left of the content box.</li>
	<li>At the top right of the Media popup, select "Create Gallery" instead of "Insert Media":
<a data-mediabox href="/images/CreateGallery.png"><img class="aligncenter" src="/images/CreateGallery.png" /></a></li>
	<li>Select the image from your media library you'd like to add to the gallery, or select "Upload Files" to add pictures from your computer.</li>
	<li>When you've selected all of the photos you want, click the blue "Create a new Gallery" button in the bottom right corner:
<a data-mediabox href="/images/CreateGalleryButton.png"><img class="aligncenter" src="/images/CreateGalleryButton.png" /></a></li>
	<li>You'll be taken to the gallery screen, where you see all of the images that you chose, and you have the option to add captions and change settings for them:
<a data-mediabox href="/images/EditGallerySettings.png"><img class="aligncenter" src="/images/EditGallerySettings.png" /></a>
The settings this time are:
<ul>
	<li><strong>Link to</strong>: Same as above, this setting dictates where the gallery images should link to when clicked. "Media File" is usually what you want. This means users are shown the full size version of the image, or the image pops up in a Lightbox. "Attachment Page" takes the user to a blank template page showing the picture and its title, which is not usually what people expect.</li>
	<li><strong>Columns</strong>: The number of columns that you want your gallery to have. Keep in mind that you don't want to have so many columns that the images don't fit horizontally in the area you're putting them.</li>
	<li><strong>Random Order</strong>: shuffles the pictures randomly each time the gallery is displayed. This is useful if you don't want to give certain images preference by displaying them in the same place every time.</li>
</ul>
</li>
	<li>Once you're satisfied with the settings, click the blue "Insert Gallery" button.</li>
</ol>
<strong>Congratulations, you should see a box added for the gallery.</strong> You can click on the picture icon that appears in the upper left corner when you select the gallery block to edit it:

<a data-mediabox href="/images/GalleryEditExample.png"><img class="aligncenter" src="/images/GalleryEditExample.png" /></a>

Preview or publish your post/page to see it.

<hr />

<h2>Adding a Video from YouTube</h2>

The easiest way to add a video to your content is to embed it from YouTube. Once a video is on YouTube (even if it's not yours) you can embed it in your website. YouTube videos are embedded through what's called an "iframe." An iframe is essentially a window on a page through which you can see another website.

<strong>Here are the steps to follow to embed a video:</strong>

<ol>
	<li>Find the video you want to embed on YouTube.</li>
	<li>Once you've opened the video, click the "Share" button below the video.</li>
	<li>Instead of "Share this video" select the "Embed" tab.</li>
	<li>Select the size of your embedded video.</li>
	<li>Copy the embed code (HTML) from YouTube.</li>
	<li>Go to your WordPress post/page in the editor. Find the location where you'd like to place the video. Switch to the "text" (HTML) tab at the top right of the content box.</li>
	<li>Paste the video in the text tab of the window, the pasted text should look something like: &lt;iframe...&gt;&lt;/iframe&gt;</li>
	<li>Save your draft or update your published post. Click on "Preview" or "View post" to see your embedded video.</li>
</ol>

YouTube makes it easy to embed videos by generating iframe code for you to copy and paste. To demonstrate both how to do it, and provide an example of an embedded YouTube video, here's a video:

<a href="//www.youtube.com/embed/M7sXJ2YaUH8" data-height="360" data-width="640" data-mediabox><img style="max-width: 400px;" src="/images/how-to-wp-video.jpg" /></a>

<strong>Congratulations, you've just embedded a video!</strong>

<hr />

<h2>Conclusion</h2>

In these first three installments of "Getting Started ..." we've gone through basically everything necessary to understand the Wordpress nomenclature and to work with post/page content in WordPress. The best way to learn is by experimenting yourself with your own web pages. And don't fear that you might "break" your website: you'd almost have to do that intentionally, because WordPress saves revisions and you can always revert to a previous version if you save something you don't like.

The next and final section of this introductory WordPress series will be about some other areas beyond the main content that you may need to edit: the Menu and Widgets.