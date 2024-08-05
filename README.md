<!-- this is my notes -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{box-sizing: border-box;}
        html{
            font-family: lora, Georgia, serif;
            margin: 2em;
            font-size: 15px;
            line-height: 1.5;
        }
        body{
            margin: 2rem 1rem 4rem;
        }
    </style>
</head>
<body>
    <p>this is some text</p>
<p>this is more text</p> 
<p>this is <em>enough</em> <i>text</i> </p> 
<p>This is </p> some  <p>more text<p> here </p> </p>.
<hr>

<dl>
  <dt>unorderd<dt>
  <dd>test1<dd>

  <dt>ordered<dt>
  <dd>test2<dd>

  <dt>definition<dt>
  <dd>test3<dd>
</dl>
<hr>

<blockquote>
<p><q>this message is a blockquote</q></p>
<cite>- John Doe</cite>
</blockquote>

<p>
  The concert starts at <time datetime="20:00">20:00</time> and you'll be able to enjoy the band for at least
  <time datetime="PT2H30M">2h 30m</time>.
</p>
<time datetime="14:15:28.5"> 14:15:28.5</time><br>
<time datetime="2025-05-08">May 8, 2025</time>.
<hr>

<p>
    we can write <code>{color:green;}</code> in our CSS<br>
    &lt; &gt;
</p>
<hr>
Pre and code elements are often combined to display a code block with proper indentation. 
these elements are handy for conveying the structure and appearance of code, 
as well as other types of content.
<pre>
<code>
&lt;ul&gt;
&lt;li&gt;Flour&lt;/li&gt;
&lt;li&gt;Sugar&lt;/li&gt;
&lt;li&gt;Salt&lt;/li&gt;
&lt;/ul&gt;
</code>
</pre>
<hr>
subscript - characters set below the normal baseline of text
superscript - characters set above the normal baseline of text
<p>H<sub>2</sub>O</p>
<p>something that has a footnote.<sup>2</sup></p>

small usually used to convey that something has very little prominence.
like the fine print at the bottom of the page.
<small> 2019 Fancy Company</small>
<hr>
<h2>HTML Attributes</h2>
<b>Global atrributes </b>- class , id. provide a name to name HTML elements and reference them in other parts if the code stack.
other important global attributes: <b>lang, dir</b>
<p class="intro">this is the introduction</p>
<p class="intro" id="article-intro">this is the introduction</p>
<hr>
<h2>ARIA Roles</h2>
they are like extra attributes that we can add to HTML elements to make them more meaningful
and help browsers understand what they represent. come in play when we want to provide 
essential info to assistive tech like screen recorders, braille displays, magnifiers etc.
<hr>
<h2>Formatting HTML</h2>
<!-- this is formatted with styles in the head -->
Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit quaerat libero magni illo atque minima ipsa soluta eos sint animi.
&copy <!-- this is the symbol for the copyright -->
</body>
</html>
