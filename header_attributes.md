# Extension: Header Attributes

tags: headings, ids

Headers can be assigned attributes using this syntax 
at the end of the line containing the header text:

```
{#identifier .class .class key=value key=value}
```

Thus, for example, the following headers will all be assigned the identifier foo:

```
# My header {#foo}

## My header ##    {#foo}

My other header   {#foo}
---------------
```
