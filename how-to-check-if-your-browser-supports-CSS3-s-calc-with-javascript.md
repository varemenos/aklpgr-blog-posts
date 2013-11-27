# How to check if your browser supports CSS3's calc with JavaScript
- Adonis K.
- varemenos
- 2013/11/27
- JavaScript
- published

Recently I had to use CSS3's calc() value for a website I was designing and it seemed ridiculous to include a whole library (Modernizr) for just 1 CSS property's value. So I decided to write a small script to detect if calc was supported by the browsers or not (and it seems like it's rather similar to Modernizr's way of detecting it).
So, here is the script:

<pre class="line-numbers"><code class="language-javascript">
// returns true if your browser supports calc()
checkCalc = function (prefix = '') {
	var el = document.createElement('div');
	el.style.cssText = prefix + 'width: calc(1px);';
	return !!el.style.length;
};

// returns true if your browser supports any version of calc(), prefixed or not
checkAllCalc = function (prefix = '') {
	return checkCalc('-webkit-') || checkCalc('-moz-') || checkCalc();
};

// check webkit prefixed support
checkCalc('-webkit-');
// check moz prefixed support
checkCalc('-moz-');
// check unprefixed/spec support
checkCalc();

// or all of the above
checkAllCalc();</code></pre>
