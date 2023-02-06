---
title: Accordion
permalink: /Accordion/
description: ""
---
<p>Accordions are collapsible blocks that are helpful in organizing plenty of content on a page. They will remain hidden until the user clicks onto them.
<br>An example of an Accordion is shown below:</p>

<ul class="jekyllcodex_accordion">
<li><input id="accordion1;" type="checkbox">
<label for="accordion1;">Accordion 1</label><div>
<p>Insert content here</p>
</div></li>
<li><input id="accordion2;" type="checkbox">
<label for="accordion2;">Accordion 2</label><div>
<p>Insert content here</p>
</div></li>
<li><input id="accordion3;" type="checkbox">
<label for="accordion3;">Accordion 3</label><div>
<p>Insert content here</p>
</div></li>
</ul>

<div><h2>How to add Accordion to my page?</h2>
<ol>
<li><strong><u>Enabling Accordion on the schools site</strong></u><br><br>
Schools would need to first inform us to enable it on their site.  (If you have Accordion on other pages, it means that it is already enabled.)</li><br>

<li><strong><u>Starting Accordion on the page</strong></u><br><br>
Next, on the page that you will like to add Accordion, insert <mark>&#60;ul class&#61;"jekyllcodex_accordion"&#62;</mark> to start the accordion code.</li><br>

<li><strong><u>Starting Accordion Item</strong></u><br><br>
To start an Accordion item, insert the following where &#35; is a unique number.<br><mark>
&#60;li&#62;&#60;input id&#61;"accordion&#35;" type&#61;"checkbox"&#62;<br>
&#60;label for&#61;"accordion&#35;"&#62;Insert Accordion title here&#60;&#47;label&#62;&#60;div&#62;</mark></li><br>

<li><strong><u>Inserting Accordion content</strong></u><br><br>
To insert content in the accordion, you can use the paragraph tags such as: (Note that you cannot use another <mark>&#60;div&#62;&#60;&#47;div&#62;</mark> tags as it will confuse the system.)<br>
<mark>&#60;p&#62;Insert content here&#60;&#47;p&#62;</mark></li><br>

<li><strong><u>Closing Accordion item</strong></u><br><br>
To close the Accordion item, insert the following tags:<br>
<mark>&#60;&#47;div&#62;&#60;&#47;li&#62;</mark></li><br>

<li><strong><u>Adding Additional Accordions</strong></u><br><br>
Repeat steps 3-5 for additional accordion items (note that # must be a unique number on the page)</li><br>

<li><strong><u>Closing Accordion on the page</strong></u><br><br>
Finally to close the Accordion code, insert <mark>&#60;&#47;ul&#62;</mark> at the end.</li><br>
</ol>

<p>
In summary, your html code should look something like this:
<br><br><mark>
&#60;ul class&#61;"jekyllcodex_accordion"&#62;<br><br>
&#60;li&#62;&#60;input id&#61;"accordion1;" type&#61;"checkbox"&#62;<br>
&#60;label for&#61;"accordion1;"&#62;Insert Accordion Title here&#60;&#47;label&#62;&#60;div&#62;<br>
&#60;p&#62;Insert content here&#60;&#47;p&#62;<br>&#60;&#47;div&#62;&#60;&#47;li&#62;<br><br>
&#60;li&#62;&#60;input id&#61;"accordion2;" type&#61;"checkbox"&#62;<br>
&#60;label for&#61;"accordion2;"&#62;Insert Accordion Title here&#60;&#47;label&#62;&#60;div&#62;<br>
&#60;p&#62;Insert content here&#60;&#47;p&#62;<br>&#60;&#47;div&#62;&#60;&#47;li&#62;<br><br>
&#60;li&#62;&#60;input id&#61;"accordion3;" type&#61;"checkbox"&#62;<br>
&#60;label for&#61;"accordion3;"&#62;Insert Accordion Title here&#60;&#47;label&#62;&#60;div&#62;<br>
&#60;p&#62;Insert content here&#60;&#47;p&#62;<br>&#60;&#47;div&#62;&#60;&#47;li&#62;<br><br>
&#60;&#47;ul&#62;</mark></p>
</div>