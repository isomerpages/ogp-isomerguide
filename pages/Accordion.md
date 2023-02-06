---
title: Accordion
permalink: /Accordion/
description: ""
---
<p>Accordions are collapsible blocks that are helpful in organizing plenty of content on a page. They will remain hidden until the user clicks onto them.</p>
<p>
<ol>
<li>Enabling Accordion on the schools site:
Schools would need to first inform us to enable it on their site.  (For your school, we have already enabled it)</li>

<li>Starting Accordion on the page
Next, on the page that you will like to add Accordion, insert &#60;ul class&#61;"jekyllcodex_accordion"&#62; to start the accordion code.</li>

<li>Starting Accordion Item
To start an Accordion item, insert the following where &#35; is a unique number.
&#60;li&#62;&#60;input id&#61;"accordion&#35;" type&#61;"checkbox"&#62;
&#60;label for&#61;"accordion&#35;"&#62;Insert Accordion title here&#60;&#47;label&#62;&#60;div&#62;</li>

<li>Inserting Accordion content
To insert content in the accordion, you can use the paragraph tags such as: (Note that you cannot use another &#60;div&#62;&#60;&#47;div&#62; syntax as it will confuse the system.)
&#60;p&#62;Insert content here&#60;&#47;p&#62;</li>

<li>Closing Accordion item
To close the Accordion item, insert the following tags:
&#60;&#47;div&#62;&#60;&#47;li&#62;</li>

<li>Repeat steps 3-5 for additional accordion items (note that # must be a unique number on the page)</li>

<li>Closing Accordion on the page
Finally to close the Accordion code, insert &#60;&#47;ul&#62; at the end.</li>
</ol></p>
<p>
In summary, you can add the following while ensuring that &#35; is a unique number

&#60;ul class&#61;"jekyllcodex_accordion"&#62;
&#60;li&#62;&#60;input id&#61;"accordion&#35;" type&#61;"checkbox"&#62;
&#60;label for&#61;"accordion&#35;"&#62;Insert Accordion Title here&#60;&#47;label&#62;&#60;div&#62;
&#60;p&#62;Insert content here&#60;&#47;p&#62;
&#60;&#47;div&#62;&#60;&#47;li&#62;
&#60;&#47;ul&#62;</p>