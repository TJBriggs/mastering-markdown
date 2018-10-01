# Mastering Markdown



## Paragraph Text

Paragraph text can be a single line or multiple lines.

An empty line is needed to create separate paragraphs.

Example paragraph with multiple lines of text...Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.



## Text Styling

**Bold Text** 

&ast;&ast;Bold Text&ast;&ast; wrapped with double asterisks.

_Italic Text_ 

&lowbar;Italic Text&lowbar; wrapped with single underscores.

*Italic Text*

&ast;Italic Text&ast; wrapped with single asterisks.

~~Strikethrough Text~~ 

&tilde;&tilde;Strikethrough Text&tilde;&tilde; wrapped with double tildes.



## Hashed Headings 

Headings create IDs for anchor linking which can come in handy for a table of contents.

**Note:** Headings created with hashes have up to 6 variations.

# Heading 1

&#35;Heading 1 with single hash

## Heading 2

&#35;&#35;Heading 2 with double hashes

### Heading 3

&#35;&#35;&#35;Heading 3 with three hashes

#### Heading 4

&#35;&#35;&#35;&#35;Heading 4 with four hashes

##### Heading 5

&#35;&#35;&#35;&#35;&#35;Heading 5 with five hashes

###### Heading 6

&#35;&#35;&#35;&#35;&#35;&#35;Heading 6 with six hashes



## Headings With Equal Signs or Dashes Below

You need atleast 3 of each symbol to trigger this style of heading.

**Note:** This heading style only has 2 variations (Heading 1 & 2).

Heading 1
==================

Heading 2
------------------



## Links in Markdown

Link with URL wrapped in &lt; and &gt;

&lt; http://thadbriggs.com &gt;

<http://thadbriggs.com>

Link text wrapped in brackets &lsqb;&rsqb; and link URL wrapped in parenthesis &lpar;&rpar;.

[Link Text](http://thadbriggs.com)

Link text wrapped in brackets &lsqb;&rsqb; and link URL wrapped in parenthesis &lpar;&rpar; with optional title text inside the parenthesis. The title text needs to be wrapped in quotes.

[Link Text](http://thadbriggs.com "This is a link to my site.")

Creating a footnote style key for the link URL can help keep the markdown text clean especially when a link is within paragraph text. The link text below is wrapped in brackets &lsqb;&rsqb; and then the key text is also wrapped in brackets. The key is defined at the bottom of the document. Here is example text showing the syntax for this link style. 

**Example Link w/key:** &lsqb;Link Text&rsqb;&lsqb;Link Key&rsqb;

**Example key definition at the bottom of the page:** &lsqb;Link Key&rsqb;: http://thadbriggs.com

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Nullam id dolor id nibh ultricies vehicula ut id elit. Sit Amet Pharetra[Link Text][1] Adipiscing Amet Sem Mollis.






[1]: http://thadbriggs.com



