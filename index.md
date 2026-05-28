# **Markdown CHEAT NOTES 🤫**

Markdown is just a way to format text based on diffrent characters and diffrent ways that you write out the text to make it show up how you want. Generally markdown's going to be rendered out as HTML but you could take a markdown file and render it out howebever you want. you could render it to a PDF  

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


## Bold / Italics
Just surround it by to `*` or `_`   
but generally not recommended using underscore `_` because it will not work if we want to bold or italic in the middle of the word/text. 

|characters| Bold / Italics  |
|----------|-----------------|
|`* *`       |*italics*        |
|`_ _ `      |_italics_        |
|`** **`     |**bold**         |
|`__ __`     |__bold__         |
|`*** ***`   |***italic & bold***|
|`___ ___`   |___italic & bold___| 


## Highlight / Crossed off
We can surround the text using double `~` if we wanted a crossed off text, and we can use double `=` if we want to have a highlight text

>PS.  
>a lot of platform now was supported using double `=` for highlight, but some of them are not. ex. GitHub does not supported using double `=` but we can use HTML which is surronded the text using `<mark></mark>`

|characters      |Highlight / Crossed off|
|----------------|-----------------------|
|`~~ ~~`         |~~Crossed Off~~        |
|`<mark></mark>` |<mark>Highlight</mark> |


## Superscript / Subscript
Create Superscript text, surrounded the text with `^`and to create subscript text you can wrap your text with a `~`
>PS.  
>This again does not work with GitHub Flavored Markdown so we can use the HTML version of this feature.  

|characters      |Superscript / Subscript|
|----------------|-----------------------|
|`<sup></sup>`   |X<sup>super</sup>      |
|`<sub></sub>`   |X<sub>sub</sub>        |

## Inline Code
used when we want to represented as code. we can surrounded the text by backtick `` ` ``.   
For example:  
`hi, im inline code`

## Code block
same as inline code, the only diffrent is we surorunded the text using triple of `` ` `` or 4 times spaces.   
For Example:
```
hello everyone,
   i'm code block, you can use me to write a code
``` 
this kind of code block we can labeled the programming language, and it will give us a syntax highlighting for JavaScript 
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
To create a link you can wrap your text in square brackets `[]` and then wrap the link in parentheses. You can even do this to make relative links. Also, if you include a URL on its own it will automatically be converted to a link in some extended Markdown flavors, otherwise you can wrap it in `<>` to make it a link.
|characters      |Links                         |
|----------------|------------------------------|
|`[word](links)` |[Markdown Guide](https://www.markdownguide.org/)|
|`<links>`       |<https://www.markdownguide.org/>|
|nothing         |https://www.markdownguide.org/  |


## Images
Images has the exact same format with the link where we have square brackets and parentheses but the diffrents is we add a `!` before the square brackets
for example like
```
    ![the img name](img address)
```
![Markdown Logo](https://cdn.commonmark.org/uploads/default/original/2X/3/366f3614de6996d79a131fdf9b41ed7d65cfe181.png)


## Blockquotes
Blockquotes are used to quote another source. To create a blockquote you can add a `>` character before your text. You can also nest blockquotes by adding multiple `>` characters.
> hello this is Blockquotes
>
>> hello this is inner Blockquotes


# Lines
To add a horizontal rule you can add triple or more `-`, `_`, or `*` characters on a single line. dont forget to makesure there is a new emtpy line between text and line.  

    This is above the horizontal rule (triple * )

    ***

    This is between the horizontal rules (triple - )

    ---

    This is between the horizontal rules (triple _ )

    ___


this is triple `-` 

---

this is triple `_`

___

this is triple `*`

***


## Lists
here are two types of lists in Markdown, ordered and unordered. To create an unordered list you can add a `-`, `*`, or `+` character before each item in your list. To create an ordered list you can add a number followed by a `.` character before each item in your list. The actual order of the numbers you use does not matter. don't forget to add one space after adding list characters. You can also nest lists by indenting them with four spaces and/or a tab.

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
    1. ordered nested list 2


## Table
 Tables are a bit more complicated than the other elements. To create a table we need to create a list of rows where each column is separated by a `|` and each row starts and ends with a `|` as well. Below the first row you need to add a row where each column consists of at least three `-` and optionally a `:` character on either side of the `-`s. The `:` character is used to align the text in the column. If you add a `:` character on the left side of the `-`s then the text will be left aligned. If you add a `:` character on the right side of the `-`s then the text will be right aligned. If you add a `:` character on both sides of the -`s` then the text will be center aligned.   
 Example: 
 1. a column without any align  
 2.  
    | Col 1 | Col 2   |
    | ----- | ------- |
    | This  | is      |
    | an    | example |
    | table | with    |
    | two   | columns |

 3. a column with align  
   
    | Right  | Center | Left |
    | -----: | :----: | :--- |
    | ---:   | :---:  | :--- |
    | R      | C      | L    |

> PS.  
> It is okay if the table does not look neat while writing it. Once rendered, it will automatically become properly aligned as long as the `|` and `-` syntax is correct.


## Checkbox
To create a checklist you can add a `- [ ]` or `- [x]` before each item in your list. The `- [ ]` will create an unchecked checkbox while the `- [x]` will create a checked checkbox.  
Example
- [ ] Unchecked `- [ ]`
- [x] Checked `- [x]`