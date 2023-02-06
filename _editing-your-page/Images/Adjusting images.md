---
title: Adjusting images
permalink: /editing-your-page/Images/adjustingimages/
description: ""
third_nav_title: Images
---
## Markdown

<p>For images added using Markdown, we are unable to adjust the images sizes.</p>

## HTML

<p>Hence, if you require to have adjustments done after you have uploaded the image, you will need to use html code instead.
Instead of a separate CSS file, Isomer uses inline CSS for adjustments of the images. (Not important if you don't understand)</p>

<p>This is how a typical image code will look like.</p>
<p>&lt;img src="/images/filename.jpg"&nbsp;style="width:25%"&gt;</p>

<p>We use the style command to control the attributes (width, height, aspect-ratio etc) of the image. We can fix the attribute using an absolute value like the number of pixels (px), a percentage of the original image size (%) or a percentage of the device frame size (vw, vh).</p>

#### Using px (pixel):
<p>&lt;img src="/images/chicken.jpg"&nbsp;style="width:200px"&gt;</p>
<center><img src="/images/chicken.jpg" style ="width:200px"/></center>

#### Using % (percentage of original size):
<p>&lt;img src="/images/chicken.jpg"&nbsp;style="width:50%"&gt;</p>
<center><img src="/images/chicken.jpg" style="width:50%"></center>

#### Using vw (view width):
<p>&lt;img src="/images/chicken.jpg" style="width:25vw"&gt;</p>
<center><img src="/images/chicken.jpg" style="width:25vw"/></center>

You can resize your window to see how the images are resized to fit.