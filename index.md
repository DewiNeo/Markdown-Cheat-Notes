# **My Markdown Secret Cheat Note 🤫**

Markdown is a way to format text using different characters and syntax to make the content appear the way you want. Generally, Markdown is rendered as HTML, but a Markdown file can also be converted into other formats, such as PDF. 

Create Markdown documentation, you will need some tools. For easier use, I recommend using Visual Studio Code. Here is the download link: [click me!](https://code.visualstudio.com/)


## Heading introduction

Just adding # before the text and you will get Heading format.  

|characters| heading |
|----------|---------|
|`#`       |heading 1|
|`##`      |heading 2|
|`###`     |heading 3|
|`#####`   |heading 4|
|`######`  |heading 5|
|`#######` |heading 6|  


## Paragraphs

Paragraphs in Markdown are the default text layout. Simply typing text will automatically create a paragraph. To separate text into different paragraphs, you need to add a blank line between them. If you only want a line break within the same paragraph, you can add two spaces at the end of a line.


## Bold / Italics

Just surround the text with `*` or `_`   
However is not recommended using underscore `_` because it may not work properly when used in the middle of a word or text. 

|characters| Bold / Italics  |
|----------|-----------------|
|`* *`       |*italics*        |
|`_ _ `      |_italics_        |
|`** **`     |**bold**         |
|`__ __`     |__bold__         |
|`*** ***`   |***italic & bold***|
|`___ ___`   |___italic & bold___| 


## Highlight / Crossed off


We can surround text with double `~` to create crossed-out (strikethrough) text, and use double `=` to create highlighted text.

>⚠️ PS:  
>Many platforms now support using double `=` for highlighting, but some do not. For example, GitHub does not support `==highlight==`. Instead, you can use HTML with the `<mark></mark>` tag.

|characters      |Highlight / Crossed off|
|----------------|-----------------------|
|`~~ ~~`         |~~Crossed Out~~        |
|`<mark></mark>` |<mark>Highlight</mark> |


## Superscript / Subscript

Create Superscript text, surround the text with `^`. To create subscript text, wrap the text with a `~`  

>⚠️ PS.  
>This also does not work in GitHub Flavored Markdown. Instead, we can use the HTML tag to achieve the same result.  
> superscript: `<sup></sup>`  
> superscript: `<sub></sub>`  

|characters      |Superscript / Subscript|
|----------------|-----------------------|
|`<sup></sup>`   |X<sup>super</sup>      |
|`<sub></sub>`   |X<sub>sub</sub>        |


## Inline Code

Inline code is used when we want to represent text as code. We can surround the text with backticks `` ` ``.   
For example:  
`hi, im inline code`


## Code block

Code block is similar to inline code. The difference is that we surround the text using triple backticks `` ` `` or four spaces.  
   
For Example:
```
hello everyone,
   i'm code block, you can use me to write a code
``` 
this kind of code block can also specify a programming language after the opening backticks to enable syntax highlighting.  
``` 
   ```js <- JavaScript / programming language
    write the code here and close it with 
    ``` 
```
for example java script code     
```js
   const a = 1
```
    

## Links

To create a link, wrap the link text in square brackets `[]`, followed by the URL in parentheses `()`. You can also use this for relative links. Some Markdown flavors automatically convert plain URLs into clickable links. Otherwise, you can wrap the URL in angle brackets `< >` to make it a link.  

|characters      |Links                         |
|----------------|------------------------------|
|`[word](links)` |[Markdown Guide](https://www.markdownguide.org/)|
|`<links>`       |<https://www.markdownguide.org/>|
|nothing         |https://www.markdownguide.org/  |


## Images

Images use the same format as links, with square brackets `[]` and parentheses `()`. The only difference is that we add an exclamation mark `!` before the square brackets. You can also use HTML `<img>` tags, which are more flexible because they allow you to control image size and styling.  
Example:
```
    ![the img name](img address)
    OR
    <img src="img address" width="width size" style="any style">
```
![Markdown Logo](https://cdn.commonmark.org/uploads/default/original/2X/3/366f3614de6996d79a131fdf9b41ed7d65cfe181.png)

<img src="https://cdn.commonmark.org/uploads/default/original/2X/3/366f3614de6996d79a131fdf9b41ed7d65cfe181.png" width="200" style="border-radius: 50%;">


## Blockquotes


Blockquotes are used to quote content from another source. To create a blockquote, add a `>` character before the text. You can also nest blockquotes by adding multiple `>` characters.  

> hello this is Blockquotes (using `>` 1 time)
>
>> hello this is inner Blockquotes (using `>` 2 time)  
> if you want to have a blank line without write any text just add a `>` and ignore it (just enter) 


# Lines

To add a horizontal rule you can add triple or more `-`, `_`, or `*` characters on a single line. Makesure there is an emtpy line between text and horizontal rule.  
Example:  

    ***  
    ---  
    ___  

this is triple `-` 

---

this is triple `_`

___

this is triple `*`

***


## Lists

here are two types of lists in Markdown: **ordered** and **unordered**. To create an unordered list, add a `-`, `*`, or `+` character before each item in the list. To create an ordered list, add a number followed by a `.` before each item in the list. The actual numbers do not need to be in order. Makesure to add one space after adding the list characters. You can also nest lists by indenting them with four spaces or a tab.

this is unorder list, using `* `
* unordered item 1 
* unordered item 2
    
this is order list, using `number. `
1. ordered item 1
2. ordered item 2
3. ordered item 3  
    unordered nested list  
    - unordered nested list x
    - unordered nested list y  

    ordered nested list
    1. ordered nested list 1
    2. ordered nested list 2


## Table

Tables in Markdown are more complex than other elements. To create a table, need to define rows where each column is separated by a `|` character. Below the header row, you need a separator row which is `-`. Separator row must contain at least three `-` characters. You can also add a `:` character to control text alignment.

The `:` character is used for alignment:

Left alignment: `:` on the left side  
Right alignment: `:` on the right side  
Center alignment: `:` on both sides  


Example: 
 1. column without any align  
   
    | Col 1 | Col 2   |
    | ----- | ------- |
    | This  | is      |
    | an    | example |
    | table | with    |
    | two   | columns |

 2. column with align  
   
    | Right  | Center | Left |
    | -----: | :----: | :--- |
    | ---:   | :---:  | :--- |
    | R      | C      | L    |

>⚠️ PS.  
>It is okay if the table does not look neat while writing it. Once rendered, it will automatically become properly aligned as long as the `|` and `-` syntax is correct.


## Checkbox

To create a checklist you can add a `- [ ]` or `- [x]` before each item in your list. The `- [ ]` will create an unchecked checkbox while the `- [x]` will create a checked checkbox.  

Example
- [ ] Unchecked `- [ ]`
- [x] Checked `- [x]`