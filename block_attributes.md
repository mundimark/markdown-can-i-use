---
layout: page
title:  Block Attributes (Block Inline Attribute Lists)
---

tags: block, ids, classes, styles

You can assign any attribute (e.g. id, class, style, etc.) to a block-level element. 
Just directly follow the block with a block inline attribute list (or short: block IAL). 
A block inline attribute list consists of a left curly brace, 
followed by a colon, 
the attribute definitions and a right curly brace. 
Here is a simple example which sets the title attribute of a block quote:

    > A nice blockquote
    {: title="Blockquote title"}

As one often wants to set one or more CSS classes on an element, there is an easy shortcut:

    > A nice blockquote
    {: .class1 .class2}

A shortcut for setting the ID is also provided. Just prefix the ID with a hash symbol:

    > A nice blockquote
    {: #with-an-id}



## Converter Compatibility

<table id="compat">
  <tr><td>Pandoc |</td>
      <td>CommonMark (Basic) |</td>
      <td>kramdown |</td>
      <td>GitHub Flavored Markdown (GFM)</td>
      </tr>
  <tr><td class="no">x</td>
      <td class="no">x</td>
      <td class="yes">Yes</td>
      <td class="no">x</td>
      </tr>
</table>
