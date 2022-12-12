---
title: Adjusting images
permalink: /editing-your-page/Images/adjustingimages/
description: ""
third_nav_title: Images
---
## Markdown

For images added using Markdown, we are unable to adjust the images after they have been uploaded. If you prefer to use Markdown, you will need to adjust the images to the correct size before uploading and adding them in.

## HTML

Hence, if you require to have adjustments done after you have uploaded the image, you will need to use html code instead.

Instead of a separate CSS file, Isomer uses inline CSS for adjustments of the images. (Not important if you don't understand)

**

<img src="/images/filename.jpg" 

    style="width:25%">

**
We use the style command to control the attributes (width, height, aspect-ratio etc) of the image. We can fix the attribute using an absolute value like the number of pixels (px), a percentage of the original iamge size (%) or a percentage of the device frame size (vw, vh).