***Markdown*** is a human-readable markup language that converts to HTML. It can be opened and modified in any text editor. Widely used for writing documentation and README files. Saved in .md format <br><br>

# Table of contents
1. [Atx-style](#atx-style)
2. [List](#list)
    - [Nested Lists](#listIn)
4. [Backtik](#backtik)
5. [Work with text](#text)
6. [Link](#link)
   - [Auto link](#autoLink)
7. [Image](#img)
8. [Features](#features)
    - [hr](#hr)
    - [Task list](#todo)
    - [Quote](#quote)
    - [Tables](#tables)
9. [Another information](#info)
    - [GFM](#gfm)
    - [Advices](#advice)
    - [HTML](#html)
    - [Comments](#comment)
    - [Emoji](#emo)

# Syntax
<div id='atx-style'/>
    
## Atx-style
\# - Atx-style - 1 level<br>
\#\# - Atx-style - 2 level and etc.<br>

<div id='list'/>

## List 

To create bulleted lists, precede each item with (-), (+) or (*). 
```
- Bagel
- Cake
``` 

- Bagel
- Cake<br>
If we use numbers with a dot (1., 2., etc.) as markers, then we will get an ordered (numbered) list. The numbers of points in the final markup will be in order (1, 2, 3), even if in Markdown there are 1., 4., 9.. This feature allows us to use “lazy numbering”, when each point is given one number.
```
1. Point one
2. Point two
3. Point three
```
1. Point one
2. Point two
3. Point three
<div id='listIn'/>

### Nested Lists 
    
```
1. Point one
    - Subparagraph one 
    - Subparagraph two
2. Point two
```
1. Point one
    - Subparagraph one 
    - Subparagraph two
2. Point two
<div id='backtik'/>
    
## backtik 
If we wrap a block of code with three or more pairs of backticks, then we can indicate the programming language we are using, to do this we need to write it immediately after the opening backticks. 

Function <br>
\`\`\`javascript<br>
console.log()<br>
\`\`\`
```javascript 
console.log()
```
outputs text to the console. 

The sum of two variables can be output like this: 
```javascript
const a = 1
const b = 2

console.log(a + b)
```
Another way to highlight code is to precede it with a tab or 4 spaces. The source code must be separated by a blank line from the previous block. 

    const a = 1
    const b = 2

<div id='text'/>

## Work with text
one pair \* or \_ will make the text italic ;<br>
two pairs \* or \_ will make the text bold ;<br>
three pairs of \* or \_ will apply both styles ;<br>
two tildes \~\~ will strike out the text. Crossed out.<br>

To escape Markdown service characters, you need to put a backslash in front of each of them ( `\*`, `\_`, `\*\*`). 

<div id='link'/>

## Link
To insert a link in line style, you must use the following construction: [Link text] (URL). It is possible to add a hint; to do this you need to add text in quotes after the URL: [Link text] (URL "Hint").<br>
`Hello, [world](https://i.pinimg.com/564x/5b/02/47/5b0247d140ff9659066d61fa63edc79a.jpg)!`<br>
Hello, [world](https://i.pinimg.com/564x/5b/02/47/5b0247d140ff9659066d61fa63edc79a.jpg)!
<div id='autoLink'/>

## Auto link
`<http://example.com/>`<br>
<http://example.com/>
<div id='img'/>

## img
To insert an image in line style, you must use the construction !⁠[Alt text] (URL of the image). 

`![Cat](https://i.pinimg.com/564x/5b/02/47/5b0247d140ff9659066d61fa63edc79a.jpg)` <br>
![Cat](https://i.pinimg.com/564x/5b/02/47/5b0247d140ff9659066d61fa63edc79a.jpg)

To resize the image we will use an html tag. 
<div id='features'/>

## Features
<div id='hr'/>
    
### \<hr>
To separate semantic blocks, you can use a horizontal bar (<hr>).  <br>
<div id='todo'/>

### Task list
To create a task list, use bulleted list syntax, but with checkboxes ([ ] or [x]) added after the bullets. 

```
- [x] Go outside
- [ ] Buy products
  - [x] Milk
  - [ ] Tomatoes
```
- [x] Go outside
- [ ] Buy products
  - [x] Milk
  - [ ] Tomatoes

<div id='quote'/>

### Quote
If you put a triangle bracket (>) at the beginning of a line, Markdown will turn the text after it into a quotation. 

`> Quote`
> First, parent quote 
> > And this is the second one, child quote 
<div id='tables'/>

### Tables
    
```
|Place|Participant|Rate|
|-:|:-:|:-|
|1|Sasha|118|
|2|Julia|92|
|3|Daniel|36|
```
|Place|Participant|Rate|
|-:|:-:|:-|
|1|Sasha|118|
|2|Julia|92|
|3|Daniel|36|

Consecutive lines will be glued into one if you do not add a hard transfer.
There are several ways you can do this: add a br or slash - \\ HTML line break tag to the end of the line

<div id='info'/>

## Info
<div id='gfm'/>
    
### GitHub Flavored Markdown
**GFM** is one of the dialects of Markdown, which, as the name suggests, is used on GitHub. It builds on the CommonMark specification and extends it with additional elements: tables, task lists, and strikethroughs. 
<div id='advice'/>    

### Advices
It is best to use the <br> tag because backslash hyphenation (\) may not be supported by all Markdown converters, as it is described in CommonMark but not in the original specification. 
<div id='html'/> 
    
### HTML
Markdown supports the use of straight HTML within a document, so you can use any HTML tags for more complex styling: <br>
`<kbd>CTRL</kbd> + <kbd>P</kbd>`<br>
<kbd>CTRL</kbd> + <kbd>P</kbd>
<div id='comment'/> 
    
### Comments
`<!-- It's a comment, it won't show up -->`<br>
example: <br>
<!-- It's a comment, it won't show up-->
<div id='emo'/> 

### Emoji (Github)
You can use emoji in your Markdown files. Here are some of them: 
```
:smile:
:laughing:
:blush:
```
:smile:
:laughing:
:blush:

