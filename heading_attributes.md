---
layout: page
title:  Heading Attributes
---

tags: headings, ids

Headings can be assigned attributes using this syntax 
at the end of the line containing the heading text:

```
{#identifier .class .class key=value key=value}
```

Thus, for example, the following headings will all be assigned the identifier foo:

```
# My heading {#foo}

## My heading ##    {#foo}

My other heading   {#foo}
----------------
```


## Converter Compatibility

<table id="compat">
  <tr><td>Pandoc</td>
      <td>kramdown</td>
      <td>CommonMark (Basic)</td>
      <td>GitHub Flavored Markdown (GFM)</td>
      </tr>
  <tr><td class="yes">Yes</td>
      <td class="yes">Yes</td>
      <td class="no">x</td>
      <td class="no">x</td>
      </tr>
</table>


