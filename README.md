jsURL
=====

Finally, a quick easy way to get url variables with JavaScript.

Installation
=====

Download jsURL and put this in the &lt;head&gt; of your code:

<pre>&lt;script type="text/javascript" src="../path/to/jsURL.js"&gt;&lt;/script&gt;</pre>

Usage
=====

To get the value of a URL parameter/variable use <pre>getValue("key");</pre>

Key meaning the name of the parameter/variable.

Example Usage
=====

Not getting it? That's cool. Here's a simple usage example to help you out.

<b>Example URL:</b> yourwebsite.com/yourpage.html?yourvariablehere=yourvaluehere

<pre>var urlparam = getValue("yourvariablehere");</pre>

The script would then get the value of the varible in the address and return the value <i>"yourvaluehere"</i>, so the value of variable in your script would become <b>yourvaluehere</b>. Make sense?

Credits & Notes
=====
I got this script a long time ago from an unknown source. But I've used it for over 2-3 years now, and and in that time I've actually improved it and thought I should share it with other coders. I in no way am saying this is 100% mine, but it was a lot worse before I improved it. Before, if your variable values had spaces, it would put <b>your+value+here</b>, annoying huh! But a simple url encoding and a lot of syntax and research fixed that. If you have any trouble feel free to contact me, I'd love to help you. I've been using this script for about 2-3 years and have done just about everything with it. I hardly use it anymore now that I've moved on to PHP (it seems intimidating but it just looks that way) and thought I shouldn't keep it to myself. Can't wait to see what you do with it! Cheers!

Need help or have suggestions?
=====
Contact me on <a href="http://brandon-jordan.weebly.com/contact-me">my website</a>, I've used this script for 2-3 years and have a lot of experience with it, and anything I don't know about, I'm willing to at least try to help you with.
