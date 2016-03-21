---
layout: page
title: Heading Attributes
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
