---
layout: post
title: Project
description: a project with a background image
img: /img/Robotic arm.jpg
---
Technology is critical for innovation, and innovation is how people, or even the whole human mankind moves forward.  

So after making the automatic curtain opener, what can I do to make something for myself?

A robotic arm. Ta-DA! Fully customizable! The best thing about the robotic arm, with the Arduino is that I can make it do whatever I want, whenever I want!
<div class="img_row">
	<img class="col two" src="{{ site.baseurl }}/img/Robotic arm.jpg" alt="" title="Robotic arm"/>
</div>	
This robot runs on Arduino and takes my programming skills to the next level. I bought the robotic arm kit with 


Every project has a beautiful feature shocase page. It's easy to include images, in a flexible 3-column grid format. Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so: 

	---
	layout: post
	title: Project
	description: a project with a background image
	img: /img/12.jpg
	---


<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/img/1.jpg" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/2.jpg" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/3.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
	Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/5.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
	This image can also have a caption. It's like magic. 
</div>

You can also put regular text between your rows of images. Say you wanted to write a little bit about your project before you posted the rest of the images. You describe how you toiled, sweated, *bled* for your project, and then.... you reveal it's glory in the next row of images.


<div class="img_row">
	<img class="col two" src="{{ site.baseurl }}/img/6.jpg" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/11.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
	You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


<br/><br/><br/>


The code is simple. Just add a col class to your image, and another class specifying the width: one, two, or three columns wide. Here's the code for the last row of images above: 

	<div class="img_row">
	  <img class="col two" src="/img/6.jpg"/>
	  <img class="col one" src="/img/11.jpg"/>
	</div>
