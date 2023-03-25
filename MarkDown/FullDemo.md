# Full demo of Github Flavoured Markdown
## Table of Index
|[**Headers**](#Headers)|[**Emphasis**](#Emphasis)|[**Lists**](#Lists)|[**Inline HTML**](#Inline-HTML)|
|-|-|-|-|
|[**Headers**](#Headers)|[**Headers**](#Headers)|[**Headers**](#Headers)|[**Headers**](#Headers)|
|[**Headers**](#Headers)|[**Headers**](#Headers)|[**Headers**](#Headers)|[**Headers**](#Headers)|
|[**Headers**](#Headers)|[**Headers**](#Headers)|[**Headers**](#Headers)|[**Headers**](#Headers)|
|[**Headers**](#Headers)|[**Headers**](#Headers)|[**Headers**](#Headers)|[**Headers**](#Headers)|

## Headers
|[Back to Top](#Table-of-Index)|
|-|

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
Alternatively, for H1 and H2, an underline-ish style:
Alt-H1
======
Alt-H2
------
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------

## Emphasis
```markdown
Emphasis, aka italics, with *asterisks* or _underscores_.
Strong emphasis, aka bold, with **asterisks** or __underscores__.
Combined emphasis with **asterisks and _underscores_**.
Strikethrough uses two tildes. ~~Scratch this.~~
```
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

## Lists
```markdown
1. First ordered list item
2. Another item
⋅⋅⋅* Unordered sub-list.
1. Actual numbers don't matter, just that it's a number
⋅⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses
```
1. First ordered list item
2. Another item
   * Unordered sub-list.
1. Actual numbers don't matter, just that it's a number
   1. Ordered sub-list
4. And another item.

   You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

   To have a line break without a paragraph, you will need to use two trailing spaces.  
   Note that this line is separate, but within the same paragraph.  
   (This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses

Blockquotes in a list item:

   > Skip a line and indent the >'s four spaces.

Preformatted text in a list item:
   ```text
Skip a line and indent eight spaces.
That's four spaces for the list
and four to trigger the code block.
   ```
## Inline HTML
```markdown
To reboot your computer, press `ctrl`+`alt`+`del`.
```
To reboot your computer, press `ctrl`+`alt`+`del`.
