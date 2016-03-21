---
layout: page
title:  Auto Identifiers
---

tags: headings, ids

A header without an explicitly specified identifier will be automatically assigned
a unique identifier based on the header text. To derive the identifier from the header text,

- Remove all formatting, links, etc.
- Remove all footnotes.
- Remove all punctuation, except underscores, hyphens, and periods.
- Replace all spaces and newlines with hyphens.
- Convert all alphabetic characters to lowercase.
- Remove everything up to the first letter (identifiers may not begin with a number or punctuation mark).
- If nothing is left after this, use the identifier section.

Thus, for example,

Header                       |  Identifier
---------------------------- | ------------
Header identifiers in HTML   |	`header-identifiers-in-html`
`*Dogs*?--in *my* house?`    |	`dogs--in-my-house`
`[HTML], [S5], or [RTF]?`    |  `html-s5-or-rtf`
`3. Applications`            |  `applications`
`33`	                     |  `section`


