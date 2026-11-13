## FontSpector report

fontspector version: 1.9.0






## Check results




<details><summary>[3] fonts/variable</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent (family/win_ascent_and_descent)</summary>
    <div>








- 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1026, but got 1007 instead. The highest point is in glyph 'tthIsinh' at wght=700. [code: ascent]
  
  


- 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 490, but got 200 instead. The lowest point is in glyph 'lUsinh' at wght=700. [code: descent]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. (googlefonts/glyph_coverage)</summary>
    <div>








- 🔥 **FAIL** fonts/variable/LankaverseSansCANARY[wght].ttf missing required codepoints:

* 0x00A0: NO-BREAK SPACE
* 0x010A: LATIN CAPITAL LETTER C WITH DOT ABOVE
* 0x010B: LATIN SMALL LETTER C WITH DOT ABOVE
* 0x0120: LATIN CAPITAL LETTER G WITH DOT ABOVE
* 0x0121: LATIN SMALL LETTER G WITH DOT ABOVE
* 0x0126: LATIN CAPITAL LETTER H WITH STROKE
* 0x0127: LATIN SMALL LETTER H WITH STROKE
* 0x0174: LATIN CAPITAL LETTER W WITH CIRCUMFLEX
* 0x0175: LATIN SMALL LETTER W WITH CIRCUMFLEX
* 0x0176: LATIN CAPITAL LETTER Y WITH CIRCUMFLEX
* 0x0177: LATIN SMALL LETTER Y WITH CIRCUMFLEX
* 0x0237: LATIN SMALL LETTER DOTLESS J
* 0x0300: COMBINING GRAVE ACCENT
* 0x0301: COMBINING ACUTE ACCENT
* 0x0302: COMBINING CIRCUMFLEX ACCENT
* 0x0303: COMBINING TILDE
* 0x0304: COMBINING MACRON
* 0x0306: COMBINING BREVE
* 0x0307: COMBINING DOT ABOVE
* 0x0308: COMBINING DIAERESIS
* 0x030A: COMBINING RING ABOVE
* 0x030B: COMBINING DOUBLE ACUTE ACCENT
* 0x030C: COMBINING CARON
* 0x0326: COMBINING COMMA BELOW
* 0x0327: COMBINING CEDILLA
* 0x0328: COMBINING OGONEK
* 0x1E80: LATIN CAPITAL LETTER W WITH GRAVE
* 0x1E81: LATIN SMALL LETTER W WITH GRAVE
* 0x1E82: LATIN CAPITAL LETTER W WITH ACUTE
* 0x1E83: LATIN SMALL LETTER W WITH ACUTE
* 0x1E84: LATIN CAPITAL LETTER W WITH DIAERESIS
* 0x1E85: LATIN SMALL LETTER W WITH DIAERESIS
* 0x1E9E: LATIN CAPITAL LETTER SHARP S
* 0x1EF2: LATIN CAPITAL LETTER Y WITH GRAVE
* 0x1EF3: LATIN SMALL LETTER Y WITH GRAVE [code: missing-codepoints]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** fonts/variable/LankaverseSansCANARY[wght].ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
* U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
* U+03C0 GREEK SMALL LETTER PI: try adding one of: math, greek, yi
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2126 OHM SIGN: try adding math
* U+212E ESTIMATED SYMBOL: try adding math
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+2219 BULLET OPERATOR: try adding one of: symbols, yi, math, tai-tham
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+25CA LOZENGE: try adding one of: symbols, math

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin, sinhala, tamil [code: unreachable-subsetting]
  
  

</div>
</details>


</div>
</details>


<details><summary>[24] fonts/variable/LankaverseSansCANARY[wght].ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check base characters have non-zero advance width. (base_has_width)</summary>
    <div>








- 🔥 **FAIL** The following glyphs had zero advance width:

* uni0BC1 (Some(3009))
* uni0BC2 (Some(3010)) [code: zero-width-bases]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- 🔥 **FAIL** Font appears to be an Indic font but is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Font contains glyphs for whitespace characters? (whitespace_glyphs)</summary>
    <div>








- 🔥 **FAIL** Whitespace glyph missing for codepoint 0x00A0 [code: missing-whitespace-glyph-0x00A0]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- 🔥 **FAIL** Failed language shaping:

| Message                                                                                       | Languages                    |
|-----------------------------------------------------------------------------------------------|------------------------------|
| Mandatory orthography codepoints:                                                             | * fr_Latn (French)           |
|   The following mark characters are missing from the font: ̧, ̂, ́, ̀, ̈                           |                              |
| Mandatory orthography codepoints:                                                             | * tr_Latn (Turkish)          |
|   The following mark characters are missing from the font: ̆, ̇, ̂, ̦, ̧, ̈                         |                              |
| Mandatory orthography codepoints:                                                             | * it_Latn (Italian)          |
|   The following mark characters are missing from the font: ́, ̈, ̂, ̀                             |                              |
| Mandatory orthography codepoints:                                                             | * fi_Latn (Finnish)          |
|   The following mark characters are missing from the font: ̈, ̃, ̊, ̌                             |                              |
| Mandatory orthography codepoints:                                                             | * cs_Latn (Czech)            |
|   The following mark characters are missing from the font: ́, ̊, ̌                               |                              |
| Mandatory orthography codepoints:                                                             | * da_Latn (Danish)           |
|   The following mark characters are missing from the font: ̊, ́                                 |                              |
| Mandatory orthography codepoints:                                                             | * pt_Latn (Portuguese)       |
|   The following mark characters are missing from the font: ̈, ̧, ́, ̃, ̀, ̂                         |                              |
| Mandatory orthography codepoints:                                                             | * ro_Latn (Romanian)         |
|   The following mark characters are missing from the font: ̂, ̆, ̦, ̧                             |                              |
| Mandatory orthography codepoints:                                                             | * es_Latn (Spanish)          |
|   The following mark characters are missing from the font: ̃, ̈, ́                               |                              |
| Mandatory orthography codepoints:                                                             | * mt_Latn (Maltese)          |
|   The following base characters are missing from the font: ċ, ġ, ħ, Ċ, Ġ, Ħ, GĦ, għ           |                              |
|   The following mark characters are missing from the font: ̂, ̇, ̀                               |                              |
| Mandatory orthography codepoints:                                                             | * is_Latn (Icelandic)        |
|   The following mark characters are missing from the font: ́, ̈, ̨                               |                              |
| Mandatory orthography codepoints:                                                             | * hu_Latn (Hungarian)        |
|   The following mark characters are missing from the font: ̈, ́, ̋                               |                              |
| Mandatory orthography codepoints:                                                             | * de_Latn (German)           |
|   The following base characters are missing from the font: ẞ                                  |                              |
|   The following mark characters are missing from the font: ̀, ̈, ́                               |                              |
| Mandatory orthography codepoints:                                                             | * nb_Latn (Norwegian Bokmål) |
|   The following mark characters are missing from the font: ́, ̈, ̊, ̂, ̀                           |                              |
| Mandatory orthography codepoints:                                                             | * pl_Latn (Polish)           |
|   The following mark characters are missing from the font: ̇, ̨, ́                               |                              |
| Mandatory orthography codepoints:                                                             | * sq_Latn (Albanian)         |
|   The following mark characters are missing from the font: ̈, ̧                                 |                              |
| Mandatory orthography codepoints:                                                             | * nl_Latn (Dutch)            |
|   The following base characters are missing from the font: íj́, ÍJ́                             |                              |
|   The following mark characters are missing from the font: ́, ̈, ̂, ̀                             |                              |
| Mandatory orthography codepoints:                                                             | * lv_Latn (Latvian)          |
|   The following mark characters are missing from the font: ̄, ̌, ̧                               |                              |
| Mandatory orthography codepoints:                                                             | * cy_Latn (Welsh)            |
|   The following base characters are missing from the font: ỳ, Ỳ, ŷ, ŵ, Ŵ, ẁ, Ẁ, ẅ, Ŷ, Ẅ, ẃ, Ẃ |                              |
|   The following mark characters are missing from the font: ̂, ́, ̈, ̀                             |                              |
| Mandatory orthography codepoints:                                                             | * sk_Latn (Slovak)           |
|   The following mark characters are missing from the font: ̌, ̂, ́, ̈                             |                              |
| Mandatory orthography codepoints:                                                             | * sv_Latn (Swedish)          |
|   The following mark characters are missing from the font: ̊, ̀, ̈, ́                             |                              |
| Mandatory orthography codepoints:                                                             | * en_Latn (English)          |
|   The following mark characters are missing from the font: ́, ̂, ̃, ̈, ̧, ̀                         |                              |
| Mandatory orthography codepoints:                                                             | * lt_Latn (Lithuanian)       |
|   The following mark characters are missing from the font: ̨, ̌, ̇, ̄                             |                              |
| Mandatory orthography codepoints:                                                             | * ca_Latn (Catalan)          |
|   The following mark characters are missing from the font: ́, ̀, ̈, ̧                             |                              |
| Mandatory orthography codepoints:                                                             | * hr_Latn (Croatian)         |
|   The following mark characters are missing from the font: ́, ̌                                 |                              | [code: failed-language-shaping]
  
  


- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages                    |
|-------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                 | * da_Latn (Danish)           |
|   The following auxiliary characters are missing from the font: Ǿ |                              |
|   The following auxiliary characters are missing from the font: ǿ |                              |
| Auxiliary orthography codepoints:                                 | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ǎ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: ǎ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ċ |                              |
|   The following auxiliary characters are missing from the font: Ǧ |                              |
|   The following auxiliary characters are missing from the font: Ǥ |                              |
|   The following auxiliary characters are missing from the font: Ȟ |                              |
|   The following auxiliary characters are missing from the font: Ħ |                              |
|   The following auxiliary characters are missing from the font: Ǩ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŝ |                              |
|   The following auxiliary characters are missing from the font: ẞ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: Ʒ |                              |
|   The following auxiliary characters are missing from the font: Ǯ |                              |
|   The following auxiliary characters are missing from the font: ċ |                              |
|   The following auxiliary characters are missing from the font: ǧ |                              |
|   The following auxiliary characters are missing from the font: ǥ |                              |
|   The following auxiliary characters are missing from the font: ȟ |                              |
|   The following auxiliary characters are missing from the font: ħ |                              |
|   The following auxiliary characters are missing from the font: ǩ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŝ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
|   The following auxiliary characters are missing from the font: ʒ |                              |
|   The following auxiliary characters are missing from the font: ǯ |                              |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ſ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * it_Latn (Italian)          |
|   The following auxiliary characters are missing from the font: ẞ | * pl_Latn (Polish)           |
| Auxiliary orthography codepoints:                                 | * lt_Latn (Lithuanian)       |
|   The following auxiliary characters are missing from the font: Ą́ |                              |
|   The following auxiliary characters are missing from the font: Ą̃ |                              |
|   The following auxiliary characters are missing from the font: Ẽ |                              |
|   The following auxiliary characters are missing from the font: Ę́ |                              |
|   The following auxiliary characters are missing from the font: Ę̃ |                              |
|   The following auxiliary characters are missing from the font: Ė́ |                              |
|   The following auxiliary characters are missing from the font: Ė̃ |                              |
|   The following auxiliary characters are missing from the font: İ́ |                              |
|   The following auxiliary characters are missing from the font: İ́ |                              |
|   The following auxiliary characters are missing from the font: İ̀ |                              |
|   The following auxiliary characters are missing from the font: İ̀ |                              |
|   The following auxiliary characters are missing from the font: İ̃ |                              |
|   The following auxiliary characters are missing from the font: İ̃ |                              |
|   The following auxiliary characters are missing from the font: Ĩ |                              |
|   The following auxiliary characters are missing from the font: Į́ |                              |
|   The following auxiliary characters are missing from the font: Į̇́ |                              |
|   The following auxiliary characters are missing from the font: Į̃ |                              |
|   The following auxiliary characters are missing from the font: Į̇̃ |                              |
|   The following auxiliary characters are missing from the font: J̃ |                              |
|   The following auxiliary characters are missing from the font: J̇̃ |                              |
|   The following auxiliary characters are missing from the font: L̃ |                              |
|   The following auxiliary characters are missing from the font: M̃ |                              |
|   The following auxiliary characters are missing from the font: R̃ |                              |
|   The following auxiliary characters are missing from the font: Ũ |                              |
|   The following auxiliary characters are missing from the font: Ų́ |                              |
|   The following auxiliary characters are missing from the font: Ų̃ |                              |
|   The following auxiliary characters are missing from the font: Ū́ |                              |
|   The following auxiliary characters are missing from the font: Ū̃ |                              |
|   The following auxiliary characters are missing from the font: ą́ |                              |
|   The following auxiliary characters are missing from the font: ą̃ |                              |
|   The following auxiliary characters are missing from the font: ẽ |                              |
|   The following auxiliary characters are missing from the font: ę́ |                              |
|   The following auxiliary characters are missing from the font: ę̃ |                              |
|   The following auxiliary characters are missing from the font: ė́ |                              |
|   The following auxiliary characters are missing from the font: ė̃ |                              |
|   The following auxiliary characters are missing from the font: i̇́ |                              |
|   The following auxiliary characters are missing from the font: i̇̀ |                              |
|   The following auxiliary characters are missing from the font: i̇̃ |                              |
|   The following auxiliary characters are missing from the font: ĩ |                              |
|   The following auxiliary characters are missing from the font: į́ |                              |
|   The following auxiliary characters are missing from the font: į̇́ |                              |
|   The following auxiliary characters are missing from the font: į̃ |                              |
|   The following auxiliary characters are missing from the font: į̇̃ |                              |
|   The following auxiliary characters are missing from the font: j̃ |                              |
|   The following auxiliary characters are missing from the font: j̇̃ |                              |
|   The following auxiliary characters are missing from the font: l̃ |                              |
|   The following auxiliary characters are missing from the font: m̃ |                              |
|   The following auxiliary characters are missing from the font: r̃ |                              |
|   The following auxiliary characters are missing from the font: ũ |                              |
|   The following auxiliary characters are missing from the font: ų́ |                              |
|   The following auxiliary characters are missing from the font: ų̃ |                              |
|   The following auxiliary characters are missing from the font: ū́ |                              |
|   The following auxiliary characters are missing from the font: ū̃ |                              |
| Auxiliary orthography codepoints:                                 | * nl_Latn (Dutch)            |
|   The following auxiliary characters are missing from the font: Ĳ |                              |
|   The following auxiliary characters are missing from the font: ĳ |                              |
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)           |
|   The following auxiliary characters are missing from the font: ẞ |                              |
|   The following auxiliary characters are missing from the font: Ǔ |                              |
|   The following auxiliary characters are missing from the font: ſ |                              |
|   The following auxiliary characters are missing from the font: ǔ |                              |
| Auxiliary orthography codepoints:                                 | * tr_Latn (Turkish)          |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: ẞ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * en_Latn (English)          |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
|   The following auxiliary characters are missing from the font: ʻ |                              |
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)          |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŀ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŀ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * cs_Latn (Czech)            |
|   The following auxiliary characters are missing from the font: Ĕ | * cy_Latn (Welsh)            |
|   The following auxiliary characters are missing from the font: Ĭ | * es_Latn (Spanish)          |
|   The following auxiliary characters are missing from the font: Ŏ | * hu_Latn (Hungarian)        |
|   The following auxiliary characters are missing from the font: Ŭ | * pt_Latn (Portuguese)       |
|   The following auxiliary characters are missing from the font: ĕ | * sk_Latn (Slovak)           |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- 🔥 **FAIL** No dotted circle glyph present and font uses a complex shaper [code: missing-dotted-circle-complex]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct (googlefonts/font_names)</summary>
    <div>








- 🔥 **FAIL** Font names are incorrect:

| Name                       | Current                          | Expected                         |
|----------------------------|----------------------------------|----------------------------------|
| Family Name                | **Lankaverse Sans Light CANARY** | **Lankaverse Sans CANARY Light** |
| Subfamily Name             | Regular                          | Regular                          |
| Full Name                  | **Lankaverse Sans Light CANARY** | **Lankaverse Sans CANARY Light** |
| Postscript Name            | LankaverseSansCANARY-Light       | LankaverseSansCANARY-Light       |
| Typographic Family Name    | Lankaverse Sans CANARY           | Lankaverse Sans CANARY           |
| Typographic Subfamily Name | Light                            | Light                            | [code: bad-names]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Version format is correct in 'name' table? (googlefonts/name/version_format)</summary>
    <div>








- 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000.

The "Version" prefix is a recommendation given by the OpenType spec.

Current version string is: "Version 0.500; [3502613]-dev" [code: bad-version-strings]
  
  


- 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000.

The "Version" prefix is a recommendation given by the OpenType spec.

Current version string is: "Version 0.500; [3502613]-dev" [code: bad-version-strings]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (googlefonts/use_typo_metrics)</summary>
    <div>








- 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) was NOT set. [code: missing-os2-fsselection-bit7]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. (opentype/GDEF_mark_chars)</summary>
    <div>








- ⚠️ **WARN** The following mark characters should be in the GDEF mark glyph class:

* U+0DCA (uni0DCA)
* U+0DD2 (uni0DD2)
* U+0DD3 (uni0DD3)
* U+0DD4 (uni0DD4)
* U+0DD6 (uni0DD6) [code: mark-chars]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron (alt_caron)</summary>
    <div>








- ⚠️ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
  
  


- ⚠️ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
  
  


- ⚠️ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
  
  


- ⚠️ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* uni0D8D (U+0D8D): found 2, expected one of: [3, 4, 6]
* uni0D8E (U+0D8E): found 3, expected one of: [5, 6, 8]
* uni0D95 (U+0D95): found 2, expected one of: [3, 4]
* uni0DD3 (U+0DD3): found 1, expected one of: [2, 3]
* uni0DDF (U+0DDF): found 2, expected one of: [1]
* uni0D9E (U+0D9E): found 1, expected one of: [2, 3, 4]
* uni0DA4 (U+0DA4): found 5, expected one of: [3, 4, 6]
* uni0DBD (U+0DBD): found 2, expected one of: [1, 4]
* uni0DC4 (U+0DC4): found 2, expected one of: [1, 3, 4]
* uni0DC5 (U+0DC5): found 1, expected one of: [2, 3, 4]
* uni0B95 (U+0B95): found 1, expected one of: [2, 3, 4]
* uni0B9A (U+0B9A): found 1, expected one of: [2, 3, 4]
* uni0B9E (U+0B9E): found 3, expected one of: [2, 5]
* uni0BA3 (U+0BA3): found 2, expected one of: [3, 4, 5]
* uni0BA8 (U+0BA8): found 2, expected one of: [1, 4, 5]
* uni0BA9 (U+0BA9): found 2, expected one of: [3, 4]
* uni0BB8 (U+0BB8): found 3, expected one of: [1, 2]
* uni0BD0 (U+0BD0): found 3, expected one of: [4, 5, 6]
* uni0BF1 (U+0BF1): found 2, expected one of: [1, 3, 4]
* uni0BEB (U+0BEB): found 2, expected one of: [1, 3, 4]
* uni0BEF (U+0BEF): found 1, expected one of: [2, 4]
* five (U+0035): found 3, expected one of: [1, 2, 5]
* guillemotleft (U+00AB): found 4, expected one of: [2, 6]
* guillemotright (U+00BB): found 4, expected one of: [2, 6]
* guilsinglleft (U+2039): found 2, expected one of: [1, 5]
* guilsinglright (U+203A): found 2, expected one of: [1, 5]
* uni0BF3 (U+0BF3): found 3, expected one of: [2]
* uni0BF5 (U+0BF5): found 5, expected one of: [2, 6]
* uni0BF6 (U+0BF6): found 3, expected one of: [2, 4]
* summation (U+2211): found 3, expected one of: [1, 2]
* uni0BC2 (U+0BC2): found 1, expected one of: [2] [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? (gpos_kerning_info)</summary>
    <div>








- ⚠️ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. (interpolation_issues)</summary>
    <div>








- ⚠️ **WARN** Interpolation issue in uni0DDA: Contour order mismatch: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14] in default vs [6, 4, 2, 1, 0, 3, 5, 7, 9, 11, 10, 8, 12, 13, 14] in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Wrong start point: contour 0 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Contour 0 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Wrong start point: contour 1 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Contour 1 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Wrong start point: contour 2 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Contour 2 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Wrong start point: contour 3 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Contour 3 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Wrong start point: contour 4 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Contour 4 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Wrong start point: contour 5 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Contour 5 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Wrong start point: contour 6 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Contour 6 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Wrong start point: contour 7 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Contour 7 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Wrong start point: contour 8 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Contour 8 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Wrong start point: contour 9 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Contour 9 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Wrong start point: contour 10 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Contour 10 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Wrong start point: contour 11 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDA: Contour 11 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Contour order mismatch: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14] in default vs [6, 4, 2, 1, 0, 3, 5, 7, 9, 11, 10, 8, 12, 13, 14] in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Wrong start point: contour 0 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Contour 0 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Wrong start point: contour 1 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Contour 1 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Wrong start point: contour 2 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Contour 2 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Wrong start point: contour 3 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Contour 3 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Wrong start point: contour 4 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Contour 4 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Wrong start point: contour 5 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Contour 5 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Wrong start point: contour 6 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Contour 6 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Wrong start point: contour 7 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Contour 7 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Wrong start point: contour 8 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Contour 8 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Wrong start point: contour 9 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Contour 9 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Wrong start point: contour 10 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Contour 10 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Wrong start point: contour 11 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDC: Contour 11 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Contour order mismatch: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15] in default vs [6, 4, 2, 1, 0, 3, 5, 7, 9, 11, 10, 8, 12, 13, 14, 15] in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Wrong start point: contour 0 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Contour 0 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Wrong start point: contour 1 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Contour 1 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Wrong start point: contour 2 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Contour 2 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Wrong start point: contour 3 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Contour 3 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Wrong start point: contour 4 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Contour 4 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Wrong start point: contour 5 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Contour 5 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Wrong start point: contour 6 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Contour 6 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Wrong start point: contour 7 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Contour 7 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Wrong start point: contour 8 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Contour 8 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Wrong start point: contour 9 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Contour 9 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Wrong start point: contour 10 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Contour 10 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Wrong start point: contour 11 should start at 2 in wght=700 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0DDE: Contour 11 becomes underweight in wght=700 compared to default [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in turkishlira: Contour order mismatch: [0, 1, 2, 3] in default vs [0, 1, 3, 2] in wght=700 [code: interpolation-issue]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 544 among a set of 13  math glyphs.
The following math glyphs have a different width, though:
width=625: approxequal
width=539: lessequal, greaterequal
width=510: less, greater
width=535: logicalnot
width=481: multiply [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? (soft_hyphen)</summary>
    <div>








- ⚠️ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* visargayasinh
* phRasinh
* uni00A0
* space.001
* uni20BD
* mooniak
* tmVirama
* turkishlira
* snRAc2.01
* snRAc2.02
* snRAc2.03
* snRAc2.04
* snRAc2.05
* snRAc2.06
* snRAc2.07
* snRAc2.08
* tmHA.alt
* tmKSSA.alt [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* jhsinh
* uni0BEB (U+0BEB)
* uni0DAC (U+0DAC)
* jIsinh
* registered (U+00AE)
* racute (U+0155)
* uni0BA4 (U+0BA4)
* uni0BB6 (U+0BB6)
* rUusinh
* m (U+006D)
* pi (U+03C0)
* tmJU
* uni0B9E (U+0B9E)
* nDRasinh
* daggerdbl (U+2021)
* Thorn (U+00DE)
* asciicircum (U+005E)
* tmKSSA
* tmRII.alt
* emacron (U+0113)
* ndRasinh
* tmHI
* tmNNAI.traditional
* eth (U+00F0)
* uni0DAA (U+0DAA)
* nDhIisinh
* nyjIisinh
* uni0BB3 (U+0BB3)
* tmLII
* dDhIisinh
* tmNNNAA.traditional
* dVasinh
* ddhsinh
* uni0DAB (U+0DAB)
* uni0156 (U+0156)
* uni0DAD (U+0DAD)
* tmSSI
* jhIisinh
* lUsinh
* Lslash (U+0141)
* tmYUU
* tmLLLII
* Dcaron (U+010E)
* jnyUusinh
* uni0D8A (U+0D8A)
* uni0D96 (U+0D96)
* tThasinh
* uni0DA1 (U+0DA1)
* nThasinh
* eogonek (U+0119)
* fi (U+FB01)
* uni0DC4 (U+0DC4)
* uni0BD7 (U+0BD7)
* f_f (U+FB00)
* h (U+0068)
* Iogonek (U+012E)
* uni0DF2 (U+0DF2)
* uni0D9E (U+0D9E)
* gDhIsinh
* f_f_i (U+FB03)
* R (U+0052)
* nnIsinh
* uni0DA3 (U+0DA3)
* nyCIsinh
* tmTI
* uni0BF6 (U+0BF6)
* r (U+0072)
* q (U+0071)
* tVsinh
* rAaesinh
* asterisk (U+002A)
* uni0DDC (U+0DDC)
* jsinh
* edieresis (U+00EB)
* bhUsinh
* jnyUsinh
* tmSSII
* tmNGU
* tUsinh
* uni0DDE (U+0DDE)
* uni0D8D (U+0D8D)
* uni0BB9 (U+0BB9)
* tThsinh
* uni0B94 (U+0B94)
* dollar (U+0024)
* adieresis (U+00E4)
* uni0BC8 (U+0BC8)
* uni0BCB (U+0BCB)
* ttTthIisinh
* mbIsinh
* tmNGUU
* tmSI
* tmRI.alt
* umacron (U+016B)
* uni0D87 (U+0D87)
* uni0D95 (U+0D95)
* thIsinh
* dIsinh
* lslash (U+0142)
* tmMU
* Atilde (U+00C3)
* u (U+0075)
* tmNNNUU
* kVIisinh
* ttTthsinh
* uni0DB3 (U+0DB3)
* tVIsinh
* eight (U+0038)
* tmNII
* rIisinh
* uni0BF2 (U+0BF2)
* nUusinh
* llRasinh
* Gbreve (U+011E)
* multiply (U+00D7)
* uni0BC2 (U+0BC2)
* uni0162 (U+0162)
* bIisinh
* mIsinh
* uni0D8C (U+0D8C)
* thorn (U+00FE)
* cIisinh
* ecaron (U+011B)
* uni0DA4 (U+0DA4)
* nUsinh
* uni0BF1 (U+0BF1)
* uni0BEF (U+0BEF)
* gUusinh
* agrave (U+00E0)
* tmNUU
* tmTTUU
* uni0122 (U+0122)
* csinh
* nDhsinh
* tmNNII
* gDhIisinh
* dagger (U+2020)
* T (U+0054)
* phIisinh
* tmMII
* uni0146 (U+0146)
* uni0BEA (U+0BEA)
* uni0DD8 (U+0DD8)
* uni0D8F (U+0D8F)
* G (U+0047)
* dhsinh
* uni0BF8 (U+0BF8)
* uni0DC5 (U+0DC5)
* uhungarumlaut (U+0171)
* ddhIsinh
* a (U+0061)
* uni2126 (U+2126)
* tmVII
* ugrave (U+00F9)
* tmLUU
* Edieresis (U+00CB)
* two (U+0032)
* snYAc2
* at (U+0040)
* rUsinh
* vsinh
* uni0DAE (U+0DAE)
* edotaccent (U+0117)
* uni0B99 (U+0B99)
* f_f_l (U+FB04)
* uni0DB8 (U+0DB8)
* dDhasinh
* dRasinh
* uni0DDD (U+0DDD)
* uni0D8E (U+0D8E)
* plus (U+002B)
* uni0137 (U+0137)
* yen (U+00A5)
* tmPI
* uni0157 (U+0157)
* kVIsinh
* uni0BED (U+0BED)
* tthIisinh
* aogonek (U+0105)
* uni0BB2 (U+0BB2)
* Lcaron (U+013D)
* threequarters (U+00BE)
* tmNNNU
* uni0DC2 (U+0DC2)
* shUusinh
* Eth (U+00D0)
* Racute (U+0154)
* tThIisinh
* bIsinh
* tmLAI.traditional
* rcaron (U+0159)
* tmLLUU
* nThIsinh
* nVIisinh
* chIisinh
* uni0D94 (U+0D94)
* uni0BAF (U+0BAF)
* tmCI
* tmKUU
* tmNYUU
* tmRRI
* oe (U+0153)
* nDasinh
* vIisinh
* uni0BCA (U+0BCA)
* Amacron (U+0100)
* tmJII
* uni0DCA (U+0DCA)
* tthsinh
* uni0D90 (U+0D90)
* dcroat (U+0111)
* uni021B (U+021B)
* ddhIisinh
* uni013B (U+013B)
* A (U+0041)
* ndUusinh
* p (U+0070)
* tmNGII
* Eogonek (U+0118)
* uni0BC6 (U+0BC6)
* bhUusinh
* tmRRII
* tmVUU
* Euro (U+20AC)
* abreve (U+0103)
* tmNU
* uni0DB6 (U+0DB6)
* llUusinh
* tmYII
* uni0DA8 (U+0DA8)
* dDhsinh
* Edotaccent (U+0116)
* tmHII
* tmCII
* tthIsinh
* uni0BB7 (U+0BB7)
* dhIisinh
* Eacute (U+00C9)
* cent (U+00A2)
* uni0B92 (U+0B92)
* uni0B8F (U+0B8F)
* tmNNAA.traditional
* tmRRUU
* Agrave (U+00C0)
* four (U+0034)
* numbersign (U+0023)
* OE (U+0152)
* ngIisinh
* E (U+0045)
* tmSHRII
* tmNNNAI.traditional
* tmCUU
* phsinh
* lessequal (U+2264)
* tmNNNII
* tmNGI
* nVasinh
* turkishlira
* tmCU
* tmRII
* Rcaron (U+0158)
* aacute (U+00E1)
* uni0BF7 (U+0BF7)
* nyjIsinh
* tUusinh
* ngsinh
* Yacute (U+00DD)
* uni0BB4 (U+0BB4)
* lUusinh
* tmRI
* uni0DC1 (U+0DC1)
* tmSHUU
* tmPUU
* nDhIsinh
* Adieresis (U+00C4)
* nThIisinh
* onequarter (U+00BC)
* uni0DF3 (U+0DF3)
* thsinh
* tThIsinh
* tmKSSI
* uni00B5 (U+00B5)
* tmVU
* nyjsinh
* rsinh
* nyUsinh
* gUsinh
* uni0DB5 (U+0DB5)
* uni0D92 (U+0D92)
* six (U+0036)
* nacute (U+0144)
* jnyRasinh
* uring (U+016F)
* Ecaron (U+011A)
* nngUsinh
* product (U+220F)
* acircumflex (U+00E2)
* uni2206 (U+2206)
* udieresis (U+00FC)
* nyCIisinh
* bsinh
* tmYU
* tmSU
* uni0DB9 (U+0DB9)
* ttTthIsinh
* dVsinh
* dUsinh
* ncaron (U+0148)
* uacute (U+00FA)
* dcaron (U+010F)
* t (U+0074)
* b (U+0062)
* tmLLLU
* Aacute (U+00C1)
* uni021A (U+021A)
* tmNNI
* tmKSSII
* Q (U+0051)
* kSsasinh
* jhIsinh
* n (U+006E)
* ttsinh
* uni2113 (U+2113)
* Oslash (U+00D8)
* khIisinh
* Ydieresis (U+0178)
* Egrave (U+00C8)
* three (U+0033)
* egrave (U+00E8)
* shUsinh
* uni0BEE (U+0BEE)
* tmNYI
* uni0123 (U+0123)
* oslash (U+00F8)
* aring (U+00E5)
* ddIisinh
* Lacute (U+0139)
* tmTII
* uni0BE9 (U+0BE9)
* uni0BC0 (U+0BC0)
* nyRasinh
* tmVI
* tmLLI
* ngIsinh
* uni0B87 (U+0B87)
* dIisinh
* uni0BB8 (U+0BB8)
* tmSHU
* uni0DA2 (U+0DA2)
* nDhasinh
* uni0DB7 (U+0DB7)
* P (U+0050)
* tmNI
* uni0DDB (U+0DDB)
* g (U+0067)
* uni0BF9 (U+0BF9)
* tmSHII
* Uogonek (U+0172)
* tmLLLUU
* msinh
* llUsinh
* gbreve (U+011F)
* uni0BF3 (U+0BF3)
* tmNNUU
* nVIsinh
* nDUsinh
* tmRRU
* uni0BA3 (U+0BA3)
* mbIisinh
* tmYI
* Ecircumflex (U+00CA)
* tmTUU
* f (U+0066)
* uni0D9F (U+0D9F)
* tmLLAI.traditional
* tmJUU
* Aogonek (U+0104)
* kVsinh
* plusminus (U+00B1)
* tmNNNI
* e (U+0065)
* uni0BE7 (U+0BE7)
* tcaron (U+0165)
* tmHU
* tmLLII
* tmmAI.traditional
* Dcroat (U+0110)
* rIsinh
* nngUusinh
* uni0DA5 (U+0DA5)
* nine (U+0039)
* tmKI
* uni0BA9 (U+0BA9)
* uni0B9A (U+0B9A)
* ucircumflex (U+00FB)
* tmHUU
* uni0BC1 (U+0BC1)
* Abreve (U+0102)
* uni0B86 (U+0B86)
* uni0DBB (U+0DBB)
* tmJI
* tmLLLI
* tmNNU
* uni0DD9 (U+0DD9)
* uni0D9B (U+0D9B)
* kVasinh
* k (U+006B)
* uni0DBD (U+0DBD)
* uni0BF5 (U+0BF5)
* uni0D9C (U+0D9C)
* Tcaron (U+0164)
* nVsinh
* hUsinh
* chsinh
* tVIisinh
* uni0BB5 (U+0BB5)
* uogonek (U+0173)
* ddsinh
* dDhIsinh
* uni0DB1 (U+0DB1)
* greaterequal (U+2265)
* tmNYII
* uni0D9A (U+0D9A)
* AE (U+00C6)
* chIsinh
* nyCasinh
* uni0D88 (U+0D88)
* phIsinh
* eacute (U+00E9)
* ttIisinh
* dVIsinh
* kUsinh
* nyUusinh
* sterling (U+00A3)
* khIsinh
* tmNYU
* uni0B8E (U+0B8E)
* bracketright (U+005D)
* tmKSSUU
* section (U+00A7)
* Y (U+0059)
* uni0B8A (U+0B8A)
* nnddsinh
* tmKU
* tmKII
* tmLU
* tmSSU
* uni0BCC (U+0BCC)
* uni0DDA (U+0DDA)
* tVasinh
* tmMI
* tmTTI
* tmHA.alt
* uni0BAE (U+0BAE)
* tmTU
* mIisinh
* hUusinh
* uni0D9D (U+0D9D)
* jIisinh
* nDUusinh
* amacron (U+0101)
* L (U+004C)
* ttTthasinh
* Acircumflex (U+00C2)
* iogonek (U+012F)
* uni0B85 (U+0B85)
* mbsinh
* uni0D86 (U+0D86)
* gDhsinh
* dUusinh
* F (U+0046)
* florin (U+0192)
* uni20BD
* nnddIisinh
* nyCsinh
* tmKSSU
* uni0B93 (U+0B93)
* tmSHI
* nThsinh
* kUusinh
* B (U+0042)
* nnIisinh
* uni0BC7 (U+0BC7)
* uni0D89 (U+0D89)
* tmTTII
* tmLLU
* H (U+0048)
* partialdiff (U+2202)
* bracketleft (U+005B)
* dVIisinh
* Emacron (U+0112)
* d (U+0064)
* uni0D91 (U+0D91)
* khsinh
* thIisinh
* ntilde (U+00F1)
* tmPU
* tmSSUU
* ordfeminine (U+00AA)
* fl (U+FB02)
* five (U+0035)
* uni0D85 (U+0D85)
* tmRUU
* uni0DA6 (U+0DA6)
* gDhasinh
* uni0DDF (U+0DDF)
* ecircumflex (U+00EA)
* notequal (U+2260)
* uni0163 (U+0163)
* tmSUU
* uni0DD3 (U+0DD3)
* ndUsinh
* uni0D93 (U+0D93)
* tmMUU
* uni0BD0 (U+0BD0)
* uni0B95 (U+0B95)
* ampersand (U+0026)
* D (U+0044)
* uni0DAF (U+0DAF)
* Aring (U+00C5)
* tmPII
* uni0BF4 (U+0BF4)
* rephasinh
* rAesinh
* tmSII
* nnddIsinh
* phRasinh
* atilde (U+00E3)
* tmKSSA.alt
* uni0BEC (U+0BEC) [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph (outline_direction)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have a counter-clockwise outer contour:

* uni0D8A (U+0D8A) has a counter-clockwise outer contour
* uni0D8A (U+0D8A) has a counter-clockwise outer contour
* uni0D8A (U+0D8A) has a counter-clockwise outer contour
* uni0D8B (U+0D8B) has a counter-clockwise outer contour
* uni0D8C (U+0D8C) has a counter-clockwise outer contour
* uni0D8C (U+0D8C) has a counter-clockwise outer contour
* uni0D8C (U+0D8C) has a counter-clockwise outer contour
* uni0D8D (U+0D8D) has a counter-clockwise outer contour
* uni0D8E (U+0D8E) has a counter-clockwise outer contour
* uni0D8E (U+0D8E) has a counter-clockwise outer contour
* uni0D90 (U+0D90) has a counter-clockwise outer contour
* uni0D90 (U+0D90) has a counter-clockwise outer contour
* uni0D96 (U+0D96) has a counter-clockwise outer contour
* uni0D96 (U+0D96) has a counter-clockwise outer contour
* uni0DD2 (U+0DD2) has a counter-clockwise outer contour
* uni0DD4 (U+0DD4) has a counter-clockwise outer contour
* uni0DD6 (U+0DD6) has a counter-clockwise outer contour
* uni0DD8 (U+0DD8) has a counter-clockwise outer contour
* uni0DF2 (U+0DF2) has a counter-clockwise outer contour
* uni0DF2 (U+0DF2) has a counter-clockwise outer contour
* uni0DDF (U+0DDF) has a counter-clockwise outer contour
* uni0DDF (U+0DDF) has a counter-clockwise outer contour
* uni0DF3 (U+0DF3) has a counter-clockwise outer contour
* uni0DF3 (U+0DF3) has a counter-clockwise outer contour
* uni0DDE (U+0DDE) has a counter-clockwise outer contour
* uni0DDE (U+0DDE) has a counter-clockwise outer contour
* ngIisinh has a counter-clockwise outer contour
* Abreve (U+0102) has a counter-clockwise outer contour
* Acircumflex (U+00C2) has a counter-clockwise outer contour
* C (U+0043) has a counter-clockwise outer contour
* Cacute (U+0106) has a counter-clockwise outer contour
* Ccaron (U+010C) has a counter-clockwise outer contour
* Ccaron (U+010C) has a counter-clockwise outer contour
* Ccedilla (U+00C7) has a counter-clockwise outer contour
* Dcaron (U+010E) has a counter-clockwise outer contour
* Ecaron (U+011A) has a counter-clockwise outer contour
* Ecircumflex (U+00CA) has a counter-clockwise outer contour
* G (U+0047) has a counter-clockwise outer contour
* Gbreve (U+011E) has a counter-clockwise outer contour
* Gbreve (U+011E) has a counter-clockwise outer contour
* uni0122 (U+0122) has a counter-clockwise outer contour
* Icircumflex (U+00CE) has a counter-clockwise outer contour
* L (U+004C) has a counter-clockwise outer contour
* L (U+004C) has a counter-clockwise outer contour
* Lacute (U+0139) has a counter-clockwise outer contour
* Lacute (U+0139) has a counter-clockwise outer contour
* Lcaron (U+013D) has a counter-clockwise outer contour
* Lcaron (U+013D) has a counter-clockwise outer contour
* Lslash (U+0141) has a counter-clockwise outer contour
* Lslash (U+0141) has a counter-clockwise outer contour
* Lslash (U+0141) has a counter-clockwise outer contour
* Ncaron (U+0147) has a counter-clockwise outer contour
* Ocircumflex (U+00D4) has a counter-clockwise outer contour
* Rcaron (U+0158) has a counter-clockwise outer contour
* Scaron (U+0160) has a counter-clockwise outer contour
* Tcaron (U+0164) has a counter-clockwise outer contour
* Ucircumflex (U+00DB) has a counter-clockwise outer contour
* W (U+0057) has a counter-clockwise outer contour
* X (U+0058) has a counter-clockwise outer contour
* Y (U+0059) has a counter-clockwise outer contour
* Y (U+0059) has a counter-clockwise outer contour
* Yacute (U+00DD) has a counter-clockwise outer contour
* Yacute (U+00DD) has a counter-clockwise outer contour
* Ydieresis (U+0178) has a counter-clockwise outer contour
* Ydieresis (U+0178) has a counter-clockwise outer contour
* Zcaron (U+017D) has a counter-clockwise outer contour
* abreve (U+0103) has a counter-clockwise outer contour
* acircumflex (U+00E2) has a counter-clockwise outer contour
* ccaron (U+010D) has a counter-clockwise outer contour
* eth (U+00F0) has a counter-clockwise outer contour
* ecaron (U+011B) has a counter-clockwise outer contour
* ecircumflex (U+00EA) has a counter-clockwise outer contour
* f (U+0066) has a counter-clockwise outer contour
* f (U+0066) has a counter-clockwise outer contour
* gbreve (U+011F) has a counter-clockwise outer contour
* icircumflex (U+00EE) has a counter-clockwise outer contour
* ncaron (U+0148) has a counter-clockwise outer contour
* ocircumflex (U+00F4) has a counter-clockwise outer contour
* rcaron (U+0159) has a counter-clockwise outer contour
* scaron (U+0161) has a counter-clockwise outer contour
* germandbls (U+00DF) has a counter-clockwise outer contour
* ucircumflex (U+00FB) has a counter-clockwise outer contour
* v (U+0076) has a counter-clockwise outer contour
* w (U+0077) has a counter-clockwise outer contour
* x (U+0078) has a counter-clockwise outer contour
* y (U+0079) has a counter-clockwise outer contour
* yacute (U+00FD) has a counter-clockwise outer contour
* ydieresis (U+00FF) has a counter-clockwise outer contour
* zcaron (U+017E) has a counter-clockwise outer contour
* f_f (U+FB00) has a counter-clockwise outer contour
* f_f (U+FB00) has a counter-clockwise outer contour
* f_f (U+FB00) has a counter-clockwise outer contour
* f_f (U+FB00) has a counter-clockwise outer contour
* three (U+0033) has a counter-clockwise outer contour
* four (U+0034) has a counter-clockwise outer contour
* four (U+0034) has a counter-clockwise outer contour
* four (U+0034) has a counter-clockwise outer contour
* five (U+0035) has a counter-clockwise outer contour
* five (U+0035) has a counter-clockwise outer contour
* five (U+0035) has a counter-clockwise outer contour
* six (U+0036) has a counter-clockwise outer contour
* seven (U+0037) has a counter-clockwise outer contour
* seven (U+0037) has a counter-clockwise outer contour
* nine (U+0039) has a counter-clockwise outer contour
* threequarters (U+00BE) has a counter-clockwise outer contour
* threequarters (U+00BE) has a counter-clockwise outer contour
* threequarters (U+00BE) has a counter-clockwise outer contour
* threequarters (U+00BE) has a counter-clockwise outer contour
* uni00B3 (U+00B3) has a counter-clockwise outer contour
* backslash (U+005C) has a counter-clockwise outer contour
* parenleft (U+0028) has a counter-clockwise outer contour
* bracketright (U+005D) has a counter-clockwise outer contour
* bracketright (U+005D) has a counter-clockwise outer contour
* bracketright (U+005D) has a counter-clockwise outer contour
* exclamdown (U+00A1) has a counter-clockwise outer contour
* exclamdown (U+00A1) has a counter-clockwise outer contour
* guillemotleft (U+00AB) has a counter-clockwise outer contour
* guillemotleft (U+00AB) has a counter-clockwise outer contour
* guillemotleft (U+00AB) has a counter-clockwise outer contour
* guillemotleft (U+00AB) has a counter-clockwise outer contour
* guilsinglleft (U+2039) has a counter-clockwise outer contour
* guilsinglleft (U+2039) has a counter-clockwise outer contour
* florin (U+0192) has a counter-clockwise outer contour
* at (U+0040) has a counter-clockwise outer contour
* uni2113 (U+2113) has a counter-clockwise outer contour
* estimated (U+212E) has a counter-clockwise outer contour
* Euro (U+20AC) has a counter-clockwise outer contour
* Euro (U+20AC) has a counter-clockwise outer contour
* Euro (U+20AC) has a counter-clockwise outer contour
* sterling (U+00A3) has a counter-clockwise outer contour
* yen (U+00A5) has a counter-clockwise outer contour
* yen (U+00A5) has a counter-clockwise outer contour
* yen (U+00A5) has a counter-clockwise outer contour
* integral (U+222B) has a counter-clockwise outer contour
* partialdiff (U+2202) has a counter-clockwise outer contour
* lozenge (U+25CA) has a counter-clockwise outer contour
* lozenge (U+25CA) has a counter-clockwise outer contour
* usignsinh.01 has a counter-clockwise outer contour
* usignsinh.02 has a counter-clockwise outer contour
* usignsinh.03 has a counter-clockwise outer contour
* uusignsinh.01 has a counter-clockwise outer contour
* uusignsinh.02 has a counter-clockwise outer contour
* uusignsinh.03 has a counter-clockwise outer contour
* circumflex (U+02C6) has a counter-clockwise outer contour
* caron (U+02C7) has a counter-clockwise outer contour
* breve (U+02D8) has a counter-clockwise outer contour
* mooniak has a counter-clockwise outer contour
* mooniak has a counter-clockwise outer contour [code: ccw-outer-contour]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* K (U+004B): Line(Line { p0: (239.0, 332.0), p1: (160.0, 332.0) }) has the same coordinates as a previous segment.
* uni0136 (U+0136): Line(Line { p0: (239.0, 332.0), p1: (160.0, 332.0) }) has the same coordinates as a previous segment.
* k (U+006B): Line(Line { p0: (152.0, 266.0), p1: (226.0, 266.0) }) has the same coordinates as a previous segment.
* uni0137 (U+0137): Line(Line { p0: (226.0, 266.0), p1: (152.0, 266.0) }) has the same coordinates as a previous segment.
* guillemotleft (U+00AB): Line(Line { p0: (100.0, 253.0), p1: (27.0, 253.0) }) has the same coordinates as a previous segment.
* guillemotleft (U+00AB): Line(Line { p0: (277.0, 253.0), p1: (204.0, 253.0) }) has the same coordinates as a previous segment.
* guillemotright (U+00BB): Line(Line { p0: (350.0, 253.0), p1: (423.0, 253.0) }) has the same coordinates as a previous segment.
* guillemotright (U+00BB): Line(Line { p0: (173.0, 253.0), p1: (246.0, 253.0) }) has the same coordinates as a previous segment.
* guilsinglleft (U+2039): Line(Line { p0: (103.0, 253.0), p1: (30.0, 253.0) }) has the same coordinates as a previous segment.
* guilsinglright (U+203A): Line(Line { p0: (177.0, 253.0), p1: (250.0, 253.0) }) has the same coordinates as a previous segment.
* lozenge (U+25CA): Line(Line { p0: (58.0, 337.0), p1: (130.0, 337.0) }) has the same coordinates as a previous segment.
* lozenge (U+25CA): Line(Line { p0: (423.0, 337.0), p1: (495.0, 337.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Description strings in the name table must not exceed 200 characters. (googlefonts/name/description_max_length)</summary>
    <div>








- ⚠️ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'MNIK' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>






### Summary

| 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 12 | 97 | 16 | 109 | 65 | 
| 4% | 32% | 5% | 36% | 22% | 



