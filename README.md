## Overview 

Docs to Markdown convert a Doc to Markdown or HTML.

## How to use

1. Find Docs to Markdown in the Plugins tab. Click on it.
2. Use the Markdown or HTML buttons in the sidebar window to convert your document to either Markdown or HTML.
3. If you select part of the document, Docs to Markdown will convert only the selection. Otherwise it will convert the entire document.

## Options

- Demote headings (H1 → H2, etc.): If you have used multiple Heading 1 headings in your Doc, choose this option to demote all heading levels to conform with the following standard: single H1 as title, H2 as top-level heading in the text body. You may need to add an H1 to function as the title after conversion.
- HTML headings/IDs: Not all Markdown renderers handle Markdown-style IDs. If that is the case for your target platform, choose this option to generate HTML headings and IDs.
- Create base64 images: Select this option if you want images to be created in base64 format.
- Render HTML tags: By default, angle brackets (<) will be replaced by the &lt; entity. If you really want to embed HTML tags in your Markdown, select this option to preserve them. Or, if you just want to use an occasional HTML tag, you can escape the opening angle bracket like this: \<tag>text\</tag>.
- Suppress top comment: Removes the informational comment at the top of the output. Warnings and errors that result from the conversion will still be part of the output.

## How to install

Detailed instructions can be found in [ONLYOFFICE API documentation](https://api.onlyoffice.com/plugin/installation).