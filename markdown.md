# Mastering Markdown

<br>

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

## Hashed Headings 

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

## Headings with Equal Signs or Dashes Below

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

## Links in Markdown

#### URL link

<http://thadbriggs.com>

**Example:** \<http://<span></span>thadbriggs.com>

<br/>

#### Bracket Link Text

[Link Text](http://thadbriggs.com)

**Example:** &lsqb;Link Text&rsqb;&lpar;http://thadbriggs.com&rpar;

<br/>

#### Bracket Link Text w/Title Text

Hover over the link to view the title text.

[Link Text](http://thadbriggs.com "This is a link to my site.")

**Example:** &lsqb;Link Text&rsqb;&lpar;http://thadbriggs.com "This is a link to my site."&rpar;

<br/>

#### Footnote Style Link

You can also create a footnote style key for the link URL. This can help keep markdown text clean which comes in handy when a link is embedded within paragraph text. Here are examples showing the syntax for this link style. 

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Nullam id dolor id nibh ultricies vehicula ut id elit. Sit Amet Pharetra [Link Text][1] Adipiscing Amet Sem Mollis.

**Example Link w/key:** 

&lsqb;Link Text&rsqb;&lsqb;1&rsqb;

**Example key defined at the bottom of the page:** 

&lsqb;1&rsqb;: http://<span></span>thadbriggs.com

<br/>

## Markdown Images

#### Bracket Style Image

![Alt text for the image](http://unsplash.it/50/50?random "Title text for image")

**Example:** 

&excl;&lsqb;Alt text for the image&rsqb;&lpar;http://unsplash.it/500/500?random "Title text for image"&rpar;

<br/>

#### Bracket Image Nested Within Link

[ ![Alt text for the image](http://unsplash.it/50/50?image=500) ](http://unsplash.it/500/500?image=500 "Title text for link")

**Example:** 

&lsqb; &excl;&lsqb;Alt text for the image&rsqb;&lpar;http://<span></span>unsplash.it/50/50?image=500&rpar; &rsqb;&lpar;http://<span></span>unsplash.it/500/500?image=500 "Title text for link"&rpar;

<br/>

#### HTML Image Nested Within Link

[ <img src="http://unsplash.it/50/50?image=250" alt="Alt text"> ](http://unsplash.it/500/500?image=250 "Title text for link")

**Example:** 

&lsqb; &lt;img src="http://<span></span>unsplash.it/50/50?image=250" alt="Alt text"&gt; &rsqb;&lpar;http://<span></span>unsplash.it/50/50?image=250&rpar; &rsqb;&lpar;http://<span></span>unsplash.it/500/500?image=250 "Title text for link"&rpar;

#### HTML Image Nested Within Link (Internal Image)

[ <img src="images/image-thumb.jpg" alt="Alt text"> ](images/image.jpg "Title text for link")

**Example:** 

&lsqb; &lt;img src="images/image-thumb.jpg" alt="Alt text"&gt; &rsqb;&lpar;http://<span></span>unsplash.it/50/50?image=300&rpar; &rsqb;&lpar;images/image.jpg "Title text for link"&rpar;

<br/>

## Markdown Lists

#### Unordered lists

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

#### Ordered Lists

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

#### Nested Lists

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

## Line Breaks, Horizontal Rule, and Block Quotes

#### Single Line Break

Single<br>
Line Break

**Example:** 

Single&lt;br&gt;<br>
Line Break

#### Double Line Break

Double

Line Break

**Example:** 

Double
<br><br>
Line Break

<br>

#### Horizontal Rule

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

#### Block Quotes

> Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Maecenas sed diam eget risus varius blandit sit amet non magna. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.
>
> — Quote Byline

**Example:**

&gt; Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Maecenas sed diam eget risus varius blandit sit amet non magna. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.<br>
&gt;<br>
&gt; &mdash; Quote Byline

<br>









[1]: http://thadbriggs.com