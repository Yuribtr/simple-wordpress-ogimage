Simple Wordpress OG Image
========================

Add og:image (Open Graph) tag to posts so Facebook can display proper image. 

The image is determined by these rules:   
1. Is there a cached image that was already set? If yes, use it. (This means no extra calls are made i.e. no performance penalty)   
2. Is there a featured image? If yes, use it.   
3. If there isn't a featured image use first image from post. If yes, use it.   
4. If there isn't an image in the post, check is there a default image. If yes, use it.   
5. If there isn't no tag will appear.   

###Version history   
**1.3.0**
Add support for Embedly cards
Enabled the plugin to work for pages
Add SwiftType meta tag

**1.2.1**
No more relative images (/wp-content/path/to/image.jpg now is going to be SITE_URL/wp-content/path/to/image.jpg)
Add few more Open Graph tags

**1.2**   
Allow multiple OG images at the same time (with option to turn it on/off)

**1.1.1**   
Add Twitter card image and general tag for more compatibilities

**1.1.0**   
Add preview box in admin edit post area   
   
**1.0.0**   
Initial release
