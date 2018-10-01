# Mastering Markdown

This markdown file contains all the lessons and example code from [Wes Bos'][2] online course [Mastering Markdown][3]. It is meant to be a quick reference for all things markdown related. 

<br>

## Table of Contents

1. [Paragraph Text](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#paragraph-text)
2. [Text Styling](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#text-styling)
3. [Headings](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#headings)
	1. [Hashed Headings](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#hashed-headings)
	2. [Headings with Equal Signs or Dashes](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#headings-with-equal-signs-or-dashes)
4. [Links](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#links)
	1. [URL Link](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#url-link)
	2. [Bracket Link](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#bracket-link)
	3. [Bracket Link w/Title Text](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#bracket-link-wtitle-text)
	4. [Footnote Link](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#footnote-link)
5. [Images](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#images)
	1. [Bracket Image](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#bracket-image)
	2. [Bracket Image w/Link](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#bracket-image-wlink)
	3. [HTML Image w/Link](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#html-image-wlink)
	4. [Internal Image w/Link](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#internal-image-wlink)
6. [Lists](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#lists)
	1. [Unordered List](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#unordered-list)
	2. [Ordered List](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#ordered-list)
	3. [Nested List](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#nested-list)
7. [Line Breaks, Horizontal Rules and BlockQuotes](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#line-breaks-horizontal-rules-and-blockquotes)
	1. [Single Line Break](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#single-line-break)
	2. [Double Line Break](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#double-line-break)
	3. [Horizontal Rule](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#horizontal-rule)
	4. [BlockQuote](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#blockquote)
8. [Code](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#code)
	1. [Code Block - Indentation](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#code-block---indentation)
	2. [Code Block - Back Ticks](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#code-block---back-ticks)
	3. [Diff Code Block](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#diff-code-block)
	4. [Inline Code](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#inline-code)
9. [Tables](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#tables)
10. [Checkboxes](https://github.com/TJBriggs/mastering-markdown/blob/master/markdown.md#checkboxes)


## Paragraph Text

Paragraph text can be a single line or multiple lines.

An empty line is needed to create separate paragraphs.

Example paragraph with multiple lines of text...Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.

<br>

## Text Styling

**Bold Text** 

**Example:** &ast;&ast;Bold Text&ast;&ast;

<br>

_Italic Text_ 

**Example:** &lowbar;Italic Text&lowbar;

<br>

*Italic Text*

**Example:** &ast;Italic Text&ast;

<br>

~~Strikethrough Text~~ 

**Example:** &tilde;&tilde;Strikethrough Text&tilde;&tilde;

<br>

## Headings

### Hashed Headings 

Headings create IDs for anchor linking which can come in handy for a table of contents.

**Note:** Headings created with hashes have up to 6 variations.

<br>

# Heading 1

**Example:** &#35; Heading 1

<br>

## Heading 2

**Example:** &#35;&#35; Heading 2

<br>

### Heading 3

**Example:** &#35;&#35;&#35; Heading 3


<br>

#### Heading 4

**Example:** &#35;&#35;&#35;&#35; Heading 4

<br>

##### Heading 5

**Example:** &#35;&#35;&#35;&#35;&#35; Heading 5

<br>

###### Heading 6

**Example:** &#35;&#35;&#35;&#35;&#35;&#35; Heading 6

<br>

### Headings with Equal Signs or Dashes

You need atleast 3 symbols to trigger this style of heading.

**Note:** This heading style only has 2 variations (Heading 1 & 2).

<br>

Heading 1
==================

**Example:** 

Heading 1<br>
&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;

<br>

Heading 2
------------------

**Example:** 

Heading 2<br/>
&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;

<br/>

## Links

### URL link

<http://thadbriggs.com>

**Example:** \<http://<span></span>thadbriggs.com>

<br/>

### Bracket Link

[Link Text](http://thadbriggs.com)

**Example:** &lsqb;Link Text&rsqb;&lpar;http://thadbriggs.com&rpar;

<br/>

### Bracket Link w/Title Text

Hover over the link to view the title text.

[Link Text](http://thadbriggs.com "This is a link to my site.")

**Example:** &lsqb;Link Text&rsqb;&lpar;http://thadbriggs.com "This is a link to my site."&rpar;

<br/>

### Footnote Link

Footnote links can improve readability which comes in handy when a link is embedded within paragraph text. Here is an example of an embedded link: 

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Nullam id dolor id nibh ultricies vehicula ut id elit. Sit Amet Pharetra [Link Text][1] Adipiscing Amet Sem Mollis.

**Example link w/key:** 

&lsqb;Link Text&rsqb;&lsqb;1&rsqb;

**Example footnote key defined at bottomo of document:** 

&lsqb;1&rsqb;: http://<span></span>thadbriggs.com

<br/>

## Images

### Bracket Image

![Alt text for the image](http://unsplash.it/50/50?random "Title text for image")

**Example:** 

&excl;&lsqb;Alt text for the image&rsqb;&lpar;http://unsplash.it/500/500?random "Title text for image"&rpar;

<br/>

### Bracket Image w/Link

[ ![Alt text for the image](http://unsplash.it/50/50?image=500) ](http://unsplash.it/500/500?image=500 "Title text for link")

**Example:** 

&lsqb; &excl;&lsqb;Alt text for the image&rsqb;&lpar;http://<span></span>unsplash.it/50/50?image=500&rpar; &rsqb;&lpar;http://<span></span>unsplash.it/500/500?image=500 "Title text for link"&rpar;

<br/>

### HTML Image w/Link

[ <img src="http://unsplash.it/50/50?image=250" alt="Alt text"> ](http://unsplash.it/500/500?image=250 "Title text for link")

**Example:** 

&lsqb; &lt;img src="http://<span></span>unsplash.it/50/50?image=250" alt="Alt text"&gt; &rsqb;&lpar;http://<span></span>unsplash.it/50/50?image=250&rpar; &rsqb;&lpar;http://<span></span>unsplash.it/500/500?image=250 "Title text for link"&rpar;

### Internal Image w/Link

[ <img src="images/image-thumb.jpg" alt="Alt text"> ](images/image.jpg "Title text for link")

**Example:** 

&lsqb; &lt;img src="images/image-thumb.jpg" alt="Alt text"&gt; &rsqb;&lpar;http://<span></span>unsplash.it/50/50?image=300&rpar; &rsqb;&lpar;images/image.jpg "Title text for link"&rpar;

<br/>

## Lists

### Unordered list

Bullets can be created with &ast; or &plus; symbols.

+ List Item 1
* List Item 2
+ List Item 3
* List Item 4

**Example:**

&plus; List Item 1<br/>
&ast; List Item 2<br/>
&plus; List Item 3<br/>
&ast; List Item 4

<br/>

### Ordered List

Start each ordered list with 1. so you can add items after the fact and the numbering will automatically update.

1. List Item 1
2. List Item 2
3. List Item 3
4. List Item 4

**Example:**

<span></span>1. List Item 1<br/>
<span></span>1. List Item 2<br/>
<span></span>1. List Item 3<br/>
<span></span>1. List Item 4

<br/>

#### Nested List

1. List Item 1
	* Nested Item
2. List Item 2
	1. Nested Item
3. List Item 3
	+ Nested Item
4. List Item 4

**Example:**

<span></span>1. List Item 1<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&ast; Nested Item
<span></span>1. List Item 2<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&plus; Nested Item
<span></span>1. List Item 3<br>
&nbsp;&nbsp;&nbsp;&nbsp;<span></span>1. Nested Item	
<span></span>1. List Item 4

<br>

## Line Breaks, Horizontal Rules and BlockQuotes

### Single Line Break

Single<br>
Line Break

**Example:** 

Single&lt;br&gt;<br>
Line Break

<br>

### Double Line Break

Double

Line Break

**Example:** 

Double
<br><br>
Line Break

<br>

### Horizontal Rule

Element or text before rule

---

Element or text after rule

**Example:**

Element or text before rule
<br><br>
&minus;&minus;&minus;
<br><br>
Element or text after rule

<br>

### BlockQuote

> Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Maecenas sed diam eget risus varius blandit sit amet non magna. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.
>
> — Quote Byline

**Example:**

&gt; Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Maecenas sed diam eget risus varius blandit sit amet non magna. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.<br>
&gt;<br>
&gt; &mdash; Quote Byline

<br>

## Code

### Code Block - Indentation

	const x = 1 + 5;
	const y = x + 3;

**Example:**

&nbsp;&nbsp;&nbsp;&nbsp;const x = 1 + 5;<br>
&nbsp;&nbsp;&nbsp;&nbsp;const y = x + 3;

<br>

### Code Block - Back Ticks

Define the code language to allow syntax highlighting.

```js
const m = 1 + 5;
const n = m + 3;
```

**Example:**

&grave;&grave;&grave;js<br>
const m = 1 + 5;<br>
const n = m + 3;<br>
&grave;&grave;&grave;

<br>

### Diff Code Block

```diff
const m = 1 + 5;
- const n = m + 3;
+ const n = b + 3;
```
**Example:**

&grave;&grave;&grave;diff<br>
const m = 1 + 5;<br>
&minus; const n = m + 3;<br>
&plus; const n = b + 3;<br>
&grave;&grave;&grave;

<br>

### Inline Code

Hey did you try this code `var x = 100;`?

**Example:** Hey did you try this code &grave;var x = 100;&grave;?

<br>

## Tables

Use pipes &vert; to seperate columns and cells. Align text with the use of colons. Colon on the left (left-align), colon on right (right-align), colons on both sides (center-align).

|Column 1 Title|Column 2 Title|
|:------------:|:------------:|
|Row 1/Cell 1|Row 1/Cell 2|
|Row 2/Cell 1|Row 2/Cell 2|

**Example:**

&vert;Column 1 Title&vert;Column 2 Title&vert;<br>
&vert;&colon;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&colon;&vert;&colon;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&minus;&colon;&vert;<br>
&vert;Row 1/Cell 1&vert;Row 1/Cell 2&vert;<br>
&vert;Row 2/Cell 1&vert;Row 2/Cell 2&vert;

<br>

## Checkboxes

* [ ] Get Milk
* [x] Crack Eggs
* [ ] Cook Bacon

**Example:**

&ast; &lsqb; &rsqb; Get Milk
&ast; &lsqb;x&rsqb; Crack Eggs
&ast; &lsqb; &rsqb; Cook Bacon

<br>

[1]: http://thadbriggs.com
[2]: https://wesbos.com
[3]: https://masteringmarkdown.com