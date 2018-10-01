# Mastering Markdown

## Paragraph Text

Paragraph text can be a single line or multiple lines.

An empty line is needed to create separate paragraphs.

Example paragraph with multiple lines of text...Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.

<br/>

## Text Styling

**Bold Text** 

&ast;&ast;Bold Text&ast;&ast; wrapped with double asterisks.

<br/>

_Italic Text_ 

&lowbar;Italic Text&lowbar; wrapped with single underscores.

<br/>

*Italic Text*

&ast;Italic Text&ast; wrapped with single asterisks.

<br/>

~~Strikethrough Text~~ 

&tilde;&tilde;Strikethrough Text&tilde;&tilde; wrapped with double tildes.

<br/>

## Hashed Headings 

Headings create IDs for anchor linking which can come in handy for a table of contents.

**Note:** Headings created with hashes have up to 6 variations.

# Heading 1

&#35; Heading 1 with single hash

<br/>

## Heading 2

&#35;&#35; Heading 2 with double hashes

<br/>

### Heading 3

&#35;&#35;&#35; Heading 3 with three hashes

<br/>

#### Heading 4

&#35;&#35;&#35;&#35; Heading 4 with four hashes

<br/>

##### Heading 5

&#35;&#35;&#35;&#35;&#35; Heading 5 with five hashes

<br/>

###### Heading 6

&#35;&#35;&#35;&#35;&#35;&#35; Heading 6 with six hashes

<br/>

## Headings with Equal Signs or Dashes Below

You need atleast 3 of each symbol to trigger this style of heading.

**Note:** This heading style only has 2 variations (Heading 1 & 2).

<br/>

Heading 1
==================

Heading 2
------------------

<br/>

## Links in Markdown

Link with URL wrapped in &lt; and &gt;

**Example:** &lt; http://thadbriggs.com &gt;

<http://thadbriggs.com>

<br/>

Link text wrapped in brackets &lsqb;&rsqb; and link URL wrapped in parenthesis &lpar;&rpar;.

**Example:** &lsqb;Link Text&rsqb;&lpar;http://thadbriggs.com&rpar;

[Link Text](http://thadbriggs.com)

<br/>

Link text wrapped in brackets &lsqb;&rsqb; and link URL wrapped in parenthesis &lpar;&rpar; with optional title text inside the parenthesis. The title text needs to be wrapped in quotes.

Hover over the link to view the title text.

**Example:** &lsqb;Link Text&rsqb;&lpar;http://thadbriggs.com "This is a link to my site."&rpar;

[Link Text](http://thadbriggs.com "This is a link to my site.")

<br/>

You can create a footnote style key for the link URL. This can help keep the markdown text clean which comes in handy when a link is embedded within paragraph text. Here are examples showing the syntax for this link style. 

**Example Link w/key:** &lsqb;Link Text&rsqb;&lsqb;Link Key&rsqb;

**Example key defined at the bottom of the page:** &lsqb;Link Key&rsqb;: http://thadbriggs.com

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Nullam id dolor id nibh ultricies vehicula ut id elit. Sit Amet Pharetra[Link Text][1] Adipiscing Amet Sem Mollis.

<br/>






[1]: http://thadbriggs.com



