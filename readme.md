# Github Readme Cheatsheet

## ***For all crazy Developers who want to write a beautiful readme for their projects.***

>### Table of Contents <br>
1. [Headings](#headings)
2. [Bold and Italic Text](#bold-and-italic-text)
3. [Lists](#lists)
4. [Adding Links To Text](#adding-links-to-text)
5. [Adding Images](#adding-images)
6. [BlockQuotes](#block-quotes)
7. [Inline Code](#inline-code)
8. [Syntax highlighting](#syntax-highlighting)
9. [Tables](#tables)
10. [StrikeThrew](#strike-threw)
11. [Line Break](#line-break)
12. [Horizontal Rule](#horizontal-rule)
>### Advanced Features <br>
13. [Custom Width and Height Images](#custom-width-and-height-images)
14. [Adding a gif/image from project directory](#adding-a-gifimage-from-project-directory)
15. [Adding Link To Images](#adding-link-to-images)
16. [Badges](#badges)
17. [Emojis](#emojis)

>### ***Headings***
---
To create a heading in readme, we need to use #. The size of headings can be changed by adding multiple # Together. The greater the number of # is, the smaller the heading is.

```markdown
Symbol  Tag       Code
------  -----     ----
#       <h1>      # h1 heading
##      <h2>      ## h2 heading
###     <h3>      ### h3 heading
####    <h4>      #### h4 heading
#####   <h5>      ##### h5 heading
######  <h6>      ###### h6 heading
```
***Output* from above code** <hr>
# h1 heading
## h2 heading
### h3 heading
#### h4 heading
##### h5 heading
###### h6 heading
<br>

>### ***Bold and Italic Text***
---
To create bold text, we need to use **. To create italic text, we need to use *.

```markdown
Symbol  Tag       Code
------  -----     ----
**      <b>       **bold**
*       <i>       *italic*
```
***Output* from above code** <hr>
**bold**
*italic*
<br>

>### ***Lists***
---
*To create a unordered list, we can use * or - for each list point.*

```markdown
Symbol  Tag       Code
------  -----     ----
*       <ul>      * Bullet Point 1 Using *
-       <ul>      - Bullet Point 2 Using -
```
***Output* from above code** <hr>
* Bullet Point 1 Using *
- Bullet Point 2 Using -

*To create a ordered list, we can simply use 1. and so on.*

```markdown
Symbol  Tag       Code
------  -----     ----
1.      <ol>      1. Point 1
2.      <ol>      2. Point 2
3.      <ol>      3. Point 3
```
***Output* from above code** <hr>
1. Point 1
2. Point 2
3. Point 3
<br>

>### ***Adding Links To Text***
---
To create a link, we need to use [Text](Link).

```markdown
Syntax:
[Text](Link)
```
***Output* from above syntax** <hr>
[Text](Link)
<br>

>### ***Adding Images***
---
`To create an image, we need to use ![Text](Link)`

```markdown
Syntax:
![Text](https://user-images.githubusercontent.com/29582239/184543797-60b6ca0d-decc-452e-b9cc-e3daac17f2cd.png)
```
***Output* from above syntax** <hr>
![Text](https://user-images.githubusercontent.com/29582239/184543797-60b6ca0d-decc-452e-b9cc-e3daac17f2cd.png)
<br>

>### ***Block Quotes***
---
To create a blockquote, we need to use <code>></code>

```markdown
Syntax:
> Code is poetry.
```
***Output* from above syntax** <hr>
> Code is poetry.
<br>

>### ***Inline Code***
---
To create inline code, we need to use `<code>Code</code>`

```markdown
Syntax:
<code>composer install</code>
```
***Output* from above syntax** <hr>
<code>composer install</code>
<br>

>### ***Syntax highlighting***
---
To create syntax highlighting, we need to use
```markdown
```code``` (Here 'code' is the language name that we want to highlight)
```

```markdown
Syntax:
```php
echo "Hello World";
```
*We need to add three backtick (```) after helo world semicolon*<br>
***Output* from above syntax** <hr>
```php
echo "Hello World";
```
<br>

>### ***Tables***
---
To create a table, we need to use | for each cell.

```markdown
Syntax:
 Header-1 | Header-2| Header-3
 ------   | ------  | ------  
 column-1 | column-2| column-3
```
***Output* from above syntax** <hr>
 Header-1 | Header-2| Header-3
 ------   | ------  | ------  
 column-1 | column-2| column-3
<br>

>### ***Strike Threw***
---
To create strike through text, we need to use `~~text~~`

```markdown
Syntax:
~~text~~
```
***Output* from above syntax** <hr>
~~text~~
<br>

>### ***Line Break***
---
To create a line break, we need to use `<br> or <br/>`

```markdown
Syntax:
<br>
```
***Output* from above syntax** <hr>
<br>
<br>

>### ***Horizontal Rule***
---
To create a horizontal rule, we need to use `<hr> or *** or ---`

```markdown
Syntax:
<hr>

***

---
```
***Output* from above syntax** 
<hr>

***

---
<br>

>### ***Custom Width and Height Images***
---
To create a custom width and height images, we need to use `<img src="link" width="100" height="100"/>`

```markdown
Syntax:
<img src="https://user-images.githubusercontent.com/29582239/184543797-60b6ca0d-decc-452e-b9cc-e3daac17f2cd.png" width="250" height="200"/>
```
***Output* from above syntax** <hr>

<img src="https://user-images.githubusercontent.com/29582239/184543797-60b6ca0d-decc-452e-b9cc-e3daac17f2cd.png" width="250" height="200"/>
<br>

>### ***Adding a gif/image from project directory***
---
To create a gif, we need to use `<img src="link" width="100" height="100"/>`

```markdown
Syntax:
<img src="assets/img/github-mark.png" width="200" height="100" alt="github-logo"/>
```
***Output* from above syntax** <hr>
<img src="assets/img/github-mark.png" width="200" height="100" alt="github-logo"/>
<br>

>### ***Adding link to images***
---
To create a link to an image, we need to use `[<img src=""/>](link)`

```markdown
Syntax:
[<img alt="github-logo" width="100" src="assets/img/github-mark.png"/>](https://github.com/csesumonpro/Github-Readme-Cheatsheet)
```
***Output* from above syntax** <hr>
[<img alt="github-logo" width="100" src="assets/img/github-mark.png"/>](https://github.com/csesumonpro/Github-Readme-Cheatsheet)
<br>

>### ***Badges***
---
[Get all about shields](https://shields.io/)

[Markdown badges](https://github.com/Ileriayo/markdown-badges)

[Get all about Badge Poser](https://poser.pugx.org/)


To create a markdown badges, we need to use `[![](link)](link)`

```markdown
Syntax:
[![](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

[![Total Downloads](https://poser.pugx.org/csesumonpro/contact/downloads)](https://packagist.org/packages/csesumonpro/contact)
```
***Output* from above syntax** <hr>
[![](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

[![Total Downloads](https://poser.pugx.org/csesumonpro/contact/downloads)](https://packagist.org/packages/csesumonpro/contact)
<br>