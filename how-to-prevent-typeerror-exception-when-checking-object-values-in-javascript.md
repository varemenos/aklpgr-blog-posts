# How to prevent TypeError Exception when checking object values in JavaScript
- Adonis K.
- varemenos
- 2013/11/11
- javascript
- published

I'm certain a lot of you have had this issue in the past, I did too. So, let me demostrate to you have to quickly solve this issue without almost no change in your current code.

<pre class="line-numbers">
<code class="language-javascript">var person = {};
if(person.name.first === "John"){
	console.log(person.name.first);
}</code>
</pre>

The code above will output the following error string `Uncaught TypeError: Cannot read property 'first' of undefined` in the JavaScript console. To fix this issue, you need to first check whether the object path you are trying to check exists.

<pre class="line-numbers">
<code class="language-javascript">var person = {};
if(person.name && person.name.first === "John"){
	console.log(person.name.first);
} else {
	console.log('no name given to this person');
}</code>
</pre>

This way you won't get any errors or broken code in production. There is another way to fix  this by using a `try catch` block as following:

<pre class="line-numbers">
<code class="language-javascript">var person = {};
try {
	if(person.name.first === "John"){
		console.log(person.name.first);
	}
} catch (e) {
	console.log(e.message);
}</code>
</pre>
