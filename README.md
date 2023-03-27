# Markdown Demo

A basic example of most available Markdown syntax.

## Headings

Headings are added using a `#` for heading level one, `##` for heading level two, etc...

## Heading Level Two

```markdown
## Heading Level Two
```

## Paragraphs

Paragraphs are added by simply adding text on their own line.

```markdown
This is a a paragraph.

And this is another paragraph. 
```

## Links

Links are added using square brackets for the clickable part and round brackets for the URL.

```markdown
[codeadam.ca](https://codeadam.ca)
```

## Images

Images are added imilarly to links. The image description is placed in square brackets, and a URL to the image is placed in the round brackets. The different between an image and a link, is that an image stats with an exclamation mark `!`.

This image:

![codeadam.ca logo](https://raw.githubusercontent.com/codeadamca/markdown-demo/main/logo.png)

Was added using this code:

```markdown
![codeadam.ca logo](https://raw.githubusercontent.com/codeadamca/markdown-demo/main/logo.png)
```

## Adding Code to Markdown

You can add inline `code` using a single backtick. Or a block of code using thee backticks:

```
# This is a Level One Header
## This is a Level Two Header
```

You can specify the language in a block of code after the three ticks:

```markdown
# This is a Level One Header
## This is a Level Two Header
```

Here is some sample JavaScript:

```javascript
document.write("Hello World!");
```

## Tables

To add tables to a Markdown documnet you use a series of dashes and bars:

| Heading 1      | Heading 2     | Heading 3     |
| -------------- | ------------- | ------------- |
| Value 1        | Value 2       | Value 3       |

Tables in your Markdown file don't need to line up:

Heading 1 | Heading 2 | Heading 3
--- | --- | ---
Value 1 | Value 2 | Value 3

## Lists

You can add lists using number `<ol>` or dashes `<ul>`:

1. This is the first list item.
2. This is the second list item.

    This is the second paragraph in the second list item.

3. This is the third list item.

## Tutorial Requirements:

* [Visual Studio Code](https://code.visualstudio.com/) 
* [Markdown Guide](https://www.markdownguide.org/)
* [Markdown](https://daringfireball.net/projects/markdown/)

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="100">
</a>
