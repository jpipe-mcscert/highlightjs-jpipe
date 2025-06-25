# highlightjs-jpipe
Syntax Highlighting for jPipe, using Highlight.js engine

For usage, add the cdn to your assets folder, then reference it in your html as tags alongside a stylesheet, core highlightjs engine and a function call.

ex. <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js"></script>
    <script src="assets/jpipe.min.js"></script>
    <script>hljs.highlightAll();</script>

To reference your code, surround it with this tag: <pre><code class="language-jpipe">...</code></pre>

You should be all good to go now!

Here's a couple different stylesheets that work well with jpipe:
- https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github.min.css (light theme)
- https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/atom-one-dark.min.css (dark theme)

Implementation example can be found here: https://github.com/DarshanVShah/jpipe-syntax-ex