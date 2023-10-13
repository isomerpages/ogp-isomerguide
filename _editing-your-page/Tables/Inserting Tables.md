---
title: Inserting Tables
permalink: /editing-your-page/insertingtables/
description: ""
third_nav_title: Tables
---
## Markdown

<img src="/images/Toolbar%20(table).png" style="width:60%">

Clicking on the table icon located within the toolbar will automatically bring up a Markdown table within your CMS like this:

<table><tbody><tr><td><p>| Column 1 | Column 2 | Column 3 | 
<br>| -------- | -------- | -------- | 
<br>| Text     | Text     | Text     | 
</p></td><td><em>This is the header portion, they are automatically bold
<br>Cell widths doesn't matter<br>
This is the first row</em></td></tr></tbody></table>

<p>| Column 1 | Column 2 | Column 3 | <em>This is the header portion, they are automatically bold</em>
<br>| -------- | -------- | -------- | <em>Cell widths doesn't matter</em>
<br>| Text     | Text     | Text     | <em>This is the first row</em>
</p>

#### Adding rows	
To add additional rows, press enter and insert another row of "| Text     | Text     | Text     |" like this:
<br>
<p>| Column 1 | Column 2 | Column 3 | 
<br>| -------- | -------- | -------- | 
<br>| Text     | Text     | Text     |
<br>| Text     | Text     | Text     |
</p>

#### Adding columns
To add additional columns, insert another "|" after the last of the row, like this:
<br>
<p>| Column 1 | Column 2 | Column 3 | Column 4 |
<br>| -------- | -------- | -------- | -------- |
<br>| Text     | Text     | Text     | Text     |
<br>| Text     | Text     | Text     | Text     |
</p>

Do note that you will have to have the same number of "|" for each row. 

### Alignment

You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row.

<p>
| Header 1 | Header 2 | Header 3 |
<br>| :--- | :----: | ---: |
<br>| Text 1A |  Text 2A | Text 3A |
<br>| Text 1B | Text 2B |  Text 3B |
</p>

They will look like this:

| Header 1 | Header 2 | Header 3 |
| :--- | :----: | ---: |
| Text 1A |  Text 2A | Text 3A |
| Text 1B | Text 2B |  Text 3B |


Do note that our Markdown tables come in a standard format;&nbsp;
*   there are dividers for rows
*   no dividers for columns even though they are clearly spaced


## I am not familiar with Markdown or HTML, can I still add a table?

There are some workarounds if you are untrained in Mardown or HTML. There are some free-to-use HTML table generator available online such as [https://www.tablesgenerator.com/](https://www.tablesgenerator.com/):

![A screenshot of online HTML table generator](/images/tablegenerator.png)

When using an online table generator, make sure that you check these two things:

*   Make sure that "Do not generate CSS" is selected
*   Copy HTML code using the "Copy to clipboard" button and paste the code directly onto your page