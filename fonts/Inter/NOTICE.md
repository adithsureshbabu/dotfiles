# Inter

Copyright (c) 2016 The Inter Project Authors. Licensed under the SIL Open Font License 1.1, in `LICENSE.txt`.

Source: the static `Inter` fonts (`extras/ttf`) of [Inter 4.1](https://github.com/rsms/inter/releases/tag/v4.1) by
Rasmus Andersson.

Changed: the OpenType features `cv03`, `cv04`, `cv11`, `ss04` and `tnum` are on by default. Their lookups are added to
an always-on `rclt` feature in the `GSUB` table, so shaping matches setting them in CSS, including Inter's contextual
`calt` rules. Only `GSUB` and the `head` checksum differ from the original: outlines, hinting, kerning, metrics and
names are byte-identical. The italics have no `cv11`, because their `a` is already single-storey.

The `.woff2` files are the same fonts repackaged, with identical glyph data and hinting.
