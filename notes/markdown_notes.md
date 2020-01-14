<!-- About: 
    This notes is about the markdown language.
    
    Markdown is lieghtweight

    Notes prepared by Veerendranath Murala
    Date : 11-Jan-2019
 --> 

 <!--
    Supported Editors:
    1) VSCODE with Extension "auto-open-markdown-preview" 
    2) Notepad++ with Plugins:
    "Markdown Panel && Markdown Viewer++" 
    3) GITHUB, GITLAB supports Markdown files
    4) 
 
 -->

<!-- Headings use # to ###### (1to6) --> 
> Headings H1 to H6

# Heading1
## Heading2
### Heading3
#### Heading4
##### Heading5
###### Heading6

<!-- Italics use * or _ --> 
> Italics use * or _ without space

*This text is italics*

_This text is italics_

<!--Note: There should not be any space between the text and * or _ in the start and end -->

<!-- Bold use ** or __ --> 
> Bold use ** or __ without space

**This is bold** 

__This is bold__

<!--Note: There should not be any space between the text and * or _ in the start and end -->

<!-- Strikethrough use ~~ --> 
> Strikethrough ~~

~~This is strikethrough~~

<!--Note: There should not be any space between the text and ~~ in the start and end -->

<!-- Horizontal Lines --- or ___ -->
> Horizontal Lines --- or ___
---
___

<!-- Printing Escape Characters use \ -->
> Printing Escape Characters use \ 
\*\*test**

<!-- Block Quote use > -->
> Block Quote use > 

> This is a quote

> dfjdfjdjfj 

<!-- Links use [](url) -->
[GITLAB](https://gitlab.com/)

<!-- Links use [](url) with Title -->
[GITLAB](https://gitlab.com/ "GITLAB Repository")

<!-- Unordered list use * -->

* item1
* item2

<!-- Nested - Unordered list use * , Max 3 leveles -->
* item1
* item2
    * item2a
    * item2b
        * item2ba
        * item2bb
            
<!-- Ordered list use 1. -->

1. item1
2. item2
2. item3 

<!--Note: even though 2. is duplicated markdown will list the next sequence number automatically-->

<!-- Inline Code Block use `` -->

` This is code block * `

<!-- Images use ![]() -->

![Markdown Logo](https://markdown-here.com/img/icon256.png)


<!-- Following are GITHUB Specific Markdown Syntax -->

<!-- Code Blocks use ``` -->

```bash
npm install 
npm start 

```

```python
def add (num1, num2):
    return num1 + num2
```

```javascript
function add(num1, num2) {
    return num1 + num2;
}

```

<!-- Tables  use | - :  -->

| header | header |
| ------ | ------ |
| cell | cell |
| cell | cell | 

<!-- Tasklist use * [] -->
* [x]  Checkbox1 
* [x]  Checkbox2
* [ ]  Checkbox3


