---
title: split row
categories: |
  strings
version: 0.71.0
strings: |
  Split a string into multiple rows using a separator
usage: |
  Split a string into multiple rows using a separator
---

# <code>{{ $frontmatter.title }}</code> for strings

<div class='command-title'>{{ $frontmatter.strings }}</div>

## Signature

```> split row (separator) --number```

## Parameters

 -  `separator`: the character that denotes what separates rows
 -  `--number {int}`: Split into maximum number of items

## Examples

Split a string into rows of char
```shell
> echo 'abc' | split row ''
```

Split a string into rows by the specified separator
```shell
> echo 'a--b--c' | split row '--'
```
