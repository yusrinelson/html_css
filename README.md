<!-- this is my notes -->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            box-sizing: border-box;
        }

        html {
            font-family: lora, Georgia, serif;
            margin: 2em;
            font-size: 15px;
            line-height: 1.5;
        }

        hr {
            border: 1px solid rgb(0, 195, 255);
        }

        body {
            margin: 2rem 1rem 4rem;
        }

        .navbar {
            border: 1px solid black;
            display: flex;
            align-items: center;
            justify-content: space-between;
            list-style: none;
            padding: 10px;
        }

        article {
            border: 1px solid black;
            padding: 10px;
            margin-bottom: 5px;
        }

        article .bilingual {
            font-weight: 600;
            color: rgb(58, 116, 143);
        }

        article .box {
            color: green;
        }
        form{
            display: flex;
            justify-content: center;
            flex-direction: column;
        }
        label{
            padding: 10px;

        }
        button{
            width: fit-content;
            padding: 10px;
        }
    </style>
</head>

<body>
    <p>this is some text</p>
    <p>this is more text</p>
    <p>this is <em>enough</em> <i>text</i> </p>
    <p>This is </p> some <p>more text
    <p> here </p>
    </p>.
    <hr>

    <dl>
        <dt>unorderd
        <dt>
        <dd>test1
        <dd>

        <dt>ordered
        <dt>
        <dd>test2
        <dd>

        <dt>definition
        <dt>
        <dd>test3
        <dd>
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
    <b>Global atrributes </b>- class , id. provide a name to name HTML elements and reference them in other parts if the
    code stack.
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
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit quaerat libero magni illo atque minima ipsa soluta
    eos sint animi.
    &copy <!-- this is the symbol for the copyright --> <br>
    we can use special characters for non breaking space. this tells the browser not to break the line between two
    words.
    we an use:
    "&nbsp" to insert a non-breaking space between the two names, ensuring they stay on the same line.
    <p>Lionel&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Messi</p>
    <hr>
    <h2>HTML Navigation and Linking</h2>
    href - hypertext reference
    HTTP - Hypertext Transport Protocol.
    When we want to create a link, we use the A element, which stands for anchor. To do this, we need to add an href
    attribute with a URL enclosed in quotes.
    absolute URL= point out the precise location on the web. HTTPS(the is "S" = secure)/HTTP must be included.
    <hr>
    <h2>HTML URL Pathways</h2>
    relative URL is not only useful for the A element linking but it is also a skill used to reference image files,
    video files, CSS, JavaScript files, or any other where a file’s path is specified.
    /images/logo.gif - creates a URL that is relative to the root level.
    ../images/logo.gif - creates a URL that is relative to the location of the file where the URL is written.
    <br><br>
    URLs can be either relative or absolute. Relative URLs are based on the current file's location, while absolute URLs
    start from the root of the website.
    By using folders and index.html files, we can create clean and user-friendly URLs.
    <hr>
    <h2>Navigation</h2>
    main navigation
    <nav role="navigation" aria-label="main">
        <ul class="navbar">
            <li>Home</li>
            <li>Blog</li>
            <li>Price</li>
        </ul>
    </nav>
    <br>
    breadcrumbs
    <nav role="breadcrumb" aria-label="breadcrumbs">
        <ol class="navbar">
            <li>Home</li>
            <li>Blog</li>
            <li>Price</li>
        </ol>
    </nav>
    <hr>
    <h2>HTML Working with Graphics and Images</h2>
    4 attributes: src, alt, width, height
    <br>
    <img src="" alt="" width="200" height="200">
    <br>
    4 main file formats: gif, svg, jpg, png
    <br><br>
    <picture>
        <source media="{min-width:600px}"
            srcset="https://plus.unsplash.com/premium_photo-1711031505781-2a45c879ceac?q=80&w=1315&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            320w>
        <img src="https://plus.unsplash.com/premium_photo-1711031505781-2a45c879ceac?q=80&w=1315&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            alt="" width="250" height="250">
    </picture>
    <hr>
    <h2>Working With Media</h2>
    <audio controls src="./media/tunnel-rain-193023.mp3"></audio><br>
    audio files has pre built audio controls. we can create our own using JavaScript & HTML media element API.
    other attributes are loop-repeats a media. Autoplay-automatically play the audio as soon as the page loads.
    opening and closing tag for the audio element is so that source element can be used to specify multiple audio files.
    <hr>
    <h2>Working with Video</h2>
    <video controls>
        <source src="./media/14037-254146876_tiny.mp4" type="video/mp4">
        <track src="./media/sample.vtt" kind="captions" label="English" srclang="en" default>
    </video><br>
    note* captions is vtt files.
    video that is 480p compressed using H.264codec and delivered as an mp4 file =
    480 lines of resolution & 720pixels wide by 400pixels tall. <br>
    ibvtt - web video text tracks.It is a simple text file with a vtt extension that follows a specific convention for
    providing information.
    <br>
    embedding - taking content from one site and placing it within the middle of another sites page.
    content that can be embedded- map from google, code demo from codepen, slide deck from speaker deck.
    <br>
    <!-- using iframe example -->
    <iframe width="640" height="360" src="https://www.youtube.com/embed/mdBjkTdoXDM"
        title="When You Wanna Study, Sleep, or Just Relax 🍀 Lofi Save Your Soul 🍁 Deep Focus - Lofi Hip Hop"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
    </iframe><br>
    note* the browser cant choose from when loading a video. it only adapts to circumstances needed.
    <hr>
    <h2>HTML Content Identification</h2>
    The lang attribute is used to specify the language of a webpage.
    using "meta charset='UTF-8'" to inform the browser about the character set being used
    <hr>
    <h2>HTML Generic Elements, Div and Span</h2>
    <pre>
    <code>
        &ltdiv&gt - to block level element
        &ltspan&gt - inline level element
    </code>
</pre>


    <article>
        <h1>this is the headline</h1>
        <div class="box">
            <p>first paragraph</p>
            <p>second paragraph <span lang="latin" class="bilingual">Lorem ipsum dolor sit amet.</span></p>
            <p>third paragraph</p>
        </div>
    </article>
    Both div and span can make use of various global attributes like class, id, lang, and aria roles.
    <hr>
    <h2>HTML Integration</h2>
    <b>crucial parts every webpage needs.</b>
    <ol>
        <li>should begin with doctype statement, which indicate the era of the HTML file.</li>
        <li>enclose everything else within the HTML element.</li>
        <li>declare the language being used</li>
    </ol>
    inside the HTML element it consists if head and body. the head contains all the metadata. eg charset, links to files
    etc
    the body contains all the content. <br>

    <b>example:</b>
    <pre>
        &lthtml&gt
        &lthead&gt
            &ltmeta charset="utf-8"&gt
            &lttitle&gtOur test webpage&lt/title&gt
            &lt/head&gt
            &ltbody&gt
                &lth1&gtthis is a headline&lt/h1&gt
                &ltp&gtthere is alot more in here&lt/p&gt
            &lt/body&gt
        &lt/html&gt
    </pre>
    note* The HTML head serves as a central hub for connecting and setting up various components,
    ensuring that all assets are loaded and sharing page information with other sites and platforms. In a way,
    it is like the headquarters for getting the page off to a good start.
    <hr>
    <h2>Content Structuring</h2>
    <b> 6 important elements to understand inside the body</b>
    <ol>
        <li>main</li>
        <li>header</li>
        <li>foooter</li>
        <li>article</li>
        <li>section</li>
        <li>aside</li>
    </ol>
    <hr>
    <h2>Form Fundamentals</h2>
    to create a form start with form element. then lable element for the names eg. email, password
    then the input(does not hav a closing tag) which has a type to specify the type of input it is.
    buttons can be customised to your liking , we can add an ation and method to make a demo work.
    <br><br>
    <form action="success.html" method="get">
        <label for="name">Name
            <input 
                type="text" 
                name="name"
                placeholder="full name">
        </label>

        <label for="email">Email
            <input 
                type="email" 
                name="email" 
                id="email"
                placeholder="e-mail" 
                required
                >
        </label>

        <label for="password">Password
            <input 
                type="password" 
                name="password" 
                id="password" 
                placeholder="password"
            >
        </label>

        <label for="search">search
            <input type="search" name="search" id="search" placeholder="search">
        </label>

        <label for="email">Phone Number
            <input 
                type="tel" 
                name="phone" 
                id="phone"
                placeholder="cell number"
                >
        </label>

        <label for="textarea">Text Area
            <textarea name="" id="" cols="30" rows="10"></textarea>
        </label>

        <label for="date">Date
            <input type="date" name="date" id="date">
        </label>

        <label for="color">Color
            <input type="color" name="color" id="color">
        </label>
        <label for="checked">checked
            <input type="checkbox" name="checkbox" id="checkbox" checked>
        </label>
        <button type="submit">Sign Up</button>
    </form><br>

</body>

</html>
