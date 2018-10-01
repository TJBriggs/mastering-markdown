# Mastering Markdown

<br/>

## Paragraph Text

Paragraph text can be a single line or multiple lines.

An empty line is needed to create separate paragraphs.

Example paragraph with multiple lines of text...Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.

<br/>

## Text Styling

**Bold Text** 

**Example:** &ast;&ast;Bold Text&ast;&ast;

<br/>

_Italic Text_ 

**Example:** &lowbar;Italic Text&lowbar;

<br/>

*Italic Text*

**Example:** &ast;Italic Text&ast;

<br/>

~~Strikethrough Text~~ 

**Example:** &tilde;&tilde;Strikethrough Text&tilde;&tilde;

<br/>

## Hashed Headings 

Headings create IDs for anchor linking which can come in handy for a table of contents.

**Note:** Headings created with hashes have up to 6 variations.

<br/>

# Heading 1

**Example:** &#35; Heading 1

<br/>

## Heading 2

**Example:** &#35;&#35; Heading 2

<br/>

### Heading 3

**Example:** &#35;&#35;&#35; Heading 3


<br/>

#### Heading 4

**Example:** &#35;&#35;&#35;&#35; Heading 4

<br/>

##### Heading 5

**Example:** &#35;&#35;&#35;&#35;&#35; Heading 5

<br/>

###### Heading 6

**Example:** &#35;&#35;&#35;&#35;&#35;&#35; Heading 6

<br/>

## Headings with Equal Signs or Dashes Below

You need atleast 3 symbols to trigger this style of heading.

**Note:** This heading style only has 2 variations (Heading 1 & 2).

<br/>

Heading 1
==================

**Example:** 

Heading 1<br/>
&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;&equals;

<br/>

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

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Nullam id dolor id nibh ultricies vehicula ut id elit. Sit Amet Pharetra[Link Text][1] Adipiscing Amet Sem Mollis.

**Example Link w/key:** 

&lsqb;Link Text&rsqb;&lsqb;1&rsqb;

**Example key defined at the bottom of the page:** 

&lsqb;1&rsqb;: http://thadbriggs.com

<br/>

## Markdown Images

![Alt text for the image](http://unsplash.it/250/250?random "Title text for image")

**Example:** 

&excl;&lsqb;Alt text for the image&rsqb;&lpar;http://unsplash.it/500/500?random "Title text for image"&rpar;

<br/>



[1]: http://thadbriggs.com



