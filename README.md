
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Example of text formatting tags and meta tags in HTML">
    <meta name="author" content="Your Name">
    <meta name="keywords" content="HTML, text formatting, meta tags">
    <title>Text Formatting Example</title>
    <style>
        .bold {
            font-weight: bold;
        }
        .italic {
            font-style: italic;
        }
        .underline {
            text-decoration: underline;
        }
        .strikethrough {
            text-decoration: line-through;
        }
        .superscript {
            vertical-align: super;
            font-size: smaller;
        }
        .code {
            font-family: monospace;
            background-color: #eee;
            padding: 2px;
        }
        .preformatted {
            white-space: pre-wrap;
            font-family: monospace;
        }
        blockquote {
            border-left: 2px solid #ccc;
            padding-left: 10px;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <h1 class="bold">Text Formatting Example</h1>
    <p>
        This is <span class="bold">important</span> text.
        This is <span class="italic">emphasized</span> text.
        This is <span class="underline">underlined</span> text.
        This is <span class="strikethrough">strikethrough</span> text.
        This is <span class="superscript">superscript</span> and this is <span class="code">code</span> text.
        <span class="tel">Tell me</span>
        <span class="arrow">&darr;</span>
    </p>
    <h2>Formatting Tags Demonstration</h2>
    <p>
        These tags will be used to make <span class="bold">bold</span>, <span class="italic">italic</span>, and <span class="underline">underline</span> styles.
        <br>
        This is <span class="preformatted">preformatted</span> text. It preserves white space and line breaks.
    </p>
    <blockquote>
        This is a block quote. It can be used to indicate a long quotation that is set off from the main text.
    </blockquote>
    <p>
        Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller <span class="superscript">font</span>.
        <br>
        Superscript text can be used for footnotes like <span class="superscript">www.</span>
    </p>
</body>
</html>
