##Automatic code detection and prettifying for phpbb3 using Google Prettify 

This is a mod for phpbb3 working on `3.0.11`

What is does is very simple. 

**1:** it loads [Google Prettify](http://code.google.com/p/google-code-prettify/) into the `overall_header.html` of Prosilver.

**2:** It adds a `class="prettyprint"` to the existing and built in phpbb 3 `[code]` tag. 


What does this mean? Well it means two things to the end user.

**First :** All code used in the stock code tags will be detected and if matched, prettified by Google Prettify automatically. (the sons of obsidian css is being used here)

![](https://raw.github.com/randomessence/gPrettifyphpbb3mod/master/contrib/examples/code.png)

**Second :** Google prettify is loaded onto the board and can be used with custom bbcodes to have a more customised display.

**bbcode** using a `<pre>` tag 

`<pre class="prettyprint">{TEXT}</pre>`

or

`<pre class="prettyprint"><code>{TEXT}</code></pre>`

will give a result like this


![](https://raw.github.com/randomessence/gPrettifyphpbb3mod/master/contrib/examples/bbcodecode.png)

you can do this for example:

`<pre class="prettyprint" style="border-radius:5px;"><code>{TEXT}</code></pre>`

-------------

extra themes are from

https://github.com/jmblog