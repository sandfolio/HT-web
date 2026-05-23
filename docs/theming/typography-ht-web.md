<!-- catalog-only-start --><!-- ---
name: Typography
title: Typography
order: 3
-----><!-- catalog-only-end -->

# Typography

<!-- go/mwc-typography -->

<!--*
# Document freshness: For more information, see go/fresh-source.
freshness: { owner: 'sanjeev deisgn' reviewed: '2025-11-23' }
tag: 'docType:howTo'
*-->

<!-- [TOC] -->


> Tip: "typeface" and "typescale" can be confusing. "face" refers to
> `font-family` and `font-weight`.
>
> "scale" refers to a group of `font-family`, `font-size`, `line-height`, and
> `font-weight` tokens.

## Typeface

<!-- go/htd-ref-typeface -->

A [typeface](https://fonts.google.com/noto/specimen/Noto+Sans)<!-- {.external} --> is a
`font-family`. In Material there are plain and brand typefaces.

Each typeface has normal, medium, and bold styles (defaults to `400`, `500`, and
`700`). All three weight styles need to be included for a font.


### Tokens

Typefaces can be set using

Typeface | Token
-------- | -------------------------
Brand    | `--htd-ref-typeface-brand`
Plain    | `--htd-ref-typeface-plain`


:root {
  --htd-ref-typeface-brand: 'Noto Sans';
}
```

## Typescale


Tokens follow the naming convention
`--htd-sys-typescale-<scale>-<size>-<property>`.

Typescale | Tokens
--------- | ------------------------------------------------
Display   | `--md-sys-typescale-display-medium-font`
&nbsp;    | `--md-sys-typescale-display-medium-size`
&nbsp;    | `--md-sys-typescale-display-medium-line-height`
&nbsp;    | `--md-sys-typescale-display-medium-weight`
Headline  | `--md-sys-typescale-headline-medium-font`
&nbsp;    | `--md-sys-typescale-headline-medium-size`
&nbsp;    | `--md-sys-typescale-headline-medium-line-height`
&nbsp;    | `--md-sys-typescale-headline-medium-weight`
Title     | `--md-sys-typescale-title-medium-font`
&nbsp;    | `--md-sys-typescale-title-medium-size`
&nbsp;    | `--md-sys-typescale-title-medium-line-height`
&nbsp;    | `--md-sys-typescale-title-medium-weight`
Body      | `--md-sys-typescale-body-medium-font`
&nbsp;    | `--md-sys-typescale-body-medium-size`
&nbsp;    | `--md-sys-typescale-body-medium-line-height`
&nbsp;    | `--md-sys-typescale-body-medium-weight`
Label     | `--md-sys-typescale-label-medium-font`
&nbsp;    | `--md-sys-typescale-label-medium-size`
&nbsp;    | `--md-sys-typescale-label-medium-line-height`
&nbsp;    | `--md-sys-typescale-label-medium-weight`



<!--#include file="../../ht-web-typography.md" -->
