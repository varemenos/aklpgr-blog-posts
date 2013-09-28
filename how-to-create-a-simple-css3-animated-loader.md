# How to create a simple CSS3 animated loader
- Adonis K.
- varemenos
- 2013/09/28
- CSS
- published

In this tutorial I will show you how to create a simple CSS3 animated loader by only using 1 HTML element.

## The markup

As mentioned before for the markup we are only going to use 1 element with the class of `spinner`

	<span class="spinner"></span>

## The CSS

For CSS we need to use the triangle CSS trick that became viral a couple of years ago which we will then add some radius to remove the rough corners. After that we will add a CSS3 animation which will spin the element around itself by using `transform: rotate()`.

	.spinner {
		display: inline-block;
		width: 0;
		height: 0;
		border: solid 30px;
		border-radius: 5em;
		border-color: #0099ff transparent #0099ff transparent;
		animation: spin 1s linear infinite;
	}

	@keyframes spin {
		0% {
			transform: rotate(0deg);
		}

		100% {
			transform: rotate(360deg);
		}
	}

## Alternative Style

	.spinner {
		display: inline-block;
		width: 0;
		height: 0;
		border: solid 30px;
		border-radius: 5em;
		border-color: transparent transparent #0099ff transparent;
		animation: spin 1s linear infinite;
	}

	@keyframes spin {
		0% {
			transform: rotate(0deg);
		}

		100% {
			transform: rotate(360deg);
		}
	}

## Demo

<p data-height="244" data-theme-id="0" data-slug-hash="EeulL" data-user="varemenos" data-default-tab="result" class='codepen'>See the Pen <a href='http://codepen.io/varemenos/pen/EeulL'>CSS3 Loaders</a> by Adonis K. (<a href='http://codepen.io/varemenos'>@varemenos</a>) on <a href='http://codepen.io'>CodePen</a></p>
<script async src="http://codepen.io/assets/embed/ei.js"></script>
