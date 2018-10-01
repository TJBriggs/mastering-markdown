# Mastering Markdown

## Paragraph Text

Paragraph text can be a single line or multiple lines.

An empty line is needed to create separate paragraphs.

Another paragraph with multiple lines of text...Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.

## Text Styling

**Bold** text with double asterisks &ast;&ast;Bold&ast;&ast;

_Italic_ text single underscores &lowbar;Italic&lowbar;

*Italic* text with single asterisks &ast;Italic&ast;

~~Strikethrough~~ with double tildes &tilde;&tilde;strikethrough&tilde;&tilde;

## Hashed Headings 

Headings create IDs for anchor linking which can come in handy for a table of contents.

**Note:** Headings created with hashes have up to 6 variations.

# H1 with single hash &#35;H1

## H2 with double hashes &#35;&#35;H2

### H2 with three hashes &#35;&#35;&#35;H3

#### H2 with four hashes &#35;&#35;&#35;&#35;H4

##### H2 with five hashes &#35;&#35;&#35;&#35;&#35;H5

###### H6 with six hashes &#35;&#35;&#35;&#35;&#35;&#35;H6

## Headings with Equal Signs or Dashes below

You need atleast 3 of each symbol to trigger this style of heading.

**Note:** This heading style has on 2 variations (Heading 1 & 2).

Heading 1
==================

Heading 2
------------------

## Links in Markdown

Link with URL wrapped in &lt; and &gt;

<http://thadbriggs.com>

Link text wrapped in brackets &lsqb;&rsqb; and link URL wrapped in parenthesis &lpar;&rpar;.

[Link Text](http://thadbriggs.com)

Link text wrapped in brackets &lsqb;&rsqb; and link URL wrapped in parenthesis &lpar;&rpar; with optional title text inside the parenthesis. The title text needs to be wrapped in quotes.

[Link Text](http://thadbriggs.com "This is a link to my site.")

Creating a footnote style key for the link URL can help keep the markdown text clean especially when a link is within paragraph text. The link text below is wrapped in brackets &lsqb;&rsqb; and then the key text is also wrapped in brackets. The key is defined at the bottom of the document. Here is example text showing the syntax for this link style. 

**Example Link w/key:** &lsqb;Link Text&rsqb;&lsqb;Link Key&rsqb;

**Example key definition at the bottom of the page:** &lsqb;Link Key&rsqb;: http://thadbriggs.com

[Link Text][1]






[1]: http://thadbriggs.com



