## FontSpector report

fontspector version: 1.7.1






## Check results




<details><summary>[3] </summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** AlanSans[wght].ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, cherokee, coptic
* U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
* U+0307 COMBINING DOT ABOVE: try adding one of: math, malayalam, old-permic, tai-le, syriac, todhri, coptic, hebrew, canadian-aboriginal, duployan, tifinagh
* U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
... and 137 others

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


<details><summary>[13] AlanSans[wght].ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

* uni0328
* uni0335
* uni0337 [code: unattached-dotted-circle-marks]
  
  

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
* Zacute (U+0179): found 3, expected one of: [2, 4, 6]
* Zdotaccent (U+017B): found 3, expected one of: [2, 4, 6]
* uni013B.loclMAH (unencoded): found 3, expected one of: [2, 4, 8]
* yacute (U+00FD): found 4, expected one of: [2, 3, 6]
* ygrave (U+1EF3): found 4, expected one of: [2, 3, 6]
* uni1EF9 (U+1EF9): found 4, expected one of: [2, 3, 6]
* uni0635 (U+0635): found 1, expected one of: [2, 3]
* uni0635.init (unencoded): found 1, expected one of: [2]
* uni0636.init (unencoded): found 2, expected one of: [3, 5]
... and 14 others [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* uni06BA.bowl
* uni06F6.urdu
* threedotsdownabovear
* threedotsdowncenterar
* UAEDirhamSign [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                              | Languages                    |
|----------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                    | * lt_Latn (Lithuanian)       |
|   Shaper didn't attach tildecomb to m when shaping the text 'm̃'      |                              |
| Auxiliary orthography codepoints:                                    | * cs_Latn (Czech)            |
|   The following auxiliary characters are missing from the font: Ĕ    | * cy_Latn (Welsh)            |
|   The following auxiliary characters are missing from the font: Ĭ    | * es_Latn (Spanish)          |
|   The following auxiliary characters are missing from the font: Ŏ    | * hu_Latn (Hungarian)        |
|   The following auxiliary characters are missing from the font: ĕ    | * pt_Latn (Portuguese)       |
|   The following auxiliary characters are missing from the font: ĭ    | * sk_Latn (Slovak)           |
|   The following auxiliary characters are missing from the font: ŏ    | * tr_Latn (Turkish)          |
| Auxiliary orthography codepoints:                                    | * da_Latn (Danish)           |
|   The following auxiliary characters are missing from the font: Ǿ    |                              |
|   The following auxiliary characters are missing from the font: ǿ    |                              |
| Auxiliary orthography codepoints:                                    | * ar_Arab (Arabic)           |
|   The following auxiliary characters are missing from the font: ‌     |                              |
|   The following auxiliary characters are missing from the font: ‍     |                              |
|   The following auxiliary characters are missing from the font: ‏     |                              |
|   The following auxiliary characters are missing from the font: ڜ    |                              |
|   The following auxiliary characters are missing from the font: ڢ    |                              |
|   The following auxiliary characters are missing from the font: ڥ    |                              |
|   The following auxiliary characters are missing from the font: ڧ    |                              |
|   The following auxiliary characters are missing from the font: ڨ    |                              |
| Auxiliary orthography codepoints:                                    | * ca_Latn (Catalan)          |
|   The following auxiliary characters are missing from the font: Ĕ    |                              |
|   The following auxiliary characters are missing from the font: Ĭ    |                              |
|   The following auxiliary characters are missing from the font: Ŀ    |                              |
|   The following auxiliary characters are missing from the font: Ŏ    |                              |
|   The following auxiliary characters are missing from the font: ĕ    |                              |
|   The following auxiliary characters are missing from the font: ĭ    |                              |
|   The following auxiliary characters are missing from the font: ŀ    |                              |
|   The following auxiliary characters are missing from the font: ŏ    |                              |
| Auxiliary orthography codepoints:                                    | * en_Latn (English)          |
|   The following auxiliary characters are missing from the font: Ĕ    |                              |
|   The following auxiliary characters are missing from the font: Ĭ    |                              |
|   The following auxiliary characters are missing from the font: Ŏ    |                              |
|   The following auxiliary characters are missing from the font: ĕ    |                              |
|   The following auxiliary characters are missing from the font: ĭ    |                              |
|   The following auxiliary characters are missing from the font: ŏ    |                              |
|   The following auxiliary characters are missing from the font: ʻ    |                              |
| Auxiliary orthography codepoints:                                    | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ǎ    |                              |
|   The following auxiliary characters are missing from the font: Ŧ    |                              |
|   The following auxiliary characters are missing from the font: ǎ    |                              |
|   The following auxiliary characters are missing from the font: ŧ    |                              |
| Auxiliary orthography codepoints:                                    | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: Ĕ    |                              |
|   The following auxiliary characters are missing from the font: Ĭ    |                              |
|   The following auxiliary characters are missing from the font: Ŏ    |                              |
|   The following auxiliary characters are missing from the font: ĕ    |                              |
|   The following auxiliary characters are missing from the font: ĭ    |                              |
|   The following auxiliary characters are missing from the font: ŏ    |                              |
|   The following auxiliary characters are missing from the font: ſ    |                              |
| Auxiliary orthography codepoints:                                    | * fa_Arab (Persian)          |
|   The following auxiliary characters are missing from the font: ـ‌‍‏    |                              |
| Auxiliary orthography codepoints:                                    | * ur_Arab (Urdu)             |
|   The following auxiliary characters are missing from the font: ؀؁؂؃‌‍‏ |                              |
|   The following auxiliary characters are missing from the font: ٗ     |                              |
|   The following auxiliary characters are missing from the font: ٻ    |                              |
|   The following auxiliary characters are missing from the font: ٺ    |                              |
|   The following auxiliary characters are missing from the font: ټ    |                              |
|   The following auxiliary characters are missing from the font: ٽ    |                              |
| Auxiliary orthography codepoints:                                    | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ǧ    |                              |
|   The following auxiliary characters are missing from the font: Ǥ    |                              |
|   The following auxiliary characters are missing from the font: Ȟ    |                              |
|   The following auxiliary characters are missing from the font: Ǩ    |                              |
|   The following auxiliary characters are missing from the font: Ŧ    |                              |
|   The following auxiliary characters are missing from the font: Ʒ    |                              |
|   The following auxiliary characters are missing from the font: Ǯ    |                              |
|   The following auxiliary characters are missing from the font: ǧ    |                              |
|   The following auxiliary characters are missing from the font: ǥ    |                              |
|   The following auxiliary characters are missing from the font: ȟ    |                              |
|   The following auxiliary characters are missing from the font: ǩ    |                              |
|   The following auxiliary characters are missing from the font: ŧ    |                              |
|   The following auxiliary characters are missing from the font: ʒ    |                              |
|   The following auxiliary characters are missing from the font: ǯ    |                              |
| Auxiliary orthography codepoints:                                    | * fr_Latn (French)           |
|   The following auxiliary characters are missing from the font: Ǔ    |                              |
|   The following auxiliary characters are missing from the font: ſ    |                              |
|   The following auxiliary characters are missing from the font: ǔ    |                              | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į̌
* į̄
* į́
* į̀
* į̃
* į̂The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̋
* į̆
* į̒
* į̊
* į̈
* į̇ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* OE (U+0152): Line(Line { p0: (584.0, 0.0), p1: (584.0, 680.0) }) has the same coordinates as a previous segment.
* OE (U+0152): Line(Line { p0: (584.0, 680.0), p1: (648.0, 680.0) }) has the same coordinates as a previous segment.
* OE (U+0152): Line(Line { p0: (648.0, 680.0), p1: (648.0, 0.0) }) has the same coordinates as a previous segment.
* OE (U+0152): Line(Line { p0: (648.0, 0.0), p1: (584.0, 0.0) }) has the same coordinates as a previous segment.
* eng (U+014B): Line(Line { p0: (508.0, 0.0), p1: (448.0, 0.0) }) has the same coordinates as a previous segment.
* four (U+0034): Line(Line { p0: (386.0, 680.0), p1: (450.0, 680.0) }) has the same coordinates as a previous segment.
* four.osf: Line(Line { p0: (386.0, 560.0), p1: (450.0, 560.0) }) has the same coordinates as a previous segment.
* four.tf: Line(Line { p0: (423.0, 680.0), p1: (487.0, 680.0) }) has the same coordinates as a previous segment.
* dollar (U+0024): Line(Line { p0: (272.0, 350.0), p1: (326.0, 350.0) }) has the same coordinates as a previous segment.
... and 6 others [code: overlapping-path-segments]
  
  

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
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. (hinting_impact)</summary>
    <div>








- ℹ️ **INFO** Hinting filesize impact:

 |               | AlanSans[wght].ttf     |
 |:------------- | ---------------:|
 | Dehinted Size | 198080 |
 | Hinted Size   | 198104   |
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








- ℹ️ **INFO** Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: Version 1.100 [code: version-not-detected]
  
  

</div>
</details>


</div>
</details>






### Summary

| 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 1 | 9 | 6 | 128 | 56 | 
| 0% | 4% | 3% | 64% | 28% | 



