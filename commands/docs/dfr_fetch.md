---
title: dfr fetch
categories: |
  lazyframe
version: 0.76.0
lazyframe: |
  collects the lazyframe to the selected rows
usage: |
  collects the lazyframe to the selected rows
---

# <code>{{ $frontmatter.title }}</code> for lazyframe

<div class='command-title'>{{ $frontmatter.lazyframe }}</div>

## Signature

```> dfr fetch ```

## Examples

Fetch a rows from the dataframe
```shell
> [[a b]; [6 2] [4 2] [2 2]] | dfr into-df | dfr fetch 2
```