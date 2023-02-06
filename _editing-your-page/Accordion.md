---
title: Accordion
permalink: /Accordion/
description: ""
---
<p>Accordions are collapsible blocks that are helpful in organizing plenty of content on a page. They will remain hidden until the user clicks onto them.</p>
<p>
<ol>
	<h5><li>Enabling Accordion on the schools site:</h5>
Schools would need to first inform us to enable it on their site.  (If you have Accordion on other pages, it means that it is already enabled.)</li>

<h5><li>Starting Accordion on the page</h5>
Next, on the page that you will like to add Accordion, insert <mark>&#60;ul class&#61;"jekyllcodex_accordion"&#62;</mark> to start the accordion code.</li>

<h5><li>Starting Accordion Item</h5>
To start an Accordion item, insert the following where &#35; is a unique number.<br><mark>
&#60;li&#62;&#60;input id&#61;"accordion&#35;" type&#61;"checkbox"&#62;<br>
&#60;label for&#61;"accordion&#35;"&#62;Insert Accordion title here&#60;&#47;label&#62;&#60;div&#62;</mark></li>

<h5><li>Inserting Accordion content</h5>
To insert content in the accordion, you can use the paragraph tags such as: (Note that you cannot use another <mark>&#60;div&#62;&#60;&#47;div&#62;</mark> tags as it will confuse the system.)<br>
<mark>&#60;p&#62;Insert content here&#60;&#47;p&#62;</mark></li>

<h5><li>Closing Accordion item</h5>
To close the Accordion item, insert the following tags:<br>
<mark>&#60;&#47;div&#62;&#60;&#47;li&#62;</mark></li>

<h5><li>Adding Additional Accordions</h5>Repeat steps 3-5 for additional accordion items (note that # must be a unique number on the page)</li>

<h5><li>Closing Accordion on the page</h5>
Finally to close the Accordion code, insert <mark>&#60;&#47;ul&#62;</mark> at the end.</li>
</ol></p>
<p>
In summary, you can add the following while ensuring that &#35; is a unique number.
<br><br><mark>
&#60;ul class&#61;"jekyllcodex_accordion"&#62;<br>
&#60;li&#62;&#60;input id&#61;"accordion&#35;" type&#61;"checkbox"&#62;<br>
&#60;label for&#61;"accordion&#35;"&#62;Insert Accordion Title here&#60;&#47;label&#62;&#60;div&#62;<br>
&#60;p&#62;Insert content here&#60;&#47;p&#62;<br>
&#60;&#47;div&#62;&#60;&#47;li&#62;
&#60;&#47;ul&#62;</mark></p>