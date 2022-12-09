---
title: Adding Images
permalink: /editing-your-page/Images/addingimages/
description: ""
third_nav_title: Images
---
## Uploading images 

1. Click on Images on the side panel of My Workspace
2. Click on Upload Image
3. Select the image from your local drive
4. Click Upload

Isomer is able to host images ('png', 'jpg', 'gif', 'tif', 'bmp', 'ico', 'svg') up to 5 MB. For larger images, you can consider using https://for.edu.sg/ which is able to host up to 10 MB.

## Using the image tool (Markdown)

When you click the image icon and it will open up a page Select Image. 

![](/images/addingimages.png)

From here, you can choose the image you have already uploaded or select "Add New" to upload new images. When you have selected your image and click Select, it will move you to the Insert Media page. 

![](/images/Insertmedia.png)

The file name should be populated with the image file name which you had just selected and your image should show up at the preview area. Alt text is the text that will appear if your images fails to load and it is optional.

When you click save, you will notice that the editor area is filled up with "!\[\](/images/filename.png)"

This is actually the Markdown code for images where enclosed within the \[\] is the alternate text and enclosed within the () is the filepath of your images.

## Using html

Inserting images
To insert an image with html code, we use the &lt;img&gt; tag. We will then link it to the source of the image by using src attribute:

&lt;img src=" "&gt;
The image is found in the Images folder and named "joyoflearning.jpg", hence, the file path is "/images/joyoflearning.jpg"

&lt;img src="/images/joyoflearning.jpg"&gt;
You can also add the style attribute which is seen here to adjust the size of the images to 45% of its original size. (The order doesn't matter, whether src comes first or style comes first)

&lt;img style="width:45%" src="/images/joyoflearning.jpg"&gt;

You can read more about html image tags here and also explore the other attributes that you can adjust: https://www.w3schools.com/tags/tag_img.asp