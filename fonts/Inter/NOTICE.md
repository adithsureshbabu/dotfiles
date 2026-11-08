# Inter

Copyright (c) 2016 The Inter Project Authors. Licensed under the SIL Open Font License 1.1, in `LICENSE.txt`.

Source: [Inter 4.1](https://github.com/rsms/inter/releases/tag/v4.1) by Rasmus Andersson, with both axes (`opsz` 14 to
32 and `wght` 100 to 900) and the nine named instances kept.

Changed:
- The OpenType features `cv03`, `cv04`, `cv11`, `ss04` and `tnum` are on by default. Their lookups are added to an
  always-on `rclt` feature in the `GSUB` table, so shaping matches setting them in CSS, including Inter's contextual
  `calt` rules. The same lookups are also listed in `calt`, because Windows 7 and 8.1 ignore `rclt`. The italic has no
  `cv11`, because its `a` is already single-storey.
- The family, full and PostScript names are shortened to "Inter".

Only `GSUB`, `name` and the `head` checksum differ from the original: outlines, variation data, kerning and metrics
are byte-identical.

The `.woff2` files are the same fonts repackaged, with identical glyph data and variation data.
