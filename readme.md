# HtmlTagNames

Python port of npm package [html-tag-names](https://www.npmjs.com/package/html-tag-names).

List of known HTML tag names.

## Contents

*   [What is this?](#what-is-this)
*   [When should I use this?](#when-should-i-use-this)
*   [Install](#install)
*   [Use](#use)
*   [API](#api)
    *   [`htmlTagNames`](#htmltagnames)
*   [Types](#types)
*   [Compatibility](#compatibility)
*   [Security](#security)
*   [Related](#related)
*   [Contribute](#contribute)
*   [License](#license)

## What is this?

This is a list of HTML tag names.
It includes ancient (for example, `nextid` and `basefont`) and modern (for
example, `shadow` and `template`) names from the HTML living standard.
The repo includes scripts to regenerate the data from the specs.

## When should I use this?

You can use this package when you need to know what tag names are allowed in
any version of HTML.

## Install

```sh
pip install html-tag-names
```

## Use

```py
from HtmlTagNames import html_tag_names

print(len(html_tag_names)) # => 148

print(html_tag_names[:20])
```

Yields:

```py
[
  'a',
  'abbr',
  'acronym',
  'address',
  'applet',
  'area',
  'article',
  'aside',
  'audio',
  'b',
  'base',
  'basefont',
  'bdi',
  'bdo',
  'bgsound',
  'big',
  'blink',
  'blockquote',
  'body',
  'br'
]
```
