---
title: to
categories: |
  formats
version: 0.93.0
formats: |
  Translate structured data to a format.
usage: |
  Translate structured data to a format.
feature: default
---
<!-- This file is automatically generated. Please edit the command in https://github.com/nushell/nushell instead. -->

# `to` for [formats](/commands/categories/formats.md)

<div class='command-title'>Translate structured data to a format.</div>

## Signature

```> to {flags} ```


## Input/output types:

| input   | output |
| ------- | ------ |
| nothing | string |

## Notes
You must use one of the following subcommands. Using this command as-is will only produce this help message.

## Subcommands:

| name                                           | type    | usage                                                         |
| ---------------------------------------------- | ------- | ------------------------------------------------------------- |
| [`to csv`](/commands/docs/to_csv.md)           | Builtin | Convert table into .csv text .                                |
| [`to html`](/commands/docs/to_html.md)         | Builtin | Convert table into simple HTML.                               |
| [`to json`](/commands/docs/to_json.md)         | Builtin | Converts table data into JSON text.                           |
| [`to md`](/commands/docs/to_md.md)             | Builtin | Convert table into simple Markdown.                           |
| [`to msgpack`](/commands/docs/to_msgpack.md)   | Builtin | Convert Nu values into MessagePack.                           |
| [`to msgpackz`](/commands/docs/to_msgpackz.md) | Builtin | Convert Nu values into brotli-compressed MessagePack.         |
| [`to nuon`](/commands/docs/to_nuon.md)         | Builtin | Converts table data into Nuon (Nushell Object Notation) text. |
| [`to text`](/commands/docs/to_text.md)         | Builtin | Converts data into simple text.                               |
| [`to toml`](/commands/docs/to_toml.md)         | Builtin | Convert record into .toml text.                               |
| [`to tsv`](/commands/docs/to_tsv.md)           | Builtin | Convert table into .tsv text.                                 |
| [`to xml`](/commands/docs/to_xml.md)           | Builtin | Convert special record structure into .xml text.              |
| [`to yaml`](/commands/docs/to_yaml.md)         | Builtin | Convert table into .yaml/.yml text.                           |