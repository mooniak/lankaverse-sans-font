## FontSpector report

fontspector version: 1.9.0






## Check results




<details><summary>[21] fonts/variable/LankaverseSansCANARY[wght].ttf</summary>
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
    <summary>🔥 <b>FAIL</b> Ensure font doesn't have Mac name table entries (platform=1). (no_mac_entries)</summary>
    <div>








- 🔥 **FAIL** Please remove name ID FAMILY_NAME [code: mac-names]
  
  


- 🔥 **FAIL** Please remove name ID FULL_NAME [code: mac-names]
  
  


- 🔥 **FAIL** Please remove name ID VERSION_STRING [code: mac-names]
  
  


- 🔥 **FAIL** Please remove name ID POSTSCRIPT_NAME [code: mac-names]
  
  


- 🔥 **FAIL** Please remove name ID DESCRIPTION [code: mac-names]
  
  


- 🔥 **FAIL** Please remove name ID TYPOGRAPHIC_FAMILY_NAME [code: mac-names]
  
  


- 🔥 **FAIL** Please remove name ID VARIATIONS_POSTSCRIPT_NAME_PREFIX [code: mac-names]
  
  


- 🔥 **FAIL** Please remove name ID NameId 261 [code: mac-names]
  
  


- 🔥 **FAIL** Please remove name ID NameId 263 [code: mac-names]
  
  


- 🔥 **FAIL** Please remove name ID NameId 265 [code: mac-names]
  
  


- 🔥 **FAIL** Please remove name ID NameId 267 [code: mac-names]
  
  


- 🔥 **FAIL** Please remove name ID NameId 269 [code: mac-names]
  
  


- 🔥 **FAIL** Please remove name ID NameId 271 [code: mac-names]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. (os2_metrics_match_hhea)</summary>
    <div>








- 🔥 **FAIL** OS/2 sTypoAscender (979) and hhea ascent (1006) must be equal. [code: ascender]
  
  


- 🔥 **FAIL** OS/2 sTypoLineGap (27) and hhea lineGap (0) must be equal. [code: lineGap]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (googlefonts/use_typo_metrics)</summary>
    <div>








- 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) was NOT set. [code: missing-os2-fsselection-bit7]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema (googlefonts/vertical_metrics)</summary>
    <div>








- 🔥 **FAIL** OS/2.sTypoLineGap is 27; it should be 0 [code: bad-OS/2.sTypoLineGap]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- 🔥 **FAIL** No dotted circle glyph present and font uses a complex shaper [code: missing-dotted-circle-complex]
  
  

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
    <summary>⚠️ <b>WARN</b> Checking Vertical Metric linegaps. (linegaps)</summary>
    <div>








- ⚠️ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 529 among a set of 13  math glyphs.
The following math glyphs have a different width, though:
width=524: lessequal, greaterequal
width=468: multiply
width=608: approxequal
width=520: logicalnot
width=496: less, greater [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font appears to be an Indic font but is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. (Overriden: Sinhala fonts: U+20B9 is optional (Sri Lanka writes රු / Rs)) [code: missing-rupee]
  
  

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
* D (U+0044)
* tmKSSII
* kVsinh
* aacute (U+00E1)
* uni0D86 (U+0D86)
* uni0DB5 (U+0DB5)
* uni2126 (U+2126)
* nDhIisinh
* ttTthIsinh
* Edotaccent (U+0116)
* Lcaron (U+013D)
* uni0DAC (U+0DAC)
* tUsinh
* tmYU
* ttTthasinh
* B (U+0042)
* ddsinh
* nVasinh
* llUusinh
* thsinh
* uacute (U+00FA)
* uni0BF7 (U+0BF7)
* R (U+0052)
* uni0BB8 (U+0BB8)
* cent (U+00A2)
* uni0156 (U+0156)
* thIsinh
* tmHA.alt
* bhUsinh
* h (U+0068)
* nUsinh
* Agrave (U+00C0)
* uni0BB3 (U+0BB3)
* uni0BF2 (U+0BF2)
* dIsinh
* Aacute (U+00C1)
* tmSHUU
* uni0D91 (U+0D91)
* tmVUU
* uni0BF4 (U+0BF4)
* gUusinh
* eight (U+0038)
* at (U+0040)
* agrave (U+00E0)
* tmNYU
* tmVII
* uni0D9C (U+0D9C)
* Eogonek (U+0118)
* tmNNNAI.traditional
* tmTTI
* Uogonek (U+0172)
* uni0BCC (U+0BCC)
* L (U+004C)
* Gbreve (U+011E)
* tmNNII
* tmTTII
* nnIisinh
* tmVI
* florin (U+0192)
* tmNYI
* uni0146 (U+0146)
* egrave (U+00E8)
* racute (U+0155)
* tmRRI
* pi (U+03C0)
* uni0BED (U+0BED)
* ampersand (U+0026)
* uni2113 (U+2113)
* nThasinh
* asciicircum (U+005E)
* tmNNUU
* tmLLLII
* uni0BF6 (U+0BF6)
* csinh
* ngIisinh
* Ydieresis (U+0178)
* gDhIisinh
* uni0DAA (U+0DAA)
* tmNGI
* tmLLI
* OE (U+0152)
* lUsinh
* tmMII
* uni0B94 (U+0B94)
* tthIisinh
* uni0D88 (U+0D88)
* tmNNAA.traditional
* uni0D89 (U+0D89)
* uni0BE7 (U+0BE7)
* kVIisinh
* uhungarumlaut (U+0171)
* nUusinh
* abreve (U+0103)
* uni0BC1 (U+0BC1)
* shUsinh
* uni0BCA (U+0BCA)
* rsinh
* Eth (U+00D0)
* uni0D8A (U+0D8A)
* tmLII
* gbreve (U+011F)
* uni0DB1 (U+0DB1)
* ttsinh
* rIsinh
* tmSSUU
* nDhasinh
* uni0D9F (U+0D9F)
* rephasinh
* tVsinh
* uni0B8E (U+0B8E)
* tmRII.alt
* ttTthsinh
* Q (U+0051)
* tmPI
* uni0DBB (U+0DBB)
* daggerdbl (U+2021)
* phIsinh
* tmMI
* uni0DA2 (U+0DA2)
* uni0DDA (U+0DDA)
* gDhIsinh
* Acircumflex (U+00C2)
* tmNGII
* gDhasinh
* uni0BA3 (U+0BA3)
* uni0DAB (U+0DAB)
* tmYII
* uni0DB6 (U+0DB6)
* section (U+00A7)
* uni0DDD (U+0DDD)
* acircumflex (U+00E2)
* g (U+0067)
* A (U+0041)
* ecaron (U+011B)
* chIisinh
* tmKSSA
* uni0DB7 (U+0DB7)
* ncaron (U+0148)
* uni0BB5 (U+0BB5)
* uni0BC7 (U+0BC7)
* uni0DD9 (U+0DD9)
* uni20BD
* jhIsinh
* oe (U+0153)
* oslash (U+00F8)
* cIisinh
* uni0D9A (U+0D9A)
* b (U+0062)
* tmLLLI
* jnyRasinh
* uni0DDE (U+0DDE)
* nDRasinh
* uni0B9A (U+0B9A)
* uni0BF3 (U+0BF3)
* uni0DC2 (U+0DC2)
* tmNNNII
* kUusinh
* dDhasinh
* mbsinh
* registered (U+00AE)
* tmNNI
* nnddIsinh
* tmRUU
* kVIsinh
* hUsinh
* uni0D8D (U+0D8D)
* Emacron (U+0112)
* dcroat (U+0111)
* tthsinh
* khsinh
* nnIsinh
* dUsinh
* eogonek (U+0119)
* ucircumflex (U+00FB)
* uni0BF1 (U+0BF1)
* rUusinh
* Eacute (U+00C9)
* e (U+0065)
* tmHU
* ddhsinh
* tmLLII
* jIisinh
* Ecircumflex (U+00CA)
* f_f_i (U+FB03)
* m (U+006D)
* uni0DD8 (U+0DD8)
* multiply (U+00D7)
* r (U+0072)
* uni0BD0 (U+0BD0)
* Egrave (U+00C8)
* bracketright (U+005D)
* tmSHI
* tmRRU
* nnddIisinh
* uni0BC0 (U+0BC0)
* tmSU
* ttTthIisinh
* Dcaron (U+010E)
* tmPII
* tmSUU
* tmNNNUU
* uni0D93 (U+0D93)
* tmHI
* uni0D85 (U+0D85)
* aring (U+00E5)
* numbersign (U+0023)
* uni0B99 (U+0B99)
* tmSI
* tmNYUU
* onequarter (U+00BC)
* ngsinh
* nnddsinh
* Ecaron (U+011A)
* eacute (U+00E9)
* mIisinh
* Aring (U+00C5)
* q (U+0071)
* umacron (U+016B)
* uni0122 (U+0122)
* bIsinh
* tmLLLU
* tmLLLUU
* notequal (U+2260)
* uni0BEB (U+0BEB)
* tmLUU
* udieresis (U+00FC)
* uni0D9E (U+0D9E)
* rAaesinh
* amacron (U+0101)
* uni0BB6 (U+0BB6)
* uni0D8E (U+0D8E)
* uni0D9B (U+0D9B)
* tmRII
* nyUusinh
* rUsinh
* tmLLAI.traditional
* p (U+0070)
* dVasinh
* tmYI
* yen (U+00A5)
* tmNNU
* uni0DB8 (U+0DB8)
* dVIisinh
* mbIsinh
* Racute (U+0154)
* hUusinh
* bracketleft (U+005B)
* tmPUU
* tmRI.alt
* Dcroat (U+0110)
* tmSII
* ntilde (U+00F1)
* Lslash (U+0141)
* phsinh
* tmLLUU
* jnyUusinh
* tmPU
* dagger (U+2020)
* uni0BB9 (U+0BB9)
* uni0DA5 (U+0DA5)
* tmSSI
* uni0B9E (U+0B9E)
* tmSSII
* nVsinh
* Tcaron (U+0164)
* ddhIsinh
* Yacute (U+00DD)
* tmTTUU
* H (U+0048)
* iogonek (U+012F)
* d (U+0064)
* plusminus (U+00B1)
* edieresis (U+00EB)
* edotaccent (U+0117)
* uni0BEE (U+0BEE)
* greaterequal (U+2265)
* Atilde (U+00C3)
* uni0DA8 (U+0DA8)
* tthIsinh
* lslash (U+0142)
* uni0DD3 (U+0DD3)
* uni0BCB (U+0BCB)
* vsinh
* P (U+0050)
* tmKI
* tmJU
* uni0B85 (U+0B85)
* tmKU
* T (U+0054)
* f (U+0066)
* ddhIisinh
* nyCasinh
* tmTI
* msinh
* tmKSSA.alt
* tmLAI.traditional
* uni0D95 (U+0D95)
* snYAc2
* tmNNNI
* vIisinh
* tmNNNAA.traditional
* jhIisinh
* uni013B (U+013B)
* uni0137 (U+0137)
* tmNYII
* dVIsinh
* tThIisinh
* dDhsinh
* ugrave (U+00F9)
* thorn (U+00FE)
* tmMUU
* uni0BAE (U+0BAE)
* tmSHII
* phRasinh
* n (U+006E)
* two (U+0032)
* uni0D94 (U+0D94)
* uni0BE9 (U+0BE9)
* tmCU
* E (U+0045)
* uni0BF9 (U+0BF9)
* dhsinh
* bhUusinh
* tmHUU
* tmRRUU
* tmSHU
* tVIisinh
* nThIisinh
* tmSHRII
* tVasinh
* nVIsinh
* kUsinh
* nDUsinh
* uring (U+016F)
* nDUusinh
* tmNGUU
* rAesinh
* nyCIsinh
* nThsinh
* tmKUU
* tmTU
* tmMU
* uni0157 (U+0157)
* uni0D92 (U+0D92)
* nDhIsinh
* phIisinh
* nVIisinh
* jIsinh
* uni0D8F (U+0D8F)
* Euro (U+20AC)
* nyjsinh
* ndRasinh
* uni0B86 (U+0B86)
* uni0BF8 (U+0BF8)
* jsinh
* tVIsinh
* Adieresis (U+00C4)
* uni0DF3 (U+0DF3)
* nThIsinh
* uni0B92 (U+0B92)
* uni0B8F (U+0B8F)
* u (U+0075)
* dollar (U+0024)
* nyCIisinh
* fl (U+FB02)
* Y (U+0059)
* k (U+006B)
* tmTII
* gDhsinh
* sterling (U+00A3)
* uni0BA9 (U+0BA9)
* uni0DAD (U+0DAD)
* tThasinh
* tmNII
* Lacute (U+0139)
* dcaron (U+010F)
* tmNGU
* emacron (U+0113)
* dUusinh
* G (U+0047)
* tmCI
* tmmAI.traditional
* kVasinh
* dhIisinh
* three (U+0033)
* tThIsinh
* tmNNNU
* nine (U+0039)
* uni0D87 (U+0D87)
* uni0D96 (U+0D96)
* a (U+0061)
* lessequal (U+2264)
* tmNU
* uni0DAF (U+0DAF)
* mIsinh
* uni021B (U+021B)
* dVsinh
* uni0DC1 (U+0DC1)
* dRasinh
* uni0DC5 (U+0DC5)
* Aogonek (U+0104)
* AE (U+00C6)
* uni0DA4 (U+0DA4)
* uni0DF2 (U+0DF2)
* uni0BB2 (U+0BB2)
* Edieresis (U+00CB)
* adieresis (U+00E4)
* ngIsinh
* uni2206 (U+2206)
* uni0123 (U+0123)
* threequarters (U+00BE)
* tmKSSI
* uni0BA4 (U+0BA4)
* tmKSSUU
* jhsinh
* ordfeminine (U+00AA)
* tmCII
* Rcaron (U+0158)
* Oslash (U+00D8)
* Abreve (U+0102)
* nyUsinh
* uogonek (U+0173)
* uni0BAF (U+0BAF)
* uni0BD7 (U+0BD7)
* dIisinh
* uni0B95 (U+0B95)
* dDhIisinh
* uni0162 (U+0162)
* ddIisinh
* thIisinh
* f_f (U+FB00)
* uni0BEF (U+0BEF)
* tmCUU
* tmLLU
* f_f_l (U+FB04)
* atilde (U+00E3)
* tmKII
* uni0BF5 (U+0BF5)
* plus (U+002B)
* tmNUU
* ndUusinh
* tmNI
* nyRasinh
* llUsinh
* tmTUU
* aogonek (U+0105)
* uni0DA3 (U+0DA3)
* product (U+220F)
* ndUsinh
* nngUusinh
* tmHII
* uni0D8C (U+0D8C)
* mbIisinh
* uni0BB4 (U+0BB4)
* nDasinh
* dDhIsinh
* partialdiff (U+2202)
* fi (U+FB01)
* Thorn (U+00DE)
* uni0163 (U+0163)
* nngUsinh
* uni0B93 (U+0B93)
* uni0BC6 (U+0BC6)
* tmKSSU
* tmNNAI.traditional
* rIisinh
* t (U+0074)
* rcaron (U+0159)
* nyjIsinh
* uni0DDC (U+0DDC)
* uni0D9D (U+0D9D)
* uni0DCA (U+0DCA)
* uni0BEC (U+0BEC)
* eth (U+00F0)
* uni0DDB (U+0DDB)
* shUusinh
* five (U+0035)
* uni0DB3 (U+0DB3)
* Amacron (U+0100)
* turkishlira
* uni0BC2 (U+0BC2)
* tmRI
* uni021A (U+021A)
* uni0BC8 (U+0BC8)
* tUusinh
* uni0DDF (U+0DDF)
* bsinh
* uni0DA1 (U+0DA1)
* uni0DBD (U+0DBD)
* uni0B87 (U+0B87)
* chIsinh
* asterisk (U+002A)
* uni0D90 (U+0D90)
* tmJUU
* tmJII
* nDhsinh
* kSsasinh
* tmLU
* tmSSU
* tThsinh
* uni0BEA (U+0BEA)
* ecircumflex (U+00EA)
* tcaron (U+0165)
* tmJI
* four (U+0034)
* lUusinh
* uni0BB7 (U+0BB7)
* uni00B5 (U+00B5)
* uni0DA6 (U+0DA6)
* jnyUsinh
* tmYUU
* Iogonek (U+012E)
* ttIisinh
* khIsinh
* khIisinh
* uni0DAE (U+0DAE)
* gUsinh
* chsinh
* nacute (U+0144)
* tmVU
* six (U+0036)
* llRasinh
* tmRRII
* nyCsinh
* uni0B8A (U+0B8A)
* uni0DC4 (U+0DC4)
* uni0DB9 (U+0DB9)
* F (U+0046)
* bIisinh
* nyjIisinh [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

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

* K (U+004B): Line(Line { p0: (232.0, 323.0), p1: (156.0, 323.0) }) has the same coordinates as a previous segment.
* uni0136 (U+0136): Line(Line { p0: (232.0, 323.0), p1: (156.0, 323.0) }) has the same coordinates as a previous segment.
* k (U+006B): Line(Line { p0: (148.0, 259.0), p1: (220.0, 259.0) }) has the same coordinates as a previous segment.
* uni0137 (U+0137): Line(Line { p0: (220.0, 259.0), p1: (148.0, 259.0) }) has the same coordinates as a previous segment.
* guillemotleft (U+00AB): Line(Line { p0: (97.0, 246.0), p1: (26.0, 246.0) }) has the same coordinates as a previous segment.
* guillemotleft (U+00AB): Line(Line { p0: (269.0, 246.0), p1: (198.0, 246.0) }) has the same coordinates as a previous segment.
* guillemotright (U+00BB): Line(Line { p0: (340.0, 246.0), p1: (411.0, 246.0) }) has the same coordinates as a previous segment.
* guillemotright (U+00BB): Line(Line { p0: (168.0, 246.0), p1: (239.0, 246.0) }) has the same coordinates as a previous segment.
* guilsinglleft (U+2039): Line(Line { p0: (100.0, 246.0), p1: (29.0, 246.0) }) has the same coordinates as a previous segment.
* guilsinglright (U+203A): Line(Line { p0: (172.0, 246.0), p1: (243.0, 246.0) }) has the same coordinates as a previous segment.
* lozenge (U+25CA): Line(Line { p0: (56.0, 328.0), p1: (126.0, 328.0) }) has the same coordinates as a previous segment.
* lozenge (U+25CA): Line(Line { p0: (411.0, 328.0), p1: (481.0, 328.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>


</div>
</details>


<details><summary>[1] fonts/variable</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent (family/win_ascent_and_descent)</summary>
    <div>








- 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 476, but got 194 instead. The lowest point is in glyph 'lUsinh' at wght=700. [code: descent]
  
  

</div>
</details>


</div>
</details>






### Summary

| 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 20 | 93 | 13 | 88 | 35 | 
| 8% | 37% | 5% | 35% | 14% | 



