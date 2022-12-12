---
title: Creating hyperlinks
permalink: /editing-your-page/hyperlinks/
description: ""
---
Inserting hyperlinks
--------------------

### Markdown

<center><img style="width:300px" src="/images/Toolbar%20(Link).png"></center>

1. Click on the hyperlink icon.

<center><img style="width:300px" src="/images/Insert%20Hyperlink.jpg"></center>

2. A pop up of "Insert hyperlink" with 2 fields, Text and Link, will appear. Text is what you will see on the page while the link is the url that it will be directing to when the user clicks on it.

3. After clicking save, a hyperlink in the Markdown format will appear in your editor page.

My favorite search engine is \[Duck Duck Go\](https://duckduckgo.com).

To create a link, enclose the link text in brackets (e.g., \[Duck Duck Go\]) and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).

#### Picture hyperlink
  

### HTML

Image with hyperlink
The code we used here is html for images with hyperlink. Html codes are usually characterized by sets of "&lt;" and "&gt;" brackets we call tags. 

Inserting hyperlink
To insert a hyperlink with html code, we use the &lt;a&gt; tag. We will then direct it to the url by using href attribute:

<a href="">
We would like the link to direct us to https://guide.isomer.gov.sg/
</a><a href="">
Next we will add the text or images that we would like to appear on the webpage and enclose it with a closing tag </a>. For e.g. I would like "Click here" to appear on the page. 

<a href="https://westwoodpri.moe.edu.sg/qql/slot/u147/Flipping%20Book/Westwood%20Publication%20Flipbook.html#p=1">Click here</a>


To add the hyperlink to images, simply have the whole images tag to be enclosed within the hyperlink tag.
<a href="https://westwoodpri.moe.edu.sg/qql/slot/u147/Flipping%20Book/Westwood%20Publication%20Flipbook.html#p=1">
<img src="/images/joyoflearning.jpg" style="width:45%">
</a>

#### Picture hyperlink: 
div&gt;
<div style="float: left">
<a href="https://www-broadricksec-moe-edu-sg-admin.cwp.sg/cca/uniformed-groups/red-cross">
<img style="width:50%" src="/images/red%20cross%20logo.png">
</a>
</div>
<div>
</div>


Hyperlinking a picture with a caption. Link opens image in new tab
<figure>
	<a target="_blank" href="/images/Capture.jpg"> <img style="width:100%" src="/images/Capture.jpg"></a>
<figcaption>
	<strong> Celebration Of Pongal Or Indian Harvest Festival </strong>
	</figcaption>
</figure>


If you will like to create a hyperlink to a particular section of a page, you can look at [anchors](/editing-your-page/anchor/).