# highlightjs-jpipe
Syntax Highlighting for JPipe, using Highlight.js engine

## Installation

This package provides syntax highlighting for the JPipe language using Highlight.js. To use it, you need to include both the Highlight.js core library and this language definition.

## Usage

### CDN Setup

Add the following to your HTML:

```html
<!-- Highlight.js core library and a theme -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js"></script>

<!-- Add jpipe cdn to your assets folder and reference it -->
<script src="assets/jpipe.min.js"></script>

<!-- Initialize highlighting -->
<script>hljs.highlightAll();</script>
```

### Code Blocks

Wrap your JPipe code with the following HTML:

```html
<pre><code class="language-jpipe">
// Your JPipe code here
</code></pre>
```

## Recommended Themes

Here are some stylesheets that work well with JPipe syntax highlighting:

- **Light theme**: `https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github.min.css`
- **Dark theme**: `https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/atom-one-dark.min.css`

## Examples

For a complete implementation example, see: https://github.com/DarshanVShah/jpipe-syntax-ex

## Development

This package is designed to work with Highlight.js v11.0.0 and above. The main language definition is located in `src/languages/jpipe.js`.