---
title: Inserting Tables
permalink: /editing-your-page/insertingtables/
description: ""
third_nav_title: Tables
---
## Markdown

![](/images/Toolbar%20(table).png)

Clicking on the table icon located within the toolbar will automatically bring up a Markdown table within your CMS like this:

<p>| Column 1 | Column 2 | Column 3 | <--- This is the header portion, they are automatically bold 
<br>| -------- | -------- | -------- | <--- Cell widths can vary, as shown below. The rendered output will look the same.
<br>| Text     | Text     | Text     | <--- This is the first row 
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

Do note that you will have to have the same number of "|" for each row. Otherwise, it will assume that you want the merge the columns for that row.

| Syntax | Description |

| --- | ----------- |

| Header | Title |

| Paragraph | Text |

  
  

### Alignment

You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row.

<p>
| Syntax      | Description | Test Text     |
<br>| :---        |    :----:   |          ---: |
<br>| Header      | Title       | Here's this   |
<br>| Paragraph   | Text        | And more      |
</p>
  
  

Do note that our Markdown tables come in a standard format; 

*   there are dividers for rows
    
*   no dividers for columns even though they are clearly spaced
    

**



## HTML


## I am not familiar with Markdown or HTML, can I still add a table?

There are some workarounds if you are untrained in html. There are also some free-to-use html table generator available online such as [https://www.tablesgenerator.com/](https://www.tablesgenerator.com/). Your teachers could paste the table content into the generator, customise the font size, text alignment and table borders etc, generate code and paste them into the CMS editor.