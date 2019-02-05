CodeSnippet MathStats 8.x-1.x
---------------

CKEditor CodeSnippet MathStats module for Drupal 8.

## About this Module
Adds syntax highlighting support for Mathematics and Statistics heavy languages in HTML `<code>` regions. The list of supported languages is by no means all-inclusive so please, post an issue if you think the list should be updated.

## Requirements
- [drupal/codesnippet](https://www.drupal.org/project/codesnippet)

## Installation
**Note:** This module will clash with existing [highlight.js](https://highlightjs.org) libraries, you may need to build a [custom package](https://highlightjs.org/download) and place it in your libraries folder: `/<drupal-root>/libraries/codesnippet/lib/highlight`.

## Usage
To enable syntax highlighting, add the prefix "language-*" to any identifier listed in the table below to the class section of a code block.

**Example:**
```html
<code class="language-r"><code>
```

## Supported Languages
|Language|Identifier|
|:--- |:--- |
|Basic|basic|
|C/C++|cpp|
|Haskell|haskell|
|JSON|json|
|JavaScript|javascript|
|LaTeX/TeX|tex|
|Markdown|markdown|
|Matlab|matlab|
|Perl|perl|
|Python|python|
|R|r|
|SAS|sas|
|Scilab|scilab|
|STATA|stata|
