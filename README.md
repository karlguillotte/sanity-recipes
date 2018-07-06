# sanity-recipes

Just a collection of recipies / snippets / frequently asked questions about Sanity.

Note that these things are just meant as inspiration and is usually not documented. You'll usually have to copy + paste the code and possibly adjust it slightly to fit your use case. Some might be published as NPM modules at some point if it makes sense.

## Table of Contents

- [Block content / block text](#block-content)
  - [As plain text](#block-content-as-plain-text)
  - [Convert quotation marks](#convert-quotation-marks-in-block-text)

---

## Block Content

### Block content as plain text

Sometimes you just want to skim over a whole bunch of block content as text. [This function](snippets/blocksToText.js) does this, with some basic options for handling non-text nodes.

### Convert quotation marks in block text

Someone wanted to convert "whatever" to «whatever» when rendering. [convertQuotationMarks()](snippets/convertQuotationMarks.js) to the rescue!
