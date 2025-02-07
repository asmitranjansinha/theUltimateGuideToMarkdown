# What is Markdown?

_**Markdown** is a plain text formatting syntax for writers. It allows you to quickly write structured content for the web, and have it seamlessly converted to clean, structured HTML._

Markdown is widely used for formatting readme files, writing messages in online discussion forums, and creating rich text using a plain text editor. Its simplicity and readability make it a popular choice for developers, writers, and content creators.

## Basic Markdown Formatting

### Headings

Headings are created by adding one to six `#` symbols before your heading text. The number of `#` symbols corresponds to the level of the heading.

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

### Text

You can format text to be italic, bold, or bold-italic using asterisks (`*`) or underscores (`_`).

```
*italic* or _italic_
**bold**
***bold-italic***
```

**_To add a link: wrap the text which you want to be linked in square brackets, followed by the URL to be linked to in parenthesis._**

```
[text](URL)
```

Example: [Refresh](https://github.com/asmitranjansinha/theUltimateGuideToMarkdown)

### Images

Markdown images have exactly the same formatting as a link, except they’re prefixed with a `!`. This time, the text in brackets is the alt text - or the descriptive text for the image.

```
![ImageTitle](ImageUrl)
```

![DisasterGirl](https://ichef.bbci.co.uk/news/976/cpsprodpb/F1F2/production/_118283916_b19c5a1f-162b-410b-8169-f58f0d153752.jpg.webp)

### Lists

#### Unordered Lists

For a bullet list, just prefix each line with a `*`, `-`, or `+`. You can also create nested lists; just indent a line with 4 spaces and it will be nested under the line above.

```
* Main
* Main
    * Sub
* Main
```

Example:
- Feature
- Feature
  - Components
- Feature

#### Ordered Lists

Ordered lists are created by prefixing each line with a number followed by a period.

```
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item
```

Example:
1. Step 1
2. Step 2
3. Step 3
    1. Sub-step 1
    2. Sub-step 2
4. Step 4

### Quotes

Blockquotes are created by prefixing the line with a `>` symbol.

```
> Your quotes go here.
```

Example:
> I drink and I know things!  
> -Tyrion

### Code

Inline code can be created by wrapping text in backticks (`` ` ``).

```
This is `inline code`.
```

For code blocks, wrap the code in triple backticks (``` ``` ```) or indent each line with 4 spaces.

    ```
    function helloWorld() {
        console.log("Hello, world!");
    }
    ```

Example:
```javascript
function helloWorld() {
    console.log("Hello, world!");
}
```

### Horizontal Rules

Horizontal rules can be created by using three or more hyphens (`-`), asterisks (`*`), or underscores (`_`).

```
---
```

Example:
---

### Tables

Tables can be created using pipes (`|`) and hyphens (`-`).

```
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1    | Data     | Data     |
| Row 2    | Data     | Data     |
```

Example:
| Syntax      | Description |
|-------------|-------------|
| Header      | Title       |
| Paragraph   | Text        |

### Task Lists

Task lists can be created using `- [ ]` for unchecked items and `- [x]` for checked items.

```
- [x] Completed task
- [ ] Incomplete task
```

Example:
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Escaping Characters

If you need to display a character that is used for formatting in Markdown, you can escape it using a backslash (`\`).

```
\*This is not italic\*
```

Example:
\*This is not italic\*

### Inline HTML

If you need more control over your content, you can use inline HTML within your Markdown.

```
<p style="color:red;">This is a red paragraph.</p>
```

Example:
<p style="color:red;">This is a red paragraph.</p>

### Footnotes

Footnotes can be added using the following syntax:

```
Here is a footnote reference,[^1] and another.[^2]

[^1]: This is the first footnote.
[^2]: This is the second footnote.
```

Example:
Here is a footnote reference,[^1] and another.[^2]

[^1]: This is the first footnote.
[^2]: This is the second footnote.

### Strikethrough

Strikethrough text can be created using two tildes (`~~`).

```
~~This text is strikethrough.~~
```

Example:
~~This text is strikethrough.~~

### Emojis

You can add emojis by using the appropriate shortcode.

```
:smile: :heart: :rocket:
```

Example:
:smile: :heart: :rocket:

### Advanced Formatting

#### Definition Lists

Some Markdown processors support definition lists.

```
Term 1
: Definition 1

Term 2
: Definition 2
```

Example:
Term 1
: Definition 1

Term 2
: Definition 2

#### Abbreviations

Some Markdown processors support abbreviations.

```
*[HTML]: HyperText Markup Language
*[CSS]: Cascading Style Sheets

The HTML specification is maintained by the W3C.
```

Example:
*[HTML]: HyperText Markup Language
*[CSS]: Cascading Style Sheets

The HTML specification is maintained by the W3C.

#### Superscript and Subscript

Some Markdown processors support superscript and subscript.

```
H~2~O and 2^10^
```

Example:
H~2~O and 2^10^

***May or may not get updated, Come back to check!***

This is my ultimate guide to Markdown readme. Feel free to contribute and add more content to this guide!
