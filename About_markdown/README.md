#   INTRODUCTION
This is an over-view about the basic syntax used in markdown. Markdown has a similar syntax as
that of HTML but markdown is easier, simplier and easy to interpret when compared to HTML.

##  Document Structure
The tags that are used in HTML can also be integreted in markdown although markdown has its own tags.

### Headings
Headings `(h1, h2, h3, etc.)` are created in markdown using `#` symbol as in:
`#` - HEADING 1
<br />
`##` - HEADING 2
<br />
`###` - HEADING 3
<br />
etc.

```markdown
#   Heading 1
##  Heading 2
### Heading 3
etc.
```
Just like in HTML, we make use of the `<h1>` tag to make heading 1, the `#` symbol is used in markdown. You can optionally use the same number of hashes at the end of the line to close the headers.

### Horizontal rules
You can separate sections of a document using the `<hr /` tags. In markdown, these are created using three or more hyphens `---`, underscore `___`, asterisk `***` or equal sign `===`, place them alone on a blank line.

```markdown
This is an example of the usage of an horizontal rule in markdown
---
You can make use of an hyphen
___
You can make use of an underscore
***
You can make use of an asterisk
===
and you can amke use of an equal sign
```

### Lists
Creating unordered lists `<ul>` in markdown, you make use of the asterisk `*`, plus `+` or hyphen `-` at the beginning of each new line

<div width="350" backgroundColor="efefef">
*   this is
*   an unordered
*   list
<br />
-   this is
-   also an unordered
-   list
-   but makes use
-   of an hyphen `-`
</div>

Ordered lists `<ol>` are numbers that are followed by periods.
<div width="350" backgroundColor="efefef">
1.  this is
2.  an ordered
3.  list
</div>

Should in case you want to begin a line with a number that is not a list, you insert a backslash `\` before the period.
`2024\. A good year to remember ...`

Paragraphs of normal text are seperated by one or more blank lines.
This is the first paragraph

this is the second paragraph

## Text formatting
Text formatting includes bold, italics, strikethrough. Underline is not mostly used because links are often identified by an underline although underline can be created using the `<u>` HTML tag.
<br />
Italics are created by enclosing the word or sentence by an asterisk `*` or underscore `_`. As in when you *want to create a word in italics* as in this.
<br />
Bold are made by unclosing a word or sentence in double asterisk `**` or underscore `__`. As in when you want to make a **word bold you enclose** it in double asterisk or underscore.
And they can  also be combined together. All *italics and some **bold like this** and*, the other All **bold and some *itaics like this* and it works**.

Strikethrough are also created using double tilde `~` symbol as in this ~~word is strikethrough~~ and it works.

##  Blockquotes and Code blocks
Blockquotes are created by beginning each line with a greater than sign `>`.
> This is a blockquote and it is made by beginning each line witha greater than sign
> You do not have to beginning each line with a greater than sign, just at the beginning of the blockquote is fine
> and it works


Code blocks are created by indenting every line with a tab or four spaces.
    this is a code block
    and so is this also
You can also create a code block by making use of three backticks.
```
This is made by using three backticks
and it works
```
You can also include the language if you want syntax highlighting.
```c
#include <stdio.h>
#include <stdlib.h>

int main(void)
{
    printf("This is a code block");

    exit(EXIT_SUCCESS);
}
```

code can be displayed in a paragraph by using a single backtick. 
This code `<bold>` and `<h1>` will be displayed not interpreted.

##  Links and Images
Both links and images make use of a combination of brackets **[]** and parantheses **()**.
For links: `It is made by enclosing a represented word for the [link](https://URL.com "site title")`.
Just like this [link](https://URL.com "site title") that leads nowhere.
<br />
Reference linkng can also be used:
```
this is a reference linking to a [site][label]

Then at the end of the document ...

[label]: https://URL.com "optional title"
```

Images makes use of a similar syntax but the exclamation mark `!` is used at the start.
`![Alt text](https://imageURL.com "this is the title")`. It also makes use of the reference linking.

##  Task lists
Task lists are created using `- [ ]` for unchecked items and `- [x]` for checked item.
- [ ] This item is unchecked
- [ ] So is this also unchecked
- [x] This item is checked
- [x] This item is checked

##  Tables
Tables are created by combining pipes `|` and hypens `-`. Three or more hyphens `---` create the headers and pipes create columns.
| Heading 1 | Heading 2 | Heading 3
| --------- | --------- | --------
|some text  | some text | some text
|some text  | some text | some text
|some text  | some text | some text
The aligninment does not necessary matters.

<hr />
**Thank you for coming this far**
**Remember**: This is just the basics to get you started in markdown.