# lazy-load-images-with-echo-js
Images are some of the specific drivers of increased page load times. Improperly sized images can cause significant issues as your users must wait and wait as the images load. Research regularly indicates that the longer a user must wait for the page to load (especially on mobile), the greater the chance they will simply leave. Because of this, it's more important than ever to make sure your images are optimized in terms of dimensions and that your UI can load within a reasonable amount of time.

A fantastic solution is offered in [Echo.js](https://github.com/toddmotto/echo). With this standalone script, you can easily add a placeholder loading image while your main images are only initiated when the user's viewpoint accesses them. The overall effect is a graceful lazy loading display that significantly improves your sites functional accessibility.

## Tutorial

For detailed instructions, view Solodev's [Lazy Load Images with Echo.js](https://www.solodev.com/blog/lazy-load-images-with-echo-js.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/7c7mpuaw/).

## HTML

The lazy loading component contains the following basic HTML markup:
```
<div class="container lazyImages">
	<div class="row">
		<div class="col-md-6">
			<img alt="Image 1" src="https://www.solodev.com/assets/lazy-load-with-echo/image-loader.gif" data-echo="https://www.solodev.com/assets/lazy-load-with-echo/image1.jpg">
		</div>
		<div class="col-md-6">
			<img alt="Image 2" src="https://www.solodev.com/assets/lazy-load-with-echo/image-loader.gif" data-echo="https://www.solodev.com/assets/lazy-load-with-echo/image2.jpg">
		</div>
	</div>
	<div class="row">
		<div class="col-md-6">
			<img alt="Image 3" src="https://www.solodev.com/assets/lazy-load-with-echo/image-loader.gif" data-echo="https://www.solodev.com/assets/lazy-load-with-echo/image3.jpg">
		</div>
		<div class="col-md-6">
			<img alt="Image 4" src="https://www.solodev.com/assets/lazy-load-with-echo/image-loader.gif" data-echo="https://www.solodev.com/assets/lazy-load-with-echo/image4.jpg">
		</div>
	</div>
	<div class="row">
		<div class="col-md-6">
			<img alt="Image 5" src="https://www.solodev.com/assets/lazy-load-with-echo/image-loader.gif" data-echo="https://www.solodev.com/assets/lazy-load-with-echo/image5.jpg">
		</div>
		<div class="col-md-6">
			<img alt="Image 6" src="https://www.solodev.com/assets/lazy-load-with-echo/image-loader.gif" data-echo="https://www.solodev.com/assets/lazy-load-with-echo/image6.jpg">
		</div>
	</div>
	<div class="row">
		<div class="col-md-6">
			<img alt="Image 7" src="https://www.solodev.com/assets/lazy-load-with-echo/image-loader.gif" data-echo="https://www.solodev.com/assets/lazy-load-with-echo/image7.jpg">
		</div>
		<div class="col-md-6">
			<img alt="Image 8" src="https://www.solodev.com/assets/lazy-load-with-echo/image-loader.gif" data-echo="https://www.solodev.com/assets/lazy-load-with-echo/image8.jpg">
		</div>
	</div>
	<div class="row">
		<div class="col-md-6">
			<img alt="Image 9" src="https://www.solodev.com/assets/lazy-load-with-echo/image-loader.gif" data-echo="https://www.solodev.com/assets/lazy-load-with-echo/image9.jpg">
		</div>
		<div class="col-md-6">
			<img alt="Image 10" src="https://www.solodev.com/assets/lazy-load-with-echo/image-loader.gif" data-echo="https://www.solodev.com/assets/lazy-load-with-echo/image10.jpg">
		</div>
	</div>
</div>
```
## CSS

All required CSS can be found in lazy-load-images.css

## JS

All needed JS is below and should be included inline:
```
<script>
  echo.init();
</script>
```

## External Includes

This tutorial contains the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
<link href="lazy-load-images.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script src="https://rawgit.com/toddmotto/echo/master/dist/echo.js"></script>
```


