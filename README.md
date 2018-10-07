# Mastering Markdown

This markdown file contains all the lessons and example code from [Wes Bos'][2] online course [Mastering Markdown][3]. It is meant to be a quick reference for all things markdown related. 

<br>

## Paragraph Text

Paragraph text can be a single line or multiple lines.

An empty line is needed to create separate paragraphs.

Example paragraph with multiple lines of text...Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.

<br>

## Text Styling

**Bold Text** 

```**Bold Text**```

<br>

_Italic Text_ 

```_Italic Text_```

<br>

*Italic Text*

```*Italic Text*```

<br>

~~Strikethrough Text~~ 

```~~Strikethrough Text~~```

<br>

## Headings

### Hashed Headings 

Headings create IDs for anchor linking which can come in handy for a table of contents.

**Note:** Headings created with hashes have up to 6 variations.

# Heading 1

<br>

## Heading 2

<br>

### Heading 3

<br>

#### Heading 4

<br>

##### Heading 5

<br>

###### Heading 6

<br>

```
	# Heading 1
	## Heading 2
	### Heading 3
	#### Heading 4
	##### Heading 5
	###### Heading 6
```

### Alternative Headings

You need atleast 3 symbols to trigger this style of heading.

**Note:** This heading style only has 2 variations (Heading 1 & 2).

<br>

Heading 1
==================

<br>

Heading 2
------------------

<br>

```
	Heading 1
	==================

	Heading 2
	------------------
```

<br/>

## Links

### URL link

<http://thadbriggs.com>

```<http://thadbriggs.com>```

<br/>

### Bracket Link

[Link Text](http://thadbriggs.com)

```[Link Text](http://thadbriggs.com)```

<br/>

### Bracket Link w/Title Text

Hover over the link to view the title text.

[Link Text](http://thadbriggs.com "This is a link to my site.")

```[Link Text](http://thadbriggs.com "This is a link to my site.")```

<br/>

### Footnote Link

Footnote links can improve readability which comes in handy when a link is embedded within paragraph text. Here is an example of an embedded link: 

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Nullam id dolor id nibh ultricies vehicula ut id elit. Sit Amet Pharetra [Link Text][1] Adipiscing Amet Sem Mollis.

**Example link w/key:** 

```[Link Text][1]```

**Example footnote key defined at bottom of the document:** 

```[1]: http://thadbriggs.com```

<br/>

## Images

### Bracket Image

![Alt text for the image](http://unsplash.it/50/50?random "Title text for image")

```![Alt text for the image](http://unsplash.it/50/50?random "Title text for image")```

<br/>

### Bracket Image w/Link

[ ![Alt text for the image](http://unsplash.it/50/50?image=500) ](http://unsplash.it/500/500?image=500 "Title text for link")

```[ ![Alt text for the image](http://unsplash.it/50/50?image=500) ](http://unsplash.it/500/500?image=500 "Title text for link")```

<br/>

### HTML Image w/Link

[ <img src="http://unsplash.it/50/50?image=250" alt="Alt text"> ](http://unsplash.it/500/500?image=250 "Title text for link")

```[ <img src="http://unsplash.it/50/50?image=250" alt="Alt text"> ](http://unsplash.it/500/500?image=250 "Title text for link")```

### Internal Image w/Link

[ <img src="images/image-thumb.jpg" alt="Alt text"> ](images/image.jpg "Title text for link")

```[ <img src="images/image-thumb.jpg" alt="Alt text"> ](images/image.jpg "Title text for link")```

<br/>

## Lists

### Unordered list

Bullets can be created with &ast; or &plus; symbols.

+ List Item 1
* List Item 2
+ List Item 3
* List Item 4

```
	+ List Item 1
	* List Item 2
	+ List Item 3
	* List Item 4
```

<br/>

### Ordered List

1. List Item 1
2. List Item 2
3. List Item 3
4. List Item 4

_Start each ordered list with `1.` so that numbering automatically updates when new items are added._

```
	1. List Item 1
	1. List Item 2
	1. List Item 3
	1. List Item 4
```

<br/>

#### Nested List

1. List Item 1
	* Nested Item
2. List Item 2
	1. Nested Item
3. List Item 3
	+ Nested Item
4. List Item 4

```
	1. List Item 1
		* Nested Item
	1. List Item 2
		1. Nested Item
	1. List Item 3
		+ Nested Item
	1. List Item 4	
```

<br>

## Line Breaks, Horizontal Rules and BlockQuotes

### Single Line Break

Single<br>
Line Break

```
	Single<br>
	Line Break
```

<br>

### Double Line Break

Double

Line Break

_Simply add a return between lines to create a double line break._

```
	Double

	Line Break

```

<br>

### Horizontal Rule

Element or text before rule

---

Element or text after rule


```
	Element or text before rule

	---

	Element or text after rule
```

<br>

### BlockQuote

> Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Maecenas sed diam eget risus varius blandit sit amet non magna. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.
>
> — Quote Byline

```
	> Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Maecenas sed diam eget risus varius blandit sit amet non magna. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.
	>
	> — Quote Byline
```

<br>

## Code

### Code Block - Indentation

	const x = 1 + 5;
	const y = x + 3;

```
	const x = 1 + 5;
	const y = x + 3;
```

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

```
	|Column 1 Title|Column 2 Title|
	|:------------:|:------------:|
	|Row 1/Cell 1|Row 1/Cell 2|
	|Row 2/Cell 1|Row 2/Cell 2|
```

<br>

## Checkboxes

* [ ] Get Milk
* [x] Crack Eggs
* [ ] Cook Bacon

```
	* [ ] Get Milk
	* [x] Crack Eggs
	* [ ] Cook Bacon
```

<br>

[1]: http://thadbriggs.com
[2]: https://wesbos.com
[3]: https://masteringmarkdown.com