### Unordered (bulleted) lists:

* Candy.
* Gum.
* Booze.


### Ordered (numbered) lists:

1.  Red
2.  Green
3.  Blue


### Sub list:

- And if you have sub lists, put two extra spaces before the sub list items.
  - Like this
  - And this


---


It’s important to note that the actual numbers you use to mark the list have no effect on the HTML output Markdown produces.


If you put blank lines between items, you’ll get `<p>` tags for the list item text. You can create multi-paragraph list items by indenting the paragraphs by 4 spaces or 1 tab:

*   A list item.

    With multiple paragraphs.

*   Another item in the list.


To put a blockquote within a list item, the blockquote’s > delimiters need to be indented:

*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.
To put a code block within a list item, the code block needs to be indented twice — 8 spaces or two tabs:

*   A list item with a code block:

        <code goes here>
It’s worth noting that it’s possible to trigger an ordered list by accident, by writing something like this:

1986. What a great season.
In other words, a number-period-space sequence at the beginning of a line. To avoid this, you can backslash-escape the period:

1986\. What a great season.
