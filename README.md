# p5js

Get Started
This page walks you through setting up a p5.js project and making your first sketch. Processing users may want to check out the Processing transition tutorial.

Download and File Setup
The easiest way to start is by using the empty example that comes with the p5.js complete download.

If you look in index.html, you'll notice that it links to the file p5.js. If you would like to use the minified version (compressed for faster page loading), change the link to p5.min.js.
```html
<script src="../p5.min.js"></script>
 ```
Alternatively, you can link to a p5.js file hosted online. All versions of p5.js are stored in a CDN (Content Delivery Network). You can see a history of these versions here: p5.js CDN. In this case you can change the link to:
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.6.1/p5.js"></script>
```
A sample HTML page might look like this:

```html
<html>
  <head>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.6.1/p5.js"></script>
    <script src="sketch.js"></script>
  </head>
  <body>
  </body>
</html>
```
You can also start with this template
