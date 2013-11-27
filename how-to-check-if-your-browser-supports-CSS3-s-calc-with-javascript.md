# How to check if your browser supports CSS3's calc with JavaScript
- Adonis K.
- varemenos
- 2013/11/27
- JavaScript
- published

Recently I had to use CSS3's calc() value for a website I had to design and it seemed ridiculous to include a whole library (modernizr) for just 1 css property value. So I decided to write a small script to detect if calc was supported by the browsers or not (and it seems like it's rather similar to Modernizr's way of detecting it).
So, here is the script:

<pre class="line-numbers"><code class="language-javascript">var myapp = myapp || {};

// returns true if your browser supports calc()
myapp.checkCalc = function (prefix = '') {
	var el = document.createElement('div');
	el.style.cssText = prefix + 'width: calc(1px);';
	return !!el.style.length;
};

// returns true if your browser supports any version of calc(), prefixed or not
myapp.checkAllCalc = function (prefix = '') {
	return myapp.checkCalc('-webkit-') || myapp.checkCalc('-moz-') || myapp.checkCalc();
};

// check webkit prefixed support
myapp.checkCalc('-webkit-');
// check moz prefixed support
myapp.checkCalc('-moz-');
// check unprefixed/spec support
myapp.checkCalc();

// or all of the above
myapp.checkAllCalc();</code></pre>
