Sublime Text HTML Page Snippets
===

Sublime Text snippets to generate the HTML5 page templates.


Install
---
Available at <b>Package Manager!</b> Just search for <b>HTML Page Snippets</b>.

or

Copy the files to your Packages directory.


Usage
---

With a blank file open, type "doc" or "docjq" or "docang" and press TAB.

<img src="http://www.burakkaya.com/lab/snippets/html-snippet.png"/>



Blank HTML Page
---

<b>tabTrigger</b>

	doc

<b>That generates:</b>

	  <!DOCTYPE html>
	  <html>
	  	<head>
	  		<title>Demo</title>
	  		<meta charset="utf-8">
	  		<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
	  	    <meta name="description" content="Demo project">
	  		<meta name="viewport" content="width=device-width, initial-scale=1">
	  		<link rel="stylesheet" href="http://netdna.bootstrapcdn.com/bootstrap/3.0.3/css/bootstrap.min.css">
	  		<style type="text/css"></style>
	  	</head>
	  	<body>
	  		<p>Let the game begin!
	  	</body>
	  	<script type="text/javascript"></script>
	  </html>


HTML Page with jQuery
---

<b>tabTrigger</b>

	docjq

<b>That generates:</b>

	<!DOCTYPE html>
	<html>
		<head>
			<title>Demo with jQuery</title>
			<meta charset="utf-8">
			<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
			<meta name="description" content="Demo project with jQuery">
			<meta name="viewport" content="width=device-width, initial-scale=1">
			<link rel="stylesheet" href="http://netdna.bootstrapcdn.com/bootstrap/3.0.3/css/bootstrap.min.css">	
			<style type="text/css"></style>
		</head>
		<body>
			<p>Let the game begin!</p>
		</body>
		<script src="http://code.jquery.com/jquery-1.10.2.min.js"></script>
		<script type="text/javascript">
			jQuery(function(){
			
			});
		</script>
	</html>
	
	
HTML Page with AngularJS
---

<b>tabTrigger</b>

	docang
	
<b>That generates:</b>	

	<!DOCTYPE html>
	<html>
		<head>
			<title>Demo</title>
			<meta charset="utf-8">
			<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
			<meta name="description" content="Demo project">
			<meta name="viewport" content="width=device-width, initial-scale=1">
			<script src="http://ajax.googleapis.com/ajax/libs/angularjs/1.2.6/angular.min.js"></script>
			<link rel="stylesheet" href="http://netdna.bootstrapcdn.com/bootstrap/3.0.3/css/bootstrap.min.css">
			<style type="text/css"></style>
		</head>
		<body ng-app>
			<p>Let the game begin!</p>
		</body>
		<script type="text/javascript"></script>
	</html>

HTML Page with ReactJS and JSX transformer
---

<b>tabTrigger</b>

	docrct
	
<b>That generates:</b>	

	<!DOCTYPE html>
	<html>
	    <head>
	        <title>Demo with React and JSX</title>
	        <meta charset="utf-8">
	        <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
	        <meta name="description" content="Demo project with React.js and JSX transformer">
	        <meta name="viewport" content="width=device-width, initial-scale=1">
	        <link rel="stylesheet" href="http://netdna.bootstrapcdn.com/bootstrap/3.0.3/css/bootstrap.min.css"> 
	        <style type="text/css"></style>
	    </head>
	    <body>
	        <div id="app"></div>
	    </body>
	    <script src="http://fb.me/react-0.12.2.min.js"></script>
	    <script src="http://fb.me/JSXTransformer-0.12.2.js"></script>
	    <script type="text/jsx">
	        /** @jsx React.DOM */
	            
	    </script>
	</html>

Building Package
---
<b>Build command for local install</b>

$> ./build &lt;dir name&gt;

<b>That generates:</b>

&lt;dir name&gt;/HTML Page Snippets.sublime-package