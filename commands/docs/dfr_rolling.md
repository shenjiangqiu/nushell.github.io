---
title: dfr rolling
categories: |
  dataframe
version: 0.93.0
dataframe: |
  Rolling calculation for a series.
usage: |
  Rolling calculation for a series.
feature: dataframe
---
<!-- This file is automatically generated. Please edit the command in https://github.com/nushell/nushell instead. -->

# `dfr rolling` for [dataframe](/commands/categories/dataframe.md)

<div class='command-title'>Rolling calculation for a series.</div>

::: warning
Dataframe commands were not shipped in the official binaries by default, you have to build it with `--features=dataframe` flag
:::

## Signature

```> dfr rolling {flags} (type) (window)```

## Parameters

 -  `type`: rolling operation
 -  `window`: Window size for rolling


## Input/output types:

| input | output |
| ----- | ------ |
| any   | any    |

## Examples

Rolling sum for a series
```nu
> [1 2 3 4 5] | dfr into-df | dfr rolling sum 2 | dfr drop-nulls
╭───┬───────────────╮
│ # │ 0_rolling_sum │
├───┼───────────────┤
│ 0 │             3 │
│ 1 │             5 │
│ 2 │             7 │
│ 3 │             9 │
╰───┴───────────────╯

```

Rolling max for a series
```nu
> [1 2 3 4 5] | dfr into-df | dfr rolling max 2 | dfr drop-nulls
╭───┬───────────────╮
│ # │ 0_rolling_max │
├───┼───────────────┤
│ 0 │             2 │
│ 1 │             3 │
│ 2 │             4 │
│ 3 │             5 │
╰───┴───────────────╯

```
