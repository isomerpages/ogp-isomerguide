---
title: Accordion
permalink: /Accordion/
description: ""
---
<p>Accordions are collapsible blocks that are helpful in organizing plenty of content on a page. They will remain hidden until the user clicks onto them.
<br><br>An example of an Accordion is shown below:</p>

<ul class="jekyllcodex_accordion">
<li><input id="accordion1;" type="checkbox">
<label for="accordion1;">Accordion 1</label><div>
<p>You can insert your text here</p>
</div></li>
<li><input id="accordion2;" type="checkbox">
<label for="accordion2;">Accordion 2</label><div>
<p>Or images like this:<br><center><img src="/images/chicken.jpg" style="width:50%"></center></p>
</div></li>
<li><input id="accordion3;" type="checkbox">
<label for="accordion3;">Accordion 3</label><div>
<p>Or even tables like this:<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-vs2s{background-color:#9b9b9b;border-color:#000000;text-align:left;vertical-align:top}
.tg .tg-73oq{border-color:#000000;text-align:left;vertical-align:top}
</style>
<center><table class="tg" style="width:50%">
<thead>
  <tr>
    <th class="tg-vs2s">Header</th>
    <th class="tg-vs2s">Header</th>
    <th class="tg-vs2s">Header</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-73oq">Test</td>
    <td class="tg-73oq">Test</td>
    <td class="tg-73oq">Test</td>
  </tr>
  <tr>
    <td class="tg-73oq">Test</td>
    <td class="tg-73oq">Test</td>
    <td class="tg-73oq">Test</td>
  </tr>
</tbody>
</table></center></p>
</div></li>
</ul>

<div><h2>How to add Accordion to my page?</h2>
<ol>
<li><b><u>Enabling Accordion on the schools site</u></b><br><br>
Schools would need to first inform us to enable it on their site. &#40;If you have Accordion on other pages, it means that it is already enabled.&#41;</li><br>

<li><b><u>Starting Accordion on the page</u></b><br><br>
Next, on the page that you will like to add Accordion, insert <mark>&#60;ul class&#61;"jekyllcodex_accordion"&#62;</mark> to start the accordion code. Remove the \ so that the code works!</li><br>

<li><b><u>Starting Accordion Item</u></b><br><br>
To start an Accordion item, insert the following where &#35; is a unique number.<br><mark>
&#60;li&#62;&#60;input id&#61;"accordion&#35;" type&#61;"checkbox"&#62;<br>
&#60;label for&#61;"accordion&#35;"&#62;Insert Accordion title here&#60;&#47;label&#62;&#60;div&#62;</mark></li><br>

<li><b><u>Inserting Accordion content</u></b><br><br>
To insert content in the accordion, you can use the paragraph tags such as: (Note that you cannot use another <mark>&#60;div&#62;&#60;&#47;div&#62;</mark> tags as it will confuse the system.)<br>
<mark>&#60;p&#62;Insert content here&#60;&#47;p&#62;</mark></li><br>

<li><b><u>Closing Accordion item</u></b><br><br>
To close the Accordion item, insert the following tags:<br>
<mark>&#60;&#47;div&#62;&#60;&#47;li&#62;</mark></li><br>

<li><b><u>Adding Additional Accordions</u></b><br><br>
Repeat steps 3-5 for additional accordion items (note that # must be a unique number on the page)</li><br>

<li><b><u>Closing Accordion on the page</u></b><br><br>
Finally to close the Accordion code, insert <mark>&#60;&#47;ul&#62;</mark> at the end.</li><br>
</ol>

<p>
In summary, your html code should look something like this:
<br><br><mark>
&#60;ul class&#61;"jekyllcodex_accordion"&#62;<br><br>
&#60;li&#62;&#60;input id&#61;"accordion1" type&#61;"checkbox"&#62;<br>
&#60;label for&#61;"accordion1"&#62;Insert Accordion Title here&#60;&#47;label&#62;&#60;div&#62;<br>
&#60;p&#62;Insert content here&#60;&#47;p&#62;<br>&#60;&#47;div&#62;&#60;&#47;li&#62;<br><br>
&#60;li&#62;&#60;input id&#61;"accordion2" type&#61;"checkbox"&#62;<br>
&#60;label for&#61;"accordion2"&#62;Insert Accordion Title here&#60;&#47;label&#62;&#60;div&#62;<br>
&#60;p&#62;Insert content here&#60;&#47;p&#62;<br>&#60;&#47;div&#62;&#60;&#47;li&#62;<br><br>
&#60;li&#62;&#60;input id&#61;"accordion3" type&#61;"checkbox"&#62;<br>
&#60;label for&#61;"accordion3"&#62;Insert Accordion Title here&#60;&#47;label&#62;&#60;div&#62;<br>
&#60;p&#62;Insert content here&#60;&#47;p&#62;<br>&#60;&#47;div&#62;&#60;&#47;li&#62;<br><br>
&#60;&#47;ul&#62;</mark></p>
</div>