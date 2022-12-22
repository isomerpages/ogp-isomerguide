---
title: Organisational Chart & Site Map
permalink: /example-folder/example-subfolder/orgchartsitemap/
third_nav_title: Tables
description: ""
---
A frequently used feature of the table is to create Organization Charts or Site Maps. In this page, we will show you how to create these features using a table and provide you with a template to start.

##  Organization Chart

#### Markdown

OCCUPANTS OF STY 143
	
| | | |
|:-:|:-:|:-:|
|<img src="/images/chicken.jpg"   style="width:100px; aspect-ratio:1.6/1" /> |   <img src="/images/chicken.jpg"   style="width:100px; aspect-ratio:1.6/1" />  | <img src="/images/chicken.jpg"  style="width:100px; aspect-ratio:1.6/1" />|
| John<br> Pecking Executive<br>john@chickens.com |Patrick<br>Runner<br>|Ronaldo<br>Occupant<br>ronaldo@chickens.com|
|<img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1.6/1" />|<img src="/images/chicken.jpg"  style="width:100px; aspect-ratio:1.6/1" />|<img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1.6/1" />|
|Timmy<br>Emotional Support Officer<br>timmyk@chickens.com|Wilson<br>Morning Alarm<br>wilson@chickens.com|Bruno<br>Worm Cleaner<br>|

##### Markdown code

You can copy below code as a template to create your own organization chart:

<p style="font-size:15px">| | | |<br>
|:-:|:-:|:-:|<br>
|&lt;img src="<span style="color:orange">/images/chicken.jpg</span>" <span style="color:blue">style="width:100px; aspect-ratio:1.6/1"</span> /&gt;|&lt;img src="<span style="color:orange">/images/chicken.jpg</span>" <span style="color:blue">style="width:100px; aspect-ratio:1.6/1"</span> /&gt;|&lt;img src="<span style="color:orange">/images/chicken.jpg</span>" <span style="color:blue">style="width:100px; aspect-ratio:1.6/1"</span> /&gt;|<br>
|<span style="color:red">John&lt;br&gt; Pecking Executive&lt;br&gt;john@chickens.com</span>|<span style="color:red">Patrick&lt;br&gt;Runner&lt;br&gt;patrick@chickens.com</span>|<span style="color:red">Ronaldo&lt;br&gt;Occupant&lt;br&gt;ronaldo@chickens.com</span>|<br>
|&lt;img src="<span style="color:orange">/images/chicken.jpg</span>" <span style="color:blue">style="width:100px; aspect-ratio:1.6/1"</span> /&gt;|&lt;img src="<span style="color:orange">/images/chicken.jpg</span>"  <span style="color:blue">style="width:100px; aspect-ratio:1.6/1"</span> /&gt;|&lt;img src="<span style="color:orange">/images/chicken.jpg</span>" <span style="color:blue">style="width:100px; aspect-ratio:1.6/1"</span> /&gt;|<br>
|<span style="color:red">Timmy&lt;br&gt;Emotional Support Officer&lt;br&gt;timmyk@chickens.com</span>|<span style="color:red">Wilson&lt;br&gt;Morning Alarm&lt;br&gt;wilson@chickens.com</span>|<span style="color:red">Bruno&lt;br&gt;Worm Cleaner&lt;br&gt;bruno@chickens.com</span>|
</p>

<span style="color:orange">/images/chicken.jpg refers to the file path of your image. In general, all images are uploaded into the /images folder and you'll only require to change the filename (note the image type .jpg, .gif, .png)</span>

<span style="color:blue">style="width:100px; aspect-ratio:1.6/1" This portion refers to the adjustment made to the image by the browser. I have fixed the width as 100 pixels and the aspect ratio such that when the screen size changes, your images will not be skewed.</span>

<span style="color:red">John&lt;br&gt; Pecking Executive&lt;br&gt;john@chickens.com refers to the text that is added below the images. You can adjust these accordingly. &lt;br&gt; is a line break to shift the following text onto the next line.</span> 

## Site Map

Site maps are created using the table feature of Isomer. We can do so using either Markdown and html. While Markdown is more readable, it does not allow for resizing of the images after the image is uploaded. This would mean that you will need to crop the images to the same size before uploading them or they will appear messy in the site map.

#### Markdown

An example of a site map using Markdown:

|   |   |   |   |
|:---:|:---:|:---:|:---:|
| [![](/images/singaporeflyer.jpeg)](https://www.singaporeflyer.com/en)|[![](/images/singaporeriver.jpg)](https://www.visitsingapore.com/see-do-singapore/places-to-see/singapore-river/)|[![](/images/merlion.jpeg)](https://www.visitsingapore.com/see-do-singapore/recreation-leisure/viewpoints/merlion-park/)|[![](/images/sentosa.jpeg)](https://www.sentosa.com.sg/)|
|Singapore<br>Flyer|Singapore <br>River|Merlion<br>Park|Sentosa|
|[![](/images/gardensbythebay.jpeg)](https://www.gardensbythebay.com.sg/)|[![](/images/laupasat.jpg)](https://laupasat.sg/)|[![](/images/changiairport.jpeg)](https://www.changiairport.com/)|[![](/images/esplanade.jpg)](https://www.esplanade.com/)|
|Gardens by<br>the bay|Lau Pa Sat|Changi<br>Airport|Esplanade|


An example of a Site Map using html:

<table>
<thead>
  <tr>
    <th colspan="2">Common Spaces</th>
    <th colspan="4">Special Rooms &amp;<br>eco-Environment Learning Spaces&nbsp;&nbsp;</th>
    <th colspan="2">Sport Facilities</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Main Driveway<br></td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Secret Garden</td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>The Main Mangrove</td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Indoor Sports Hall</td>
  </tr>
  <tr>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Foyer</td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Maths Room</td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Eco-Garden</td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Field</td>
  </tr>
  <tr>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Parade Square</td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Science Room</td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Permaculture and<br>Butterfly Garden</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Playground</td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Art Room</td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Experimental Pond</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Canteen</td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Music Room</td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Koi Pond</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>PAL Room</td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Flow Pond</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Library</td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Turtle Pond</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Computer Lab</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Learning Lab</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td><img src="/images/chicken.jpg" style="width:100px; aspect-ratio:1"></td>
    <td>Dental Clinic</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</tbody>
</table>