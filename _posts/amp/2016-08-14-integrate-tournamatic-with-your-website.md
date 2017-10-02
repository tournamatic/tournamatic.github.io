---
layout: amp-post
title: Integrate Tournamatic within your website
published: true
description: Integrate your website with tournamatic.com and represent your tournaments like a pro.
category: Sports
tags:
  - tournament
  - integration
  - widget
  - website
  - tournament page
  - embed
imageUrl: https://i.imgur.com/uiMT9dh.png
---


## Add the new Tournamatic widget to your website!

Tournamatic makes it quick and easy to create a webpage for your tournament, complete with all of the information needed for a successful event. Using Tournamatic, you can share venue details with your participants and teams. You can also use the page to accept registration and payments for divisions or draws in the tournament from players, as well as have one easy place for participants and fans to access the tournament’s schedule and results. Creating a tournament page on Tournamatic offers you a ton of great features so you can organize and host an amazing tournament.
<!--more-->
But you may **already have a website** set up for your tournament, either as a stand-alone site or as part of your club or association’s page, which means you probably don’t need another one. That’s why we’ve built a brand new feature that allows you to add a Tournamatic widget to your site! Once you’ve set up your tournament on [Tournamatic](https://tournamatic.com), you can add the Tournamatic widget anywhere on your website. The widget will allow you to reap the benefits of our powerful tournament management engine while also creating a seamless experience for your users. Both you and your users will be able to take advantage of all of Tournamatic’s services, directly from within your own site.

[Add your tournament to your own website](https://i.imgur.com/uiMT9dh.png)

### How can I add the Tournamatic widget to my site?

It’s as easy as copying and pasting two lines of code into the HTML of your page.
Add the following HTML code to the bottom of your document, right before closing body (</body>) tag.

	<div id="tournamatic-entry-widget" data-tournament="10" 
	data-width="100%" data-height="800"></div>
	<script src="https://tournamatic.com/asset/widget.js">
	</script>

Then replace the data-tournament value with your tournament’s identifier. (See the Parameters section for more details.)
Here is an example of a simple HTML page that has the Tournamatic widget added to it:

	<!DOCTYPE HTML>
	<html lang="en">
	<head>
		<title></title>
	</head>
	<body>
		<div id="tournamatic-entry-widget" data-tournament="10" 
		data-width="100%" data-height="800"> </div>
		<script src="https://tournamatic.com/asset/widget.js"></script>
	</body>
	</html>

### Parameters

The parameters used in the widget and their functions are as follows:

Tournament identifier: **data-tournament** is your tournament’s ID. 
The ID is created and emailed to you once you’ve completed the associated step as part of the tournament setup process on Tournamatic. 
You’ll need to change the data-tournament value to correspond with your tournament ID.

Width: **data-width** is the width of the container of the widget. 
It can be adjusted by percentage (like 100%) or by pixels, set by a number (ex. 600).

Height: **data-height** is the height of the container of the widget. 
This parameter can only be adjusted in pixels, set by a number (ex. 800).

Once you’ve adjusted the parameters to your liking, you’re done! Congratulations! You now have your very own Tournamatic widget displayed on your website. The widget is powered by our robust tournament management engine and offers all of Tournamatic’s comprehensive features, making it easy for you to organize and manage your tournament.
If you have questions or your widget isn’t displaying properly, please feel free to [contact us](https://tournamatic.com/#!/contact) for additional support.
