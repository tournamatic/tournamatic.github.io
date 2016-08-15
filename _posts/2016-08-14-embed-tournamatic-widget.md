---
published: true
---

## Add Tournamatic Widget to your Website

Tournamatic makes it very easy to create a web page for your tournament.
This web page can contain all the information you want to communicate with your participants and teams, allow them to register for a division/draw in the tournament and access schedules and results.

However, some tournament organizers already have a website. 
This website could be just designed for the tournament or it could be a club or association website that has a tournament section.
I am very excited to announce that you can now insert Tournamatic widget on your website.
After you create your tournament on [Tournamatic](https://tournamatic.com), you can embed Tournamatic widget that represents your tournament, anywhere on your website.
By inserting Tournamatic widget you can reap the benefits of a powerful tournament management engine and at the same time produce a seamless experience for your users and allow them to take advantage of Tournamatic services from within your own website.

### How?

It’s as easy as copying and pasting. All you need is to add two lines to your html page.

Add the following html piece to the bottom of your document right before closing body (</body>) tag.
Replace data-tournament value with your own tournament identifier. See Parameters section for details.

	<div id="tournamatic-entry-widget" data-tournament="10" data-width="100%" data-height="800"></div>
	<script src="https://tournamatic.com/asset/widget.js"></script>

Here is a simple html where has the Tournamatic widget inserted in:

	<!DOCTYPE HTML>
	<html lang="en">
	<head>
		<meta http-equiv="content-type" content="text/html; charset=utf-8">
		<title></title>
	</head>
	<body>
		<div id="tournamatic-entry-widget" data-tournament="10" data-width="100%" data-height="800"> </div>
		<script src="https://tournamatic.com/asset/widget.js"></script>
	</body>
	</html>

### Parameters

Tournament identifier: **data-tournament** is your tournament id which is emailed to you when you created your tournament.

Width: **data-width** is the width of the container of the widget. It can be in percentage like 100% or in pixels if you set it to a number.

Height: **data-height** is the height of the container of the widget. It has to be in pixels so you need to set it to a number.
