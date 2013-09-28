# A thought towards stregthening the autocomplete feature of Text Editors
- Adonis K.
- varemenos
- 2013/09/23
- General
- published

There is a way to make auto-complete better, more accurate by parsing thousands of paragraphs and creating lists of keyword-lists which are ordered lists of words that are possible to appear after typing the selected keyword. For example most of the JavaScript users would expect after typing `console` to get a suggestion of the keyword `log`, so the keyword-list named console will most probably have the keyword `log` at it's first list-node.

> Had this idea in my mind for a while now, never had the guts or the time to try implement it or research if someone else has tried implementing it but hear me out you might be inspired with an even better idea.
A lot of us use powerful IDEs and Text Editors that help us code faster by using snippets and auto-complete features which are great but not _truly_ great and thus what I want to suggest today is a way of enhancing the 2nd of the features I mentioned earlier which is auto-complete. We all know that most of the times the accuracy of the auto complete/suggest feature is weak (usually because it doesn't have any intelligence at all and just filters the words you are typing).


Visual example:

<pre class="line-numbers">
<code class="language-javascript">list = {
	window: [...],
	document: [...],
	...,
	console: [
		"log",
		"assert",
		"time",
		...,
		"dir",
		"count"
	]
}</code>
</pre>

I guess you are now wondering how we will manage to seed such lists, that could most probably happen by using a crawl-bot in open source projects (on GitHub for example). After forking and categorizing the files by programming language and removing comments and strings, we can then start using self-learning neural systems to filter out those forked projects and get some accurate results.

After we've created the keyword-lists, we could then implement the auto-complete feature via a plugin/extension system.

Due to exams and other responsibilities I have right now I couldn't write more details about this, so later in the future I will write the second part which will describe how to implement this.
