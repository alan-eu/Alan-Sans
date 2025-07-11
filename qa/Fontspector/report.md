## FontSpector report

fontspector version: 1.1.0






## Check results




<details><summary>[3] </summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** Alan[wght].ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, canadian-aboriginal, coptic, tai-le, syriac, todhri, malayalam, duployan, hebrew, math, tifinagh
* U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
* U+030C COMBINING CARON: try adding one of: tai-le, cherokee
... and 11 others

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin [code: unreachable-subsetting]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Check for presence of an ARTICLE.en_us.html file (googlefonts/description/has_article)</summary>
    <div>








- ℹ️ **INFO** This font doesn't have an ARTICLE.en_us.html file. [code: missing-article]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Check axis ordering on the STAT table. (googlefonts/STAT/axis_order)</summary>
    <div>








- ℹ️ **INFO** None of the fonts lack a STAT table.

	And these are the most common STAT axis orderings:
	wght: 1 [code: summary]
  
  

</div>
</details>


</div>
</details>


<details><summary>[17] Alan[wght].ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:
* periodcentered.loclCAT
* periodcentered.loclCAT.case
* degree [code: no-contour]
  
  


- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     infered from the typical ammounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* .notdef (unencoded): found 1, expected one of: {4, 0, 3, 2, 5}
* uni1EBC (U+1EBC): found 5, expected one of: {2, 3}
* uni1E20 (U+1E20): found 3, expected one of: {2}
* OE (U+0152): found 6, expected one of: {4, 2, 5, 1, 3}
* uni1EF8 (U+1EF8): found 4, expected one of: {3, 2}
* uni013B.loclMAH (unencoded): found 3, expected one of: {2}
* ydieresis (U+00FF): found 5, expected one of: {3, 4}
* ygrave (U+1EF3): found 4, expected one of: {2, 3}
* uni1EF9 (U+1EF9): found 4, expected one of: {2, 3}
... and 17 others [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. (interpolation_issues)</summary>
    <div>








- ⚠️ **WARN** Glyph Ohungarumlaut has interpolation issues:
* Contour order mismatch: [0, 1, 2, 3] in default vs [0, 1, 3, 2] in wght=900 [code: glyph]
  
  


- ⚠️ **WARN** Glyph Uhungarumlaut has interpolation issues:
* Contour order mismatch: [0, 1, 2] in default vs [0, 2, 1] in wght=900 [code: glyph]
  
  


- ⚠️ **WARN** Glyph ohungarumlaut has interpolation issues:
* Contour order mismatch: [0, 1, 2, 3] in default vs [0, 1, 3, 2] in wght=900 [code: glyph]
  
  


- ⚠️ **WARN** Glyph uhungarumlaut has interpolation issues:
* Contour order mismatch: [0, 1, 2] in default vs [0, 2, 1] in wght=900 [code: glyph]
  
  


- ⚠️ **WARN** Glyph slash has interpolation issues:
* Contour 0 becomes underweight in wght=900 compared to default [code: glyph]
  
  


- ⚠️ **WARN** Glyph backslash has interpolation issues:
* Wrong start point: contour 0 should start at 4 in wght=900
* Contour 0 becomes underweight in wght=900 compared to default [code: glyph]
  
  


- ⚠️ **WARN** Glyph multiply has interpolation issues:
* Contour order mismatch: [0, 1] in default vs [1, 0] in wght=900 [code: glyph]
  
  


- ⚠️ **WARN** Glyph uni030B has interpolation issues:
* Contour order mismatch: [0, 1] in default vs [1, 0] in wght=900 [code: glyph]
  
  


- ⚠️ **WARN** Glyph uni030B.case has interpolation issues:
* Contour order mismatch: [0, 1] in default vs [1, 0] in wght=900 [code: glyph]
  
  


- ⚠️ **WARN** Glyph hungarumlaut has interpolation issues:
* Contour order mismatch: [0, 1] in default vs [1, 0] in wght=900 [code: glyph]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? (ligature_carets)</summary>
    <div>








- ⚠️ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure Stylistic Sets have description. (stylisticset_description)</summary>
    <div>








- ⚠️ **WARN** The stylistic set ss02 lacks a description string in the name table [code: missing-description]
  
  


- ⚠️ **WARN** The stylistic set ss03 lacks a description string in the name table [code: missing-description]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages                    |
|-------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                 | * en_Latn (English)          |
|   The following auxiliary characters are missing from the font: ʻ |                              |
| Auxiliary orthography codepoints:                                 | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
| Auxiliary orthography codepoints:                                 | * lt_Latn (Lithuanian)       |
|   Shaper didn't attach tildecomb to m when shaping the text 'm̃'   |                              |
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)          |
|   The following auxiliary characters are missing from the font: Ŀ |                              |
|   The following auxiliary characters are missing from the font: ŀ |                              |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: ſ | * fr_Latn (French)           |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ǥ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: Ʒ |                              |
|   The following auxiliary characters are missing from the font: Ǯ |                              |
|   The following auxiliary characters are missing from the font: ǥ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
|   The following auxiliary characters are missing from the font: ʒ |                              |
|   The following auxiliary characters are missing from the font: ǯ |                              | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following separator glyphs are missing:
* U+2028
* U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: * į̄
* į̃
* į̂
* į́
* į̌
* į̀The dot of soft dotted characters _should_ disappear in other cases, for example: * į̦̒
* į̦̄
* į̦̃
* į̦̂
* į̦́
* į̦̋
* į̦̊
* į̦̈
* į̦̆
... and 57 others [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* OE (U+0152): Line(Line { p0: (580.0, 0.0), p1: (580.0, 680.0) }) has the same coordinates as a previous segment.
* OE (U+0152): Line(Line { p0: (580.0, 680.0), p1: (644.0, 680.0) }) has the same coordinates as a previous segment.
* OE (U+0152): Line(Line { p0: (644.0, 680.0), p1: (644.0, 0.0) }) has the same coordinates as a previous segment.
* OE (U+0152): Line(Line { p0: (644.0, 0.0), p1: (580.0, 0.0) }) has the same coordinates as a previous segment.
* four (U+0034): Line(Line { p0: (386.0, 680.0), p1: (450.0, 680.0) }) has the same coordinates as a previous segment.
* four.osf: Line(Line { p0: (386.0, 560.0), p1: (450.0, 560.0) }) has the same coordinates as a previous segment.
* four.tf: Line(Line { p0: (386.0, 680.0), p1: (450.0, 680.0) }) has the same coordinates as a previous segment.
* dollar (U+0024): Line(Line { p0: (272.0, 350.0), p1: (326.0, 350.0) }) has the same coordinates as a previous segment.
* greater (U+003E): Line(Line { p0: (536.0, 274.0), p1: (536.0, 226.0) }) has the same coordinates as a previous segment.
... and 5 others [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'NONE' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Checking OS/2 fsSelection value. (opentype/xavgcharwidth)</summary>
    <div>








- ℹ️ **INFO** OS/2 xAvgCharWidth is 576 but it should be 575 which corresponds to the average of the widths of all glyphs in the font. These are similar values, which may be a symptom of the slightly different calculation of the xAvgCharWidth value in font editors. There's further discussion on this at https://github.com/fonttools/fontbakery/issues/1622 [code: xAvgCharWidth-close]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. (hinting_impact)</summary>
    <div>








- ℹ️ **INFO** Hinting filesize impact:

 |               | Alan[wght].ttf     |
 |:------------- | ---------------:|
 | Dehinted Size | 56836 |
 | Hinted Size   | 56860   |
 | Increase      | 24      |
 | Change        | 0.0 %  | [code: size-impact]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? (required_tables)</summary>
    <div>








- ℹ️ **INFO** This font contains the following optional tables:

    loca
    prep
    GPOS
    GSUB
    gasp [code: optional-tables]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table
set to optimize rendering? (googlefonts/gasp)</summary>
    <div>








- ℹ️ **INFO** These are the ppm ranges declared on the gasp table:

| PPM <= 65535 | - Use grid-fitting                                    |
|              | 	- Use grayscale rendering                            |
|              | 	- Use gridfitting with ClearType symmetric smoothing |
|              | 	- Use smoothing along multiple axes with ClearType®  |
|--------------|-------------------------------------------------------|
 [code: ranges]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? (googlefonts/old_ttfautohint)</summary>
    <div>








- ℹ️ **INFO** Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: Version 1.000 [code: version-not-detected]
  
  

</div>
</details>


</div>
</details>






### Summary

| ⚠️ WARN | ✅ PASS | ℹ️ INFO | 🔥 FAIL | ⏩ SKIP | 
| ---|---|---|---|---|
| 23 | 110 | 7 | 1 | 49 | 
| 13% | 61% | 4% | 1% | 27% | 



