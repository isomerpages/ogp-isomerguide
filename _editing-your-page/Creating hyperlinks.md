---
title: Creating hyperlinks
permalink: /editing-your-page/hyperlinks/
description: ""
---
Inserting hyperlinks
--------------------

### Markdown

<center><img style="width:300px" src="/images/Toolbar%20(Link).png"></center>

<ol><li>Click on the hyperlink icon.</li>

<center><img style="width:300px" src="/images/Insert%20Hyperlink.jpg"></center>

<li>A pop up of "Insert hyperlink" with 2 fields, Text and Link, will appear. Text is what you will see on the page while the link is the url that it will be directing to when the user clicks on it.</li>

<li>After clicking save, a hyperlink in the Markdown format will appear in your editor page.</li></ol>

<b>Markdown format</b>

The format for markdown hyperlinks goes like this:<br> \[Isomer Guide\](https://guide.isomer.gov.sg).

To create a link, enclose the link text in brackets (e.g., \[Isomer Guide\]) and then follow it immediately with the URL in parentheses (e.g., (https://guide.isomer.gov.sg)).

#### Picture hyperlink

<ol><li>To create a picture hyperlink, first add the picture following the steps <a href="/editing-your-page/Images/addingimages/">here</a>. Your markdown code should look like this: <br>
!\[\](/images/chicken.jpg)</li>

<li>Next copy and paste this into the Text portion of the hyperlink. After you click save, the hyperlink code shoudl appear to be embeded between the brackets like this:

[![](/images/chicken.jpg&#41;]&#40;https:&#47;&#47;guide.isomer.gov.sg&#47;&#41;</li>

<li>On your page, it will appear like this:

[![](/images/chicken.jpg)](https://guide.isomer.gov.sg/)</li></ol>

### HTML

Image with hyperlink
The code we used here is html for images with hyperlink. Html codes are usually characterized by sets of "&lt;" and "&gt;" brackets we call tags. 

Inserting hyperlink
To insert a hyperlink with html code, we use the &lt;a&gt; tag. We will then direct it to the url by using href attribute:

&lt;a href=""&gt;

We would like the link to direct us to https://guide.isomer.gov.sg/. Hence, we will include the URL in between the " ":

&lt;a href="https:&#47;&#47;guide.isomer.gov.sg"&gt;

Next we will add the text or images that we would like to appear on the webpage and enclose it with a closing tag &lt;/a&gt;. For e.g. I would like "Click here" to appear on the page. 

&lt;a href="https:&#47;&#47;guide.isomer.gov.sg"&gt;Click Here&lt;/a&gt;

On your page, it will look like this:

<a href="https://guide.isomer.gov,.sg/">Click here</a>

#### Picture hyperlink: 
To add the hyperlink to images, simply have the whole images tag enclosed within the hyperlink tag.

&lt;a href="https:&#47;&#47;guide.isomer.gov.sg"&gt;&lt;img src="/images/chicken.jpg/"&gt;&lt;/a&gt;

#### Opening link in a new tab:
If you would like the link to open in a new tab, you can use the target attribute and set it to &#95;blank.

For e.g. if you would like &lt;a href="https:&#47;&#47;guide.isomer.gov.sg"&gt;Click Here&lt;/a&gt; to open in a new tab. It will look like this:

&lt;a href="https:&#47;&#47;guide.isomer.gov.sg" target=&#95;blank"&gt;Click Here&lt;/a&gt;

On your page, it will appear like this:

<a href="https://guide.isomer.gov,.sg/" target="_blank">Click here</a>

####  Creating a hyperlink to a particular section
If you will like to create a hyperlink to a particular section of a page, you can look at [anchors](/editing-your-page/anchor/).