---
title: to arrow
categories: |
  dataframe
version: 0.71.0
dataframe: |
  Saves dataframe to arrow file
usage: |
  Saves dataframe to arrow file
---

# <code>{{ $frontmatter.title }}</code> for dataframe

<div class='command-title'>{{ $frontmatter.dataframe }}</div>

## Signature

```> to arrow (file)```

## Parameters

 -  `file`: file path to save dataframe

## Examples

Saves dataframe to arrow file
```shell
> [[a b]; [1 2] [3 4]] | into df | to arrow test.arrow
```