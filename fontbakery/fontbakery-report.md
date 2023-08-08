## Fontbakery report

Fontbakery version: 0.8.11

<details><summary><b>[19] PitagonSansMono-ExtraBoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Pitagon Sans Mono ExtraBold' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, exclam_equal_equal.liga.ss19.001, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- dollar.cv14

	- eight.dnom

	- eight.numr

	- exclam_equal.liga.ss19.001

	- exclam_equal_equal.liga.ss19.001

	- five.dnom

	- five.numr

	- four.dnom

	- four.numr

	- nine.dnom

	- nine.numr

	- one.dnom

	- one.numr

	- seven.dnom

	- seven.numr

	- six.dnom

	- six.numr

	- three.dnom

	- three.numr

	- two.dnom

	- two.numr

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- zero.dnom 

	- zero.numr
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1697 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* section (U+00A7): X=1.0,Y=2.0 (should be at baseline 0?)

	* section (U+00A7): X=151.0,Y=2.0 (should be at baseline 0?)

	* uni00B2 (U+00B2): X=422.0,Y=731.0 (should be at cap-height 730?)

	* uni00B2 (U+00B2): X=328.0,Y=731.0 (should be at cap-height 730?)

	* onequarter (U+00BC): X=197.0,Y=729.0 (should be at cap-height 730?)

	* onequarter (U+00BC): X=312.0,Y=729.0 (should be at cap-height 730?)

	* oe (U+0153): X=313.0,Y=2.0 (should be at baseline 0?)

	* oe (U+0153): X=197.5,Y=2.0 (should be at baseline 0?)

	* uni01D8 (U+01D8): X=573.5,Y=1018.0 (should be at ascender 1020?)

	* uni01DA (U+01DA): X=235.5,Y=1018.0 (should be at ascender 1020?)

	* uni01DC (U+01DC): X=259.5,Y=1018.0 (should be at ascender 1020?)

	* hookabovecomb (U+0309): X=-227.0,Y=732.0 (should be at cap-height 730?)

	* uni03C2 (U+03C2): X=480.0,Y=1.0 (should be at baseline 0?)

	* uni03D7 (U+03D7): X=404.0,Y=-1.0 (should be at baseline 0?)

	* uni1EA3 (U+1EA3): X=378.0,Y=732.0 (should be at cap-height 730?)

	* uni1EBB (U+1EBB): X=373.0,Y=732.0 (should be at cap-height 730?)

	* uni1EC9 (U+1EC9): X=393.0,Y=732.0 (should be at cap-height 730?)

	* uni1ECF (U+1ECF): X=373.0,Y=732.0 (should be at cap-height 730?)

	* uni1EDF (U+1EDF): X=363.0,Y=732.0 (should be at cap-height 730?)

	* uni1EE7 (U+1EE7): X=373.0,Y=732.0 (should be at cap-height 730?)

	* uni1EED (U+1EED): X=353.0,Y=732.0 (should be at cap-height 730?)

	* uni1EF7 (U+1EF7): X=373.0,Y=732.0 (should be at cap-height 730?)

	* quotesinglbase (U+201A): X=221.0,Y=2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=91.0,Y=2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=346.0,Y=2.0 (should be at baseline 0?)

	* uni2070 (U+2070): X=427.0,Y=729.0 (should be at cap-height 730?)

	* uni2070 (U+2070): X=315.0,Y=729.0 (should be at cap-height 730?)

	* uni2085 (U+2085): X=84.0,Y=2.0 (should be at baseline 0?)

	* uni2085 (U+2085): X=182.0,Y=2.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=362.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=238.0,Y=-1.0 (should be at baseline 0?)

	* uni21DF (U+21DF): X=238.0,Y=731.0 (should be at cap-height 730?)

	* uni21DF (U+21DF): X=362.0,Y=731.0 (should be at cap-height 730?)

	* uni21E7 (U+21E7): X=301.0,Y=729.0 (should be at cap-height 730?)

	* uni21EA (U+21EA): X=300.0,Y=728.0 (should be at cap-height 730?)

	* piads (U+E001): X=158.0,Y=2.0 (should be at baseline 0?)

	* pioffice (U+E002): X=158.0,Y=2.0 (should be at baseline 0?)

	* pitagram (U+E003): X=158.0,Y=2.0 (should be at baseline 0?)

	* piweb (U+E004): X=158.0,Y=2.0 (should be at baseline 0?)

	* pisign (U+E005): X=158.0,Y=2.0 (should be at baseline 0?)

	* petapp (U+E006): X=534.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=303.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=293.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=318.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=336.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=331.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=328.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=326.0,Y=1.5 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=278.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=274.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=272.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* picall (U+E009): X=158.0,Y=2.0 (should be at baseline 0?)

	* uniFE62 (U+FE62): X=196.0,Y=-1.0 (should be at baseline 0?) 

	* uniFE62 (U+FE62): X=316.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): B<<464.0,491.5>-<490.0,593.0>-<512.0,670.0>>/L<<512.0,670.0>--<372.0,332.0>> = 6.553998704225972

	* M (U+004D): L<<240.0,337.0>--<209.0,661.0>>/B<<209.0,661.0>-<208.0,596.0>-<202.5,495.5>> = 6.346770593215412

	* Mu (U+039C): B<<464.0,491.5>-<490.0,593.0>-<512.0,670.0>>/L<<512.0,670.0>--<372.0,332.0>> = 6.553998704225972

	* Mu (U+039C): L<<240.0,337.0>--<209.0,661.0>>/B<<209.0,661.0>-<208.0,596.0>-<202.5,495.5>> = 6.346770593215412

	* N (U+004E): L<<319.0,25.0>--<223.0,565.0>>/B<<223.0,565.0>-<221.0,533.0>-<217.5,489.0>> = 13.656932362539646

	* Nacute (U+0143): L<<319.0,25.0>--<223.0,565.0>>/B<<223.0,565.0>-<221.0,533.0>-<217.5,489.0>> = 13.656932362539646

	* Ncaron (U+0147): L<<319.0,25.0>--<223.0,565.0>>/B<<223.0,565.0>-<221.0,533.0>-<217.5,489.0>> = 13.656932362539646

	* Ntilde (U+00D1): L<<319.0,25.0>--<223.0,565.0>>/B<<223.0,565.0>-<221.0,533.0>-<217.5,489.0>> = 13.656932362539646

	* Nu (U+039D): L<<319.0,25.0>--<223.0,565.0>>/B<<223.0,565.0>-<221.0,533.0>-<217.5,489.0>> = 13.656932362539646

	* W (U+0057): B<<148.0,149.5>-<145.0,122.0>-<142.0,100.0>>/B<<142.0,100.0>-<148.0,122.0>-<154.5,149.5>> = 7.489952684632385

	* W (U+0057): B<<352.5,587.0>-<355.0,617.0>-<357.0,640.0>>/B<<357.0,640.0>-<352.0,617.0>-<345.5,587.0>> = 7.295032999782122

	* W (U+0057): B<<400.5,149.5>-<399.0,122.0>-<398.0,100.0>>/B<<398.0,100.0>-<402.0,122.0>-<407.5,149.5>> = 7.702284266266219

	* Wacute (U+1E82): B<<148.0,149.5>-<145.0,122.0>-<142.0,100.0>>/B<<142.0,100.0>-<148.0,122.0>-<154.5,149.5>> = 7.489952684632385

	* Wacute (U+1E82): B<<352.5,587.0>-<355.0,617.0>-<357.0,640.0>>/B<<357.0,640.0>-<352.0,617.0>-<345.5,587.0>> = 7.295032999782122

	* Wacute (U+1E82): B<<400.5,149.5>-<399.0,122.0>-<398.0,100.0>>/B<<398.0,100.0>-<402.0,122.0>-<407.5,149.5>> = 7.702284266266219

	* Wcircumflex (U+0174): B<<148.0,149.5>-<145.0,122.0>-<142.0,100.0>>/B<<142.0,100.0>-<148.0,122.0>-<154.5,149.5>> = 7.489952684632385

	* Wcircumflex (U+0174): B<<352.5,587.0>-<355.0,617.0>-<357.0,640.0>>/B<<357.0,640.0>-<352.0,617.0>-<345.5,587.0>> = 7.295032999782122

	* Wcircumflex (U+0174): B<<400.5,149.5>-<399.0,122.0>-<398.0,100.0>>/B<<398.0,100.0>-<402.0,122.0>-<407.5,149.5>> = 7.702284266266219

	* Wdieresis (U+1E84): B<<148.0,149.5>-<145.0,122.0>-<142.0,100.0>>/B<<142.0,100.0>-<148.0,122.0>-<154.5,149.5>> = 7.489952684632385

	* Wdieresis (U+1E84): B<<352.5,587.0>-<355.0,617.0>-<357.0,640.0>>/B<<357.0,640.0>-<352.0,617.0>-<345.5,587.0>> = 7.295032999782122

	* Wdieresis (U+1E84): B<<400.5,149.5>-<399.0,122.0>-<398.0,100.0>>/B<<398.0,100.0>-<402.0,122.0>-<407.5,149.5>> = 7.702284266266219

	* Wgrave (U+1E80): B<<148.0,149.5>-<145.0,122.0>-<142.0,100.0>>/B<<142.0,100.0>-<148.0,122.0>-<154.5,149.5>> = 7.489952684632385

	* Wgrave (U+1E80): B<<352.5,587.0>-<355.0,617.0>-<357.0,640.0>>/B<<357.0,640.0>-<352.0,617.0>-<345.5,587.0>> = 7.295032999782122

	* Wgrave (U+1E80): B<<400.5,149.5>-<399.0,122.0>-<398.0,100.0>>/B<<398.0,100.0>-<402.0,122.0>-<407.5,149.5>> = 7.702284266266219

	* ae (U+00E6): B<<303.5,535.5>-<333.0,511.0>-<331.0,468.0>>/B<<331.0,468.0>-<343.0,511.0>-<381.0,535.5>> = 12.929810173199169

	* aeacute (U+01FD): B<<303.5,535.5>-<333.0,511.0>-<331.0,468.0>>/B<<331.0,468.0>-<343.0,511.0>-<381.0,535.5>> = 12.929810173199169

	* endOfMediumcontrol (U+2419): B<<414.5,176.5>-<415.0,165.0>-<415.0,153.0>>/B<<415.0,153.0>-<418.0,165.0>-<422.0,176.5>> = 14.036243467926457

	* endOfMediumcontrol (U+2419): B<<525.0,207.0>-<533.0,251.0>-<546.0,289.0>>/L<<546.0,289.0>--<450.0,96.0>> = 7.560093066068733

	* endOfMediumcontrol (U+2419): L<<364.0,96.0>--<326.0,286.0>>/B<<326.0,286.0>-<327.0,261.0>-<325.5,236.5>> = 9.019322431381651

	* endOfTextcontrol (U+2403): B<<412.5,102.5>-<410.0,112.0>-<409.0,122.0>>/B<<409.0,122.0>-<408.0,112.0>-<404.5,102.5>> = 11.42118627499929

	* eta (U+03B7): L<<249.0,520.0>--<237.0,448.0>>/B<<237.0,448.0>-<257.0,499.0>-<302.0,529.5>> = 11.950647266846158

	* etatonos (U+03AE): L<<249.0,520.0>--<237.0,448.0>>/B<<237.0,448.0>-<257.0,499.0>-<302.0,529.5>> = 11.950647266846158

	* h (U+0068): L<<259.0,550.0>--<238.0,449.0>>/B<<238.0,449.0>-<258.0,499.0>-<302.5,529.5>> = 10.055776061063874

	* hcircumflex (U+0125): L<<259.0,550.0>--<238.0,449.0>>/B<<238.0,449.0>-<258.0,499.0>-<302.5,529.5>> = 10.055776061063874

	* lambda (U+03BB): B<<330.0,351.5>-<329.0,383.0>-<329.0,403.0>>/B<<329.0,403.0>-<324.0,383.0>-<313.0,352.0>> = 14.036243467926484

	* n (U+006E): L<<249.0,520.0>--<237.0,448.0>>/B<<237.0,448.0>-<257.0,499.0>-<302.0,529.5>> = 11.950647266846158

	* nacute (U+0144): L<<249.0,520.0>--<237.0,448.0>>/B<<237.0,448.0>-<257.0,499.0>-<302.0,529.5>> = 11.950647266846158

	* napostrophe (U+0149): L<<249.0,520.0>--<237.0,448.0>>/B<<237.0,448.0>-<257.0,499.0>-<302.0,529.5>> = 11.950647266846158

	* ncaron (U+0148): L<<249.0,520.0>--<237.0,448.0>>/B<<237.0,448.0>-<257.0,499.0>-<302.0,529.5>> = 11.950647266846158

	* ntilde (U+00F1): L<<249.0,520.0>--<237.0,448.0>>/B<<237.0,448.0>-<257.0,499.0>-<302.0,529.5>> = 11.950647266846158

	* nu (U+03BD): B<<272.5,183.0>-<275.0,153.0>-<273.0,127.0>>/B<<273.0,127.0>-<279.0,153.0>-<290.5,183.0>> = 8.595911436920954

	* omega (U+03C9): B<<297.5,23.0>-<269.0,56.0>-<273.0,109.0>>/B<<273.0,109.0>-<258.0,54.0>-<220.0,22.0>> = 10.939091183192135

	* omegatonos (U+03CE): B<<297.5,23.0>-<269.0,56.0>-<273.0,109.0>>/B<<273.0,109.0>-<258.0,54.0>-<220.0,22.0>> = 10.939091183192135

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<365.0,279.0>-<368.0,276.0>-<370.0,275.0>>/L<<370.0,275.0>--<365.0,279.0>> = 12.094757077012058

	* petapp.minimal (U+E007): B<<402.0,358.0>-<402.0,357.0>-<401.0,355.0>>/L<<401.0,355.0>--<402.0,358.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>>/L<<437.0,404.0>--<440.0,406.0>> = 7.125016348901757

	* petapp.minimal (U+E007): B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>>/L<<442.0,407.0>--<447.0,409.0>> = 4.763641690726143

	* petapp.minimal (U+E007): B<<468.0,415.0>-<467.0,415.0>-<465.0,414.0>>/L<<465.0,414.0>--<468.0,415.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>>/L<<467.0,106.0>--<469.0,103.0>> = 11.309932474020195

	* petapp.minimal (U+E007): B<<484.5,8.5>-<484.0,4.0>-<483.0,0.0>>/B<<483.0,0.0>-<483.0,3.0>-<483.0,6.5>> = 14.036243467926484

	* petapp.minimal (U+E007): L<<408.0,166.0>--<411.0,165.0>>/B<<411.0,165.0>-<409.0,166.0>-<408.0,166.5>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<413.0,298.0>--<412.0,301.0>>/B<<412.0,301.0>-<413.0,299.0>-<413.0,298.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<417.0,160.0>--<420.0,159.0>>/B<<420.0,159.0>-<418.0,160.0>-<417.0,160.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<437.0,404.0>--<440.0,406.0>>/B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>> = 11.309932474020227

	* petapp.minimal (U+E007): L<<442.0,407.0>--<447.0,409.0>>/B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>> = 3.3664606634297236

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<467.0,106.0>--<469.0,103.0>>/B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>> = 7.125016348901757

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<90.0,577.0>-<99.0,557.0>> = 4.969740728110289

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* r (U+0072): L<<269.0,520.0>--<258.0,447.0>>/B<<258.0,447.0>-<279.0,500.0>-<324.0,530.0>> = 13.045637062948598

	* racute (U+0155): L<<269.0,520.0>--<258.0,447.0>>/B<<258.0,447.0>-<279.0,500.0>-<324.0,530.0>> = 13.045637062948598

	* rcaron (U+0159): L<<269.0,520.0>--<258.0,447.0>>/B<<258.0,447.0>-<279.0,500.0>-<324.0,530.0>> = 13.045637062948598

	* startOfTextcontrol (U+2402): B<<412.5,102.5>-<410.0,112.0>-<409.0,122.0>>/B<<409.0,122.0>-<408.0,112.0>-<404.5,102.5>> = 11.42118627499929

	* sterling (U+00A3): B<<214.5,162.0>-<177.0,145.0>-<143.0,140.0>>/L<<143.0,140.0>--<513.0,140.0>> = 8.365886124032546

	* trademark (U+2122): B<<425.5,646.0>-<423.0,676.0>-<421.0,695.0>>/B<<421.0,695.0>-<421.0,672.0>-<419.0,641.0>> = 6.009005957494474

	* trademark (U+2122): B<<565.0,639.0>-<574.0,673.0>-<581.0,700.0>>/B<<581.0,700.0>-<574.0,680.0>-<560.5,648.0>> = 4.755591138648516

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni0145 (U+0145): L<<319.0,25.0>--<223.0,565.0>>/B<<223.0,565.0>-<221.0,533.0>-<217.5,489.0>> = 13.656932362539646

	* uni0146 (U+0146): L<<249.0,520.0>--<237.0,448.0>>/B<<237.0,448.0>-<257.0,499.0>-<302.0,529.5>> = 11.950647266846158

	* uni0157 (U+0157): L<<269.0,520.0>--<258.0,447.0>>/B<<258.0,447.0>-<279.0,500.0>-<324.0,530.0>> = 13.045637062948598

	* uni019B (U+019B): B<<330.0,351.5>-<329.0,383.0>-<329.0,403.0>>/B<<329.0,403.0>-<324.0,383.0>-<313.0,352.0>> = 14.036243467926484

	* uni03D6 (U+03D6): B<<298.0,22.5>-<270.0,55.0>-<273.0,109.0>>/B<<273.0,109.0>-<259.0,55.0>-<220.0,22.5>> = 11.354624960675853

	* uni03D7 (U+03D7): B<<168.5,162.0>-<158.0,124.0>-<149.0,95.0>>/L<<149.0,95.0>--<395.0,550.0>> = 11.156827388965786

	* uni03D7 (U+03D7): B<<427.5,377.0>-<437.0,411.0>-<445.0,435.0>>/L<<445.0,435.0>--<204.0,0.0>> = 10.552511815274025

	* uni040E (U+040E): B<<312.0,378.0>-<314.0,347.0>-<314.0,327.0>>/B<<314.0,327.0>-<319.0,347.0>-<329.5,378.5>> = 14.036243467926484

	* uni0418 (U+0418): B<<178.5,242.0>-<168.0,198.0>-<160.0,165.0>>/L<<160.0,165.0>--<435.0,730.0>> = 12.32638084247264

	* uni0418 (U+0418): B<<449.0,480.0>-<460.0,529.0>-<469.0,565.0>>/L<<469.0,565.0>--<193.0,0.0>> = 11.999060974358631

	* uni0419 (U+0419): B<<178.5,242.0>-<168.0,198.0>-<160.0,165.0>>/L<<160.0,165.0>--<435.0,730.0>> = 12.32638084247264

	* uni0419 (U+0419): B<<449.0,480.0>-<460.0,529.0>-<469.0,565.0>>/L<<469.0,565.0>--<193.0,0.0>> = 11.999060974358631

	* uni041C (U+041C): B<<464.0,491.5>-<490.0,593.0>-<512.0,670.0>>/L<<512.0,670.0>--<372.0,332.0>> = 6.553998704225972

	* uni041C (U+041C): L<<240.0,337.0>--<209.0,661.0>>/B<<209.0,661.0>-<208.0,596.0>-<202.5,495.5>> = 6.346770593215412

	* uni0423 (U+0423): B<<312.0,378.0>-<314.0,347.0>-<314.0,327.0>>/B<<314.0,327.0>-<319.0,347.0>-<329.5,378.5>> = 14.036243467926484

	* uni0431 (U+0431): L<<214.0,461.0>--<204.0,398.0>>/B<<204.0,398.0>-<221.0,454.0>-<267.0,485.0>> = 7.8674686925622925

	* uni0434 (U+0434): B<<398.0,485.0>-<435.0,454.0>-<434.0,397.0>>/L<<434.0,397.0>--<444.0,461.0>> = 7.875573145266023

	* uni043C (U+043C): B<<293.5,281.5>-<296.0,253.0>-<295.0,239.0>>/B<<295.0,239.0>-<299.0,253.0>-<308.5,281.5>> = 11.859779120947936

	* uni043C (U+043C): B<<437.0,319.0>-<450.0,377.0>-<460.0,420.0>>/L<<460.0,420.0>--<345.0,155.0>> = 10.367131017114666

	* uni043C (U+043C): L<<218.0,155.0>--<183.0,420.0>>/B<<183.0,420.0>-<181.0,379.0>-<176.0,322.0>> = 10.316522804351882

	* uni04E4 (U+04E4): B<<178.5,242.0>-<168.0,198.0>-<160.0,165.0>>/L<<160.0,165.0>--<435.0,730.0>> = 12.32638084247264

	* uni04E4 (U+04E4): B<<449.0,480.0>-<460.0,529.0>-<469.0,565.0>>/L<<469.0,565.0>--<193.0,0.0>> = 11.999060974358631

	* uni20BF (U+20BF): B<<482.5,404.0>-<442.0,384.0>-<396.0,381.0>>/B<<396.0,381.0>-<446.0,380.0>-<483.5,361.0>> = 4.877159837335479

	* uni2116 (U+2116): B<<154.5,551.5>-<153.0,596.0>-<152.0,630.0>>/B<<152.0,630.0>-<151.0,575.0>-<148.0,509.5>> = 2.726310993906212

	* uni2116 (U+2116): B<<262.0,183.0>-<264.0,137.0>-<266.0,100.0>>/B<<266.0,100.0>-<267.0,155.0>-<269.5,220.5>> = 4.135684734927

	* uni2197 (U+2197): B<<408.5,476.5>-<412.0,497.0>-<418.0,507.0>>/L<<418.0,507.0>--<130.0,214.0>> = 13.543176642444744

	* uni227A (U+227A): B<<445.0,409.5>-<339.0,337.0>-<175.0,329.0>>/B<<175.0,329.0>-<336.0,320.0>-<419.5,250.5>> = 5.992242075275782

	* uni227B (U+227B): B<<173.0,253.5>-<280.0,327.0>-<444.0,337.0>>/B<<444.0,337.0>-<282.0,345.0>-<198.0,413.5>> = 6.3164494839575855

	* uni227C (U+227C): B<<477.0,534.5>-<371.0,462.0>-<207.0,454.0>>/B<<207.0,454.0>-<368.0,445.0>-<451.5,375.5>> = 5.992242075275782

	* uni22CE (U+22CE): B<<247.0,446.5>-<302.0,350.0>-<283.0,185.0>>/B<<283.0,185.0>-<319.0,351.0>-<405.5,447.5>> = 5.667347387595207

	* uni234B (U+234B): L<<277.0,130.0>--<277.0,475.0>>/L<<277.0,475.0>--<204.0,130.0>> = 11.947234104599477

	* uni234B (U+234B): L<<393.0,130.0>--<320.0,475.0>>/L<<320.0,475.0>--<320.0,130.0>> = 11.947234104599477

	* uni2352 (U+2352): L<<208.0,600.0>--<282.0,260.0>>/L<<282.0,260.0>--<282.0,600.0>> = 12.278765370963031

	* uni2352 (U+2352): L<<324.0,600.0>--<324.0,260.0>>/L<<324.0,260.0>--<396.0,600.0>> = 11.956584243149111

	* uni236C (U+236C): L<<248.0,520.0>--<225.0,376.0>>/B<<225.0,376.0>-<250.0,457.0>-<294.0,457.0>> = 8.077663719203109

	* uni236C (U+236C): L<<379.0,210.0>--<403.0,364.0>>/B<<403.0,364.0>-<378.0,287.0>-<335.0,287.0>> = 9.129375888433097

	* uni2375 (U+2375): B<<298.0,22.5>-<270.0,55.0>-<273.0,109.0>>/B<<273.0,109.0>-<259.0,55.0>-<220.0,22.5>> = 11.354624960675853

	* uni2379 (U+2379): B<<298.0,22.5>-<270.0,55.0>-<273.0,109.0>>/B<<273.0,109.0>-<259.0,55.0>-<220.0,22.5>> = 11.354624960675853

	* uni26A1 (U+26A1): L<<579.0,440.0>--<49.0,-110.0>>/L<<49.0,-110.0>--<294.0,310.0>> = 13.68265114620652

	* v (U+0076): B<<272.5,183.0>-<275.0,153.0>-<273.0,127.0>>/B<<273.0,127.0>-<279.0,153.0>-<290.5,183.0>> = 8.595911436920954

	* w (U+0077): B<<151.0,169.0>-<147.0,126.0>-<144.0,97.0>>/B<<144.0,97.0>-<151.0,126.0>-<161.0,169.0>> = 7.664293271390927

	* w (U+0077): B<<322.5,379.0>-<324.0,419.0>-<326.0,445.0>>/B<<326.0,445.0>-<323.0,428.0>-<316.5,403.0>> = 5.609274446445703

	* w (U+0077): B<<400.0,168.5>-<397.0,125.0>-<395.0,96.0>>/B<<395.0,96.0>-<401.0,125.0>-<410.0,168.5>> = 7.74418294640162

	* wacute (U+1E83): B<<151.0,169.0>-<147.0,126.0>-<144.0,97.0>>/B<<144.0,97.0>-<151.0,126.0>-<161.0,169.0>> = 7.664293271390927

	* wacute (U+1E83): B<<322.5,379.0>-<324.0,419.0>-<326.0,445.0>>/B<<326.0,445.0>-<323.0,428.0>-<316.5,403.0>> = 5.609274446445703

	* wacute (U+1E83): B<<400.0,168.5>-<397.0,125.0>-<395.0,96.0>>/B<<395.0,96.0>-<401.0,125.0>-<410.0,168.5>> = 7.74418294640162

	* wcircumflex (U+0175): B<<151.0,169.0>-<147.0,126.0>-<144.0,97.0>>/B<<144.0,97.0>-<151.0,126.0>-<161.0,169.0>> = 7.664293271390927

	* wcircumflex (U+0175): B<<322.5,379.0>-<324.0,419.0>-<326.0,445.0>>/B<<326.0,445.0>-<323.0,428.0>-<316.5,403.0>> = 5.609274446445703

	* wcircumflex (U+0175): B<<400.0,168.5>-<397.0,125.0>-<395.0,96.0>>/B<<395.0,96.0>-<401.0,125.0>-<410.0,168.5>> = 7.74418294640162

	* wdieresis (U+1E85): B<<151.0,169.0>-<147.0,126.0>-<144.0,97.0>>/B<<144.0,97.0>-<151.0,126.0>-<161.0,169.0>> = 7.664293271390927

	* wdieresis (U+1E85): B<<322.5,379.0>-<324.0,419.0>-<326.0,445.0>>/B<<326.0,445.0>-<323.0,428.0>-<316.5,403.0>> = 5.609274446445703

	* wdieresis (U+1E85): B<<400.0,168.5>-<397.0,125.0>-<395.0,96.0>>/B<<395.0,96.0>-<401.0,125.0>-<410.0,168.5>> = 7.74418294640162

	* wgrave (U+1E81): B<<151.0,169.0>-<147.0,126.0>-<144.0,97.0>>/B<<144.0,97.0>-<151.0,126.0>-<161.0,169.0>> = 7.664293271390927

	* wgrave (U+1E81): B<<322.5,379.0>-<324.0,419.0>-<326.0,445.0>>/B<<326.0,445.0>-<323.0,428.0>-<316.5,403.0>> = 5.609274446445703 

	* wgrave (U+1E81): B<<400.0,168.5>-<397.0,125.0>-<395.0,96.0>>/B<<395.0,96.0>-<401.0,125.0>-<410.0,168.5>> = 7.74418294640162 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[18] PitagonSansMono-Italic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, exclam_equal_equal.liga.ss19.001, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- dollar.cv14

	- eight.dnom

	- eight.numr

	- exclam_equal.liga.ss19.001

	- exclam_equal_equal.liga.ss19.001

	- five.dnom

	- five.numr

	- four.dnom

	- four.numr

	- nine.dnom

	- nine.numr

	- one.dnom

	- one.numr

	- seven.dnom

	- seven.numr

	- six.dnom

	- six.numr

	- three.dnom

	- three.numr

	- two.dnom

	- two.numr

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- zero.dnom 

	- zero.numr
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1697 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* braceleft (U+007B): X=458.5,Y=728.5 (should be at cap-height 730?)

	* braceright (U+007D): X=286.0,Y=728.5 (should be at cap-height 730?)

	* eogonek (U+0119): X=356.0,Y=1.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=357.0,Y=1.0 (should be at baseline 0?)

	* uogonek (U+0173): X=355.0,Y=1.0 (should be at baseline 0?)

	* uni01EA (U+01EA): X=357.0,Y=1.0 (should be at baseline 0?)

	* uni01EB (U+01EB): X=355.0,Y=1.0 (should be at baseline 0?)

	* ogonek (U+02DB): X=290.0,Y=1.0 (should be at baseline 0?)

	* uni0328 (U+0328): X=-310.0,Y=1.0 (should be at baseline 0?)

	* zeta (U+03B6): X=388.0,Y=-2.0 (should be at baseline 0?)

	* uni03D7 (U+03D7): X=420.0,Y=-2.0 (should be at baseline 0?)

	* arrowupdn (U+2195): X=222.0,Y=1.0 (should be at baseline 0?)

	* arrowupdn (U+2195): X=222.0,Y=729.0 (should be at cap-height 730?)

	* arrowupdn (U+2195): X=380.0,Y=729.0 (should be at cap-height 730?)

	* arrowupdn (U+2195): X=380.0,Y=1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=343.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=257.0,Y=-1.0 (should be at baseline 0?)

	* uni21DF (U+21DF): X=257.0,Y=731.0 (should be at cap-height 730?)

	* uni21DF (U+21DF): X=343.0,Y=731.0 (should be at cap-height 730?)

	* uni21E7 (U+21E7): X=301.0,Y=729.0 (should be at cap-height 730?)

	* uni21EA (U+21EA): X=300.0,Y=728.0 (should be at cap-height 730?)

	* uni2262 (U+2262): X=466.0,Y=729.0 (should be at cap-height 730?)

	* uni2262 (U+2262): X=531.0,Y=729.0 (should be at cap-height 730?)

	* uni2987 (U+2987): X=400.0,Y=729.0 (should be at cap-height 730?)

	* uni2988 (U+2988): X=200.0,Y=729.0 (should be at cap-height 730?)

	* piads (U+E001): X=158.0,Y=2.0 (should be at baseline 0?)

	* pioffice (U+E002): X=158.0,Y=2.0 (should be at baseline 0?)

	* pitagram (U+E003): X=158.0,Y=2.0 (should be at baseline 0?)

	* piweb (U+E004): X=158.0,Y=2.0 (should be at baseline 0?)

	* pisign (U+E005): X=158.0,Y=2.0 (should be at baseline 0?)

	* petapp (U+E006): X=534.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=303.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=293.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=318.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=336.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=331.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=328.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=326.0,Y=1.5 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=278.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=274.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=272.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* picall (U+E009): X=158.0,Y=2.0 (should be at baseline 0?)

	* uniFF5B (U+FF5B): X=458.5,Y=728.5 (should be at cap-height 730?) 

	* uniFF5D (U+FF5D): X=286.0,Y=728.5 (should be at cap-height 730?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): B<<495.5,586.0>-<508.0,651.0>-<521.0,703.0>>/L<<521.0,703.0>--<351.0,341.0>> = 11.11912896594182

	* M (U+004D): L<<263.0,344.0>--<211.0,694.0>>/B<<211.0,694.0>-<207.0,620.0>-<196.5,532.0>> = 11.544756952519174

	* Mu (U+039C): B<<495.5,586.0>-<508.0,651.0>-<521.0,703.0>>/L<<521.0,703.0>--<351.0,341.0>> = 11.11912896594182

	* Mu (U+039C): L<<263.0,344.0>--<211.0,694.0>>/B<<211.0,694.0>-<207.0,620.0>-<196.5,532.0>> = 11.544756952519174

	* W (U+0057): B<<138.5,121.5>-<135.0,86.0>-<132.0,65.0>>/B<<132.0,65.0>-<138.0,86.0>-<146.5,121.5>> = 7.815293546766825

	* W (U+0057): B<<360.0,616.5>-<363.0,649.0>-<364.0,667.0>>/B<<364.0,667.0>-<359.0,649.0>-<351.5,616.5>> = 12.344280876890016

	* W (U+0057): B<<397.5,121.5>-<396.0,86.0>-<394.0,65.0>>/B<<394.0,65.0>-<399.0,86.0>-<407.5,121.5>> = 7.952165722745561

	* Wacute (U+1E82): B<<138.5,121.5>-<135.0,86.0>-<132.0,65.0>>/B<<132.0,65.0>-<138.0,86.0>-<146.5,121.5>> = 7.815293546766825

	* Wacute (U+1E82): B<<360.0,616.5>-<363.0,649.0>-<364.0,667.0>>/B<<364.0,667.0>-<359.0,649.0>-<351.5,616.5>> = 12.344280876890016

	* Wacute (U+1E82): B<<397.5,121.5>-<396.0,86.0>-<394.0,65.0>>/B<<394.0,65.0>-<399.0,86.0>-<407.5,121.5>> = 7.952165722745561

	* Wcircumflex (U+0174): B<<138.5,121.5>-<135.0,86.0>-<132.0,65.0>>/B<<132.0,65.0>-<138.0,86.0>-<146.5,121.5>> = 7.815293546766825

	* Wcircumflex (U+0174): B<<360.0,616.5>-<363.0,649.0>-<364.0,667.0>>/B<<364.0,667.0>-<359.0,649.0>-<351.5,616.5>> = 12.344280876890016

	* Wcircumflex (U+0174): B<<397.5,121.5>-<396.0,86.0>-<394.0,65.0>>/B<<394.0,65.0>-<399.0,86.0>-<407.5,121.5>> = 7.952165722745561

	* Wdieresis (U+1E84): B<<138.5,121.5>-<135.0,86.0>-<132.0,65.0>>/B<<132.0,65.0>-<138.0,86.0>-<146.5,121.5>> = 7.815293546766825

	* Wdieresis (U+1E84): B<<360.0,616.5>-<363.0,649.0>-<364.0,667.0>>/B<<364.0,667.0>-<359.0,649.0>-<351.5,616.5>> = 12.344280876890016

	* Wdieresis (U+1E84): B<<397.5,121.5>-<396.0,86.0>-<394.0,65.0>>/B<<394.0,65.0>-<399.0,86.0>-<407.5,121.5>> = 7.952165722745561

	* Wgrave (U+1E80): B<<138.5,121.5>-<135.0,86.0>-<132.0,65.0>>/B<<132.0,65.0>-<138.0,86.0>-<146.5,121.5>> = 7.815293546766825

	* Wgrave (U+1E80): B<<360.0,616.5>-<363.0,649.0>-<364.0,667.0>>/B<<364.0,667.0>-<359.0,649.0>-<351.5,616.5>> = 12.344280876890016

	* Wgrave (U+1E80): B<<397.5,121.5>-<396.0,86.0>-<394.0,65.0>>/B<<394.0,65.0>-<399.0,86.0>-<407.5,121.5>> = 7.952165722745561

	* a (U+0061): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* aacute (U+00E1): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* abreve (U+0103): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* acircumflex (U+00E2): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* adieresis (U+00E4): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* ae (U+00E6): B<<306.0,535.5>-<336.0,511.0>-<335.0,471.0>>/B<<335.0,471.0>-<346.0,511.0>-<382.5,535.5>> = 13.944155064661553

	* aeacute (U+01FD): B<<306.0,535.5>-<336.0,511.0>-<335.0,471.0>>/B<<335.0,471.0>-<346.0,511.0>-<382.5,535.5>> = 13.944155064661553

	* agrave (U+00E0): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* alpha (U+03B1): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* alphatonos (U+03AC): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* amacron (U+0101): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* aogonek (U+0105): B<<388.5,50.5>-<376.0,78.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.44205632596418

	* aring (U+00E5): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* arrowboth (U+2194): B<<514.0,251.0>-<540.0,285.0>-<566.0,290.0>>/L<<566.0,290.0>--<34.0,290.0>> = 10.885527054658743

	* arrowboth (U+2194): L<<566.0,290.0>--<34.0,290.0>>/B<<34.0,290.0>-<60.0,285.0>-<86.0,251.0>> = 10.885527054658743

	* arrowdown (U+2193): L<<369.0,730.0>--<369.0,112.0>>/B<<369.0,112.0>-<371.0,120.0>-<382.0,133.5>> = 14.036243467926484

	* arrowleft (U+2190): L<<580.0,290.0>--<124.0,290.0>>/B<<124.0,290.0>-<150.0,285.0>-<176.0,251.0>> = 10.885527054658743

	* arrowright (U+2192): B<<424.0,251.0>-<450.0,285.0>-<476.0,290.0>>/L<<476.0,290.0>--<20.0,290.0>> = 10.885527054658743

	* arrowupdn (U+2195): L<<340.0,778.0>--<340.0,-48.0>>/B<<340.0,-48.0>-<342.0,-40.0>-<353.0,-26.5>> = 14.036243467926484

	* atilde (U+00E3): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* braceleft (U+007B): B<<372.5,405.5>-<334.0,370.0>-<257.0,363.0>>/B<<257.0,363.0>-<331.0,356.0>-<358.0,317.0>> = 10.5982202679845

	* dcaron (U+010F): L<<319.0,0.0>--<335.0,99.0>>/B<<335.0,99.0>-<320.0,47.0>-<280.5,18.5>> = 6.91027439122602

	* endOfMediumcontrol (U+2419): B<<532.5,211.5>-<542.0,260.0>-<558.0,298.0>>/L<<558.0,298.0>--<440.0,96.0>> = 7.458041922399734

	* endOfMediumcontrol (U+2419): L<<373.0,96.0>--<317.0,295.0>>/B<<317.0,295.0>-<318.0,270.0>-<317.5,243.5>> = 13.426365356096166

	* perthousand (U+2030): B<<395.0,271.0>-<415.0,252.0>-<412.0,220.0>>/B<<412.0,220.0>-<420.0,252.0>-<446.5,271.0>> = 8.680418425071275

	* perthousand (U+2030): B<<405.5,14.0>-<385.0,33.0>-<388.0,65.0>>/B<<388.0,65.0>-<380.0,33.0>-<353.5,14.0>> = 8.680418425071275

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<365.0,279.0>-<368.0,276.0>-<370.0,275.0>>/L<<370.0,275.0>--<365.0,279.0>> = 12.094757077012058

	* petapp.minimal (U+E007): B<<402.0,358.0>-<402.0,357.0>-<401.0,355.0>>/L<<401.0,355.0>--<402.0,358.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>>/L<<437.0,404.0>--<440.0,406.0>> = 7.125016348901757

	* petapp.minimal (U+E007): B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>>/L<<442.0,407.0>--<447.0,409.0>> = 4.763641690726143

	* petapp.minimal (U+E007): B<<468.0,415.0>-<467.0,415.0>-<465.0,414.0>>/L<<465.0,414.0>--<468.0,415.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>>/L<<467.0,106.0>--<469.0,103.0>> = 11.309932474020195

	* petapp.minimal (U+E007): B<<484.5,8.5>-<484.0,4.0>-<483.0,0.0>>/B<<483.0,0.0>-<483.0,3.0>-<483.0,6.5>> = 14.036243467926484

	* petapp.minimal (U+E007): L<<408.0,166.0>--<411.0,165.0>>/B<<411.0,165.0>-<409.0,166.0>-<408.0,166.5>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<413.0,298.0>--<412.0,301.0>>/B<<412.0,301.0>-<413.0,299.0>-<413.0,298.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<417.0,160.0>--<420.0,159.0>>/B<<420.0,159.0>-<418.0,160.0>-<417.0,160.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<437.0,404.0>--<440.0,406.0>>/B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>> = 11.309932474020227

	* petapp.minimal (U+E007): L<<442.0,407.0>--<447.0,409.0>>/B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>> = 3.3664606634297236

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<467.0,106.0>--<469.0,103.0>>/B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>> = 7.125016348901757

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<90.0,577.0>-<99.0,557.0>> = 4.969740728110289

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* trademark (U+2122): B<<430.0,655.0>-<427.0,680.0>-<424.0,700.0>>/B<<424.0,700.0>-<423.0,681.0>-<421.0,650.0>> = 11.543553114131484

	* trademark (U+2122): B<<571.5,650.0>-<579.0,681.0>-<584.0,700.0>>/B<<584.0,700.0>-<575.0,680.0>-<564.0,654.5>> = 9.484182481483423

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni01CE (U+01CE): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni0418 (U+0418): B<<154.5,166.5>-<147.0,130.0>-<141.0,105.0>>/L<<141.0,105.0>--<462.0,730.0>> = 13.689298950275678

	* uni0418 (U+0418): B<<474.0,564.5>-<482.0,601.0>-<488.0,625.0>>/L<<488.0,625.0>--<166.0,0.0>> = 13.221280231721906

	* uni0419 (U+0419): B<<154.5,166.5>-<147.0,130.0>-<141.0,105.0>>/L<<141.0,105.0>--<462.0,730.0>> = 13.689298950275678

	* uni0419 (U+0419): B<<474.0,564.5>-<482.0,601.0>-<488.0,625.0>>/L<<488.0,625.0>--<166.0,0.0>> = 13.221280231721906

	* uni041C (U+041C): B<<495.5,586.0>-<508.0,651.0>-<521.0,703.0>>/L<<521.0,703.0>--<351.0,341.0>> = 11.11912896594182

	* uni041C (U+041C): L<<263.0,344.0>--<211.0,694.0>>/B<<211.0,694.0>-<207.0,620.0>-<196.5,532.0>> = 11.544756952519174

	* uni0430 (U+0430): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni0434 (U+0434): B<<421.0,487.5>-<457.0,459.0>-<460.0,409.0>>/L<<460.0,409.0>--<468.0,458.0>> = 12.706232139650806

	* uni04E4 (U+04E4): B<<154.5,166.5>-<147.0,130.0>-<141.0,105.0>>/L<<141.0,105.0>--<462.0,730.0>> = 13.689298950275678

	* uni04E4 (U+04E4): B<<474.0,564.5>-<482.0,601.0>-<488.0,625.0>>/L<<488.0,625.0>--<166.0,0.0>> = 13.221280231721906

	* uni1EA1 (U+1EA1): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni1EA3 (U+1EA3): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni1EA5 (U+1EA5): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni1EA7 (U+1EA7): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni1EA9 (U+1EA9): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni1EAB (U+1EAB): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni1EAD (U+1EAD): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni1EAF (U+1EAF): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni1EB1 (U+1EB1): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni1EB3 (U+1EB3): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni1EB5 (U+1EB5): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni1EB7 (U+1EB7): B<<400.0,32.0>-<374.0,64.0>-<381.0,111.0>>/B<<381.0,111.0>-<362.0,56.0>-<314.5,23.0>> = 10.586559877113459

	* uni2116 (U+2116): B<<153.0,581.5>-<150.0,618.0>-<148.0,646.0>>/B<<148.0,646.0>-<146.0,618.0>-<142.5,580.5>> = 8.171233559949677

	* uni2116 (U+2116): B<<252.0,151.0>-<255.0,114.0>-<256.0,85.0>>/B<<256.0,85.0>-<259.0,114.0>-<262.0,152.0>> = 7.881075124652449

	* uni2196 (U+2196): B<<215.5,652.0>-<198.0,653.0>-<187.0,660.0>>/L<<187.0,660.0>--<553.0,294.0>> = 12.528807709151522

	* uni2197 (U+2197): L<<47.0,294.0>--<413.0,660.0>>/B<<413.0,660.0>-<403.0,653.0>-<385.0,652.0>> = 10.00797980144135

	* uni2198 (U+2198): B<<385.0,78.0>-<403.0,77.0>-<413.0,70.0>>/L<<413.0,70.0>--<47.0,436.0>> = 10.00797980144135

	* uni2199 (U+2199): L<<553.0,436.0>--<187.0,70.0>>/B<<187.0,70.0>-<198.0,77.0>-<215.5,78.0>> = 12.52880770915155

	* uni227A (U+227A): B<<381.5,369.0>-<305.0,333.0>-<212.0,327.0>>/B<<212.0,327.0>-<303.0,321.0>-<368.5,286.5>> = 7.463669595831076

	* uni227B (U+227B): B<<249.0,292.0>-<326.0,328.0>-<419.0,335.0>>/B<<419.0,335.0>-<328.0,340.0>-<262.0,374.5>> = 7.449426425206001

	* uni227C (U+227C): B<<401.5,494.0>-<325.0,458.0>-<232.0,452.0>>/B<<232.0,452.0>-<323.0,446.0>-<388.5,411.5>> = 7.463669595831076

	* uni22CE (U+22CE): B<<274.5,387.0>-<298.0,316.0>-<289.0,224.0>>/B<<289.0,224.0>-<310.0,316.0>-<357.5,387.5>> = 7.270846208793773

	* uni234B (U+234B): L<<276.0,80.0>--<276.0,547.0>>/L<<276.0,547.0>--<162.0,80.0>> = 13.718258047264216

	* uni234B (U+234B): L<<439.0,80.0>--<324.0,546.0>>/L<<324.0,546.0>--<324.0,80.0>> = 13.862532692910552

	* uni2352 (U+2352): L<<162.0,650.0>--<280.0,179.0>>/L<<280.0,179.0>--<276.0,650.0>> = 13.578286072669737

	* uni2352 (U+2352): L<<324.0,650.0>--<324.0,179.0>>/L<<324.0,179.0>--<438.0,650.0>> = 13.606103054249314

	* uni236C (U+236C): L<<218.0,530.0>--<196.0,392.0>>/B<<196.0,392.0>-<221.0,457.0>-<272.0,457.0>> = 11.97962289680413

	* uni236C (U+236C): L<<410.0,200.0>--<435.0,356.0>>/B<<435.0,356.0>-<410.0,287.0>-<357.0,287.0>> = 10.81180512840688

	* uni26A1 (U+26A1): L<<580.0,440.0>--<50.0,-110.0>>/L<<50.0,-110.0>--<295.0,310.0>> = 13.68265114620652

	* uniFF5B (U+FF5B): B<<372.5,405.5>-<334.0,370.0>-<257.0,363.0>>/B<<257.0,363.0>-<331.0,356.0>-<358.0,317.0>> = 10.5982202679845

	* w (U+0077): B<<143.0,113.5>-<142.0,87.0>-<140.0,70.0>>/B<<140.0,70.0>-<145.0,87.0>-<152.0,113.5>> = 9.679703526277825

	* w (U+0077): B<<330.5,439.5>-<332.0,471.0>-<333.0,488.0>>/B<<333.0,488.0>-<329.0,471.0>-<320.0,439.5>> = 9.87405925175738

	* w (U+0077): B<<393.5,113.5>-<393.0,87.0>-<391.0,70.0>>/B<<391.0,70.0>-<396.0,87.0>-<403.0,113.5>> = 9.679703526277825

	* wacute (U+1E83): B<<143.0,113.5>-<142.0,87.0>-<140.0,70.0>>/B<<140.0,70.0>-<145.0,87.0>-<152.0,113.5>> = 9.679703526277825

	* wacute (U+1E83): B<<330.5,439.5>-<332.0,471.0>-<333.0,488.0>>/B<<333.0,488.0>-<329.0,471.0>-<320.0,439.5>> = 9.87405925175738

	* wacute (U+1E83): B<<393.5,113.5>-<393.0,87.0>-<391.0,70.0>>/B<<391.0,70.0>-<396.0,87.0>-<403.0,113.5>> = 9.679703526277825

	* wcircumflex (U+0175): B<<143.0,113.5>-<142.0,87.0>-<140.0,70.0>>/B<<140.0,70.0>-<145.0,87.0>-<152.0,113.5>> = 9.679703526277825

	* wcircumflex (U+0175): B<<330.5,439.5>-<332.0,471.0>-<333.0,488.0>>/B<<333.0,488.0>-<329.0,471.0>-<320.0,439.5>> = 9.87405925175738

	* wcircumflex (U+0175): B<<393.5,113.5>-<393.0,87.0>-<391.0,70.0>>/B<<391.0,70.0>-<396.0,87.0>-<403.0,113.5>> = 9.679703526277825

	* wdieresis (U+1E85): B<<143.0,113.5>-<142.0,87.0>-<140.0,70.0>>/B<<140.0,70.0>-<145.0,87.0>-<152.0,113.5>> = 9.679703526277825

	* wdieresis (U+1E85): B<<330.5,439.5>-<332.0,471.0>-<333.0,488.0>>/B<<333.0,488.0>-<329.0,471.0>-<320.0,439.5>> = 9.87405925175738

	* wdieresis (U+1E85): B<<393.5,113.5>-<393.0,87.0>-<391.0,70.0>>/B<<391.0,70.0>-<396.0,87.0>-<403.0,113.5>> = 9.679703526277825

	* wgrave (U+1E81): B<<143.0,113.5>-<142.0,87.0>-<140.0,70.0>>/B<<140.0,70.0>-<145.0,87.0>-<152.0,113.5>> = 9.679703526277825

	* wgrave (U+1E81): B<<330.5,439.5>-<332.0,471.0>-<333.0,488.0>>/B<<333.0,488.0>-<329.0,471.0>-<320.0,439.5>> = 9.87405925175738 

	* wgrave (U+1E81): B<<393.5,113.5>-<393.0,87.0>-<391.0,70.0>>/B<<391.0,70.0>-<396.0,87.0>-<403.0,113.5>> = 9.679703526277825 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[19] PitagonSansMono-ExtraLightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Pitagon Sans Mono ExtraLight' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, exclam_equal_equal.liga.ss19.001, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- dollar.cv14

	- eight.dnom

	- eight.numr

	- exclam_equal.liga.ss19.001

	- exclam_equal_equal.liga.ss19.001

	- five.dnom

	- five.numr

	- four.dnom

	- four.numr

	- nine.dnom

	- nine.numr

	- one.dnom

	- one.numr

	- seven.dnom

	- seven.numr

	- six.dnom

	- six.numr

	- three.dnom

	- three.numr

	- two.dnom

	- two.numr

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- zero.dnom 

	- zero.numr
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: uni2288	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: uni2288	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1697 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.06%) have a different width. You should check the widths of: ['uniFF5D'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* four (U+0034): X=428.0,Y=729.0 (should be at cap-height 730?)

	* four (U+0034): X=505.0,Y=729.0 (should be at cap-height 730?)

	* section (U+00A7): X=404.0,Y=1.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=617.0,Y=731.0 (should be at cap-height 730?)

	* acircumflex (U+00E2): X=369.0,Y=731.0 (should be at cap-height 730?)

	* ecircumflex (U+00EA): X=364.0,Y=731.0 (should be at cap-height 730?)

	* icircumflex (U+00EE): X=379.0,Y=731.0 (should be at cap-height 730?)

	* ocircumflex (U+00F4): X=364.0,Y=731.0 (should be at cap-height 730?)

	* ucircumflex (U+00FB): X=364.0,Y=731.0 (should be at cap-height 730?)

	* ccircumflex (U+0109): X=373.0,Y=731.0 (should be at cap-height 730?)

	* gcircumflex (U+011D): X=361.0,Y=731.0 (should be at cap-height 730?)

	* jcircumflex (U+0135): X=444.0,Y=731.0 (should be at cap-height 730?)

	* scircumflex (U+015D): X=364.0,Y=731.0 (should be at cap-height 730?)

	* uni0162 (U+0162): X=235.0,Y=1.0 (should be at baseline 0?)

	* uni0162 (U+0162): X=284.0,Y=2.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=349.0,Y=2.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=364.0,Y=731.0 (should be at cap-height 730?)

	* ycircumflex (U+0177): X=364.0,Y=731.0 (should be at cap-height 730?)

	* uni01EA (U+01EA): X=349.0,Y=2.0 (should be at baseline 0?)

	* Oslashacute (U+01FE): X=617.0,Y=731.0 (should be at cap-height 730?)

	* circumflex (U+02C6): X=365.0,Y=731.0 (should be at cap-height 730?)

	* uni0302 (U+0302): X=-235.0,Y=731.0 (should be at cap-height 730?)

	* xi (U+03BE): X=380.0,Y=-1.0 (should be at baseline 0?)

	* uni03C2 (U+03C2): X=329.0,Y=-1.0 (should be at baseline 0?)

	* uni1EA5 (U+1EA5): X=368.0,Y=731.0 (should be at cap-height 730?)

	* uni1EA7 (U+1EA7): X=368.0,Y=731.0 (should be at cap-height 730?)

	* uni1EA9 (U+1EA9): X=368.0,Y=731.0 (should be at cap-height 730?)

	* uni1EAB (U+1EAB): X=369.0,Y=731.0 (should be at cap-height 730?)

	* uni1EAD (U+1EAD): X=369.0,Y=731.0 (should be at cap-height 730?)

	* uni1EBF (U+1EBF): X=363.0,Y=731.0 (should be at cap-height 730?)

	* uni1EC1 (U+1EC1): X=363.0,Y=731.0 (should be at cap-height 730?)

	* uni1EC3 (U+1EC3): X=363.0,Y=731.0 (should be at cap-height 730?)

	* uni1EC5 (U+1EC5): X=364.0,Y=731.0 (should be at cap-height 730?)

	* uni1EC7 (U+1EC7): X=364.0,Y=731.0 (should be at cap-height 730?)

	* uni1ED1 (U+1ED1): X=363.0,Y=731.0 (should be at cap-height 730?)

	* uni1ED3 (U+1ED3): X=363.0,Y=731.0 (should be at cap-height 730?)

	* uni1ED5 (U+1ED5): X=363.0,Y=731.0 (should be at cap-height 730?)

	* uni1ED7 (U+1ED7): X=364.0,Y=731.0 (should be at cap-height 730?)

	* uni1ED9 (U+1ED9): X=364.0,Y=731.0 (should be at cap-height 730?)

	* quotesinglbase (U+201A): X=254.5,Y=1.5 (should be at baseline 0?)

	* quotedblbase (U+201E): X=145.5,Y=1.5 (should be at baseline 0?)

	* quotedblbase (U+201E): X=380.5,Y=1.5 (should be at baseline 0?)

	* uni2085 (U+2085): X=102.0,Y=-1.0 (should be at baseline 0?)

	* uni2085 (U+2085): X=157.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=331.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=269.0,Y=-1.0 (should be at baseline 0?)

	* uni21DF (U+21DF): X=269.0,Y=731.0 (should be at cap-height 730?)

	* uni21DF (U+21DF): X=331.0,Y=731.0 (should be at cap-height 730?)

	* uni21E7 (U+21E7): X=301.0,Y=729.0 (should be at cap-height 730?)

	* uni21EA (U+21EA): X=300.0,Y=728.0 (should be at cap-height 730?)

	* uni225F (U+225F): X=402.0,Y=729.0 (should be at cap-height 730?)

	* uni225F (U+225F): X=272.0,Y=729.0 (should be at cap-height 730?)

	* uni2273 (U+2273): X=356.0,Y=-2.0 (should be at baseline 0?)

	* pitagon (U+E000): X=158.0,Y=2.0 (should be at baseline 0?)

	* piads (U+E001): X=158.0,Y=2.0 (should be at baseline 0?)

	* pioffice (U+E002): X=158.0,Y=2.0 (should be at baseline 0?)

	* pitagram (U+E003): X=158.0,Y=2.0 (should be at baseline 0?)

	* piweb (U+E004): X=158.0,Y=2.0 (should be at baseline 0?)

	* pisign (U+E005): X=158.0,Y=2.0 (should be at baseline 0?)

	* petapp (U+E006): X=534.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=303.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=293.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=318.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=336.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=331.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=328.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=326.0,Y=1.5 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=278.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=274.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=272.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?) 

	* picall (U+E009): X=158.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): L<<272.0,339.0>--<204.0,701.0>>/B<<204.0,701.0>-<201.0,647.0>-<191.5,567.5>> = 13.818596729370949

	* Mu (U+039C): L<<272.0,339.0>--<204.0,701.0>>/B<<204.0,701.0>-<201.0,647.0>-<191.5,567.5>> = 13.818596729370949

	* W (U+0057): B<<136.5,118.5>-<134.0,76.0>-<131.0,47.0>>/B<<131.0,47.0>-<137.0,66.0>-<144.0,92.0>> = 11.61942725995233

	* W (U+0057): B<<362.5,615.0>-<365.0,656.0>-<366.0,681.0>>/B<<366.0,681.0>-<359.0,656.0>-<348.5,615.5>> = 13.351636414570187

	* Wacute (U+1E82): B<<136.5,118.5>-<134.0,76.0>-<131.0,47.0>>/B<<131.0,47.0>-<137.0,66.0>-<144.0,92.0>> = 11.61942725995233

	* Wacute (U+1E82): B<<362.5,615.0>-<365.0,656.0>-<366.0,681.0>>/B<<366.0,681.0>-<359.0,656.0>-<348.5,615.5>> = 13.351636414570187

	* Wcircumflex (U+0174): B<<136.5,118.5>-<134.0,76.0>-<131.0,47.0>>/B<<131.0,47.0>-<137.0,66.0>-<144.0,92.0>> = 11.61942725995233

	* Wcircumflex (U+0174): B<<362.5,615.0>-<365.0,656.0>-<366.0,681.0>>/B<<366.0,681.0>-<359.0,656.0>-<348.5,615.5>> = 13.351636414570187

	* Wdieresis (U+1E84): B<<136.5,118.5>-<134.0,76.0>-<131.0,47.0>>/B<<131.0,47.0>-<137.0,66.0>-<144.0,92.0>> = 11.61942725995233

	* Wdieresis (U+1E84): B<<362.5,615.0>-<365.0,656.0>-<366.0,681.0>>/B<<366.0,681.0>-<359.0,656.0>-<348.5,615.5>> = 13.351636414570187

	* Wgrave (U+1E80): B<<136.5,118.5>-<134.0,76.0>-<131.0,47.0>>/B<<131.0,47.0>-<137.0,66.0>-<144.0,92.0>> = 11.61942725995233

	* Wgrave (U+1E80): B<<362.5,615.0>-<365.0,656.0>-<366.0,681.0>>/B<<366.0,681.0>-<359.0,656.0>-<348.5,615.5>> = 13.351636414570187

	* a (U+0061): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* aacute (U+00E1): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* abreve (U+0103): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* acircumflex (U+00E2): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* adieresis (U+00E4): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* agrave (U+00E0): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* alpha (U+03B1): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* alphatonos (U+03AC): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* amacron (U+0101): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* aogonek (U+0105): B<<397.5,44.0>-<384.0,71.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.173489138541147

	* aring (U+00E5): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* atilde (U+00E3): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* b (U+0062): L<<216.0,576.0>--<197.0,462.0>>/B<<197.0,462.0>-<217.0,508.0>-<261.0,534.0>> = 14.036243467926457

	* dcaron (U+010F): L<<344.0,0.0>--<357.0,83.0>>/B<<357.0,83.0>-<338.0,38.0>-<298.0,14.0>> = 13.988835623356287

	* endOfMediumcontrol (U+2419): B<<538.5,214.0>-<548.0,265.0>-<562.0,303.0>>/L<<562.0,303.0>--<431.0,96.0>> = 12.10282463250833

	* eng (U+014B): L<<210.0,533.0>--<197.0,451.0>>/B<<197.0,451.0>-<216.0,502.0>-<260.0,531.0>> = 11.424324937373473

	* eta (U+03B7): L<<209.0,533.0>--<196.0,454.0>>/B<<196.0,454.0>-<216.0,504.0>-<260.0,532.0>> = 12.456737584252155

	* etatonos (U+03AE): L<<209.0,533.0>--<196.0,454.0>>/B<<196.0,454.0>-<216.0,504.0>-<260.0,532.0>> = 12.456737584252155

	* g (U+0067): B<<420.0,532.0>-<455.0,504.0>-<459.0,455.0>>/L<<459.0,455.0>--<472.0,536.0>> = 13.784721125234766

	* gbreve (U+011F): B<<420.0,532.0>-<455.0,504.0>-<459.0,455.0>>/L<<459.0,455.0>--<472.0,536.0>> = 13.784721125234766

	* gcaron (U+01E7): B<<420.0,532.0>-<455.0,504.0>-<459.0,455.0>>/L<<459.0,455.0>--<472.0,536.0>> = 13.784721125234766

	* gcircumflex (U+011D): B<<420.0,532.0>-<455.0,504.0>-<459.0,455.0>>/L<<459.0,455.0>--<472.0,536.0>> = 13.784721125234766

	* gdotaccent (U+0121): B<<420.0,532.0>-<455.0,504.0>-<459.0,455.0>>/L<<459.0,455.0>--<472.0,536.0>> = 13.784721125234766

	* n (U+006E): L<<209.0,533.0>--<196.0,454.0>>/B<<196.0,454.0>-<216.0,504.0>-<260.0,532.0>> = 12.456737584252155

	* nacute (U+0144): L<<209.0,533.0>--<196.0,454.0>>/B<<196.0,454.0>-<216.0,504.0>-<260.0,532.0>> = 12.456737584252155

	* napostrophe (U+0149): L<<209.0,533.0>--<196.0,454.0>>/B<<196.0,454.0>-<216.0,504.0>-<260.0,532.0>> = 12.456737584252155

	* ncaron (U+0148): L<<209.0,533.0>--<196.0,454.0>>/B<<196.0,454.0>-<216.0,504.0>-<260.0,532.0>> = 12.456737584252155

	* ntilde (U+00F1): L<<209.0,533.0>--<196.0,454.0>>/B<<196.0,454.0>-<216.0,504.0>-<260.0,532.0>> = 12.456737584252155

	* omega (U+03C9): B<<294.5,18.0>-<269.0,46.0>-<271.0,94.0>>/B<<271.0,94.0>-<257.0,44.0>-<223.5,17.0>> = 13.25630242681988

	* omegatonos (U+03CE): B<<294.5,18.0>-<269.0,46.0>-<271.0,94.0>>/B<<271.0,94.0>-<257.0,44.0>-<223.5,17.0>> = 13.25630242681988

	* perthousand (U+2030): B<<395.5,271.0>-<416.0,252.0>-<413.0,221.0>>/B<<413.0,221.0>-<421.0,252.0>-<447.0,271.0>> = 8.942753948409665

	* perthousand (U+2030): B<<406.0,14.0>-<386.0,33.0>-<389.0,64.0>>/B<<389.0,64.0>-<380.0,33.0>-<353.5,14.0>> = 10.661666105370736

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<364.0,279.0>-<367.0,276.0>-<370.0,274.0>>/L<<370.0,274.0>--<364.0,279.0>> = 6.115503566285384

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<482.0,68.0>-<482.0,69.0>-<481.0,71.0>>/L<<481.0,71.0>--<482.0,68.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<404.0,317.0>--<403.0,320.0>>/B<<403.0,320.0>-<404.0,318.0>-<404.0,317.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<89.0,577.0>-<98.5,557.0>> = 2.4895529219991284

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* q (U+0071): L<<383.0,-26.0>--<402.0,87.0>>/B<<402.0,87.0>-<382.0,40.0>-<338.5,15.0>> = 13.506775350914868

	* r (U+0072): L<<231.0,533.0>--<218.0,456.0>>/B<<218.0,456.0>-<239.0,504.0>-<281.5,532.0>> = 14.046433007124216

	* racute (U+0155): L<<231.0,533.0>--<218.0,456.0>>/B<<218.0,456.0>-<239.0,504.0>-<281.5,532.0>> = 14.046433007124216

	* rcaron (U+0159): L<<231.0,533.0>--<218.0,456.0>>/B<<218.0,456.0>-<239.0,504.0>-<281.5,532.0>> = 14.046433007124216

	* thorn (U+00FE): L<<214.0,576.0>--<195.0,462.0>>/B<<195.0,462.0>-<215.0,508.0>-<259.0,534.0>> = 14.036243467926457

	* trademark (U+2122): B<<576.0,652.0>-<583.0,684.0>-<588.0,706.0>>/B<<588.0,706.0>-<579.0,687.0>-<566.0,660.5>> = 12.541909876659929

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni00B5 (U+00B5): B<<172.0,16.0>-<143.0,42.0>-<139.0,86.0>>/L<<139.0,86.0>--<125.0,-8.0>> = 13.665573540749627

	* uni0123 (U+0123): B<<420.0,532.0>-<455.0,504.0>-<459.0,455.0>>/L<<459.0,455.0>--<472.0,536.0>> = 13.784721125234766

	* uni0146 (U+0146): L<<209.0,533.0>--<196.0,454.0>>/B<<196.0,454.0>-<216.0,504.0>-<260.0,532.0>> = 12.456737584252155

	* uni0157 (U+0157): L<<231.0,533.0>--<218.0,456.0>>/B<<218.0,456.0>-<239.0,504.0>-<281.5,532.0>> = 14.046433007124216

	* uni01CE (U+01CE): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni01F5 (U+01F5): B<<420.0,532.0>-<455.0,504.0>-<459.0,455.0>>/L<<459.0,455.0>--<472.0,536.0>> = 13.784721125234766

	* uni03BC (U+03BC): B<<172.0,16.0>-<143.0,42.0>-<139.0,86.0>>/L<<139.0,86.0>--<125.0,-8.0>> = 13.665573540749627

	* uni0418 (U+0418): B<<142.0,141.5>-<134.0,98.0>-<128.0,75.0>>/L<<128.0,75.0>--<481.0,730.0>> = 13.700743156213651

	* uni0419 (U+0419): B<<142.0,141.5>-<134.0,98.0>-<128.0,75.0>>/L<<128.0,75.0>--<481.0,730.0>> = 13.700743156213651

	* uni041C (U+041C): L<<272.0,339.0>--<204.0,701.0>>/B<<204.0,701.0>-<201.0,647.0>-<191.5,567.5>> = 13.818596729370949

	* uni0430 (U+0430): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni0431 (U+0431): L<<183.0,468.0>--<173.0,400.0>>/B<<173.0,400.0>-<192.0,453.0>-<237.0,481.0>> = 11.356391640414433

	* uni0434 (U+0434): B<<427.5,478.5>-<464.0,448.0>-<466.0,395.0>>/L<<466.0,395.0>--<477.0,468.0>> = 10.730221368064038

	* uni04E4 (U+04E4): B<<142.0,141.5>-<134.0,98.0>-<128.0,75.0>>/L<<128.0,75.0>--<481.0,730.0>> = 13.700743156213651

	* uni1EA1 (U+1EA1): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni1EA3 (U+1EA3): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni1EA5 (U+1EA5): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni1EA7 (U+1EA7): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni1EA9 (U+1EA9): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni1EAB (U+1EAB): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni1EAD (U+1EAD): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni1EAF (U+1EAF): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni1EB1 (U+1EB1): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni1EB3 (U+1EB3): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni1EB5 (U+1EB5): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni1EB7 (U+1EB7): B<<406.5,30.5>-<383.0,61.0>-<390.0,108.0>>/B<<390.0,108.0>-<371.0,54.0>-<324.5,22.0>> = 10.913371046342982

	* uni2116 (U+2116): B<<151.5,608.5>-<149.0,638.0>-<147.0,660.0>>/B<<147.0,660.0>-<145.0,632.0>-<139.5,587.0>> = 9.28004568770961

	* uni2116 (U+2116): B<<252.5,118.5>-<255.0,90.0>-<256.0,69.0>>/B<<256.0,69.0>-<258.0,99.0>-<263.0,144.0>> = 6.540385828196569

	* uni227A (U+227A): B<<375.5,369.5>-<298.0,334.0>-<204.0,328.0>>/B<<204.0,328.0>-<296.0,322.0>-<362.0,287.0>> = 7.38361977946671

	* uni227B (U+227B): B<<256.5,290.0>-<334.0,326.0>-<428.0,333.0>>/B<<428.0,333.0>-<336.0,339.0>-<269.5,373.5>> = 7.990243121330726

	* uni227C (U+227C): B<<395.5,494.5>-<318.0,459.0>-<224.0,453.0>>/B<<224.0,453.0>-<316.0,447.0>-<382.0,412.0>> = 7.38361977946671

	* uni22CE (U+22CE): B<<273.5,383.5>-<297.0,312.0>-<288.0,219.0>>/B<<288.0,219.0>-<309.0,312.0>-<356.5,383.5>> = 7.1968155337661655

	* uni236C (U+236C): L<<205.0,536.0>--<184.0,402.0>>/B<<184.0,402.0>-<207.0,456.0>-<258.0,456.0>> = 14.163668066044865

	* uni236C (U+236C): L<<423.0,194.0>--<446.0,344.0>>/B<<446.0,344.0>-<423.0,288.0>-<371.0,288.0>> = 13.611199413419484

	* uni26A1 (U+26A1): L<<580.0,440.0>--<50.0,-110.0>>/L<<50.0,-110.0>--<295.0,310.0>> = 13.68265114620652

	* w (U+0077): B<<144.0,149.0>-<143.0,86.0>-<139.0,49.0>>/B<<139.0,49.0>-<144.0,68.0>-<151.5,93.0>> = 8.573387741441062

	* w (U+0077): B<<334.5,446.5>-<334.0,479.0>-<335.0,499.0>>/B<<335.0,499.0>-<331.0,479.0>-<320.5,446.5>> = 8.447527247908404

	* w (U+0077): B<<390.0,94.5>-<390.0,69.0>-<389.0,49.0>>/B<<389.0,49.0>-<393.0,69.0>-<399.5,94.5>> = 8.447527247908404

	* wacute (U+1E83): B<<144.0,149.0>-<143.0,86.0>-<139.0,49.0>>/B<<139.0,49.0>-<144.0,68.0>-<151.5,93.0>> = 8.573387741441062

	* wacute (U+1E83): B<<334.5,446.5>-<334.0,479.0>-<335.0,499.0>>/B<<335.0,499.0>-<331.0,479.0>-<320.5,446.5>> = 8.447527247908404

	* wacute (U+1E83): B<<390.0,94.5>-<390.0,69.0>-<389.0,49.0>>/B<<389.0,49.0>-<393.0,69.0>-<399.5,94.5>> = 8.447527247908404

	* wcircumflex (U+0175): B<<144.0,149.0>-<143.0,86.0>-<139.0,49.0>>/B<<139.0,49.0>-<144.0,68.0>-<151.5,93.0>> = 8.573387741441062

	* wcircumflex (U+0175): B<<334.5,446.5>-<334.0,479.0>-<335.0,499.0>>/B<<335.0,499.0>-<331.0,479.0>-<320.5,446.5>> = 8.447527247908404

	* wcircumflex (U+0175): B<<390.0,94.5>-<390.0,69.0>-<389.0,49.0>>/B<<389.0,49.0>-<393.0,69.0>-<399.5,94.5>> = 8.447527247908404

	* wdieresis (U+1E85): B<<144.0,149.0>-<143.0,86.0>-<139.0,49.0>>/B<<139.0,49.0>-<144.0,68.0>-<151.5,93.0>> = 8.573387741441062

	* wdieresis (U+1E85): B<<334.5,446.5>-<334.0,479.0>-<335.0,499.0>>/B<<335.0,499.0>-<331.0,479.0>-<320.5,446.5>> = 8.447527247908404

	* wdieresis (U+1E85): B<<390.0,94.5>-<390.0,69.0>-<389.0,49.0>>/B<<389.0,49.0>-<393.0,69.0>-<399.5,94.5>> = 8.447527247908404

	* wgrave (U+1E81): B<<144.0,149.0>-<143.0,86.0>-<139.0,49.0>>/B<<139.0,49.0>-<144.0,68.0>-<151.5,93.0>> = 8.573387741441062

	* wgrave (U+1E81): B<<334.5,446.5>-<334.0,479.0>-<335.0,499.0>>/B<<335.0,499.0>-<331.0,479.0>-<320.5,446.5>> = 8.447527247908404 

	* wgrave (U+1E81): B<<390.0,94.5>-<390.0,69.0>-<389.0,49.0>>/B<<389.0,49.0>-<393.0,69.0>-<399.5,94.5>> = 8.447527247908404 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[19] PitagonSansMono-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Pitagon Sans Mono ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- uni2070.zero

	- uni2080.zero

	- zero.dnom.zero 

	- zero.numr.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1710 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.06%) have a different width. You should check the widths of: ['uniFF5D'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): L<<263.0,338.0>--<137.0,701.0>>/B<<137.0,701.0>-<142.0,647.0>-<145.0,567.5>> = 13.852186986094962

	* Mu (U+039C): L<<263.0,338.0>--<137.0,701.0>>/B<<137.0,701.0>-<142.0,647.0>-<145.0,567.5>> = 13.852186986094962

	* W (U+0057): B<<164.0,118.5>-<168.0,76.0>-<170.0,47.0>>/B<<170.0,47.0>-<174.0,76.0>-<178.5,118.5>> = 11.798499531015755

	* W (U+0057): B<<309.0,615.0>-<305.0,656.0>-<303.0,681.0>>/B<<303.0,681.0>-<299.0,656.0>-<295.0,615.5>> = 13.664198180723144

	* W (U+0057): B<<422.5,118.5>-<427.0,76.0>-<431.0,47.0>>/B<<431.0,47.0>-<433.0,66.0>-<436.0,92.0>> = 13.862319259472695

	* Wacute (U+1E82): B<<164.0,118.5>-<168.0,76.0>-<170.0,47.0>>/B<<170.0,47.0>-<174.0,76.0>-<178.5,118.5>> = 11.798499531015755

	* Wacute (U+1E82): B<<309.0,615.0>-<305.0,656.0>-<303.0,681.0>>/B<<303.0,681.0>-<299.0,656.0>-<295.0,615.5>> = 13.664198180723144

	* Wacute (U+1E82): B<<422.5,118.5>-<427.0,76.0>-<431.0,47.0>>/B<<431.0,47.0>-<433.0,66.0>-<436.0,92.0>> = 13.862319259472695

	* Wcircumflex (U+0174): B<<164.0,118.5>-<168.0,76.0>-<170.0,47.0>>/B<<170.0,47.0>-<174.0,76.0>-<178.5,118.5>> = 11.798499531015755

	* Wcircumflex (U+0174): B<<309.0,615.0>-<305.0,656.0>-<303.0,681.0>>/B<<303.0,681.0>-<299.0,656.0>-<295.0,615.5>> = 13.664198180723144

	* Wcircumflex (U+0174): B<<422.5,118.5>-<427.0,76.0>-<431.0,47.0>>/B<<431.0,47.0>-<433.0,66.0>-<436.0,92.0>> = 13.862319259472695

	* Wdieresis (U+1E84): B<<164.0,118.5>-<168.0,76.0>-<170.0,47.0>>/B<<170.0,47.0>-<174.0,76.0>-<178.5,118.5>> = 11.798499531015755

	* Wdieresis (U+1E84): B<<309.0,615.0>-<305.0,656.0>-<303.0,681.0>>/B<<303.0,681.0>-<299.0,656.0>-<295.0,615.5>> = 13.664198180723144

	* Wdieresis (U+1E84): B<<422.5,118.5>-<427.0,76.0>-<431.0,47.0>>/B<<431.0,47.0>-<433.0,66.0>-<436.0,92.0>> = 13.862319259472695

	* Wgrave (U+1E80): B<<164.0,118.5>-<168.0,76.0>-<170.0,47.0>>/B<<170.0,47.0>-<174.0,76.0>-<178.5,118.5>> = 11.798499531015755

	* Wgrave (U+1E80): B<<309.0,615.0>-<305.0,656.0>-<303.0,681.0>>/B<<303.0,681.0>-<299.0,656.0>-<295.0,615.5>> = 13.664198180723144

	* Wgrave (U+1E80): B<<422.5,118.5>-<427.0,76.0>-<431.0,47.0>>/B<<431.0,47.0>-<433.0,66.0>-<436.0,92.0>> = 13.862319259472695

	* endOfMediumcontrol (U+2419): B<<513.5,214.0>-<515.0,265.0>-<524.0,303.0>>/L<<524.0,303.0>--<430.0,107.0>> = 12.297464682716209

	* endOfMediumcontrol (U+2419): L<<370.0,107.0>--<276.0,300.0>>/B<<276.0,300.0>-<284.0,262.0>-<286.5,217.0>> = 14.079583686220822

	* eng (U+014B): L<<170.0,535.0>--<170.0,452.0>>/B<<170.0,452.0>-<181.0,503.0>-<220.0,531.5>> = 12.171458208587458

	* eta (U+03B7): L<<169.0,535.0>--<169.0,455.0>>/B<<169.0,455.0>-<181.0,504.0>-<220.0,532.0>> = 13.760785111791225

	* etatonos (U+03AE): L<<169.0,535.0>--<169.0,455.0>>/B<<169.0,455.0>-<181.0,504.0>-<220.0,532.0>> = 13.760785111791225

	* g (U+0067): B<<380.0,532.0>-<420.0,504.0>-<431.0,455.0>>/L<<431.0,455.0>--<431.0,550.0>> = 12.652556500557967

	* gbreve (U+011F): B<<380.0,532.0>-<420.0,504.0>-<431.0,455.0>>/L<<431.0,455.0>--<431.0,550.0>> = 12.652556500557967

	* gcaron (U+01E7): B<<380.0,532.0>-<420.0,504.0>-<431.0,455.0>>/L<<431.0,455.0>--<431.0,550.0>> = 12.652556500557967

	* gcircumflex (U+011D): B<<380.0,532.0>-<420.0,504.0>-<431.0,455.0>>/L<<431.0,455.0>--<431.0,550.0>> = 12.652556500557967

	* gdotaccent (U+0121): B<<380.0,532.0>-<420.0,504.0>-<431.0,455.0>>/L<<431.0,455.0>--<431.0,550.0>> = 12.652556500557967

	* h (U+0068): L<<169.0,730.0>--<169.0,454.0>>/B<<169.0,454.0>-<180.0,504.0>-<220.0,532.0>> = 12.407418527400745

	* hcircumflex (U+0125): L<<169.0,730.0>--<169.0,454.0>>/B<<169.0,454.0>-<180.0,504.0>-<220.0,532.0>> = 12.407418527400745

	* n (U+006E): L<<169.0,535.0>--<169.0,455.0>>/B<<169.0,455.0>-<181.0,504.0>-<220.0,532.0>> = 13.760785111791225

	* nacute (U+0144): L<<169.0,535.0>--<169.0,455.0>>/B<<169.0,455.0>-<181.0,504.0>-<220.0,532.0>> = 13.760785111791225

	* napostrophe (U+0149): L<<169.0,535.0>--<169.0,455.0>>/B<<169.0,455.0>-<181.0,504.0>-<220.0,532.0>> = 13.760785111791225

	* ncaron (U+0148): L<<169.0,535.0>--<169.0,455.0>>/B<<169.0,455.0>-<181.0,504.0>-<220.0,532.0>> = 13.760785111791225

	* ntilde (U+00F1): L<<169.0,535.0>--<169.0,455.0>>/B<<169.0,455.0>-<181.0,504.0>-<220.0,532.0>> = 13.760785111791225

	* omega (U+03C9): B<<336.0,18.0>-<306.0,46.0>-<300.0,94.0>>/B<<300.0,94.0>-<294.0,46.0>-<264.0,18.0>> = 14.25003269780357

	* omegatonos (U+03CE): B<<336.0,18.0>-<306.0,46.0>-<300.0,94.0>>/B<<300.0,94.0>-<294.0,46.0>-<264.0,18.0>> = 14.25003269780357

	* perthousand (U+2030): B<<406.0,271.0>-<429.0,252.0>-<432.0,221.0>>/B<<432.0,221.0>-<435.0,252.0>-<458.0,271.0>> = 11.055080303312293

	* perthousand (U+2030): B<<457.0,14.0>-<434.0,33.0>-<433.0,64.0>>/B<<433.0,64.0>-<429.0,33.0>-<405.5,14.0>> = 9.199989625886975

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<364.0,279.0>-<367.0,276.0>-<370.0,274.0>>/L<<370.0,274.0>--<364.0,279.0>> = 6.115503566285384

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<482.0,68.0>-<482.0,69.0>-<481.0,71.0>>/L<<481.0,71.0>--<482.0,68.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<404.0,317.0>--<403.0,320.0>>/B<<403.0,320.0>-<404.0,318.0>-<404.0,317.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<89.0,577.0>-<98.5,557.0>> = 2.4895529219991284

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni0123 (U+0123): B<<380.0,532.0>-<420.0,504.0>-<431.0,455.0>>/L<<431.0,455.0>--<431.0,550.0>> = 12.652556500557967

	* uni0146 (U+0146): L<<169.0,535.0>--<169.0,455.0>>/B<<169.0,455.0>-<181.0,504.0>-<220.0,532.0>> = 13.760785111791225

	* uni01F5 (U+01F5): B<<380.0,532.0>-<420.0,504.0>-<431.0,455.0>>/L<<431.0,455.0>--<431.0,550.0>> = 12.652556500557967

	* uni041C (U+041C): L<<263.0,338.0>--<137.0,701.0>>/B<<137.0,701.0>-<142.0,647.0>-<145.0,567.5>> = 13.852186986094962

	* uni0431 (U+0431): L<<153.0,468.0>--<153.0,397.0>>/B<<153.0,397.0>-<164.0,449.0>-<205.5,479.0>> = 11.944177188446329

	* uni2116 (U+2116): B<<278.0,118.5>-<285.0,90.0>-<289.0,69.0>>/B<<289.0,69.0>-<287.0,99.0>-<284.5,144.0>> = 6.970223033272254

	* uni2116 (U+2116): B<<99.5,608.5>-<92.0,638.0>-<87.0,660.0>>/B<<87.0,660.0>-<89.0,632.0>-<90.5,587.0>> = 8.718649285311828

	* uni227A (U+227A): B<<346.0,373.5>-<274.0,339.0>-<181.0,333.0>>/B<<181.0,333.0>-<274.0,326.0>-<346.0,290.0>> = 7.9958549469592395

	* uni227B (U+227B): B<<254.0,290.5>-<326.0,327.0>-<419.0,333.0>>/B<<419.0,333.0>-<326.0,339.0>-<254.0,373.5>> = 7.382771972902524

	* uni227C (U+227C): B<<346.0,498.5>-<274.0,464.0>-<181.0,458.0>>/B<<181.0,458.0>-<274.0,451.0>-<346.0,415.0>> = 7.9958549469592395

	* uni22CE (U+22CE): B<<256.5,383.5>-<291.0,312.0>-<297.0,219.0>>/B<<297.0,219.0>-<304.0,312.0>-<339.5,383.5>> = 7.9958549469592395

	* uni26A1 (U+26A1): L<<580.0,440.0>--<50.0,-110.0>>/L<<50.0,-110.0>--<295.0,310.0>> = 13.68265114620652

	* w (U+0077): B<<172.5,93.0>-<175.0,68.0>-<176.0,49.0>>/B<<176.0,49.0>-<178.0,68.0>-<181.5,93.0>> = 9.021793461677795

	* w (U+0077): B<<307.5,446.5>-<302.0,479.0>-<301.0,499.0>>/B<<301.0,499.0>-<299.0,479.0>-<293.5,446.5>> = 8.57299836361137

	* w (U+0077): B<<419.5,94.5>-<424.0,69.0>-<425.0,49.0>>/B<<425.0,49.0>-<427.0,69.0>-<429.5,94.5>> = 8.57299836361137

	* wacute (U+1E83): B<<172.5,93.0>-<175.0,68.0>-<176.0,49.0>>/B<<176.0,49.0>-<178.0,68.0>-<181.5,93.0>> = 9.021793461677795

	* wacute (U+1E83): B<<307.5,446.5>-<302.0,479.0>-<301.0,499.0>>/B<<301.0,499.0>-<299.0,479.0>-<293.5,446.5>> = 8.57299836361137

	* wacute (U+1E83): B<<419.5,94.5>-<424.0,69.0>-<425.0,49.0>>/B<<425.0,49.0>-<427.0,69.0>-<429.5,94.5>> = 8.57299836361137

	* wcircumflex (U+0175): B<<172.5,93.0>-<175.0,68.0>-<176.0,49.0>>/B<<176.0,49.0>-<178.0,68.0>-<181.5,93.0>> = 9.021793461677795

	* wcircumflex (U+0175): B<<307.5,446.5>-<302.0,479.0>-<301.0,499.0>>/B<<301.0,499.0>-<299.0,479.0>-<293.5,446.5>> = 8.57299836361137

	* wcircumflex (U+0175): B<<419.5,94.5>-<424.0,69.0>-<425.0,49.0>>/B<<425.0,49.0>-<427.0,69.0>-<429.5,94.5>> = 8.57299836361137

	* wdieresis (U+1E85): B<<172.5,93.0>-<175.0,68.0>-<176.0,49.0>>/B<<176.0,49.0>-<178.0,68.0>-<181.5,93.0>> = 9.021793461677795

	* wdieresis (U+1E85): B<<307.5,446.5>-<302.0,479.0>-<301.0,499.0>>/B<<301.0,499.0>-<299.0,479.0>-<293.5,446.5>> = 8.57299836361137

	* wdieresis (U+1E85): B<<419.5,94.5>-<424.0,69.0>-<425.0,49.0>>/B<<425.0,49.0>-<427.0,69.0>-<429.5,94.5>> = 8.57299836361137

	* wgrave (U+1E81): B<<172.5,93.0>-<175.0,68.0>-<176.0,49.0>>/B<<176.0,49.0>-<178.0,68.0>-<181.5,93.0>> = 9.021793461677795

	* wgrave (U+1E81): B<<307.5,446.5>-<302.0,479.0>-<301.0,499.0>>/B<<301.0,499.0>-<299.0,479.0>-<293.5,446.5>> = 8.57299836361137 

	* wgrave (U+1E81): B<<419.5,94.5>-<424.0,69.0>-<425.0,49.0>>/B<<425.0,49.0>-<427.0,69.0>-<429.5,94.5>> = 8.57299836361137 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* b (U+0062): L<<169.0,576.0>--<168.0,460.0>>

	* d (U+0064): L<<432.0,460.0>--<431.0,576.0>>

	* five (U+0035): L<<171.0,655.0>--<172.0,470.0>>

	* thorn (U+00FE): L<<167.0,576.0>--<166.0,460.0>>

	* uni0427 (U+0427): L<<430.0,0.0>--<431.0,282.0>>

	* uni0428 (U+0428): L<<70.0,0.0>--<69.0,730.0>>

	* uni0448 (U+0448): L<<70.0,0.0>--<69.0,550.0>>

	* uni04B6 (U+04B6): L<<420.0,0.0>--<421.0,282.0>>

	* uni04BA (U+04BA): L<<170.0,730.0>--<169.0,448.0>>

	* uni04F4 (U+04F4): L<<430.0,0.0>--<431.0,282.0>>

	* uni207A (U+207A): L<<328.0,585.0>--<327.0,470.0>> 

	* uni2352 (U+2352): L<<279.0,157.0>--<277.0,671.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[20] PitagonSansMono-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Pitagon Sans Mono ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- uni2070.zero

	- uni2080.zero

	- zero.dnom.zero 

	- zero.numr.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1710 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* section (U+00A7): X=45.0,Y=2.0 (should be at baseline 0?)

	* section (U+00A7): X=195.0,Y=2.0 (should be at baseline 0?)

	* uni00B2 (U+00B2): X=350.0,Y=731.0 (should be at cap-height 730?)

	* uni00B2 (U+00B2): X=256.0,Y=731.0 (should be at cap-height 730?)

	* cedilla (U+00B8): X=238.0,Y=1.0 (should be at baseline 0?)

	* onequarter (U+00BC): X=126.0,Y=729.0 (should be at cap-height 730?)

	* onequarter (U+00BC): X=241.0,Y=729.0 (should be at cap-height 730?)

	* Oslash (U+00D8): X=456.0,Y=731.0 (should be at cap-height 730?)

	* aogonek (U+0105): X=519.0,Y=-2.0 (should be at baseline 0?)

	* oe (U+0153): X=357.0,Y=2.0 (should be at baseline 0?)

	* oe (U+0153): X=241.5,Y=2.0 (should be at baseline 0?)

	* uni019B (U+019B): X=446.0,Y=728.0 (should be at cap-height 730?)

	* uni019B (U+019B): X=463.5,Y=729.0 (should be at cap-height 730?)

	* uni01D8 (U+01D8): X=455.5,Y=1018.0 (should be at ascender 1020?)

	* uni01DA (U+01DA): X=119.5,Y=1018.0 (should be at ascender 1020?)

	* uni01DA (U+01DA): X=480.5,Y=1018.0 (should be at ascender 1020?)

	* uni01DC (U+01DC): X=142.5,Y=1018.0 (should be at ascender 1020?)

	* Oslashacute (U+01FE): X=456.0,Y=731.0 (should be at cap-height 730?)

	* hookabovecomb (U+0309): X=-293.0,Y=732.0 (should be at cap-height 730?)

	* uni0327 (U+0327): X=-362.0,Y=1.0 (should be at baseline 0?)

	* uni1EA3 (U+1EA3): X=312.0,Y=732.0 (should be at cap-height 730?)

	* uni1EBB (U+1EBB): X=307.0,Y=732.0 (should be at cap-height 730?)

	* uni1EC9 (U+1EC9): X=327.0,Y=732.0 (should be at cap-height 730?)

	* uni1ECF (U+1ECF): X=307.0,Y=732.0 (should be at cap-height 730?)

	* uni1EDF (U+1EDF): X=297.0,Y=732.0 (should be at cap-height 730?)

	* uni1EE7 (U+1EE7): X=307.0,Y=732.0 (should be at cap-height 730?)

	* uni1EED (U+1EED): X=287.0,Y=732.0 (should be at cap-height 730?)

	* uni1EF7 (U+1EF7): X=307.0,Y=732.0 (should be at cap-height 730?)

	* quotesinglbase (U+201A): X=264.5,Y=2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=134.5,Y=2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=389.5,Y=2.0 (should be at baseline 0?)

	* uni2070 (U+2070): X=356.0,Y=729.0 (should be at cap-height 730?)

	* uni2070 (U+2070): X=244.0,Y=729.0 (should be at cap-height 730?)

	* uni2085 (U+2085): X=128.0,Y=2.0 (should be at baseline 0?)

	* uni2085 (U+2085): X=226.0,Y=2.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=362.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=238.0,Y=-1.0 (should be at baseline 0?)

	* uni21DF (U+21DF): X=238.0,Y=731.0 (should be at cap-height 730?)

	* uni21DF (U+21DF): X=362.0,Y=731.0 (should be at cap-height 730?)

	* uni21E7 (U+21E7): X=301.0,Y=729.0 (should be at cap-height 730?)

	* uni21EA (U+21EA): X=300.0,Y=728.0 (should be at cap-height 730?)

	* enquirycontrol (U+2405): X=450.0,Y=2.0 (should be at baseline 0?)

	* piads (U+E001): X=158.0,Y=2.0 (should be at baseline 0?)

	* pioffice (U+E002): X=158.0,Y=2.0 (should be at baseline 0?)

	* pitagram (U+E003): X=158.0,Y=2.0 (should be at baseline 0?)

	* piweb (U+E004): X=158.0,Y=2.0 (should be at baseline 0?)

	* pisign (U+E005): X=158.0,Y=2.0 (should be at baseline 0?)

	* petapp (U+E006): X=534.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=303.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=293.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=318.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=336.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=331.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=328.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=326.0,Y=1.5 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=278.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=274.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=272.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* picall (U+E009): X=158.0,Y=2.0 (should be at baseline 0?)

	* uniFE62 (U+FE62): X=240.0,Y=-1.0 (should be at baseline 0?) 

	* uniFE62 (U+FE62): X=360.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): B<<430.5,491.5>-<440.0,593.0>-<450.0,670.0>>/L<<450.0,670.0>--<364.0,334.0>> = 6.9571812935693735

	* M (U+004D): L<<232.0,334.0>--<148.0,661.0>>/B<<148.0,661.0>-<158.0,596.0>-<168.5,495.5>> = 5.660522893881687

	* Mu (U+039C): B<<430.5,491.5>-<440.0,593.0>-<450.0,670.0>>/L<<450.0,670.0>--<364.0,334.0>> = 6.9571812935693735

	* Mu (U+039C): L<<232.0,334.0>--<148.0,661.0>>/B<<148.0,661.0>-<158.0,596.0>-<168.5,495.5>> = 5.660522893881687

	* N (U+004E): L<<243.0,707.0>--<424.0,165.0>>/B<<424.0,165.0>-<421.0,202.0>-<417.0,250.5>> = 13.831193073752647

	* N (U+004E): L<<357.0,23.0>--<178.0,565.0>>/B<<178.0,565.0>-<181.0,533.0>-<184.0,489.0>> = 12.920410115348359

	* Nacute (U+0143): L<<243.0,707.0>--<424.0,165.0>>/B<<424.0,165.0>-<421.0,202.0>-<417.0,250.5>> = 13.831193073752647

	* Nacute (U+0143): L<<357.0,23.0>--<178.0,565.0>>/B<<178.0,565.0>-<181.0,533.0>-<184.0,489.0>> = 12.920410115348359

	* Ncaron (U+0147): L<<243.0,707.0>--<424.0,165.0>>/B<<424.0,165.0>-<421.0,202.0>-<417.0,250.5>> = 13.831193073752647

	* Ncaron (U+0147): L<<357.0,23.0>--<178.0,565.0>>/B<<178.0,565.0>-<181.0,533.0>-<184.0,489.0>> = 12.920410115348359

	* Ntilde (U+00D1): L<<243.0,707.0>--<424.0,165.0>>/B<<424.0,165.0>-<421.0,202.0>-<417.0,250.5>> = 13.831193073752647

	* Ntilde (U+00D1): L<<357.0,23.0>--<178.0,565.0>>/B<<178.0,565.0>-<181.0,533.0>-<184.0,489.0>> = 12.920410115348359

	* Nu (U+039D): L<<243.0,707.0>--<424.0,165.0>>/B<<424.0,165.0>-<421.0,202.0>-<417.0,250.5>> = 13.831193073752647

	* Nu (U+039D): L<<357.0,23.0>--<178.0,565.0>>/B<<178.0,565.0>-<181.0,533.0>-<184.0,489.0>> = 12.920410115348359

	* W (U+0057): B<<171.5,149.5>-<173.0,122.0>-<173.0,100.0>>/B<<173.0,100.0>-<175.0,122.0>-<177.5,149.5>> = 5.1944289077348

	* W (U+0057): B<<304.0,587.0>-<302.0,617.0>-<300.0,640.0>>/B<<300.0,640.0>-<299.0,617.0>-<297.0,587.0>> = 7.459293650109428

	* W (U+0057): B<<424.0,149.5>-<427.0,122.0>-<429.0,100.0>>/B<<429.0,100.0>-<430.0,122.0>-<431.0,149.5>> = 7.7969911102345595

	* Wacute (U+1E82): B<<171.5,149.5>-<173.0,122.0>-<173.0,100.0>>/B<<173.0,100.0>-<175.0,122.0>-<177.5,149.5>> = 5.1944289077348

	* Wacute (U+1E82): B<<304.0,587.0>-<302.0,617.0>-<300.0,640.0>>/B<<300.0,640.0>-<299.0,617.0>-<297.0,587.0>> = 7.459293650109428

	* Wacute (U+1E82): B<<424.0,149.5>-<427.0,122.0>-<429.0,100.0>>/B<<429.0,100.0>-<430.0,122.0>-<431.0,149.5>> = 7.7969911102345595

	* Wcircumflex (U+0174): B<<171.5,149.5>-<173.0,122.0>-<173.0,100.0>>/B<<173.0,100.0>-<175.0,122.0>-<177.5,149.5>> = 5.1944289077348

	* Wcircumflex (U+0174): B<<304.0,587.0>-<302.0,617.0>-<300.0,640.0>>/B<<300.0,640.0>-<299.0,617.0>-<297.0,587.0>> = 7.459293650109428

	* Wcircumflex (U+0174): B<<424.0,149.5>-<427.0,122.0>-<429.0,100.0>>/B<<429.0,100.0>-<430.0,122.0>-<431.0,149.5>> = 7.7969911102345595

	* Wdieresis (U+1E84): B<<171.5,149.5>-<173.0,122.0>-<173.0,100.0>>/B<<173.0,100.0>-<175.0,122.0>-<177.5,149.5>> = 5.1944289077348

	* Wdieresis (U+1E84): B<<304.0,587.0>-<302.0,617.0>-<300.0,640.0>>/B<<300.0,640.0>-<299.0,617.0>-<297.0,587.0>> = 7.459293650109428

	* Wdieresis (U+1E84): B<<424.0,149.5>-<427.0,122.0>-<429.0,100.0>>/B<<429.0,100.0>-<430.0,122.0>-<431.0,149.5>> = 7.7969911102345595

	* Wgrave (U+1E80): B<<171.5,149.5>-<173.0,122.0>-<173.0,100.0>>/B<<173.0,100.0>-<175.0,122.0>-<177.5,149.5>> = 5.1944289077348

	* Wgrave (U+1E80): B<<304.0,587.0>-<302.0,617.0>-<300.0,640.0>>/B<<300.0,640.0>-<299.0,617.0>-<297.0,587.0>> = 7.459293650109428

	* Wgrave (U+1E80): B<<424.0,149.5>-<427.0,122.0>-<429.0,100.0>>/B<<429.0,100.0>-<430.0,122.0>-<431.0,149.5>> = 7.7969911102345595

	* a (U+0061): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* aacute (U+00E1): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* abreve (U+0103): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* acircumflex (U+00E2): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* adieresis (U+00E4): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* ae (U+00E6): B<<262.5,535.5>-<296.0,511.0>-<301.0,468.0>>/B<<301.0,468.0>-<306.0,511.0>-<340.0,535.5>> = 13.265029230276953

	* ae (U+00E6): B<<341.5,14.5>-<306.0,39.0>-<301.0,81.0>>/B<<301.0,81.0>-<296.0,39.0>-<262.0,14.5>> = 13.57794914887754

	* aeacute (U+01FD): B<<262.5,535.5>-<296.0,511.0>-<301.0,468.0>>/B<<301.0,468.0>-<306.0,511.0>-<340.0,535.5>> = 13.265029230276953

	* aeacute (U+01FD): B<<341.5,14.5>-<306.0,39.0>-<301.0,81.0>>/B<<301.0,81.0>-<296.0,39.0>-<262.0,14.5>> = 13.57794914887754

	* agrave (U+00E0): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* amacron (U+0101): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* aogonek (U+0105): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* aring (U+00E5): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* atilde (U+00E3): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* endOfMediumcontrol (U+2419): B<<398.0,176.5>-<401.0,165.0>-<402.0,153.0>>/B<<402.0,153.0>-<404.0,165.0>-<406.0,176.5>> = 14.22596389875178

	* endOfMediumcontrol (U+2419): B<<501.0,207.0>-<502.0,251.0>-<509.0,289.0>>/L<<509.0,289.0>--<452.0,119.0>> = 8.098524124548995

	* endOfMediumcontrol (U+2419): L<<350.0,119.0>--<290.0,286.0>>/B<<290.0,286.0>-<295.0,261.0>-<297.0,236.5>> = 8.452488458374477

	* endOfTextcontrol (U+2403): B<<398.5,232.0>-<404.0,222.0>-<405.0,214.0>>/B<<405.0,214.0>-<406.0,222.0>-<408.5,232.0>> = 14.25003269780357

	* endOfTextcontrol (U+2403): B<<402.0,103.5>-<397.0,114.0>-<396.0,122.0>>/B<<396.0,122.0>-<395.0,112.0>-<393.0,102.0>> = 12.835609486401424

	* eta (U+03B7): L<<211.0,530.0>--<211.0,450.0>>/B<<211.0,450.0>-<223.0,500.0>-<262.5,530.0>> = 13.495733280795811

	* etatonos (U+03AE): L<<211.0,530.0>--<211.0,450.0>>/B<<211.0,450.0>-<223.0,500.0>-<262.5,530.0>> = 13.495733280795811

	* h (U+0068): L<<216.0,550.0>--<211.0,451.0>>/B<<211.0,451.0>-<224.0,501.0>-<263.5,530.5>> = 11.68294660181812

	* hcircumflex (U+0125): L<<216.0,550.0>--<211.0,451.0>>/B<<211.0,451.0>-<224.0,501.0>-<263.5,530.5>> = 11.68294660181812

	* lambda (U+03BB): B<<314.5,351.5>-<309.0,383.0>-<307.0,403.0>>/B<<307.0,403.0>-<304.0,383.0>-<297.5,352.0>> = 14.241358747447757

	* n (U+006E): L<<211.0,530.0>--<211.0,450.0>>/B<<211.0,450.0>-<223.0,500.0>-<262.5,530.0>> = 13.495733280795811

	* nacute (U+0144): L<<211.0,530.0>--<211.0,450.0>>/B<<211.0,450.0>-<223.0,500.0>-<262.5,530.0>> = 13.495733280795811

	* napostrophe (U+0149): L<<211.0,530.0>--<211.0,450.0>>/B<<211.0,450.0>-<223.0,500.0>-<262.5,530.0>> = 13.495733280795811

	* ncaron (U+0148): L<<211.0,530.0>--<211.0,450.0>>/B<<211.0,450.0>-<223.0,500.0>-<262.5,530.0>> = 13.495733280795811

	* ntilde (U+00F1): L<<211.0,530.0>--<211.0,450.0>>/B<<211.0,450.0>-<223.0,500.0>-<262.5,530.0>> = 13.495733280795811

	* nu (U+03BD): B<<291.5,183.0>-<299.0,153.0>-<301.0,127.0>>/B<<301.0,127.0>-<303.0,153.0>-<310.0,183.0>> = 8.797410709991048

	* omega (U+03C9): B<<338.5,22.5>-<305.0,55.0>-<300.0,109.0>>/B<<300.0,109.0>-<294.0,55.0>-<260.0,22.5>> = 11.630272951281148

	* omegatonos (U+03CE): B<<338.5,22.5>-<305.0,55.0>-<300.0,109.0>>/B<<300.0,109.0>-<294.0,55.0>-<260.0,22.5>> = 11.630272951281148

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<365.0,279.0>-<368.0,276.0>-<370.0,275.0>>/L<<370.0,275.0>--<365.0,279.0>> = 12.094757077012058

	* petapp.minimal (U+E007): B<<402.0,358.0>-<402.0,357.0>-<401.0,355.0>>/L<<401.0,355.0>--<402.0,358.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>>/L<<437.0,404.0>--<440.0,406.0>> = 7.125016348901757

	* petapp.minimal (U+E007): B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>>/L<<442.0,407.0>--<447.0,409.0>> = 4.763641690726143

	* petapp.minimal (U+E007): B<<468.0,415.0>-<467.0,415.0>-<465.0,414.0>>/L<<465.0,414.0>--<468.0,415.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>>/L<<467.0,106.0>--<469.0,103.0>> = 11.309932474020195

	* petapp.minimal (U+E007): B<<484.5,8.5>-<484.0,4.0>-<483.0,0.0>>/B<<483.0,0.0>-<483.0,3.0>-<483.0,6.5>> = 14.036243467926484

	* petapp.minimal (U+E007): L<<408.0,166.0>--<411.0,165.0>>/B<<411.0,165.0>-<409.0,166.0>-<408.0,166.5>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<413.0,298.0>--<412.0,301.0>>/B<<412.0,301.0>-<413.0,299.0>-<413.0,298.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<417.0,160.0>--<420.0,159.0>>/B<<420.0,159.0>-<418.0,160.0>-<417.0,160.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<437.0,404.0>--<440.0,406.0>>/B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>> = 11.309932474020227

	* petapp.minimal (U+E007): L<<442.0,407.0>--<447.0,409.0>>/B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>> = 3.3664606634297236

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<467.0,106.0>--<469.0,103.0>>/B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>> = 7.125016348901757

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<90.0,577.0>-<99.0,557.0>> = 4.969740728110289

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* r (U+0072): L<<231.0,530.0>--<231.0,446.0>>/B<<231.0,446.0>-<243.0,499.0>-<283.5,529.5>> = 12.757532160876671

	* racute (U+0155): L<<231.0,530.0>--<231.0,446.0>>/B<<231.0,446.0>-<243.0,499.0>-<283.5,529.5>> = 12.757532160876671

	* rcaron (U+0159): L<<231.0,530.0>--<231.0,446.0>>/B<<231.0,446.0>-<243.0,499.0>-<283.5,529.5>> = 12.757532160876671

	* startOfTextcontrol (U+2402): B<<398.5,232.0>-<404.0,222.0>-<405.0,214.0>>/B<<405.0,214.0>-<406.0,222.0>-<408.5,232.0>> = 14.25003269780357

	* startOfTextcontrol (U+2402): B<<402.0,103.5>-<397.0,114.0>-<396.0,122.0>>/B<<396.0,122.0>-<395.0,112.0>-<393.0,102.0>> = 12.835609486401424

	* sterling (U+00A3): B<<232.5,162.0>-<198.0,145.0>-<165.0,140.0>>/L<<165.0,140.0>--<535.0,140.0>> = 8.615648184164108

	* trademark (U+2122): B<<367.5,646.0>-<360.0,676.0>-<355.0,695.0>>/B<<355.0,695.0>-<358.0,672.0>-<361.5,641.0>> = 7.3121548652982025

	* trademark (U+2122): B<<508.0,639.0>-<511.0,673.0>-<514.0,700.0>>/B<<514.0,700.0>-<510.0,680.0>-<502.0,648.0>> = 4.969740728110216

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni0145 (U+0145): L<<243.0,707.0>--<424.0,165.0>>/B<<424.0,165.0>-<421.0,202.0>-<417.0,250.5>> = 13.831193073752647

	* uni0145 (U+0145): L<<357.0,23.0>--<178.0,565.0>>/B<<178.0,565.0>-<181.0,533.0>-<184.0,489.0>> = 12.920410115348359

	* uni0146 (U+0146): L<<211.0,530.0>--<211.0,450.0>>/B<<211.0,450.0>-<223.0,500.0>-<262.5,530.0>> = 13.495733280795811

	* uni0157 (U+0157): L<<231.0,530.0>--<231.0,446.0>>/B<<231.0,446.0>-<243.0,499.0>-<283.5,529.5>> = 12.757532160876671

	* uni019B (U+019B): B<<314.5,351.5>-<309.0,383.0>-<307.0,403.0>>/B<<307.0,403.0>-<304.0,383.0>-<297.5,352.0>> = 14.241358747447757

	* uni01CE (U+01CE): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni03D6 (U+03D6): B<<338.5,22.5>-<305.0,55.0>-<300.0,109.0>>/B<<300.0,109.0>-<294.0,55.0>-<260.5,22.5>> = 11.630272951281148

	* uni03D7 (U+03D7): B<<195.5,205.5>-<193.0,152.0>-<182.0,110.0>>/L<<182.0,110.0>--<354.0,550.0>> = 6.674587110203547

	* uni03D7 (U+03D7): B<<404.5,338.0>-<407.0,385.0>-<416.0,420.0>>/L<<416.0,420.0>--<246.0,0.0>> = 7.615453812634431

	* uni040E (U+040E): B<<297.5,378.0>-<304.0,347.0>-<307.0,327.0>>/B<<307.0,327.0>-<309.0,347.0>-<314.5,378.5>> = 14.241358747447757

	* uni0418 (U+0418): B<<184.0,242.0>-<181.0,198.0>-<178.0,165.0>>/L<<178.0,165.0>--<365.0,730.0>> = 13.11874373402061

	* uni0418 (U+0418): B<<417.0,480.0>-<421.0,529.0>-<424.0,565.0>>/L<<424.0,565.0>--<235.0,0.0>> = 13.732130654478466

	* uni0419 (U+0419): B<<184.0,242.0>-<181.0,198.0>-<178.0,165.0>>/L<<178.0,165.0>--<365.0,730.0>> = 13.11874373402061

	* uni0419 (U+0419): B<<417.0,480.0>-<421.0,529.0>-<424.0,565.0>>/L<<424.0,565.0>--<235.0,0.0>> = 13.732130654478466

	* uni041C (U+041C): B<<430.5,491.5>-<440.0,593.0>-<450.0,670.0>>/L<<450.0,670.0>--<364.0,334.0>> = 6.9571812935693735

	* uni041C (U+041C): L<<232.0,334.0>--<148.0,661.0>>/B<<148.0,661.0>-<158.0,596.0>-<168.5,495.5>> = 5.660522893881687

	* uni0423 (U+0423): B<<297.5,378.0>-<304.0,347.0>-<307.0,327.0>>/B<<307.0,327.0>-<309.0,347.0>-<314.5,378.5>> = 14.241358747447757

	* uni0430 (U+0430): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni0431 (U+0431): L<<185.0,461.0>--<185.0,397.0>>/B<<185.0,397.0>-<194.0,454.0>-<235.5,485.0>> = 8.972626614896399

	* uni0438 (U+0438): B<<195.5,205.5>-<193.0,152.0>-<182.0,110.0>>/L<<182.0,110.0>--<354.0,550.0>> = 6.674587110203547

	* uni0438 (U+0438): B<<404.5,338.0>-<407.0,385.0>-<416.0,420.0>>/L<<416.0,420.0>--<246.0,0.0>> = 7.615453812634431

	* uni0439 (U+0439): B<<195.5,205.5>-<193.0,152.0>-<182.0,110.0>>/L<<182.0,110.0>--<354.0,550.0>> = 6.674587110203547

	* uni0439 (U+0439): B<<404.5,338.0>-<407.0,385.0>-<416.0,420.0>>/L<<416.0,420.0>--<246.0,0.0>> = 7.615453812634431

	* uni043C (U+043C): B<<427.0,398.5>-<430.0,449.0>-<436.0,481.0>>/L<<436.0,481.0>--<355.0,185.0>> = 4.6845881186490175

	* uni043C (U+043C): L<<242.0,185.0>--<160.0,466.0>>/B<<160.0,466.0>-<167.0,435.0>-<171.0,388.0>> = 3.543678454313032

	* uni04E4 (U+04E4): B<<184.0,242.0>-<181.0,198.0>-<178.0,165.0>>/L<<178.0,165.0>--<365.0,730.0>> = 13.11874373402061

	* uni04E4 (U+04E4): B<<417.0,480.0>-<421.0,529.0>-<424.0,565.0>>/L<<424.0,565.0>--<235.0,0.0>> = 13.732130654478466

	* uni04E5 (U+04E5): B<<195.5,205.5>-<193.0,152.0>-<182.0,110.0>>/L<<182.0,110.0>--<354.0,550.0>> = 6.674587110203547

	* uni04E5 (U+04E5): B<<404.5,338.0>-<407.0,385.0>-<416.0,420.0>>/L<<416.0,420.0>--<246.0,0.0>> = 7.615453812634431

	* uni1EA1 (U+1EA1): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni1EA3 (U+1EA3): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni1EA5 (U+1EA5): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni1EA7 (U+1EA7): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni1EA9 (U+1EA9): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni1EAB (U+1EAB): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni1EAD (U+1EAD): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni1EAF (U+1EAF): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni1EB1 (U+1EB1): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni1EB3 (U+1EB3): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni1EB5 (U+1EB5): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni1EB7 (U+1EB7): L<<389.0,28.0>--<389.0,95.0>>/B<<389.0,95.0>-<379.0,46.0>-<336.5,18.0>> = 11.534620653644708

	* uni20BF (U+20BF): B<<463.0,404.0>-<426.0,384.0>-<380.0,381.0>>/B<<380.0,381.0>-<430.0,380.0>-<470.5,361.0>> = 4.877159837335479

	* uni2116 (U+2116): B<<111.5,551.5>-<103.0,596.0>-<96.0,630.0>>/B<<96.0,630.0>-<103.0,575.0>-<110.5,509.5>> = 4.3804393862150395

	* uni2116 (U+2116): B<<277.5,183.0>-<287.0,137.0>-<294.0,100.0>>/B<<294.0,100.0>-<287.0,155.0>-<278.5,220.5>> = 3.4599284100656305

	* uni2197 (U+2197): B<<408.5,476.5>-<412.0,497.0>-<418.0,507.0>>/L<<418.0,507.0>--<130.0,214.0>> = 13.543176642444744

	* uni227A (U+227A): B<<423.0,413.5>-<328.0,345.0>-<165.0,337.0>>/B<<165.0,337.0>-<328.0,327.0>-<423.0,253.5>> = 6.320486566337609

	* uni227B (U+227B): B<<177.0,253.5>-<272.0,327.0>-<435.0,337.0>>/B<<435.0,337.0>-<272.0,345.0>-<177.0,413.5>> = 6.320486566337609

	* uni227C (U+227C): B<<423.0,538.5>-<328.0,470.0>-<165.0,462.0>>/B<<165.0,462.0>-<328.0,452.0>-<423.0,378.5>> = 6.320486566337609

	* uni22CE (U+22CE): B<<220.0,446.5>-<291.0,350.0>-<299.0,185.0>>/B<<299.0,185.0>-<308.0,351.0>-<379.0,447.5>> = 5.879162770526505

	* uni234B (U+234B): L<<277.0,130.0>--<277.0,475.0>>/L<<277.0,475.0>--<204.0,130.0>> = 11.947234104599477

	* uni234B (U+234B): L<<393.0,130.0>--<320.0,475.0>>/L<<320.0,475.0>--<320.0,130.0>> = 11.947234104599477

	* uni2352 (U+2352): L<<208.0,600.0>--<282.0,260.0>>/L<<282.0,260.0>--<282.0,600.0>> = 12.278765370963031

	* uni2352 (U+2352): L<<324.0,600.0>--<324.0,260.0>>/L<<324.0,260.0>--<396.0,600.0>> = 11.956584243149111

	* uni236C (U+236C): L<<210.0,520.0>--<210.0,379.0>>/B<<210.0,379.0>-<223.0,457.0>-<266.0,457.0>> = 9.462322208025613

	* uni236C (U+236C): L<<390.0,210.0>--<390.0,365.0>>/B<<390.0,365.0>-<377.0,287.0>-<334.0,287.0>> = 9.462322208025613

	* uni2375 (U+2375): B<<338.5,22.5>-<305.0,55.0>-<300.0,109.0>>/B<<300.0,109.0>-<294.0,55.0>-<260.5,22.5>> = 11.630272951281148

	* uni2379 (U+2379): B<<338.5,22.5>-<305.0,55.0>-<300.0,109.0>>/B<<300.0,109.0>-<294.0,55.0>-<260.5,22.5>> = 11.630272951281148

	* uni26A1 (U+26A1): L<<579.0,440.0>--<49.0,-110.0>>/L<<49.0,-110.0>--<294.0,310.0>> = 13.68265114620652

	* v (U+0076): B<<291.5,183.0>-<299.0,153.0>-<301.0,127.0>>/B<<301.0,127.0>-<303.0,153.0>-<310.0,183.0>> = 8.797410709991048

	* w (U+0077): B<<171.0,169.0>-<174.0,126.0>-<176.0,97.0>>/B<<176.0,97.0>-<178.0,126.0>-<181.0,169.0>> = 7.890372458075046

	* w (U+0077): B<<307.0,379.0>-<302.0,419.0>-<300.0,445.0>>/B<<300.0,445.0>-<300.0,428.0>-<297.0,403.0>> = 4.398705354995508

	* w (U+0077): B<<420.0,168.5>-<424.0,125.0>-<426.0,96.0>>/B<<426.0,96.0>-<428.0,125.0>-<430.0,168.5>> = 7.890372458075046

	* wacute (U+1E83): B<<171.0,169.0>-<174.0,126.0>-<176.0,97.0>>/B<<176.0,97.0>-<178.0,126.0>-<181.0,169.0>> = 7.890372458075046

	* wacute (U+1E83): B<<307.0,379.0>-<302.0,419.0>-<300.0,445.0>>/B<<300.0,445.0>-<300.0,428.0>-<297.0,403.0>> = 4.398705354995508

	* wacute (U+1E83): B<<420.0,168.5>-<424.0,125.0>-<426.0,96.0>>/B<<426.0,96.0>-<428.0,125.0>-<430.0,168.5>> = 7.890372458075046

	* wcircumflex (U+0175): B<<171.0,169.0>-<174.0,126.0>-<176.0,97.0>>/B<<176.0,97.0>-<178.0,126.0>-<181.0,169.0>> = 7.890372458075046

	* wcircumflex (U+0175): B<<307.0,379.0>-<302.0,419.0>-<300.0,445.0>>/B<<300.0,445.0>-<300.0,428.0>-<297.0,403.0>> = 4.398705354995508

	* wcircumflex (U+0175): B<<420.0,168.5>-<424.0,125.0>-<426.0,96.0>>/B<<426.0,96.0>-<428.0,125.0>-<430.0,168.5>> = 7.890372458075046

	* wdieresis (U+1E85): B<<171.0,169.0>-<174.0,126.0>-<176.0,97.0>>/B<<176.0,97.0>-<178.0,126.0>-<181.0,169.0>> = 7.890372458075046

	* wdieresis (U+1E85): B<<307.0,379.0>-<302.0,419.0>-<300.0,445.0>>/B<<300.0,445.0>-<300.0,428.0>-<297.0,403.0>> = 4.398705354995508

	* wdieresis (U+1E85): B<<420.0,168.5>-<424.0,125.0>-<426.0,96.0>>/B<<426.0,96.0>-<428.0,125.0>-<430.0,168.5>> = 7.890372458075046

	* wgrave (U+1E81): B<<171.0,169.0>-<174.0,126.0>-<176.0,97.0>>/B<<176.0,97.0>-<178.0,126.0>-<181.0,169.0>> = 7.890372458075046

	* wgrave (U+1E81): B<<307.0,379.0>-<302.0,419.0>-<300.0,445.0>>/B<<300.0,445.0>-<300.0,428.0>-<297.0,403.0>> = 4.398705354995508 

	* wgrave (U+1E81): B<<420.0,168.5>-<424.0,125.0>-<426.0,96.0>>/B<<426.0,96.0>-<428.0,125.0>-<430.0,168.5>> = 7.890372458075046 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0402 (U+0402): L<<425.0,41.0>--<424.0,290.0>>

	* uni0402 (U+0402): L<<574.0,295.0>--<575.0,25.0>>

	* uni040B (U+040B): L<<425.0,0.0>--<424.0,290.0>>

	* uni040B (U+040B): L<<574.0,295.0>--<575.0,0.0>> 

	* uniE0A2 (U+E0A2): L<<345.0,50.0>--<344.0,210.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] PitagonSansMono-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- uni2070.zero

	- uni2080.zero

	- zero.dnom.zero 

	- zero.numr.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1710 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* braceleft (U+007B): X=387.0,Y=728.5 (should be at cap-height 730?)

	* braceright (U+007D): X=214.5,Y=728.5 (should be at cap-height 730?)

	* Aogonek (U+0104): X=534.0,Y=1.0 (should be at baseline 0?)

	* Aogonek (U+0104): X=534.0,Y=1.0 (should be at baseline 0?)

	* aogonek (U+0105): X=497.0,Y=-1.0 (should be at baseline 0?)

	* eogonek (U+0119): X=400.0,Y=1.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=401.0,Y=1.0 (should be at baseline 0?)

	* uogonek (U+0173): X=399.0,Y=1.0 (should be at baseline 0?)

	* uni019B (U+019B): X=446.0,Y=728.0 (should be at cap-height 730?)

	* uni019B (U+019B): X=463.5,Y=729.0 (should be at cap-height 730?)

	* uni01EA (U+01EA): X=401.0,Y=1.0 (should be at baseline 0?)

	* uni01EB (U+01EB): X=399.0,Y=1.0 (should be at baseline 0?)

	* ogonek (U+02DB): X=334.0,Y=1.0 (should be at baseline 0?)

	* uni0328 (U+0328): X=-266.0,Y=1.0 (should be at baseline 0?)

	* xi (U+03BE): X=528.0,Y=-0.5 (should be at baseline 0?)

	* uni03C2 (U+03C2): X=483.0,Y=-0.5 (should be at baseline 0?)

	* arrowupdn (U+2195): X=222.0,Y=1.0 (should be at baseline 0?)

	* arrowupdn (U+2195): X=222.0,Y=729.0 (should be at cap-height 730?)

	* arrowupdn (U+2195): X=380.0,Y=729.0 (should be at cap-height 730?)

	* arrowupdn (U+2195): X=380.0,Y=1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=343.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=257.0,Y=-1.0 (should be at baseline 0?)

	* uni21DF (U+21DF): X=257.0,Y=731.0 (should be at cap-height 730?)

	* uni21DF (U+21DF): X=343.0,Y=731.0 (should be at cap-height 730?)

	* uni21E7 (U+21E7): X=301.0,Y=729.0 (should be at cap-height 730?)

	* uni21EA (U+21EA): X=300.0,Y=728.0 (should be at cap-height 730?)

	* uni2262 (U+2262): X=397.0,Y=729.0 (should be at cap-height 730?)

	* uni2262 (U+2262): X=460.0,Y=729.0 (should be at cap-height 730?)

	* uni2987 (U+2987): X=400.0,Y=729.0 (should be at cap-height 730?)

	* uni2988 (U+2988): X=200.0,Y=729.0 (should be at cap-height 730?)

	* piads (U+E001): X=158.0,Y=2.0 (should be at baseline 0?)

	* pioffice (U+E002): X=158.0,Y=2.0 (should be at baseline 0?)

	* pitagram (U+E003): X=158.0,Y=2.0 (should be at baseline 0?)

	* piweb (U+E004): X=158.0,Y=2.0 (should be at baseline 0?)

	* pisign (U+E005): X=158.0,Y=2.0 (should be at baseline 0?)

	* petapp (U+E006): X=534.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=303.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=293.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=318.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=336.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=331.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=328.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=326.0,Y=1.5 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=278.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=274.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=272.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* picall (U+E009): X=158.0,Y=2.0 (should be at baseline 0?)

	* uniFF5B (U+FF5B): X=387.0,Y=728.5 (should be at cap-height 730?) 

	* uniFF5D (U+FF5D): X=214.5,Y=728.5 (should be at cap-height 730?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): B<<447.0,586.0>-<450.0,651.0>-<454.0,703.0>>/L<<454.0,703.0>--<341.0,343.0>> = 13.027788212756235

	* M (U+004D): L<<253.0,343.0>--<145.0,694.0>>/B<<145.0,694.0>-<153.0,620.0>-<156.0,532.0>> = 10.932553874022712

	* Mu (U+039C): B<<447.0,586.0>-<450.0,651.0>-<454.0,703.0>>/L<<454.0,703.0>--<341.0,343.0>> = 13.027788212756235

	* Mu (U+039C): L<<253.0,343.0>--<145.0,694.0>>/B<<145.0,694.0>-<153.0,620.0>-<156.0,532.0>> = 10.932553874022712

	* W (U+0057): B<<166.0,121.5>-<168.0,86.0>-<169.0,65.0>>/B<<169.0,65.0>-<171.0,86.0>-<174.5,121.5>> = 8.166643024911759

	* W (U+0057): B<<306.0,616.5>-<304.0,649.0>-<302.0,667.0>>/B<<302.0,667.0>-<300.0,649.0>-<298.0,616.5>> = 12.680383491819825

	* W (U+0057): B<<425.0,121.5>-<429.0,86.0>-<431.0,65.0>>/B<<431.0,65.0>-<433.0,86.0>-<435.5,121.5>> = 10.880664062011007

	* Wacute (U+1E82): B<<166.0,121.5>-<168.0,86.0>-<169.0,65.0>>/B<<169.0,65.0>-<171.0,86.0>-<174.5,121.5>> = 8.166643024911759

	* Wacute (U+1E82): B<<306.0,616.5>-<304.0,649.0>-<302.0,667.0>>/B<<302.0,667.0>-<300.0,649.0>-<298.0,616.5>> = 12.680383491819825

	* Wacute (U+1E82): B<<425.0,121.5>-<429.0,86.0>-<431.0,65.0>>/B<<431.0,65.0>-<433.0,86.0>-<435.5,121.5>> = 10.880664062011007

	* Wcircumflex (U+0174): B<<166.0,121.5>-<168.0,86.0>-<169.0,65.0>>/B<<169.0,65.0>-<171.0,86.0>-<174.5,121.5>> = 8.166643024911759

	* Wcircumflex (U+0174): B<<306.0,616.5>-<304.0,649.0>-<302.0,667.0>>/B<<302.0,667.0>-<300.0,649.0>-<298.0,616.5>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<425.0,121.5>-<429.0,86.0>-<431.0,65.0>>/B<<431.0,65.0>-<433.0,86.0>-<435.5,121.5>> = 10.880664062011007

	* Wdieresis (U+1E84): B<<166.0,121.5>-<168.0,86.0>-<169.0,65.0>>/B<<169.0,65.0>-<171.0,86.0>-<174.5,121.5>> = 8.166643024911759

	* Wdieresis (U+1E84): B<<306.0,616.5>-<304.0,649.0>-<302.0,667.0>>/B<<302.0,667.0>-<300.0,649.0>-<298.0,616.5>> = 12.680383491819825

	* Wdieresis (U+1E84): B<<425.0,121.5>-<429.0,86.0>-<431.0,65.0>>/B<<431.0,65.0>-<433.0,86.0>-<435.5,121.5>> = 10.880664062011007

	* Wgrave (U+1E80): B<<166.0,121.5>-<168.0,86.0>-<169.0,65.0>>/B<<169.0,65.0>-<171.0,86.0>-<174.5,121.5>> = 8.166643024911759

	* Wgrave (U+1E80): B<<306.0,616.5>-<304.0,649.0>-<302.0,667.0>>/B<<302.0,667.0>-<300.0,649.0>-<298.0,616.5>> = 12.680383491819825

	* Wgrave (U+1E80): B<<425.0,121.5>-<429.0,86.0>-<431.0,65.0>>/B<<431.0,65.0>-<433.0,86.0>-<435.5,121.5>> = 10.880664062011007

	* ae (U+00E6): B<<265.0,535.5>-<299.0,511.0>-<304.0,471.0>>/B<<304.0,471.0>-<309.0,511.0>-<341.5,535.5>> = 14.25003269780357

	* aeacute (U+01FD): B<<265.0,535.5>-<299.0,511.0>-<304.0,471.0>>/B<<304.0,471.0>-<309.0,511.0>-<341.5,535.5>> = 14.25003269780357

	* arrowboth (U+2194): B<<514.0,251.0>-<540.0,285.0>-<566.0,290.0>>/L<<566.0,290.0>--<34.0,290.0>> = 10.885527054658743

	* arrowboth (U+2194): L<<566.0,290.0>--<34.0,290.0>>/B<<34.0,290.0>-<60.0,285.0>-<86.0,251.0>> = 10.885527054658743

	* arrowdown (U+2193): L<<340.0,730.0>--<340.0,112.0>>/B<<340.0,112.0>-<342.0,120.0>-<353.0,133.5>> = 14.036243467926484

	* arrowleft (U+2190): L<<580.0,290.0>--<124.0,290.0>>/B<<124.0,290.0>-<150.0,285.0>-<176.0,251.0>> = 10.885527054658743

	* arrowright (U+2192): B<<424.0,251.0>-<450.0,285.0>-<476.0,290.0>>/L<<476.0,290.0>--<20.0,290.0>> = 10.885527054658743

	* arrowupdn (U+2195): L<<340.0,778.0>--<340.0,-48.0>>/B<<340.0,-48.0>-<342.0,-40.0>-<353.0,-26.5>> = 14.036243467926484

	* braceleft (U+007B): B<<352.0,405.5>-<319.0,370.0>-<244.0,363.0>>/B<<244.0,363.0>-<319.0,356.0>-<352.0,317.0>> = 10.664317763319094

	* endOfMediumcontrol (U+2419): B<<508.0,211.5>-<510.0,260.0>-<520.0,298.0>>/L<<520.0,298.0>--<441.0,111.0>> = 8.158545047840526

	* endOfMediumcontrol (U+2419): L<<360.0,111.0>--<279.0,295.0>>/B<<279.0,295.0>-<284.0,270.0>-<287.5,243.5>> = 12.449996507806564

	* perthousand (U+2030): B<<406.0,271.0>-<429.0,252.0>-<431.0,220.0>>/B<<431.0,220.0>-<434.0,252.0>-<457.5,271.0>> = 8.932159417852464

	* perthousand (U+2030): B<<457.0,14.0>-<434.0,33.0>-<432.0,65.0>>/B<<432.0,65.0>-<428.0,33.0>-<404.5,14.0>> = 10.701350723899111

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<365.0,279.0>-<368.0,276.0>-<370.0,275.0>>/L<<370.0,275.0>--<365.0,279.0>> = 12.094757077012058

	* petapp.minimal (U+E007): B<<402.0,358.0>-<402.0,357.0>-<401.0,355.0>>/L<<401.0,355.0>--<402.0,358.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>>/L<<437.0,404.0>--<440.0,406.0>> = 7.125016348901757

	* petapp.minimal (U+E007): B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>>/L<<442.0,407.0>--<447.0,409.0>> = 4.763641690726143

	* petapp.minimal (U+E007): B<<468.0,415.0>-<467.0,415.0>-<465.0,414.0>>/L<<465.0,414.0>--<468.0,415.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>>/L<<467.0,106.0>--<469.0,103.0>> = 11.309932474020195

	* petapp.minimal (U+E007): B<<484.5,8.5>-<484.0,4.0>-<483.0,0.0>>/B<<483.0,0.0>-<483.0,3.0>-<483.0,6.5>> = 14.036243467926484

	* petapp.minimal (U+E007): L<<408.0,166.0>--<411.0,165.0>>/B<<411.0,165.0>-<409.0,166.0>-<408.0,166.5>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<413.0,298.0>--<412.0,301.0>>/B<<412.0,301.0>-<413.0,299.0>-<413.0,298.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<417.0,160.0>--<420.0,159.0>>/B<<420.0,159.0>-<418.0,160.0>-<417.0,160.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<437.0,404.0>--<440.0,406.0>>/B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>> = 11.309932474020227

	* petapp.minimal (U+E007): L<<442.0,407.0>--<447.0,409.0>>/B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>> = 3.3664606634297236

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<467.0,106.0>--<469.0,103.0>>/B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>> = 7.125016348901757

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<90.0,577.0>-<99.0,557.0>> = 4.969740728110289

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* trademark (U+2122): B<<370.0,655.0>-<363.0,680.0>-<357.0,700.0>>/B<<357.0,700.0>-<359.0,681.0>-<362.0,650.0>> = 10.690238276499054

	* trademark (U+2122): B<<512.5,650.0>-<515.0,681.0>-<517.0,700.0>>/B<<517.0,700.0>-<511.0,680.0>-<504.0,654.5>> = 10.690238276499054

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni03D7 (U+03D7): B<<176.5,165.0>-<175.0,119.0>-<167.0,90.0>>/L<<167.0,90.0>--<396.0,550.0>> = 11.043158402033892

	* uni03D7 (U+03D7): B<<423.5,387.0>-<425.0,433.0>-<433.0,462.0>>/L<<433.0,462.0>--<204.0,0.0>> = 10.944119521287831

	* uni041C (U+041C): B<<447.0,586.0>-<450.0,651.0>-<454.0,703.0>>/L<<454.0,703.0>--<341.0,343.0>> = 13.027788212756235

	* uni041C (U+041C): L<<253.0,343.0>--<145.0,694.0>>/B<<145.0,694.0>-<153.0,620.0>-<156.0,532.0>> = 10.932553874022712

	* uni0431 (U+0431): L<<161.0,458.0>--<161.0,413.0>>/B<<161.0,413.0>-<173.0,461.0>-<213.5,488.5>> = 14.036243467926457

	* uni0438 (U+0438): B<<176.5,165.0>-<175.0,119.0>-<167.0,90.0>>/L<<167.0,90.0>--<396.0,550.0>> = 11.043158402033892

	* uni0438 (U+0438): B<<423.5,387.0>-<425.0,433.0>-<433.0,462.0>>/L<<433.0,462.0>--<204.0,0.0>> = 10.944119521287831

	* uni0439 (U+0439): B<<176.5,165.0>-<175.0,119.0>-<167.0,90.0>>/L<<167.0,90.0>--<396.0,550.0>> = 11.043158402033892

	* uni0439 (U+0439): B<<423.5,387.0>-<425.0,433.0>-<433.0,462.0>>/L<<433.0,462.0>--<204.0,0.0>> = 10.944119521287831

	* uni043C (U+043C): B<<443.5,332.0>-<445.0,436.0>-<455.0,506.0>>/L<<455.0,506.0>--<338.0,215.0>> = 13.773075727683198

	* uni043C (U+043C): L<<256.0,215.0>--<146.0,490.0>>/B<<146.0,490.0>-<155.0,428.0>-<156.5,332.0>> = 13.541971506472978

	* uni04E5 (U+04E5): B<<176.5,165.0>-<175.0,119.0>-<167.0,90.0>>/L<<167.0,90.0>--<396.0,550.0>> = 11.043158402033892

	* uni04E5 (U+04E5): B<<423.5,387.0>-<425.0,433.0>-<433.0,462.0>>/L<<433.0,462.0>--<204.0,0.0>> = 10.944119521287831

	* uni2116 (U+2116): B<<105.5,581.5>-<97.0,618.0>-<90.0,646.0>>/B<<90.0,646.0>-<92.0,618.0>-<94.5,580.5>> = 9.950626687951587

	* uni2116 (U+2116): B<<272.5,151.0>-<281.0,114.0>-<287.0,85.0>>/B<<287.0,85.0>-<285.0,114.0>-<282.0,152.0>> = 7.74418294640162

	* uni2196 (U+2196): B<<215.5,652.0>-<198.0,653.0>-<187.0,660.0>>/L<<187.0,660.0>--<553.0,294.0>> = 12.528807709151522

	* uni2197 (U+2197): L<<47.0,294.0>--<413.0,660.0>>/B<<413.0,660.0>-<403.0,653.0>-<385.0,652.0>> = 10.00797980144135

	* uni2198 (U+2198): B<<385.0,78.0>-<403.0,77.0>-<413.0,70.0>>/L<<413.0,70.0>--<47.0,436.0>> = 10.00797980144135

	* uni2199 (U+2199): L<<553.0,436.0>--<187.0,70.0>>/B<<187.0,70.0>-<198.0,77.0>-<215.5,78.0>> = 12.52880770915155

	* uni227A (U+227A): B<<353.5,374.5>-<282.0,340.0>-<190.0,335.0>>/B<<190.0,335.0>-<282.0,328.0>-<353.5,292.0>> = 7.461918605064565

	* uni227B (U+227B): B<<246.5,292.0>-<318.0,328.0>-<410.0,335.0>>/B<<410.0,335.0>-<318.0,340.0>-<246.5,374.5>> = 7.461918605064565

	* uni227C (U+227C): B<<353.5,499.5>-<282.0,465.0>-<190.0,460.0>>/B<<190.0,460.0>-<282.0,453.0>-<353.5,417.0>> = 7.461918605064565

	* uni22CE (U+22CE): B<<256.5,387.5>-<291.0,316.0>-<297.0,224.0>>/B<<297.0,224.0>-<304.0,316.0>-<339.5,387.5>> = 8.082474950734255

	* uni234B (U+234B): L<<276.0,80.0>--<276.0,547.0>>/L<<276.0,547.0>--<162.0,80.0>> = 13.718258047264216

	* uni234B (U+234B): L<<439.0,80.0>--<324.0,546.0>>/L<<324.0,546.0>--<324.0,80.0>> = 13.862532692910552

	* uni2352 (U+2352): L<<162.0,650.0>--<280.0,179.0>>/L<<280.0,179.0>--<276.0,650.0>> = 13.578286072669737

	* uni2352 (U+2352): L<<324.0,650.0>--<324.0,179.0>>/L<<324.0,179.0>--<438.0,650.0>> = 13.606103054249314

	* uni236C (U+236C): L<<178.0,530.0>--<178.0,390.0>>/B<<178.0,390.0>-<192.0,457.0>-<244.0,457.0>> = 11.80243420778352

	* uni236C (U+236C): L<<422.0,200.0>--<422.0,354.0>>/B<<422.0,354.0>-<408.0,287.0>-<356.0,287.0>> = 11.80243420778352

	* uni26A1 (U+26A1): L<<580.0,440.0>--<50.0,-110.0>>/L<<50.0,-110.0>--<295.0,310.0>> = 13.68265114620652

	* uniFF5B (U+FF5B): B<<352.0,405.5>-<319.0,370.0>-<244.0,363.0>>/B<<244.0,363.0>-<319.0,356.0>-<352.0,317.0>> = 10.664317763319094

	* w (U+0077): B<<171.0,113.5>-<174.0,87.0>-<175.0,70.0>>/B<<175.0,70.0>-<177.0,87.0>-<179.5,113.5>> = 10.076297471186699

	* w (U+0077): B<<305.5,439.5>-<302.0,471.0>-<300.0,488.0>>/B<<300.0,488.0>-<299.0,471.0>-<295.0,439.5>> = 10.076297471186699

	* w (U+0077): B<<421.5,113.5>-<425.0,87.0>-<426.0,70.0>>/B<<426.0,70.0>-<428.0,87.0>-<431.0,113.5>> = 10.076297471186699

	* wacute (U+1E83): B<<171.0,113.5>-<174.0,87.0>-<175.0,70.0>>/B<<175.0,70.0>-<177.0,87.0>-<179.5,113.5>> = 10.076297471186699

	* wacute (U+1E83): B<<305.5,439.5>-<302.0,471.0>-<300.0,488.0>>/B<<300.0,488.0>-<299.0,471.0>-<295.0,439.5>> = 10.076297471186699

	* wacute (U+1E83): B<<421.5,113.5>-<425.0,87.0>-<426.0,70.0>>/B<<426.0,70.0>-<428.0,87.0>-<431.0,113.5>> = 10.076297471186699

	* wcircumflex (U+0175): B<<171.0,113.5>-<174.0,87.0>-<175.0,70.0>>/B<<175.0,70.0>-<177.0,87.0>-<179.5,113.5>> = 10.076297471186699

	* wcircumflex (U+0175): B<<305.5,439.5>-<302.0,471.0>-<300.0,488.0>>/B<<300.0,488.0>-<299.0,471.0>-<295.0,439.5>> = 10.076297471186699

	* wcircumflex (U+0175): B<<421.5,113.5>-<425.0,87.0>-<426.0,70.0>>/B<<426.0,70.0>-<428.0,87.0>-<431.0,113.5>> = 10.076297471186699

	* wdieresis (U+1E85): B<<171.0,113.5>-<174.0,87.0>-<175.0,70.0>>/B<<175.0,70.0>-<177.0,87.0>-<179.5,113.5>> = 10.076297471186699

	* wdieresis (U+1E85): B<<305.5,439.5>-<302.0,471.0>-<300.0,488.0>>/B<<300.0,488.0>-<299.0,471.0>-<295.0,439.5>> = 10.076297471186699

	* wdieresis (U+1E85): B<<421.5,113.5>-<425.0,87.0>-<426.0,70.0>>/B<<426.0,70.0>-<428.0,87.0>-<431.0,113.5>> = 10.076297471186699

	* wgrave (U+1E81): B<<171.0,113.5>-<174.0,87.0>-<175.0,70.0>>/B<<175.0,70.0>-<177.0,87.0>-<179.5,113.5>> = 10.076297471186699

	* wgrave (U+1E81): B<<305.5,439.5>-<302.0,471.0>-<300.0,488.0>>/B<<300.0,488.0>-<299.0,471.0>-<295.0,439.5>> = 10.076297471186699 

	* wgrave (U+1E81): B<<421.5,113.5>-<425.0,87.0>-<426.0,70.0>>/B<<426.0,70.0>-<428.0,87.0>-<431.0,113.5>> = 10.076297471186699 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* phi (U+03C6): L<<139.0,358.0>--<138.0,202.0>>

	* uni0409 (U+0409): L<<157.0,655.0>--<153.0,194.0>>

	* uni0428 (U+0428): L<<62.0,0.0>--<60.0,730.0>>

	* uni0448 (U+0448): L<<62.0,0.0>--<60.0,550.0>> 

	* uni2352 (U+2352): L<<280.0,179.0>--<276.0,650.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[21] PitagonSansMono-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Pitagon Sans Mono Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- uni2070.zero

	- uni2080.zero

	- zero.dnom.zero 

	- zero.numr.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1710 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.06%) have a different width. You should check the widths of: ['uniFF5D'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* four (U+0034): X=380.0,Y=729.0 (should be at cap-height 730?)

	* four (U+0034): X=409.0,Y=729.0 (should be at cap-height 730?)

	* section (U+00A7): X=507.0,Y=2.0 (should be at baseline 0?)

	* Aogonek (U+0104): X=519.0,Y=1.0 (should be at baseline 0?)

	* Aogonek (U+0104): X=482.0,Y=2.0 (should be at baseline 0?)

	* aogonek (U+0105): X=483.0,Y=1.0 (should be at baseline 0?)

	* uni0162 (U+0162): X=281.0,Y=2.0 (should be at baseline 0?)

	* uni0162 (U+0162): X=323.0,Y=2.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=388.0,Y=2.0 (should be at baseline 0?)

	* uni01EA (U+01EA): X=388.0,Y=2.0 (should be at baseline 0?)

	* Alphatonos (U+0386): X=131.0,Y=728.0 (should be at cap-height 730?)

	* Alphatonos (U+0386): X=160.0,Y=728.0 (should be at cap-height 730?)

	* Epsilontonos (U+0388): X=11.0,Y=728.0 (should be at cap-height 730?)

	* Epsilontonos (U+0388): X=40.0,Y=728.0 (should be at cap-height 730?)

	* Etatonos (U+0389): X=11.0,Y=728.0 (should be at cap-height 730?)

	* Etatonos (U+0389): X=40.0,Y=728.0 (should be at cap-height 730?)

	* Iotatonos (U+038A): X=11.0,Y=728.0 (should be at cap-height 730?)

	* Iotatonos (U+038A): X=40.0,Y=728.0 (should be at cap-height 730?)

	* Omicrontonos (U+038C): X=41.0,Y=728.0 (should be at cap-height 730?)

	* Omicrontonos (U+038C): X=70.0,Y=728.0 (should be at cap-height 730?)

	* Upsilontonos (U+038E): X=-9.0,Y=728.0 (should be at cap-height 730?)

	* Upsilontonos (U+038E): X=20.0,Y=728.0 (should be at cap-height 730?)

	* Omegatonos (U+038F): X=41.0,Y=728.0 (should be at cap-height 730?)

	* Omegatonos (U+038F): X=70.0,Y=728.0 (should be at cap-height 730?)

	* zeta (U+03B6): X=460.0,Y=1.0 (should be at baseline 0?)

	* uni03D5 (U+03D5): X=275.0,Y=731.0 (should be at cap-height 730?)

	* uni03D5 (U+03D5): X=325.0,Y=731.0 (should be at cap-height 730?)

	* uni0444 (U+0444): X=275.0,Y=731.0 (should be at cap-height 730?)

	* uni0444 (U+0444): X=325.0,Y=731.0 (should be at cap-height 730?)

	* quotesinglbase (U+201A): X=303.5,Y=0.5 (should be at baseline 0?)

	* quotedblbase (U+201E): X=198.5,Y=0.5 (should be at baseline 0?)

	* quotedblbase (U+201E): X=428.5,Y=0.5 (should be at baseline 0?)

	* uni21DE (U+21DE): X=323.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=277.0,Y=-1.0 (should be at baseline 0?)

	* uni21DF (U+21DF): X=277.0,Y=731.0 (should be at cap-height 730?)

	* uni21DF (U+21DF): X=323.0,Y=731.0 (should be at cap-height 730?)

	* uni21E7 (U+21E7): X=301.0,Y=729.0 (should be at cap-height 730?)

	* uni21EA (U+21EA): X=300.0,Y=728.0 (should be at cap-height 730?)

	* uni22BC (U+22BC): X=60.0,Y=732.0 (should be at cap-height 730?)

	* uni22BC (U+22BC): X=540.0,Y=732.0 (should be at cap-height 730?)

	* uni22BD (U+22BD): X=60.0,Y=732.0 (should be at cap-height 730?)

	* uni22BD (U+22BD): X=540.0,Y=732.0 (should be at cap-height 730?)

	* uni27C5 (U+27C5): X=470.0,Y=732.0 (should be at cap-height 730?)

	* uni27C6 (U+27C6): X=140.0,Y=732.0 (should be at cap-height 730?)

	* pitagon (U+E000): X=158.0,Y=2.0 (should be at baseline 0?)

	* piads (U+E001): X=158.0,Y=2.0 (should be at baseline 0?)

	* pioffice (U+E002): X=158.0,Y=2.0 (should be at baseline 0?)

	* pitagram (U+E003): X=158.0,Y=2.0 (should be at baseline 0?)

	* piweb (U+E004): X=158.0,Y=2.0 (should be at baseline 0?)

	* pisign (U+E005): X=158.0,Y=2.0 (should be at baseline 0?)

	* petapp (U+E006): X=534.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=303.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=293.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=318.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=336.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=331.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=328.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=326.0,Y=1.5 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=278.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=274.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=272.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?) 

	* picall (U+E009): X=158.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* asterisk (U+002A): L<<323.0,343.0>--<323.0,343.0>> -> L<<323.0,343.0>--<323.0,343.0>>

	* petapp (U+E006): L<<114.0,264.0>--<141.0,249.0>> -> L<<141.0,249.0>--<164.0,236.0>>

	* petapp (U+E006): L<<141.0,290.0>--<107.0,310.0>> -> L<<107.0,310.0>--<93.0,318.0>>

	* petapp (U+E006): L<<178.0,269.0>--<141.0,290.0>> -> L<<141.0,290.0>--<107.0,310.0>>

	* petapp (U+E006): L<<186.0,560.0>--<192.0,557.0>> -> L<<192.0,557.0>--<276.0,509.0>>

	* petapp (U+E006): L<<192.0,260.0>--<178.0,269.0>> -> L<<178.0,269.0>--<141.0,290.0>>

	* petapp (U+E006): L<<192.0,557.0>--<276.0,509.0>> -> L<<276.0,509.0>--<317.0,484.0>>

	* petapp (U+E006): L<<240.0,233.0>--<194.0,259.0>> -> L<<194.0,259.0>--<192.0,260.0>>

	* petapp (U+E006): L<<276.0,211.0>--<240.0,233.0>> -> L<<240.0,233.0>--<194.0,259.0>>

	* petapp (U+E006): L<<276.0,509.0>--<317.0,484.0>> -> L<<317.0,484.0>--<334.0,474.0>>

	* petapp (U+E006): L<<278.0,210.0>--<276.0,211.0>> -> L<<276.0,211.0>--<240.0,233.0>>

	* petapp (U+E006): L<<356.0,65.0>--<356.0,65.0>> -> L<<356.0,65.0>--<357.0,65.0>>

	* petapp (U+E006): L<<389.0,387.0>--<389.0,389.0>> -> L<<389.0,389.0>--<389.0,390.0>>

	* petapp (U+E006): L<<389.0,388.0>--<389.0,389.0>> -> L<<389.0,389.0>--<389.0,390.0>>

	* petapp (U+E006): L<<389.0,389.0>--<389.0,388.0>> -> L<<389.0,388.0>--<389.0,387.0>>

	* petapp (U+E006): L<<496.0,422.0>--<500.0,422.0>> -> L<<500.0,422.0>--<534.0,422.0>>

	* petapp.minimal (U+E007): L<<125.0,518.0>--<307.0,337.0>> -> L<<307.0,337.0>--<312.0,332.0>>

	* petapp.minimal (U+E007): L<<127.0,280.0>--<192.0,254.0>> -> L<<192.0,254.0>--<253.0,229.0>>

	* petapp.minimal (U+E007): L<<192.0,254.0>--<253.0,229.0>> -> L<<253.0,229.0>--<265.0,224.0>>

	* petapp.minimal (U+E007): L<<214.0,264.0>--<177.0,282.0>> -> L<<177.0,282.0>--<157.0,292.0>>

	* petapp.minimal (U+E007): L<<253.0,229.0>--<265.0,224.0>> -> L<<265.0,224.0>--<307.0,207.0>>

	* petapp.minimal (U+E007): L<<253.0,244.0>--<214.0,264.0>> -> L<<214.0,264.0>--<177.0,282.0>>

	* petapp.minimal (U+E007): L<<255.0,140.0>--<232.0,144.0>> -> L<<232.0,144.0>--<157.0,158.0>>

	* petapp.minimal (U+E007): L<<265.0,224.0>--<307.0,207.0>> -> L<<307.0,207.0>--<388.0,174.0>>

	* petapp.minimal (U+E007): L<<270.0,235.0>--<253.0,244.0>> -> L<<253.0,244.0>--<214.0,264.0>>

	* petapp.minimal (U+E007): L<<307.0,131.0>--<255.0,140.0>> -> L<<255.0,140.0>--<232.0,144.0>>

	* petapp.minimal (U+E007): L<<307.0,217.0>--<270.0,235.0>> -> L<<270.0,235.0>--<253.0,244.0>>

	* petapp.minimal (U+E007): L<<307.0,337.0>--<312.0,332.0>> -> L<<312.0,332.0>--<317.0,326.0>>

	* petapp.minimal (U+E007): L<<312.0,332.0>--<317.0,326.0>> -> L<<317.0,326.0>--<364.0,279.0>>

	* petapp.minimal (U+E007): L<<370.0,120.0>--<307.0,131.0>> -> L<<307.0,131.0>--<255.0,140.0>>

	* petapp.minimal (U+E007): L<<393.0,173.0>--<307.0,217.0>> -> L<<307.0,217.0>--<270.0,235.0>>

	* petapp.minimal (U+E007): L<<485.0,22.0>--<485.0,23.0>> -> L<<485.0,23.0>--<485.0,24.0>>

	* petapp.minimal (U+E007): L<<486.0,25.0>--<486.0,26.0>> -> L<<486.0,26.0>--<486.0,27.0>>

	* petapp.minimal (U+E007): L<<486.0,26.0>--<486.0,27.0>> -> L<<486.0,27.0>--<486.0,28.0>>

	* petapp.minimal (U+E007): L<<486.0,27.0>--<486.0,28.0>> -> L<<486.0,28.0>--<486.0,29.0>>

	* petapp.minimal (U+E007): L<<486.0,28.0>--<486.0,29.0>> -> L<<486.0,29.0>--<486.0,30.0>>

	* petapp.minimal (U+E007): L<<489.0,55.0>--<488.0,47.0>> -> L<<488.0,47.0>--<486.0,30.0>>

	* petapp.minimal (U+E007): L<<493.0,98.0>--<489.0,55.0>> -> L<<489.0,55.0>--<488.0,47.0>>

	* petapp.minimal (U+E007): L<<494.0,121.0>--<493.0,98.0>> -> L<<493.0,98.0>--<489.0,55.0>>

	* petapp.minimal (U+E007): L<<495.0,131.0>--<494.0,121.0>> -> L<<494.0,121.0>--<493.0,98.0>>

	* petapp.minimal (U+E007): L<<497.0,147.0>--<495.0,131.0>> -> L<<495.0,131.0>--<494.0,121.0>>

	* petapp.wpda (U+E008): L<<381.0,83.0>--<375.0,81.0>> -> L<<375.0,81.0>--<366.0,77.0>>

	* petapp.wpda (U+E008): L<<395.0,92.0>--<387.0,87.0>> -> L<<387.0,87.0>--<381.0,83.0>>

	* piads (U+E001): L<<332.0,488.0>--<536.0,340.0>> -> L<<536.0,340.0>--<539.0,338.0>>

	* piads (U+E001): L<<557.0,281.0>--<556.0,277.0>> -> L<<556.0,277.0>--<478.0,38.0>>

	* picall (U+E009): L<<332.0,488.0>--<536.0,340.0>> -> L<<536.0,340.0>--<539.0,338.0>>

	* pioffice (U+E002): L<<557.0,282.0>--<556.0,278.0>> -> L<<556.0,278.0>--<478.0,38.0>>

	* pisafe (U+E010): L<<300.0,636.0>--<383.0,605.0>> -> L<<383.0,605.0>--<502.0,563.0>>

	* pisafe (U+E010): L<<383.0,605.0>--<502.0,563.0>> -> L<<502.0,563.0>--<531.0,552.0>>

	* pisafe (U+E010): L<<40.0,288.0>--<40.0,390.0>> -> L<<40.0,390.0>--<40.0,394.0>>

	* pisafe (U+E010): L<<502.0,563.0>--<531.0,552.0>> -> L<<531.0,552.0>--<536.0,550.0>>

	* pisafe (U+E010): L<<63.0,550.0>--<68.0,552.0>> -> L<<68.0,552.0>--<97.0,563.0>>

	* pisafe (U+E010): L<<68.0,552.0>--<97.0,563.0>> -> L<<97.0,563.0>--<216.0,605.0>>

	* pisafe (U+E010): L<<97.0,563.0>--<216.0,605.0>> -> L<<216.0,605.0>--<299.0,636.0>>

	* pisign (U+E005): L<<557.0,282.0>--<556.0,278.0>> -> L<<556.0,278.0>--<478.0,38.0>>

	* pitagon (U+E000): L<<122.0,38.0>--<43.0,279.0>> -> L<<43.0,279.0>--<42.0,282.0>>

	* pitagram (U+E003): L<<557.0,282.0>--<556.0,278.0>> -> L<<556.0,278.0>--<478.0,38.0>>

	* piweb (U+E004): L<<557.0,282.0>--<556.0,278.0>> -> L<<556.0,278.0>--<478.0,38.0>>

	* sparks (U+E011): L<<130.0,436.0>--<136.0,434.0>> -> L<<136.0,434.0>--<245.0,395.0>>

	* sparks (U+E011): L<<136.0,434.0>--<245.0,395.0>> -> L<<245.0,395.0>--<263.0,389.0>>

	* sparks (U+E011): L<<183.0,341.0>--<224.0,306.0>> -> L<<224.0,306.0>--<235.0,295.0>>

	* sparks (U+E011): L<<251.0,59.0>--<73.0,367.0>> -> L<<73.0,367.0>--<44.0,418.0>>

	* sparks (U+E011): L<<256.0,362.0>--<231.0,360.0>> -> L<<231.0,360.0>--<219.0,359.0>>

	* sparks (U+E011): L<<276.0,14.0>--<251.0,59.0>> -> L<<251.0,59.0>--<73.0,367.0>>

	* sparks (U+E011): L<<336.0,389.0>--<358.0,397.0>> -> L<<358.0,397.0>--<463.0,434.0>>

	* sparks (U+E011): L<<348.0,58.0>--<331.0,29.0>> -> L<<331.0,29.0>--<323.0,14.0>>

	* sparks (U+E011): L<<358.0,397.0>--<463.0,434.0>> -> L<<463.0,434.0>--<478.0,440.0>>

	* sparks (U+E011): L<<364.0,295.0>--<375.0,306.0>> -> L<<375.0,306.0>--<416.0,341.0>>

	* sparks (U+E011): L<<368.0,360.0>--<347.0,362.0>> -> L<<347.0,362.0>--<341.0,362.0>>

	* sparks (U+E011): L<<391.0,358.0>--<368.0,360.0>> -> L<<368.0,360.0>--<347.0,362.0>>

	* sparks (U+E011): L<<392.0,358.0>--<391.0,358.0>> -> L<<391.0,358.0>--<368.0,360.0>>

	* sparks (U+E011): L<<411.0,357.0>--<392.0,358.0>> -> L<<392.0,358.0>--<391.0,358.0>>

	* sparks (U+E011): L<<412.0,357.0>--<411.0,357.0>> -> L<<411.0,357.0>--<392.0,358.0>>

	* sparks (U+E011): L<<446.0,227.0>--<348.0,58.0>> -> L<<348.0,58.0>--<331.0,29.0>>

	* sparks (U+E011): L<<463.0,434.0>--<478.0,440.0>> -> L<<478.0,440.0>--<523.0,456.0>>

	* sparks (U+E011): L<<530.0,373.0>--<446.0,227.0>> -> L<<446.0,227.0>--<348.0,58.0>>

	* sparks (U+E011): L<<555.0,418.0>--<530.0,373.0>> -> L<<530.0,373.0>--<446.0,227.0>>

	* sparks (U+E011): L<<76.0,456.0>--<130.0,436.0>> -> L<<130.0,436.0>--<136.0,434.0>>

	* uni0162 (U+0162): L<<324.0,5.0>--<323.0,2.0>> -> L<<323.0,2.0>--<314.0,-22.0>>

	* uni0163 (U+0163): L<<488.0,0.0>--<355.0,0.0>> -> L<<355.0,0.0>--<353.0,0.0>>

	* uni203D (U+203D): L<<250.0,205.0>--<240.0,465.0>> -> L<<240.0,465.0>--<240.0,565.0>>

	* uni203D (U+203D): L<<290.0,565.0>--<290.0,465.0>> -> L<<290.0,465.0>--<287.0,375.0>>

	* uni229B (U+229B): L<<323.0,328.0>--<323.0,328.0>> -> L<<323.0,328.0>--<323.0,328.0>>

	* uni2358 (U+2358): L<<277.0,430.0>--<267.0,560.0>> -> L<<267.0,560.0>--<267.0,730.0>>

	* uni2358 (U+2358): L<<333.0,730.0>--<333.0,560.0>> -> L<<333.0,560.0>--<324.0,430.0>>

	* uni235E (U+235E): L<<277.0,430.0>--<267.0,560.0>> -> L<<267.0,560.0>--<267.0,730.0>>

	* uni235E (U+235E): L<<333.0,730.0>--<333.0,560.0>> -> L<<333.0,560.0>--<324.0,430.0>>

	* uni26A0 (U+26A0): L<<266.0,550.0>--<266.0,479.0>> -> L<<266.0,479.0>--<275.0,200.0>> 

	* uni26A0 (U+26A0): L<<324.0,200.0>--<334.0,479.0>> -> L<<334.0,479.0>--<334.0,550.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): L<<269.0,335.0>--<131.0,705.0>>/B<<131.0,705.0>-<134.0,678.0>-<136.0,635.0>> = 14.113964228060471

	* Mu (U+039C): L<<269.0,335.0>--<131.0,705.0>>/B<<131.0,705.0>-<134.0,678.0>-<136.0,635.0>> = 14.113964228060471

	* W (U+0057): B<<165.5,87.0>-<169.0,58.0>-<171.0,35.0>>/B<<171.0,35.0>-<174.0,58.0>-<177.5,87.0>> = 12.401148699282784

	* Wacute (U+1E82): B<<165.5,87.0>-<169.0,58.0>-<171.0,35.0>>/B<<171.0,35.0>-<174.0,58.0>-<177.5,87.0>> = 12.401148699282784

	* Wcircumflex (U+0174): B<<165.5,87.0>-<169.0,58.0>-<171.0,35.0>>/B<<171.0,35.0>-<174.0,58.0>-<177.5,87.0>> = 12.401148699282784

	* Wdieresis (U+1E84): B<<165.5,87.0>-<169.0,58.0>-<171.0,35.0>>/B<<171.0,35.0>-<174.0,58.0>-<177.5,87.0>> = 12.401148699282784

	* Wgrave (U+1E80): B<<165.5,87.0>-<169.0,58.0>-<171.0,35.0>>/B<<171.0,35.0>-<174.0,58.0>-<177.5,87.0>> = 12.401148699282784

	* perthousand (U+2030): B<<407.0,271.5>-<430.0,253.0>-<432.0,221.0>>/B<<432.0,221.0>-<435.0,253.0>-<458.0,271.5>> = 8.932159417852464

	* perthousand (U+2030): B<<458.0,14.0>-<435.0,33.0>-<433.0,64.0>>/B<<433.0,64.0>-<429.0,33.0>-<405.5,14.0>> = 11.043765346343616

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<364.0,279.0>-<367.0,276.0>-<370.0,274.0>>/L<<370.0,274.0>--<364.0,279.0>> = 6.115503566285384

	* petapp.minimal (U+E007): B<<402.0,326.0>-<402.0,324.0>-<403.0,322.0>>/L<<403.0,322.0>--<402.0,326.0>> = 12.528807709151492

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<403.0,322.0>--<402.0,326.0>>/B<<402.0,326.0>-<402.0,324.0>-<403.0,322.0>> = 14.036243467926484

	* petapp.minimal (U+E007): L<<404.0,317.0>--<403.0,320.0>>/B<<403.0,320.0>-<404.0,318.0>-<404.0,317.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<485.0,44.0>--<486.0,41.0>>/B<<486.0,41.0>-<485.0,43.0>-<485.0,44.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,238.0>--<88.0,326.0>>/B<<88.0,326.0>-<93.0,305.0>-<107.0,292.0>> = 13.392497753751098

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<89.0,577.0>-<98.5,557.0>> = 2.4895529219991284

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni041C (U+041C): L<<269.0,335.0>--<131.0,705.0>>/B<<131.0,705.0>-<134.0,678.0>-<136.0,635.0>> = 14.113964228060471

	* uni0431 (U+0431): L<<148.0,475.0>--<148.0,385.0>>/B<<148.0,385.0>-<157.0,441.0>-<199.0,473.0>> = 9.130176482278666

	* uni2116 (U+2116): B<<102.0,602.0>-<92.0,643.0>-<85.0,670.0>>/B<<85.0,670.0>-<86.0,651.0>-<86.5,617.0>> = 11.521667576356743

	* uni2116 (U+2116): B<<276.0,120.5>-<286.0,82.0>-<291.0,59.0>>/B<<291.0,59.0>-<290.0,79.0>-<288.5,113.0>> = 9.40236850178064

	* uni227A (U+227A): B<<341.0,372.0>-<269.0,337.0>-<175.0,332.0>>/B<<175.0,332.0>-<269.0,325.0>-<341.0,289.0>> = 7.303624566364305

	* uni227B (U+227B): B<<259.0,289.0>-<331.0,325.0>-<425.0,332.0>>/B<<425.0,332.0>-<331.0,337.0>-<259.0,372.0>> = 7.303624566364305

	* uni227C (U+227C): B<<341.0,497.0>-<269.0,462.0>-<175.0,457.0>>/B<<175.0,457.0>-<269.0,450.0>-<341.0,414.0>> = 7.303624566364305

	* uni22CE (U+22CE): B<<256.5,381.0>-<291.0,309.0>-<297.0,215.0>>/B<<297.0,215.0>-<304.0,309.0>-<339.5,381.0>> = 7.91106890247665

	* uni26A1 (U+26A1): L<<580.0,440.0>--<50.0,-110.0>>/L<<50.0,-110.0>--<295.0,310.0>> = 13.68265114620652

	* w (U+0077): B<<173.5,80.0>-<176.0,56.0>-<177.0,35.0>>/B<<177.0,35.0>-<179.0,56.0>-<183.5,79.5>> = 8.166643024911759

	* w (U+0077): B<<310.0,451.5>-<303.0,485.0>-<301.0,507.0>>/B<<301.0,507.0>-<300.0,485.0>-<293.0,451.5>> = 7.7969911102345595

	* w (U+0077): B<<419.0,82.0>-<424.0,58.0>-<425.0,35.0>>/B<<425.0,35.0>-<427.0,57.0>-<428.5,82.0>> = 7.683981829733913

	* wacute (U+1E83): B<<173.5,80.0>-<176.0,56.0>-<177.0,35.0>>/B<<177.0,35.0>-<179.0,56.0>-<183.5,79.5>> = 8.166643024911759

	* wacute (U+1E83): B<<310.0,451.5>-<303.0,485.0>-<301.0,507.0>>/B<<301.0,507.0>-<300.0,485.0>-<293.0,451.5>> = 7.7969911102345595

	* wacute (U+1E83): B<<419.0,82.0>-<424.0,58.0>-<425.0,35.0>>/B<<425.0,35.0>-<427.0,57.0>-<428.5,82.0>> = 7.683981829733913

	* wcircumflex (U+0175): B<<173.5,80.0>-<176.0,56.0>-<177.0,35.0>>/B<<177.0,35.0>-<179.0,56.0>-<183.5,79.5>> = 8.166643024911759

	* wcircumflex (U+0175): B<<310.0,451.5>-<303.0,485.0>-<301.0,507.0>>/B<<301.0,507.0>-<300.0,485.0>-<293.0,451.5>> = 7.7969911102345595

	* wcircumflex (U+0175): B<<419.0,82.0>-<424.0,58.0>-<425.0,35.0>>/B<<425.0,35.0>-<427.0,57.0>-<428.5,82.0>> = 7.683981829733913

	* wdieresis (U+1E85): B<<173.5,80.0>-<176.0,56.0>-<177.0,35.0>>/B<<177.0,35.0>-<179.0,56.0>-<183.5,79.5>> = 8.166643024911759

	* wdieresis (U+1E85): B<<310.0,451.5>-<303.0,485.0>-<301.0,507.0>>/B<<301.0,507.0>-<300.0,485.0>-<293.0,451.5>> = 7.7969911102345595

	* wdieresis (U+1E85): B<<419.0,82.0>-<424.0,58.0>-<425.0,35.0>>/B<<425.0,35.0>-<427.0,57.0>-<428.5,82.0>> = 7.683981829733913

	* wgrave (U+1E81): B<<173.5,80.0>-<176.0,56.0>-<177.0,35.0>>/B<<177.0,35.0>-<179.0,56.0>-<183.5,79.5>> = 8.166643024911759

	* wgrave (U+1E81): B<<310.0,451.5>-<303.0,485.0>-<301.0,507.0>>/B<<301.0,507.0>-<300.0,485.0>-<293.0,451.5>> = 7.7969911102345595 

	* wgrave (U+1E81): B<<419.0,82.0>-<424.0,58.0>-<425.0,35.0>>/B<<425.0,35.0>-<427.0,57.0>-<428.5,82.0>> = 7.683981829733913 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0427 (U+0427): L<<440.0,0.0>--<441.0,289.0>>

	* uni0447 (U+0447): L<<436.0,0.0>--<437.0,202.0>>

	* uni04B6 (U+04B6): L<<430.0,0.0>--<431.0,289.0>>

	* uni04B7 (U+04B7): L<<433.0,0.0>--<434.0,202.0>>

	* uni04BA (U+04BA): L<<160.0,730.0>--<159.0,441.0>>

	* uni04BB (U+04BB): L<<164.0,550.0>--<163.0,348.0>>

	* uni04F4 (U+04F4): L<<440.0,0.0>--<441.0,289.0>>

	* uni04F5 (U+04F5): L<<436.0,0.0>--<437.0,202.0>>

	* uni207A (U+207A): L<<320.0,585.0>--<319.0,464.0>> 

	* uni2352 (U+2352): L<<279.0,143.0>--<277.0,685.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] PitagonSansMono-LightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Pitagon Sans Mono Light' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, exclam_equal_equal.liga.ss19.001, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- dollar.cv14

	- eight.dnom

	- eight.numr

	- exclam_equal.liga.ss19.001

	- exclam_equal_equal.liga.ss19.001

	- five.dnom

	- five.numr

	- four.dnom

	- four.numr

	- nine.dnom

	- nine.numr

	- one.dnom

	- one.numr

	- seven.dnom

	- seven.numr

	- six.dnom

	- six.numr

	- three.dnom

	- three.numr

	- two.dnom

	- two.numr

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- zero.dnom 

	- zero.numr
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1697 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* Oslash (U+00D8): X=620.0,Y=728.0 (should be at cap-height 730?)

	* eogonek (U+0119): X=355.0,Y=1.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=354.0,Y=1.0 (should be at baseline 0?)

	* uogonek (U+0173): X=353.0,Y=1.0 (should be at baseline 0?)

	* uni01EA (U+01EA): X=354.0,Y=1.0 (should be at baseline 0?)

	* uni01EB (U+01EB): X=353.0,Y=1.0 (should be at baseline 0?)

	* Oslashacute (U+01FE): X=620.0,Y=728.0 (should be at cap-height 730?)

	* ogonek (U+02DB): X=287.0,Y=1.0 (should be at baseline 0?)

	* uni0328 (U+0328): X=-313.0,Y=1.0 (should be at baseline 0?)

	* zeta (U+03B6): X=395.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=338.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=262.0,Y=-1.0 (should be at baseline 0?)

	* uni21DF (U+21DF): X=262.0,Y=731.0 (should be at cap-height 730?)

	* uni21DF (U+21DF): X=338.0,Y=731.0 (should be at cap-height 730?)

	* uni21E7 (U+21E7): X=301.0,Y=729.0 (should be at cap-height 730?)

	* uni21EA (U+21EA): X=300.0,Y=728.0 (should be at cap-height 730?)

	* uni27C6 (U+27C6): X=302.0,Y=-2.0 (should be at baseline 0?)

	* piads (U+E001): X=158.0,Y=2.0 (should be at baseline 0?)

	* pioffice (U+E002): X=158.0,Y=2.0 (should be at baseline 0?)

	* pitagram (U+E003): X=158.0,Y=2.0 (should be at baseline 0?)

	* piweb (U+E004): X=158.0,Y=2.0 (should be at baseline 0?)

	* pisign (U+E005): X=158.0,Y=2.0 (should be at baseline 0?)

	* petapp (U+E006): X=534.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=303.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=293.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=318.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=336.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=331.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=328.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=326.0,Y=1.5 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=278.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=274.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=272.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?) 

	* picall (U+E009): X=158.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): B<<502.0,599.0>-<514.0,658.0>-<525.0,704.0>>/L<<525.0,704.0>--<348.0,339.0>> = 12.42159304169058

	* M (U+004D): L<<267.0,342.0>--<208.0,697.0>>/B<<208.0,697.0>-<204.0,632.0>-<194.0,547.5>> = 12.95760117858538

	* Mu (U+039C): B<<502.0,599.0>-<514.0,658.0>-<525.0,704.0>>/L<<525.0,704.0>--<348.0,339.0>> = 12.42159304169058

	* Mu (U+039C): L<<267.0,342.0>--<208.0,697.0>>/B<<208.0,697.0>-<204.0,632.0>-<194.0,547.5>> = 12.95760117858538

	* W (U+0057): B<<137.0,120.0>-<134.0,81.0>-<132.0,57.0>>/B<<132.0,57.0>-<139.0,81.0>-<148.5,120.0>> = 11.496563017585768

	* W (U+0057): B<<361.0,616.0>-<364.0,652.0>-<365.0,673.0>>/B<<365.0,673.0>-<359.0,652.0>-<350.0,616.0>> = 13.21908490701659

	* W (U+0057): B<<396.5,119.5>-<395.0,81.0>-<393.0,57.0>>/B<<393.0,57.0>-<400.0,81.0>-<409.5,120.0>> = 11.496563017585768

	* Wacute (U+1E82): B<<137.0,120.0>-<134.0,81.0>-<132.0,57.0>>/B<<132.0,57.0>-<139.0,81.0>-<148.5,120.0>> = 11.496563017585768

	* Wacute (U+1E82): B<<361.0,616.0>-<364.0,652.0>-<365.0,673.0>>/B<<365.0,673.0>-<359.0,652.0>-<350.0,616.0>> = 13.21908490701659

	* Wacute (U+1E82): B<<396.5,119.5>-<395.0,81.0>-<393.0,57.0>>/B<<393.0,57.0>-<400.0,81.0>-<409.5,120.0>> = 11.496563017585768

	* Wcircumflex (U+0174): B<<137.0,120.0>-<134.0,81.0>-<132.0,57.0>>/B<<132.0,57.0>-<139.0,81.0>-<148.5,120.0>> = 11.496563017585768

	* Wcircumflex (U+0174): B<<361.0,616.0>-<364.0,652.0>-<365.0,673.0>>/B<<365.0,673.0>-<359.0,652.0>-<350.0,616.0>> = 13.21908490701659

	* Wcircumflex (U+0174): B<<396.5,119.5>-<395.0,81.0>-<393.0,57.0>>/B<<393.0,57.0>-<400.0,81.0>-<409.5,120.0>> = 11.496563017585768

	* Wdieresis (U+1E84): B<<137.0,120.0>-<134.0,81.0>-<132.0,57.0>>/B<<132.0,57.0>-<139.0,81.0>-<148.5,120.0>> = 11.496563017585768

	* Wdieresis (U+1E84): B<<361.0,616.0>-<364.0,652.0>-<365.0,673.0>>/B<<365.0,673.0>-<359.0,652.0>-<350.0,616.0>> = 13.21908490701659

	* Wdieresis (U+1E84): B<<396.5,119.5>-<395.0,81.0>-<393.0,57.0>>/B<<393.0,57.0>-<400.0,81.0>-<409.5,120.0>> = 11.496563017585768

	* Wgrave (U+1E80): B<<137.0,120.0>-<134.0,81.0>-<132.0,57.0>>/B<<132.0,57.0>-<139.0,81.0>-<148.5,120.0>> = 11.496563017585768

	* Wgrave (U+1E80): B<<361.0,616.0>-<364.0,652.0>-<365.0,673.0>>/B<<365.0,673.0>-<359.0,652.0>-<350.0,616.0>> = 13.21908490701659

	* Wgrave (U+1E80): B<<396.5,119.5>-<395.0,81.0>-<393.0,57.0>>/B<<393.0,57.0>-<400.0,81.0>-<409.5,120.0>> = 11.496563017585768

	* a (U+0061): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* aacute (U+00E1): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* abreve (U+0103): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* acircumflex (U+00E2): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* adieresis (U+00E4): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* agrave (U+00E0): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* alpha (U+03B1): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* alphatonos (U+03AC): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* amacron (U+0101): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* aogonek (U+0105): B<<393.0,47.5>-<380.0,75.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.927602155972298

	* aring (U+00E5): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* arrowboth (U+2194): L<<578.0,295.0>--<21.0,295.0>>/B<<21.0,295.0>-<45.0,289.0>-<69.0,257.0>> = 14.036243467926457

	* arrowleft (U+2190): L<<580.0,295.0>--<111.0,295.0>>/B<<111.0,295.0>-<135.0,289.0>-<159.0,257.0>> = 14.036243467926457

	* arrowright (U+2192): B<<441.0,257.0>-<465.0,289.0>-<489.0,295.0>>/L<<489.0,295.0>--<20.0,295.0>> = 14.036243467926457

	* atilde (U+00E3): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* b (U+0062): B<<185.5,19.0>-<150.0,48.0>-<148.0,99.0>>/L<<148.0,99.0>--<132.0,0.0>> = 11.426284523521181

	* b (U+0062): L<<223.0,573.0>--<202.0,451.0>>/B<<202.0,451.0>-<219.0,503.0>-<263.5,531.5>> = 8.33708363873393

	* d (U+0064): B<<414.0,530.5>-<450.0,501.0>-<452.0,451.0>>/L<<452.0,451.0>--<470.0,573.0>> = 10.683535230030996

	* d (U+0064): L<<380.0,0.0>--<396.0,99.0>>/B<<396.0,99.0>-<379.0,47.0>-<335.5,18.5>> = 8.923221076880477

	* dcaron (U+010F): B<<369.5,531.5>-<401.0,503.0>-<403.0,453.0>>/L<<403.0,453.0>--<421.0,573.0>> = 10.821375652586612

	* dcaron (U+010F): L<<330.0,0.0>--<345.0,89.0>>/B<<345.0,89.0>-<327.0,42.0>-<287.5,16.0>> = 11.38909074091777

	* endOfMediumcontrol (U+2419): B<<534.5,212.5>-<544.0,262.0>-<560.0,300.0>>/L<<560.0,300.0>--<436.0,96.0>> = 8.459384818002684

	* omega (U+03C9): B<<294.0,22.0>-<268.0,54.0>-<272.0,108.0>>/B<<272.0,108.0>-<260.0,51.0>-<225.0,20.5>> = 7.65226324056912

	* omegatonos (U+03CE): B<<294.0,22.0>-<268.0,54.0>-<272.0,108.0>>/B<<272.0,108.0>-<260.0,51.0>-<225.0,20.5>> = 7.65226324056912

	* p (U+0070): L<<216.0,530.0>--<203.0,451.0>>/B<<203.0,451.0>-<220.0,503.0>-<264.0,531.5>> = 8.759091132406985

	* perthousand (U+2030): B<<395.0,271.0>-<415.0,252.0>-<412.0,220.0>>/B<<412.0,220.0>-<421.0,252.0>-<447.0,271.0>> = 10.352812786160532

	* perthousand (U+2030): B<<405.5,14.0>-<385.0,33.0>-<388.0,65.0>>/B<<388.0,65.0>-<380.0,33.0>-<353.5,14.0>> = 8.680418425071275

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<365.0,279.0>-<368.0,276.0>-<370.0,275.0>>/L<<370.0,275.0>--<365.0,279.0>> = 12.094757077012058

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>>/L<<437.0,404.0>--<440.0,406.0>> = 7.125016348901757

	* petapp.minimal (U+E007): B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>>/L<<442.0,407.0>--<447.0,409.0>> = 4.763641690726143

	* petapp.minimal (U+E007): B<<468.0,415.0>-<467.0,415.0>-<465.0,414.0>>/L<<465.0,414.0>--<468.0,415.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<486.0,17.0>-<484.0,7.0>-<483.0,0.0>>/B<<483.0,0.0>-<483.0,3.0>-<483.0,6.5>> = 8.13010235415596

	* petapp.minimal (U+E007): L<<404.0,317.0>--<403.0,320.0>>/B<<403.0,320.0>-<404.0,318.0>-<404.0,317.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<437.0,404.0>--<440.0,406.0>>/B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>> = 11.309932474020227

	* petapp.minimal (U+E007): L<<442.0,407.0>--<447.0,409.0>>/B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>> = 3.3664606634297236

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<475.0,91.0>--<476.0,88.0>>/B<<476.0,88.0>-<475.0,90.0>-<474.5,91.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<89.0,577.0>-<98.5,557.0>> = 2.4895529219991284

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* q (U+0071): B<<413.0,530.5>-<449.0,501.0>-<451.0,451.0>>/L<<451.0,451.0>--<467.0,550.0>> = 11.471152000264679

	* q (U+0071): L<<376.0,-23.0>--<397.0,98.0>>/B<<397.0,98.0>-<380.0,47.0>-<336.0,18.5>> = 8.589126455069394

	* thorn (U+00FE): B<<181.5,19.0>-<146.0,48.0>-<144.0,99.0>>/L<<144.0,99.0>--<128.0,0.0>> = 11.426284523521181

	* thorn (U+00FE): L<<219.0,573.0>--<198.0,451.0>>/B<<198.0,451.0>-<215.0,503.0>-<259.5,531.5>> = 8.33708363873393

	* trademark (U+2122): B<<428.5,658.0>-<425.0,683.0>-<421.0,703.0>>/B<<421.0,703.0>-<420.0,683.0>-<417.5,651.0>> = 14.172337700131925

	* trademark (U+2122): B<<573.5,651.0>-<581.0,683.0>-<586.0,703.0>>/B<<586.0,703.0>-<577.0,683.0>-<565.0,657.0>> = 10.191501850027691

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni01CE (U+01CE): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni0418 (U+0418): B<<481.0,582.0>-<488.0,615.0>-<494.0,638.0>>/L<<494.0,638.0>--<157.0,0.0>> = 13.222729997439428

	* uni0419 (U+0419): B<<481.0,582.0>-<488.0,615.0>-<494.0,638.0>>/L<<494.0,638.0>--<157.0,0.0>> = 13.222729997439428

	* uni041C (U+041C): B<<502.0,599.0>-<514.0,658.0>-<525.0,704.0>>/L<<525.0,704.0>--<348.0,339.0>> = 12.42159304169058

	* uni041C (U+041C): L<<267.0,342.0>--<208.0,697.0>>/B<<208.0,697.0>-<204.0,632.0>-<194.0,547.5>> = 12.95760117858538

	* uni0430 (U+0430): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni0431 (U+0431): L<<187.0,463.0>--<179.0,410.0>>/B<<179.0,410.0>-<199.0,460.0>-<243.5,486.5>> = 13.217788006237873

	* uni0434 (U+0434): B<<423.5,484.0>-<460.0,455.0>-<463.0,403.0>>/L<<463.0,403.0>--<472.0,463.0>> = 11.832631284383096

	* uni0440 (U+0440): L<<216.0,530.0>--<203.0,451.0>>/B<<203.0,451.0>-<220.0,503.0>-<264.0,531.5>> = 8.759091132406985

	* uni04E4 (U+04E4): B<<481.0,582.0>-<488.0,615.0>-<494.0,638.0>>/L<<494.0,638.0>--<157.0,0.0>> = 13.222729997439428

	* uni1EA1 (U+1EA1): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni1EA3 (U+1EA3): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni1EA5 (U+1EA5): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni1EA7 (U+1EA7): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni1EA9 (U+1EA9): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni1EAB (U+1EAB): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni1EAD (U+1EAD): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni1EAF (U+1EAF): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni1EB1 (U+1EB1): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni1EB3 (U+1EB3): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni1EB5 (U+1EB5): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni1EB7 (U+1EB7): B<<403.0,31.0>-<378.0,62.0>-<385.0,110.0>>/B<<385.0,110.0>-<366.0,55.0>-<319.0,22.5>> = 10.760559540291425

	* uni2116 (U+2116): B<<152.5,594.0>-<150.0,627.0>-<148.0,652.0>>/B<<148.0,652.0>-<146.0,628.0>-<142.5,595.5>> = 9.337562950627003

	* uni2116 (U+2116): B<<252.5,136.5>-<255.0,103.0>-<256.0,78.0>>/B<<256.0,78.0>-<258.0,103.0>-<261.0,136.5>> = 6.864531302539317

	* uni227A (U+227A): B<<379.0,369.0>-<302.0,333.0>-<208.0,327.0>>/B<<208.0,327.0>-<300.0,321.0>-<366.0,286.5>> = 7.38361977946671

	* uni227B (U+227B): B<<252.0,291.0>-<329.0,327.0>-<423.0,334.0>>/B<<423.0,334.0>-<331.0,340.0>-<265.0,374.0>> = 7.990243121330726

	* uni227C (U+227C): B<<399.0,494.0>-<322.0,458.0>-<228.0,452.0>>/B<<228.0,452.0>-<320.0,446.0>-<386.0,411.5>> = 7.38361977946671

	* uni22CE (U+22CE): B<<274.0,385.5>-<297.0,314.0>-<288.0,221.0>>/B<<288.0,221.0>-<309.0,314.0>-<356.5,385.5>> = 7.1968155337661655

	* uni234B (U+234B): L<<276.0,71.0>--<276.0,557.0>>/L<<276.0,557.0>--<153.0,71.0>> = 14.202558761363669

	* uni234B (U+234B): L<<447.0,71.0>--<324.0,556.0>>/L<<324.0,556.0>--<324.0,71.0>> = 14.230653995020582

	* uni2352 (U+2352): L<<154.0,659.0>--<280.0,169.0>>/L<<280.0,169.0>--<276.0,659.0>> = 13.95306286747249

	* uni2352 (U+2352): L<<324.0,659.0>--<324.0,169.0>>/L<<324.0,169.0>--<447.0,659.0>> = 14.091256201393758

	* uni236C (U+236C): L<<212.0,533.0>--<191.0,396.0>>/B<<191.0,396.0>-<215.0,457.0>-<266.0,457.0>> = 12.762058104679202

	* uni236C (U+236C): L<<416.0,197.0>--<440.0,351.0>>/B<<440.0,351.0>-<416.0,287.0>-<363.0,287.0>> = 11.698086455955083

	* uni26A1 (U+26A1): L<<580.0,440.0>--<50.0,-110.0>>/L<<50.0,-110.0>--<295.0,310.0>> = 13.68265114620652

	* w (U+0077): B<<142.5,104.0>-<141.0,78.0>-<140.0,61.0>>/B<<140.0,61.0>-<144.0,78.0>-<151.5,104.0>> = 9.87405925175738

	* w (U+0077): B<<332.5,442.5>-<333.0,475.0>-<334.0,493.0>>/B<<334.0,493.0>-<330.0,475.0>-<320.0,442.5>> = 9.348977589287225

	* w (U+0077): B<<391.5,105.0>-<391.0,79.0>-<390.0,61.0>>/B<<390.0,61.0>-<394.0,79.0>-<401.0,105.0>> = 9.348977589287225

	* wacute (U+1E83): B<<142.5,104.0>-<141.0,78.0>-<140.0,61.0>>/B<<140.0,61.0>-<144.0,78.0>-<151.5,104.0>> = 9.87405925175738

	* wacute (U+1E83): B<<332.5,442.5>-<333.0,475.0>-<334.0,493.0>>/B<<334.0,493.0>-<330.0,475.0>-<320.0,442.5>> = 9.348977589287225

	* wacute (U+1E83): B<<391.5,105.0>-<391.0,79.0>-<390.0,61.0>>/B<<390.0,61.0>-<394.0,79.0>-<401.0,105.0>> = 9.348977589287225

	* wcircumflex (U+0175): B<<142.5,104.0>-<141.0,78.0>-<140.0,61.0>>/B<<140.0,61.0>-<144.0,78.0>-<151.5,104.0>> = 9.87405925175738

	* wcircumflex (U+0175): B<<332.5,442.5>-<333.0,475.0>-<334.0,493.0>>/B<<334.0,493.0>-<330.0,475.0>-<320.0,442.5>> = 9.348977589287225

	* wcircumflex (U+0175): B<<391.5,105.0>-<391.0,79.0>-<390.0,61.0>>/B<<390.0,61.0>-<394.0,79.0>-<401.0,105.0>> = 9.348977589287225

	* wdieresis (U+1E85): B<<142.5,104.0>-<141.0,78.0>-<140.0,61.0>>/B<<140.0,61.0>-<144.0,78.0>-<151.5,104.0>> = 9.87405925175738

	* wdieresis (U+1E85): B<<332.5,442.5>-<333.0,475.0>-<334.0,493.0>>/B<<334.0,493.0>-<330.0,475.0>-<320.0,442.5>> = 9.348977589287225

	* wdieresis (U+1E85): B<<391.5,105.0>-<391.0,79.0>-<390.0,61.0>>/B<<390.0,61.0>-<394.0,79.0>-<401.0,105.0>> = 9.348977589287225

	* wgrave (U+1E81): B<<142.5,104.0>-<141.0,78.0>-<140.0,61.0>>/B<<140.0,61.0>-<144.0,78.0>-<151.5,104.0>> = 9.87405925175738

	* wgrave (U+1E81): B<<332.5,442.5>-<333.0,475.0>-<334.0,493.0>>/B<<334.0,493.0>-<330.0,475.0>-<320.0,442.5>> = 9.348977589287225 

	* wgrave (U+1E81): B<<391.5,105.0>-<391.0,79.0>-<390.0,61.0>>/B<<390.0,61.0>-<394.0,79.0>-<401.0,105.0>> = 9.348977589287225 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[19] PitagonSansMono-BoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Pitagon Sans Mono' / SUBFAMILY_NAME = 'Bold Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, exclam_equal_equal.liga.ss19.001, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- dollar.cv14

	- eight.dnom

	- eight.numr

	- exclam_equal.liga.ss19.001

	- exclam_equal_equal.liga.ss19.001

	- five.dnom

	- five.numr

	- four.dnom

	- four.numr

	- nine.dnom

	- nine.numr

	- one.dnom

	- one.numr

	- seven.dnom

	- seven.numr

	- six.dnom

	- six.numr

	- three.dnom

	- three.numr

	- two.dnom

	- two.numr

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- zero.dnom 

	- zero.numr
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1697 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 2 glyphs (0.11%) have a different width. You should check the widths of: ['periodcentered.loclCAT', 'periodcentered.loclCAT.case'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=441.0,Y=1.0 (should be at baseline 0?)

	* parenright (U+0029): X=71.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=14.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=141.0,Y=1.0 (should be at baseline 0?)

	* onequarter (U+00BC): X=196.0,Y=729.0 (should be at cap-height 730?)

	* onequarter (U+00BC): X=299.0,Y=729.0 (should be at cap-height 730?)

	* eth (U+00F0): X=522.0,Y=731.0 (should be at cap-height 730?)

	* eth (U+00F0): X=542.5,Y=729.5 (should be at cap-height 730?)

	* ccaron (U+010D): X=396.0,Y=728.0 (should be at cap-height 730?)

	* ecaron (U+011B): X=387.0,Y=728.0 (should be at cap-height 730?)

	* ncaron (U+0148): X=392.0,Y=728.0 (should be at cap-height 730?)

	* rcaron (U+0159): X=407.0,Y=728.0 (should be at cap-height 730?)

	* scaron (U+0161): X=387.0,Y=728.0 (should be at cap-height 730?)

	* zcaron (U+017E): X=387.0,Y=728.0 (should be at cap-height 730?)

	* uni01CE (U+01CE): X=392.0,Y=728.0 (should be at cap-height 730?)

	* uni01D0 (U+01D0): X=405.0,Y=728.0 (should be at cap-height 730?)

	* uni01D2 (U+01D2): X=387.0,Y=728.0 (should be at cap-height 730?)

	* uni01D4 (U+01D4): X=387.0,Y=728.0 (should be at cap-height 730?)

	* uni01D8 (U+01D8): X=463.0,Y=1021.0 (should be at ascender 1020?)

	* uni01D8 (U+01D8): X=542.0,Y=1021.0 (should be at ascender 1020?)

	* uni01DA (U+01DA): X=262.0,Y=1021.0 (should be at ascender 1020?)

	* uni01DA (U+01DA): X=322.0,Y=1021.0 (should be at ascender 1020?)

	* uni01DA (U+01DA): X=506.0,Y=1021.0 (should be at ascender 1020?)

	* uni01DA (U+01DA): X=567.0,Y=1021.0 (should be at ascender 1020?)

	* uni01DC (U+01DC): X=289.0,Y=1021.0 (should be at ascender 1020?)

	* uni01DC (U+01DC): X=366.0,Y=1021.0 (should be at ascender 1020?)

	* gcaron (U+01E7): X=384.0,Y=728.0 (should be at cap-height 730?)

	* caron (U+02C7): X=387.0,Y=728.0 (should be at cap-height 730?)

	* uni030C (U+030C): X=-213.0,Y=728.0 (should be at cap-height 730?)

	* uni03D7 (U+03D7): X=411.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=354.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=246.0,Y=-1.0 (should be at baseline 0?)

	* uni21DF (U+21DF): X=246.0,Y=731.0 (should be at cap-height 730?)

	* uni21DF (U+21DF): X=354.0,Y=731.0 (should be at cap-height 730?)

	* uni21E7 (U+21E7): X=301.0,Y=729.0 (should be at cap-height 730?)

	* uni21EA (U+21EA): X=300.0,Y=728.0 (should be at cap-height 730?)

	* uni2257 (U+2257): X=372.0,Y=731.0 (should be at cap-height 730?)

	* lessequal (U+2264): X=595.0,Y=728.0 (should be at cap-height 730?)

	* greaterequal (U+2265): X=147.0,Y=728.0 (should be at cap-height 730?)

	* uni2270 (U+2270): X=595.0,Y=728.0 (should be at cap-height 730?)

	* uni2271 (U+2271): X=148.0,Y=729.0 (should be at cap-height 730?)

	* uni2272 (U+2272): X=595.0,Y=728.0 (should be at cap-height 730?)

	* uni2273 (U+2273): X=148.0,Y=728.0 (should be at cap-height 730?)

	* uni22B4 (U+22B4): X=595.0,Y=728.0 (should be at cap-height 730?)

	* piads (U+E001): X=158.0,Y=2.0 (should be at baseline 0?)

	* pioffice (U+E002): X=158.0,Y=2.0 (should be at baseline 0?)

	* pitagram (U+E003): X=158.0,Y=2.0 (should be at baseline 0?)

	* piweb (U+E004): X=158.0,Y=2.0 (should be at baseline 0?)

	* pisign (U+E005): X=158.0,Y=2.0 (should be at baseline 0?)

	* petapp (U+E006): X=534.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=303.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=293.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=318.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=336.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=331.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=328.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=326.0,Y=1.5 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=278.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=274.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=272.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* picall (U+E009): X=158.0,Y=2.0 (should be at baseline 0?)

	* uniFE62 (U+FE62): X=206.0,Y=-1.0 (should be at baseline 0?) 

	* uniFE62 (U+FE62): X=306.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): B<<487.0,568.5>-<502.0,632.0>-<516.0,684.0>>/L<<516.0,684.0>--<363.0,336.0>> = 8.664451644579756

	* M (U+004D): L<<250.0,340.0>--<210.0,675.0>>/B<<210.0,675.0>-<208.0,606.0>-<200.0,510.5>> = 8.469332548596192

	* Mu (U+039C): B<<487.0,568.5>-<502.0,632.0>-<516.0,684.0>>/L<<516.0,684.0>--<363.0,336.0>> = 8.664451644579756

	* Mu (U+039C): L<<250.0,340.0>--<210.0,675.0>>/B<<210.0,675.0>-<208.0,606.0>-<200.0,510.5>> = 8.469332548596192

	* N (U+004E): L<<300.0,708.0>--<406.0,140.0>>/B<<406.0,140.0>-<408.0,172.0>-<412.0,215.5>> = 14.147258402419789

	* Nacute (U+0143): L<<300.0,708.0>--<406.0,140.0>>/B<<406.0,140.0>-<408.0,172.0>-<412.0,215.5>> = 14.147258402419789

	* Ncaron (U+0147): L<<300.0,708.0>--<406.0,140.0>>/B<<406.0,140.0>-<408.0,172.0>-<412.0,215.5>> = 14.147258402419789

	* Ntilde (U+00D1): L<<300.0,708.0>--<406.0,140.0>>/B<<406.0,140.0>-<408.0,172.0>-<412.0,215.5>> = 14.147258402419789

	* Nu (U+039D): L<<300.0,708.0>--<406.0,140.0>>/B<<406.0,140.0>-<408.0,172.0>-<412.0,215.5>> = 14.147258402419789

	* W (U+0057): B<<146.0,153.5>-<142.0,113.0>-<138.0,85.0>>/B<<138.0,85.0>-<145.0,113.0>-<155.0,153.5>> = 5.906141113770497

	* W (U+0057): B<<354.5,582.5>-<358.0,624.0>-<360.0,651.0>>/B<<360.0,651.0>-<353.0,624.0>-<344.0,582.5>> = 10.298060281481256

	* W (U+0057): B<<400.0,153.5>-<398.0,113.0>-<396.0,85.0>>/B<<396.0,85.0>-<402.0,113.0>-<411.0,153.5>> = 8.009140297037188

	* Wacute (U+1E82): B<<146.0,153.5>-<142.0,113.0>-<138.0,85.0>>/B<<138.0,85.0>-<145.0,113.0>-<155.0,153.5>> = 5.906141113770497

	* Wacute (U+1E82): B<<354.5,582.5>-<358.0,624.0>-<360.0,651.0>>/B<<360.0,651.0>-<353.0,624.0>-<344.0,582.5>> = 10.298060281481256

	* Wacute (U+1E82): B<<400.0,153.5>-<398.0,113.0>-<396.0,85.0>>/B<<396.0,85.0>-<402.0,113.0>-<411.0,153.5>> = 8.009140297037188

	* Wcircumflex (U+0174): B<<146.0,153.5>-<142.0,113.0>-<138.0,85.0>>/B<<138.0,85.0>-<145.0,113.0>-<155.0,153.5>> = 5.906141113770497

	* Wcircumflex (U+0174): B<<354.5,582.5>-<358.0,624.0>-<360.0,651.0>>/B<<360.0,651.0>-<353.0,624.0>-<344.0,582.5>> = 10.298060281481256

	* Wcircumflex (U+0174): B<<400.0,153.5>-<398.0,113.0>-<396.0,85.0>>/B<<396.0,85.0>-<402.0,113.0>-<411.0,153.5>> = 8.009140297037188

	* Wdieresis (U+1E84): B<<146.0,153.5>-<142.0,113.0>-<138.0,85.0>>/B<<138.0,85.0>-<145.0,113.0>-<155.0,153.5>> = 5.906141113770497

	* Wdieresis (U+1E84): B<<354.5,582.5>-<358.0,624.0>-<360.0,651.0>>/B<<360.0,651.0>-<353.0,624.0>-<344.0,582.5>> = 10.298060281481256

	* Wdieresis (U+1E84): B<<400.0,153.5>-<398.0,113.0>-<396.0,85.0>>/B<<396.0,85.0>-<402.0,113.0>-<411.0,153.5>> = 8.009140297037188

	* Wgrave (U+1E80): B<<146.0,153.5>-<142.0,113.0>-<138.0,85.0>>/B<<138.0,85.0>-<145.0,113.0>-<155.0,153.5>> = 5.906141113770497

	* Wgrave (U+1E80): B<<354.5,582.5>-<358.0,624.0>-<360.0,651.0>>/B<<360.0,651.0>-<353.0,624.0>-<344.0,582.5>> = 10.298060281481256

	* Wgrave (U+1E80): B<<400.0,153.5>-<398.0,113.0>-<396.0,85.0>>/B<<396.0,85.0>-<402.0,113.0>-<411.0,153.5>> = 8.009140297037188

	* a (U+0061): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* aacute (U+00E1): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* abreve (U+0103): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* acircumflex (U+00E2): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* adieresis (U+00E4): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* ae (U+00E6): B<<304.5,535.5>-<334.0,511.0>-<333.0,469.0>>/B<<333.0,469.0>-<344.0,511.0>-<381.5,535.5>> = 13.31246560584708

	* aeacute (U+01FD): B<<304.5,535.5>-<334.0,511.0>-<333.0,469.0>>/B<<333.0,469.0>-<344.0,511.0>-<381.5,535.5>> = 13.31246560584708

	* agrave (U+00E0): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* alpha (U+03B1): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* alphatonos (U+03AC): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* amacron (U+0101): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* aogonek (U+0105): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* aring (U+00E5): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* atilde (U+00E3): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* b (U+0062): L<<249.0,576.0>--<226.0,452.0>>/B<<226.0,452.0>-<249.0,504.0>-<292.0,532.0>> = 13.352153051109923

	* d (U+0064): L<<357.0,0.0>--<373.0,101.0>>/B<<373.0,101.0>-<351.0,47.0>-<307.5,18.5>> = 13.164590699521147

	* endOfMediumcontrol (U+2419): B<<528.0,208.5>-<537.0,254.0>-<551.0,293.0>>/L<<551.0,293.0>--<446.0,96.0>> = 8.31055262866471

	* endOfMediumcontrol (U+2419): L<<368.0,96.0>--<322.0,290.0>>/B<<322.0,290.0>-<323.0,264.0>-<322.0,239.0>> = 11.136650741597574

	* nu (U+03BD): B<<267.5,155.5>-<271.0,125.0>-<270.0,103.0>>/B<<270.0,103.0>-<275.0,125.0>-<287.5,155.5>> = 10.201703862786887

	* omega (U+03C9): B<<294.5,25.5>-<267.0,61.0>-<274.0,116.0>>/B<<274.0,116.0>-<262.0,57.0>-<224.0,23.5>> = 4.243368404860427

	* omegatonos (U+03CE): B<<294.5,25.5>-<267.0,61.0>-<274.0,116.0>>/B<<274.0,116.0>-<262.0,57.0>-<224.0,23.5>> = 4.243368404860427

	* p (U+0070): B<<212.0,20.5>-<177.0,51.0>-<171.0,104.0>>/L<<171.0,104.0>--<154.0,-26.0>> = 13.909065447374811

	* p (U+0070): L<<238.0,523.0>--<227.0,452.0>>/B<<227.0,452.0>-<249.0,504.0>-<292.0,532.0>> = 14.12530774315449

	* perthousand (U+2030): B<<394.0,272.0>-<416.0,254.0>-<414.0,224.0>>/B<<414.0,224.0>-<423.0,254.0>-<450.5,272.0>> = 12.885169399703255

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<365.0,279.0>-<368.0,276.0>-<370.0,275.0>>/L<<370.0,275.0>--<365.0,279.0>> = 12.094757077012058

	* petapp.minimal (U+E007): B<<402.0,358.0>-<402.0,357.0>-<401.0,355.0>>/L<<401.0,355.0>--<402.0,358.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>>/L<<437.0,404.0>--<440.0,406.0>> = 7.125016348901757

	* petapp.minimal (U+E007): B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>>/L<<442.0,407.0>--<447.0,409.0>> = 4.763641690726143

	* petapp.minimal (U+E007): B<<468.0,415.0>-<467.0,415.0>-<465.0,414.0>>/L<<465.0,414.0>--<468.0,415.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>>/L<<467.0,106.0>--<469.0,103.0>> = 11.309932474020195

	* petapp.minimal (U+E007): B<<484.5,8.5>-<484.0,4.0>-<483.0,0.0>>/B<<483.0,0.0>-<483.0,3.0>-<483.0,6.5>> = 14.036243467926484

	* petapp.minimal (U+E007): L<<408.0,166.0>--<411.0,165.0>>/B<<411.0,165.0>-<409.0,166.0>-<408.0,166.5>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<413.0,298.0>--<412.0,301.0>>/B<<412.0,301.0>-<413.0,299.0>-<413.0,298.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<417.0,160.0>--<420.0,159.0>>/B<<420.0,159.0>-<418.0,160.0>-<417.0,160.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<437.0,404.0>--<440.0,406.0>>/B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>> = 11.309932474020227

	* petapp.minimal (U+E007): L<<442.0,407.0>--<447.0,409.0>>/B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>> = 3.3664606634297236

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<467.0,106.0>--<469.0,103.0>>/B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>> = 7.125016348901757

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<90.0,577.0>-<99.0,557.0>> = 4.969740728110289

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* r (U+0072): L<<258.0,523.0>--<245.0,442.0>>/B<<245.0,442.0>-<263.0,497.0>-<308.0,528.5>> = 9.003997494105551

	* racute (U+0155): L<<258.0,523.0>--<245.0,442.0>>/B<<245.0,442.0>-<263.0,497.0>-<308.0,528.5>> = 9.003997494105551

	* rcaron (U+0159): L<<258.0,523.0>--<245.0,442.0>>/B<<245.0,442.0>-<263.0,497.0>-<308.0,528.5>> = 9.003997494105551

	* thorn (U+00FE): L<<247.0,576.0>--<224.0,452.0>>/B<<224.0,452.0>-<247.0,504.0>-<290.0,532.0>> = 13.352153051109923

	* trademark (U+2122): B<<427.0,650.0>-<424.0,678.0>-<422.0,697.0>>/B<<422.0,697.0>-<421.0,669.0>-<418.5,627.0>> = 8.05441444638168

	* trademark (U+2122): B<<569.0,651.5>-<576.0,679.0>-<582.0,700.0>>/B<<582.0,700.0>-<574.0,680.0>-<561.5,650.5>> = 5.856013585428907

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni0145 (U+0145): L<<300.0,708.0>--<406.0,140.0>>/B<<406.0,140.0>-<408.0,172.0>-<412.0,215.5>> = 14.147258402419789

	* uni0157 (U+0157): L<<258.0,523.0>--<245.0,442.0>>/B<<245.0,442.0>-<263.0,497.0>-<308.0,528.5>> = 9.003997494105551

	* uni01CE (U+01CE): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni03D6 (U+03D6): B<<298.0,21.0>-<271.0,52.0>-<273.0,104.0>>/B<<273.0,104.0>-<258.0,52.0>-<220.5,21.0>> = 13.888218187086354

	* uni03D7 (U+03D7): B<<161.0,148.0>-<152.0,114.0>-<144.0,89.0>>/L<<144.0,89.0>--<411.0,550.0>> = 12.333708696626756

	* uni03D7 (U+03D7): B<<436.5,396.0>-<445.0,428.0>-<452.0,450.0>>/L<<452.0,450.0>--<188.0,0.0>> = 12.74860349423594

	* uni0418 (U+0418): B<<168.5,210.0>-<159.0,169.0>-<152.0,140.0>>/L<<152.0,140.0>--<446.0,730.0>> = 12.916874940693031

	* uni0418 (U+0418): B<<459.0,514.5>-<469.0,558.0>-<477.0,590.0>>/L<<477.0,590.0>--<182.0,0.0>> = 12.528807709151492

	* uni0419 (U+0419): B<<168.5,210.0>-<159.0,169.0>-<152.0,140.0>>/L<<152.0,140.0>--<446.0,730.0>> = 12.916874940693031

	* uni0419 (U+0419): B<<459.0,514.5>-<469.0,558.0>-<477.0,590.0>>/L<<477.0,590.0>--<182.0,0.0>> = 12.528807709151492

	* uni041C (U+041C): B<<487.0,568.5>-<502.0,632.0>-<516.0,684.0>>/L<<516.0,684.0>--<363.0,336.0>> = 8.664451644579756

	* uni041C (U+041C): L<<250.0,340.0>--<210.0,675.0>>/B<<210.0,675.0>-<208.0,606.0>-<200.0,510.5>> = 8.469332548596192

	* uni0430 (U+0430): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni0431 (U+0431): L<<204.0,460.0>--<196.0,408.0>>/B<<196.0,408.0>-<215.0,460.0>-<260.0,488.0>> = 11.325363601983543

	* uni0434 (U+0434): B<<406.5,486.5>-<443.0,457.0>-<445.0,403.0>>/L<<445.0,403.0>--<454.0,460.0>> = 11.09372301155785

	* uni043C (U+043C): B<<444.5,336.0>-<458.0,399.0>-<468.0,444.0>>/L<<468.0,444.0>--<339.0,159.0>> = 11.824201465878133

	* uni043C (U+043C): L<<225.0,159.0>--<184.0,443.0>>/B<<184.0,443.0>-<181.0,400.0>-<174.5,339.5>> = 12.205730688309098

	* uni0440 (U+0440): B<<212.0,20.5>-<177.0,51.0>-<171.0,104.0>>/L<<171.0,104.0>--<154.0,-26.0>> = 13.909065447374811

	* uni0440 (U+0440): L<<238.0,523.0>--<227.0,452.0>>/B<<227.0,452.0>-<249.0,504.0>-<292.0,532.0>> = 14.12530774315449

	* uni04E4 (U+04E4): B<<168.5,210.0>-<159.0,169.0>-<152.0,140.0>>/L<<152.0,140.0>--<446.0,730.0>> = 12.916874940693031

	* uni04E4 (U+04E4): B<<459.0,514.5>-<469.0,558.0>-<477.0,590.0>>/L<<477.0,590.0>--<182.0,0.0>> = 12.528807709151492

	* uni1EA1 (U+1EA1): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni1EA3 (U+1EA3): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni1EA5 (U+1EA5): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni1EA7 (U+1EA7): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni1EA9 (U+1EA9): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni1EAB (U+1EAB): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni1EAD (U+1EAD): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni1EAF (U+1EAF): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni1EB1 (U+1EB1): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni1EB3 (U+1EB3): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni1EB5 (U+1EB5): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni1EB7 (U+1EB7): L<<369.0,117.0>--<370.0,126.0>>/B<<370.0,126.0>-<353.0,65.0>-<303.0,27.5>> = 9.232351850900354

	* uni20BF (U+20BF): B<<516.0,433.0>-<469.0,391.0>-<406.0,383.0>>/B<<406.0,383.0>-<473.0,375.0>-<511.0,330.5>> = 14.04597220558138

	* uni2116 (U+2116): B<<154.0,564.0>-<152.0,605.0>-<150.0,637.0>>/B<<150.0,637.0>-<149.0,596.0>-<146.0,546.5>> = 4.973515402293559

	* uni2116 (U+2116): B<<257.5,169.5>-<260.0,127.0>-<262.0,94.0>>/B<<262.0,94.0>-<263.0,135.0>-<265.5,184.5>> = 4.86541028621343

	* uni227A (U+227A): B<<374.0,369.0>-<293.0,334.0>-<190.0,328.0>>/B<<190.0,328.0>-<341.0,319.0>-<422.0,248.5>> = 6.744795616892271

	* uni227B (U+227B): B<<249.5,294.0>-<331.0,330.0>-<434.0,336.0>>/B<<434.0,336.0>-<282.0,344.0>-<200.5,413.5>> = 6.346638165719862

	* uni227C (U+227C): B<<401.0,494.0>-<320.0,459.0>-<217.0,453.0>>/B<<217.0,453.0>-<368.0,444.0>-<449.0,373.5>> = 6.744795616892271

	* uni22CE (U+22CE): B<<245.5,448.5>-<302.0,355.0>-<285.0,201.0>>/B<<285.0,201.0>-<308.0,304.0>-<355.0,380.5>> = 6.288339675518264

	* uni234B (U+234B): L<<277.0,109.0>--<277.0,505.0>>/L<<277.0,505.0>--<187.0,109.0>> = 12.80426606528674

	* uni234B (U+234B): L<<412.0,109.0>--<322.0,504.0>>/L<<322.0,504.0>--<322.0,109.0>> = 12.835609486401424

	* uni2352 (U+2352): L<<189.0,621.0>--<281.0,226.0>>/L<<281.0,226.0>--<280.0,621.0>> = 12.966040693270955

	* uni2352 (U+2352): L<<324.0,621.0>--<324.0,226.0>>/L<<324.0,226.0>--<413.0,621.0>> = 12.697640216649821

	* uni236C (U+236C): L<<236.0,524.0>--<213.0,382.0>>/B<<213.0,382.0>-<238.0,457.0>-<285.0,457.0>> = 9.234548353851613

	* uni236C (U+236C): L<<392.0,206.0>--<416.0,361.0>>/B<<416.0,361.0>-<391.0,287.0>-<344.0,287.0>> = 9.865205951012403

	* uni2375 (U+2375): B<<297.5,20.5>-<270.0,51.0>-<273.0,104.0>>/B<<273.0,104.0>-<258.0,51.0>-<220.0,20.5>> = 12.562813657833368

	* uni2379 (U+2379): B<<297.5,20.5>-<270.0,51.0>-<273.0,104.0>>/B<<273.0,104.0>-<258.0,51.0>-<220.0,20.5>> = 12.562813657833368

	* uni26A1 (U+26A1): L<<579.0,440.0>--<49.0,-110.0>>/L<<49.0,-110.0>--<294.0,310.0>> = 13.68265114620652

	* v (U+0076): B<<267.5,155.5>-<271.0,125.0>-<270.0,103.0>>/B<<270.0,103.0>-<275.0,125.0>-<287.5,155.5>> = 10.201703862786887

	* w (U+0077): B<<148.0,146.0>-<145.0,110.0>-<142.0,86.0>>/B<<142.0,86.0>-<148.0,110.0>-<157.0,146.0>> = 6.911227119024609

	* w (U+0077): B<<325.5,403.5>-<327.0,440.0>-<329.0,463.0>>/B<<329.0,463.0>-<325.0,440.0>-<314.5,403.5>> = 4.8960662149740015

	* w (U+0077): B<<397.0,145.5>-<395.0,109.0>-<393.0,85.0>>/B<<393.0,85.0>-<399.0,109.0>-<407.0,145.5>> = 9.272601777200244

	* wacute (U+1E83): B<<148.0,146.0>-<145.0,110.0>-<142.0,86.0>>/B<<142.0,86.0>-<148.0,110.0>-<157.0,146.0>> = 6.911227119024609

	* wacute (U+1E83): B<<325.5,403.5>-<327.0,440.0>-<329.0,463.0>>/B<<329.0,463.0>-<325.0,440.0>-<314.5,403.5>> = 4.8960662149740015

	* wacute (U+1E83): B<<397.0,145.5>-<395.0,109.0>-<393.0,85.0>>/B<<393.0,85.0>-<399.0,109.0>-<407.0,145.5>> = 9.272601777200244

	* wcircumflex (U+0175): B<<148.0,146.0>-<145.0,110.0>-<142.0,86.0>>/B<<142.0,86.0>-<148.0,110.0>-<157.0,146.0>> = 6.911227119024609

	* wcircumflex (U+0175): B<<325.5,403.5>-<327.0,440.0>-<329.0,463.0>>/B<<329.0,463.0>-<325.0,440.0>-<314.5,403.5>> = 4.8960662149740015

	* wcircumflex (U+0175): B<<397.0,145.5>-<395.0,109.0>-<393.0,85.0>>/B<<393.0,85.0>-<399.0,109.0>-<407.0,145.5>> = 9.272601777200244

	* wdieresis (U+1E85): B<<148.0,146.0>-<145.0,110.0>-<142.0,86.0>>/B<<142.0,86.0>-<148.0,110.0>-<157.0,146.0>> = 6.911227119024609

	* wdieresis (U+1E85): B<<325.5,403.5>-<327.0,440.0>-<329.0,463.0>>/B<<329.0,463.0>-<325.0,440.0>-<314.5,403.5>> = 4.8960662149740015

	* wdieresis (U+1E85): B<<397.0,145.5>-<395.0,109.0>-<393.0,85.0>>/B<<393.0,85.0>-<399.0,109.0>-<407.0,145.5>> = 9.272601777200244

	* wgrave (U+1E81): B<<148.0,146.0>-<145.0,110.0>-<142.0,86.0>>/B<<142.0,86.0>-<148.0,110.0>-<157.0,146.0>> = 6.911227119024609

	* wgrave (U+1E81): B<<325.5,403.5>-<327.0,440.0>-<329.0,463.0>>/B<<329.0,463.0>-<325.0,440.0>-<314.5,403.5>> = 4.8960662149740015 

	* wgrave (U+1E81): B<<397.0,145.5>-<395.0,109.0>-<393.0,85.0>>/B<<393.0,85.0>-<399.0,109.0>-<407.0,145.5>> = 9.272601777200244 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[19] PitagonSansMono-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- uni2070.zero

	- uni2080.zero

	- zero.dnom.zero 

	- zero.numr.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1710 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 2 glyphs (0.11%) have a different width. You should check the widths of: ['periodcentered.loclCAT', 'periodcentered.loclCAT.case'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* section (U+00A7): X=58.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=185.0,Y=1.0 (should be at baseline 0?)

	* macron (U+00AF): X=128.0,Y=732.0 (should be at cap-height 730?)

	* macron (U+00AF): X=472.0,Y=732.0 (should be at cap-height 730?)

	* onequarter (U+00BC): X=125.0,Y=729.0 (should be at cap-height 730?)

	* onequarter (U+00BC): X=227.0,Y=729.0 (should be at cap-height 730?)

	* amacron (U+0101): X=133.0,Y=732.0 (should be at cap-height 730?)

	* amacron (U+0101): X=477.0,Y=732.0 (should be at cap-height 730?)

	* aogonek (U+0105): X=510.0,Y=-2.0 (should be at baseline 0?)

	* aogonek (U+0105): X=417.0,Y=1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=293.0,Y=728.0 (should be at cap-height 730?)

	* ccaron (U+010D): X=327.0,Y=729.0 (should be at cap-height 730?)

	* emacron (U+0113): X=128.0,Y=732.0 (should be at cap-height 730?)

	* emacron (U+0113): X=472.0,Y=732.0 (should be at cap-height 730?)

	* ecaron (U+011B): X=284.0,Y=728.0 (should be at cap-height 730?)

	* ecaron (U+011B): X=318.0,Y=729.0 (should be at cap-height 730?)

	* imacron (U+012B): X=146.0,Y=732.0 (should be at cap-height 730?)

	* imacron (U+012B): X=490.0,Y=732.0 (should be at cap-height 730?)

	* ncaron (U+0148): X=289.0,Y=728.0 (should be at cap-height 730?)

	* ncaron (U+0148): X=323.0,Y=729.0 (should be at cap-height 730?)

	* omacron (U+014D): X=128.0,Y=732.0 (should be at cap-height 730?)

	* omacron (U+014D): X=472.0,Y=732.0 (should be at cap-height 730?)

	* rcaron (U+0159): X=304.0,Y=728.0 (should be at cap-height 730?)

	* rcaron (U+0159): X=338.0,Y=729.0 (should be at cap-height 730?)

	* scaron (U+0161): X=284.0,Y=728.0 (should be at cap-height 730?)

	* scaron (U+0161): X=318.0,Y=729.0 (should be at cap-height 730?)

	* umacron (U+016B): X=128.0,Y=732.0 (should be at cap-height 730?)

	* umacron (U+016B): X=472.0,Y=732.0 (should be at cap-height 730?)

	* zcaron (U+017E): X=284.0,Y=728.0 (should be at cap-height 730?)

	* zcaron (U+017E): X=318.0,Y=729.0 (should be at cap-height 730?)

	* uni019B (U+019B): X=446.0,Y=728.0 (should be at cap-height 730?)

	* uni019B (U+019B): X=463.5,Y=729.0 (should be at cap-height 730?)

	* uni01CE (U+01CE): X=289.0,Y=728.0 (should be at cap-height 730?)

	* uni01CE (U+01CE): X=323.0,Y=729.0 (should be at cap-height 730?)

	* uni01D0 (U+01D0): X=302.0,Y=728.0 (should be at cap-height 730?)

	* uni01D0 (U+01D0): X=336.0,Y=729.0 (should be at cap-height 730?)

	* uni01D2 (U+01D2): X=284.0,Y=728.0 (should be at cap-height 730?)

	* uni01D2 (U+01D2): X=318.0,Y=729.0 (should be at cap-height 730?)

	* uni01D4 (U+01D4): X=284.0,Y=728.0 (should be at cap-height 730?)

	* uni01D4 (U+01D4): X=318.0,Y=729.0 (should be at cap-height 730?)

	* uni01D8 (U+01D8): X=348.0,Y=1021.0 (should be at ascender 1020?)

	* uni01D8 (U+01D8): X=425.0,Y=1021.0 (should be at ascender 1020?)

	* uni01DA (U+01DA): X=148.0,Y=1021.0 (should be at ascender 1020?)

	* uni01DA (U+01DA): X=208.0,Y=1021.0 (should be at ascender 1020?)

	* uni01DA (U+01DA): X=391.0,Y=1021.0 (should be at ascender 1020?)

	* uni01DA (U+01DA): X=452.0,Y=1021.0 (should be at ascender 1020?)

	* uni01DC (U+01DC): X=173.0,Y=1021.0 (should be at ascender 1020?)

	* uni01DC (U+01DC): X=253.0,Y=1021.0 (should be at ascender 1020?)

	* gcaron (U+01E7): X=281.0,Y=728.0 (should be at cap-height 730?)

	* gcaron (U+01E7): X=315.0,Y=729.0 (should be at cap-height 730?)

	* uni0233 (U+0233): X=128.0,Y=732.0 (should be at cap-height 730?)

	* uni0233 (U+0233): X=472.0,Y=732.0 (should be at cap-height 730?)

	* caron (U+02C7): X=284.0,Y=728.0 (should be at cap-height 730?)

	* caron (U+02C7): X=318.0,Y=729.0 (should be at cap-height 730?)

	* uni02C9 (U+02C9): X=128.0,Y=732.0 (should be at cap-height 730?)

	* uni02C9 (U+02C9): X=472.0,Y=732.0 (should be at cap-height 730?)

	* uni0304 (U+0304): X=-472.0,Y=732.0 (should be at cap-height 730?)

	* uni0304 (U+0304): X=-128.0,Y=732.0 (should be at cap-height 730?)

	* uni030C (U+030C): X=-316.0,Y=728.0 (should be at cap-height 730?)

	* uni030C (U+030C): X=-282.0,Y=729.0 (should be at cap-height 730?)

	* uni21DE (U+21DE): X=354.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=246.0,Y=-1.0 (should be at baseline 0?)

	* uni21DF (U+21DF): X=246.0,Y=731.0 (should be at cap-height 730?)

	* uni21DF (U+21DF): X=354.0,Y=731.0 (should be at cap-height 730?)

	* uni21E7 (U+21E7): X=301.0,Y=729.0 (should be at cap-height 730?)

	* uni21EA (U+21EA): X=300.0,Y=728.0 (should be at cap-height 730?)

	* uni2257 (U+2257): X=300.0,Y=731.0 (should be at cap-height 730?)

	* lessequal (U+2264): X=524.0,Y=728.0 (should be at cap-height 730?)

	* greaterequal (U+2265): X=76.0,Y=728.0 (should be at cap-height 730?)

	* uni2270 (U+2270): X=524.0,Y=728.0 (should be at cap-height 730?)

	* uni2271 (U+2271): X=76.0,Y=729.0 (should be at cap-height 730?)

	* uni2272 (U+2272): X=524.0,Y=728.0 (should be at cap-height 730?)

	* uni2273 (U+2273): X=76.0,Y=728.0 (should be at cap-height 730?)

	* uni22B4 (U+22B4): X=524.0,Y=728.0 (should be at cap-height 730?)

	* piads (U+E001): X=158.0,Y=2.0 (should be at baseline 0?)

	* pioffice (U+E002): X=158.0,Y=2.0 (should be at baseline 0?)

	* pitagram (U+E003): X=158.0,Y=2.0 (should be at baseline 0?)

	* piweb (U+E004): X=158.0,Y=2.0 (should be at baseline 0?)

	* pisign (U+E005): X=158.0,Y=2.0 (should be at baseline 0?)

	* petapp (U+E006): X=534.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=303.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=293.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=318.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=336.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=331.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=328.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=326.0,Y=1.5 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=278.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=274.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=272.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* picall (U+E009): X=158.0,Y=2.0 (should be at baseline 0?)

	* uniFE62 (U+FE62): X=250.0,Y=-1.0 (should be at baseline 0?) 

	* uniFE62 (U+FE62): X=350.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): B<<441.0,568.5>-<446.0,632.0>-<452.0,684.0>>/L<<452.0,684.0>--<354.0,338.0>> = 9.232139528711867

	* M (U+004D): L<<241.0,338.0>--<147.0,675.0>>/B<<147.0,675.0>-<156.0,606.0>-<163.5,510.5>> = 8.154066291072258

	* Mu (U+039C): B<<441.0,568.5>-<446.0,632.0>-<452.0,684.0>>/L<<452.0,684.0>--<354.0,338.0>> = 9.232139528711867

	* Mu (U+039C): L<<241.0,338.0>--<147.0,675.0>>/B<<147.0,675.0>-<156.0,606.0>-<163.5,510.5>> = 8.154066291072258

	* N (U+004E): L<<232.0,710.0>--<428.0,140.0>>/B<<428.0,140.0>-<425.0,172.0>-<422.0,215.5>> = 13.620201100533224

	* Nacute (U+0143): L<<232.0,710.0>--<428.0,140.0>>/B<<428.0,140.0>-<425.0,172.0>-<422.0,215.5>> = 13.620201100533224

	* Ncaron (U+0147): L<<232.0,710.0>--<428.0,140.0>>/B<<428.0,140.0>-<425.0,172.0>-<422.0,215.5>> = 13.620201100533224

	* Ntilde (U+00D1): L<<232.0,710.0>--<428.0,140.0>>/B<<428.0,140.0>-<425.0,172.0>-<422.0,215.5>> = 13.620201100533224

	* Nu (U+039D): L<<232.0,710.0>--<428.0,140.0>>/B<<428.0,140.0>-<425.0,172.0>-<422.0,215.5>> = 13.620201100533224

	* W (U+0057): B<<168.5,153.5>-<171.0,113.0>-<171.0,85.0>>/B<<171.0,85.0>-<174.0,113.0>-<177.5,153.5>> = 6.115503566285384

	* W (U+0057): B<<306.0,582.5>-<303.0,624.0>-<301.0,651.0>>/B<<301.0,651.0>-<299.0,624.0>-<296.0,582.5>> = 8.472789598117709

	* W (U+0057): B<<422.5,153.5>-<427.0,113.0>-<430.0,85.0>>/B<<430.0,85.0>-<431.0,113.0>-<433.5,153.5>> = 8.16091205517261

	* Wacute (U+1E82): B<<168.5,153.5>-<171.0,113.0>-<171.0,85.0>>/B<<171.0,85.0>-<174.0,113.0>-<177.5,153.5>> = 6.115503566285384

	* Wacute (U+1E82): B<<306.0,582.5>-<303.0,624.0>-<301.0,651.0>>/B<<301.0,651.0>-<299.0,624.0>-<296.0,582.5>> = 8.472789598117709

	* Wacute (U+1E82): B<<422.5,153.5>-<427.0,113.0>-<430.0,85.0>>/B<<430.0,85.0>-<431.0,113.0>-<433.5,153.5>> = 8.16091205517261

	* Wcircumflex (U+0174): B<<168.5,153.5>-<171.0,113.0>-<171.0,85.0>>/B<<171.0,85.0>-<174.0,113.0>-<177.5,153.5>> = 6.115503566285384

	* Wcircumflex (U+0174): B<<306.0,582.5>-<303.0,624.0>-<301.0,651.0>>/B<<301.0,651.0>-<299.0,624.0>-<296.0,582.5>> = 8.472789598117709

	* Wcircumflex (U+0174): B<<422.5,153.5>-<427.0,113.0>-<430.0,85.0>>/B<<430.0,85.0>-<431.0,113.0>-<433.5,153.5>> = 8.16091205517261

	* Wdieresis (U+1E84): B<<168.5,153.5>-<171.0,113.0>-<171.0,85.0>>/B<<171.0,85.0>-<174.0,113.0>-<177.5,153.5>> = 6.115503566285384

	* Wdieresis (U+1E84): B<<306.0,582.5>-<303.0,624.0>-<301.0,651.0>>/B<<301.0,651.0>-<299.0,624.0>-<296.0,582.5>> = 8.472789598117709

	* Wdieresis (U+1E84): B<<422.5,153.5>-<427.0,113.0>-<430.0,85.0>>/B<<430.0,85.0>-<431.0,113.0>-<433.5,153.5>> = 8.16091205517261

	* Wgrave (U+1E80): B<<168.5,153.5>-<171.0,113.0>-<171.0,85.0>>/B<<171.0,85.0>-<174.0,113.0>-<177.5,153.5>> = 6.115503566285384

	* Wgrave (U+1E80): B<<306.0,582.5>-<303.0,624.0>-<301.0,651.0>>/B<<301.0,651.0>-<299.0,624.0>-<296.0,582.5>> = 8.472789598117709

	* Wgrave (U+1E80): B<<422.5,153.5>-<427.0,113.0>-<430.0,85.0>>/B<<430.0,85.0>-<431.0,113.0>-<433.5,153.5>> = 8.16091205517261

	* a (U+0061): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* aacute (U+00E1): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* abreve (U+0103): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* acircumflex (U+00E2): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* adieresis (U+00E4): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* ae (U+00E6): B<<263.5,535.5>-<297.0,511.0>-<302.0,469.0>>/B<<302.0,469.0>-<307.0,511.0>-<340.5,535.5>> = 13.57794914887754

	* aeacute (U+01FD): B<<263.5,535.5>-<297.0,511.0>-<302.0,469.0>>/B<<302.0,469.0>-<307.0,511.0>-<340.5,535.5>> = 13.57794914887754

	* agrave (U+00E0): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* amacron (U+0101): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* aogonek (U+0105): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* aring (U+00E5): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* atilde (U+00E3): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* endOfMediumcontrol (U+2419): B<<503.5,208.5>-<505.0,254.0>-<514.0,293.0>>/L<<514.0,293.0>--<447.0,116.0>> = 7.738594775550269

	* endOfMediumcontrol (U+2419): L<<354.0,116.0>--<285.0,290.0>>/B<<285.0,290.0>-<290.0,264.0>-<293.0,239.0>> = 10.745359781859175

	* eta (U+03B7): L<<199.0,530.0>--<199.0,447.0>>/B<<199.0,447.0>-<209.0,499.0>-<248.0,529.5>> = 10.885527054658743

	* etatonos (U+03AE): L<<199.0,530.0>--<199.0,447.0>>/B<<199.0,447.0>-<209.0,499.0>-<248.0,529.5>> = 10.885527054658743

	* h (U+0068): L<<202.0,550.0>--<199.0,448.0>>/B<<199.0,448.0>-<209.0,500.0>-<248.0,530.0>> = 9.20084273676248

	* hcircumflex (U+0125): L<<202.0,550.0>--<199.0,448.0>>/B<<199.0,448.0>-<209.0,500.0>-<248.0,530.0>> = 9.20084273676248

	* n (U+006E): L<<199.0,530.0>--<199.0,447.0>>/B<<199.0,447.0>-<209.0,499.0>-<248.0,529.5>> = 10.885527054658743

	* nacute (U+0144): L<<199.0,530.0>--<199.0,447.0>>/B<<199.0,447.0>-<209.0,499.0>-<248.0,529.5>> = 10.885527054658743

	* napostrophe (U+0149): L<<199.0,530.0>--<199.0,447.0>>/B<<199.0,447.0>-<209.0,499.0>-<248.0,529.5>> = 10.885527054658743

	* ncaron (U+0148): L<<199.0,530.0>--<199.0,447.0>>/B<<199.0,447.0>-<209.0,499.0>-<248.0,529.5>> = 10.885527054658743

	* ntilde (U+00F1): L<<199.0,530.0>--<199.0,447.0>>/B<<199.0,447.0>-<209.0,499.0>-<248.0,529.5>> = 10.885527054658743

	* omega (U+03C9): B<<334.5,25.5>-<301.0,61.0>-<300.0,116.0>>/B<<300.0,116.0>-<297.0,59.0>-<263.5,24.5>> = 4.054414180193229

	* omegatonos (U+03CE): B<<334.5,25.5>-<301.0,61.0>-<300.0,116.0>>/B<<300.0,116.0>-<297.0,59.0>-<263.5,24.5>> = 4.054414180193229

	* p (U+0070): B<<252.5,20.0>-<213.0,50.0>-<198.0,104.0>>/L<<198.0,104.0>--<202.0,-26.0>> = 13.761719973093708

	* perthousand (U+2030): B<<460.5,13.0>-<436.0,31.0>-<433.0,61.0>>/B<<433.0,61.0>-<429.0,31.0>-<404.5,13.0>> = 13.305236506091092

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<365.0,279.0>-<368.0,276.0>-<370.0,275.0>>/L<<370.0,275.0>--<365.0,279.0>> = 12.094757077012058

	* petapp.minimal (U+E007): B<<402.0,358.0>-<402.0,357.0>-<401.0,355.0>>/L<<401.0,355.0>--<402.0,358.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>>/L<<437.0,404.0>--<440.0,406.0>> = 7.125016348901757

	* petapp.minimal (U+E007): B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>>/L<<442.0,407.0>--<447.0,409.0>> = 4.763641690726143

	* petapp.minimal (U+E007): B<<468.0,415.0>-<467.0,415.0>-<465.0,414.0>>/L<<465.0,414.0>--<468.0,415.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>>/L<<467.0,106.0>--<469.0,103.0>> = 11.309932474020195

	* petapp.minimal (U+E007): B<<484.5,8.5>-<484.0,4.0>-<483.0,0.0>>/B<<483.0,0.0>-<483.0,3.0>-<483.0,6.5>> = 14.036243467926484

	* petapp.minimal (U+E007): L<<408.0,166.0>--<411.0,165.0>>/B<<411.0,165.0>-<409.0,166.0>-<408.0,166.5>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<413.0,298.0>--<412.0,301.0>>/B<<412.0,301.0>-<413.0,299.0>-<413.0,298.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<417.0,160.0>--<420.0,159.0>>/B<<420.0,159.0>-<418.0,160.0>-<417.0,160.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<437.0,404.0>--<440.0,406.0>>/B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>> = 11.309932474020227

	* petapp.minimal (U+E007): L<<442.0,407.0>--<447.0,409.0>>/B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>> = 3.3664606634297236

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<467.0,106.0>--<469.0,103.0>>/B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>> = 7.125016348901757

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<90.0,577.0>-<99.0,557.0>> = 4.969740728110289

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* r (U+0072): L<<219.0,530.0>--<219.0,443.0>>/B<<219.0,443.0>-<229.0,497.0>-<268.5,528.5>> = 10.491477012331599

	* racute (U+0155): L<<219.0,530.0>--<219.0,443.0>>/B<<219.0,443.0>-<229.0,497.0>-<268.5,528.5>> = 10.491477012331599

	* rcaron (U+0159): L<<219.0,530.0>--<219.0,443.0>>/B<<219.0,443.0>-<229.0,497.0>-<268.5,528.5>> = 10.491477012331599

	* thorn (U+00FE): L<<200.0,576.0>--<196.0,450.0>>/B<<196.0,450.0>-<211.0,502.0>-<250.5,531.0>> = 14.272513384400337

	* trademark (U+2122): B<<368.5,650.0>-<361.0,678.0>-<356.0,697.0>>/B<<356.0,697.0>-<359.0,669.0>-<363.0,627.0>> = 8.628059270185302

	* trademark (U+2122): B<<510.5,651.5>-<513.0,679.0>-<515.0,700.0>>/B<<515.0,700.0>-<510.0,680.0>-<502.5,650.5>> = 8.595911436920954

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni0145 (U+0145): L<<232.0,710.0>--<428.0,140.0>>/B<<428.0,140.0>-<425.0,172.0>-<422.0,215.5>> = 13.620201100533224

	* uni0146 (U+0146): L<<199.0,530.0>--<199.0,447.0>>/B<<199.0,447.0>-<209.0,499.0>-<248.0,529.5>> = 10.885527054658743

	* uni0157 (U+0157): L<<219.0,530.0>--<219.0,443.0>>/B<<219.0,443.0>-<229.0,497.0>-<268.5,528.5>> = 10.491477012331599

	* uni01CE (U+01CE): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni03D6 (U+03D6): B<<338.5,21.0>-<306.0,52.0>-<300.0,104.0>>/B<<300.0,104.0>-<293.0,52.0>-<260.5,21.0>> = 14.248748916992179

	* uni03D7 (U+03D7): B<<187.5,188.5>-<185.0,138.0>-<176.0,102.0>>/L<<176.0,102.0>--<371.0,550.0>> = 9.485700605419696

	* uni03D7 (U+03D7): B<<412.0,358.0>-<414.0,405.0>-<423.0,437.0>>/L<<423.0,437.0>--<229.0,0.0>> = 8.229516562394858

	* uni040E (U+040E): B<<298.5,349.5>-<306.0,319.0>-<308.0,300.0>>/B<<308.0,300.0>-<310.0,319.0>-<316.5,349.5>> = 12.018011914988996

	* uni0418 (U+0418): B<<422.0,514.5>-<425.0,558.0>-<428.0,590.0>>/L<<428.0,590.0>--<225.0,0.0>> = 13.630865371979267

	* uni0419 (U+0419): B<<422.0,514.5>-<425.0,558.0>-<428.0,590.0>>/L<<428.0,590.0>--<225.0,0.0>> = 13.630865371979267

	* uni041C (U+041C): B<<441.0,568.5>-<446.0,632.0>-<452.0,684.0>>/L<<452.0,684.0>--<354.0,338.0>> = 9.232139528711867

	* uni041C (U+041C): L<<241.0,338.0>--<147.0,675.0>>/B<<147.0,675.0>-<156.0,606.0>-<163.5,510.5>> = 8.154066291072258

	* uni0423 (U+0423): B<<298.5,349.5>-<306.0,319.0>-<308.0,300.0>>/B<<308.0,300.0>-<310.0,319.0>-<316.5,349.5>> = 12.018011914988996

	* uni0430 (U+0430): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni0431 (U+0431): L<<175.0,460.0>--<175.0,404.0>>/B<<175.0,404.0>-<185.0,458.0>-<226.5,487.0>> = 10.491477012331599

	* uni0438 (U+0438): B<<187.5,188.5>-<185.0,138.0>-<176.0,102.0>>/L<<176.0,102.0>--<371.0,550.0>> = 9.485700605419696

	* uni0438 (U+0438): B<<412.0,358.0>-<414.0,405.0>-<423.0,437.0>>/L<<423.0,437.0>--<229.0,0.0>> = 8.229516562394858

	* uni0439 (U+0439): B<<187.5,188.5>-<185.0,138.0>-<176.0,102.0>>/L<<176.0,102.0>--<371.0,550.0>> = 9.485700605419696

	* uni0439 (U+0439): B<<412.0,358.0>-<414.0,405.0>-<423.0,437.0>>/L<<423.0,437.0>--<229.0,0.0>> = 8.229516562394858

	* uni043C (U+043C): B<<435.0,410.5>-<438.0,458.0>-<444.0,491.0>>/L<<444.0,491.0>--<348.0,197.0>> = 7.7785989142825995

	* uni043C (U+043C): L<<248.0,197.0>--<154.0,476.0>>/B<<154.0,476.0>-<162.0,435.0>-<165.5,371.5>> = 7.578634575587578

	* uni0440 (U+0440): B<<252.5,20.0>-<213.0,50.0>-<198.0,104.0>>/L<<198.0,104.0>--<202.0,-26.0>> = 13.761719973093708

	* uni04E4 (U+04E4): B<<422.0,514.5>-<425.0,558.0>-<428.0,590.0>>/L<<428.0,590.0>--<225.0,0.0>> = 13.630865371979267

	* uni04E5 (U+04E5): B<<187.5,188.5>-<185.0,138.0>-<176.0,102.0>>/L<<176.0,102.0>--<371.0,550.0>> = 9.485700605419696

	* uni04E5 (U+04E5): B<<412.0,358.0>-<414.0,405.0>-<423.0,437.0>>/L<<423.0,437.0>--<229.0,0.0>> = 8.229516562394858

	* uni1EA1 (U+1EA1): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni1EA3 (U+1EA3): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni1EA5 (U+1EA5): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni1EA7 (U+1EA7): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni1EA9 (U+1EA9): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni1EAB (U+1EAB): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni1EAD (U+1EAD): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni1EAF (U+1EAF): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni1EB1 (U+1EB1): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni1EB3 (U+1EB3): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni1EB5 (U+1EB5): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni1EB7 (U+1EB7): L<<401.0,25.0>--<401.0,103.0>>/B<<401.0,103.0>-<394.0,50.0>-<351.0,20.0>> = 7.523820438638637

	* uni20BF (U+20BF): B<<491.0,433.0>-<451.0,391.0>-<390.0,383.0>>/B<<390.0,383.0>-<458.0,375.0>-<503.0,330.5>> = 14.181395984349283

	* uni2116 (U+2116): B<<108.5,564.0>-<100.0,605.0>-<94.0,637.0>>/B<<94.0,637.0>-<98.0,596.0>-<103.5,546.5>> = 5.047457472191301

	* uni2116 (U+2116): B<<275.0,169.5>-<284.0,127.0>-<291.0,94.0>>/B<<291.0,94.0>-<286.0,135.0>-<280.5,184.5>> = 5.0231749760292725

	* uni227A (U+227A): B<<421.0,413.5>-<328.0,344.0>-<176.0,336.0>>/B<<176.0,336.0>-<328.0,326.0>-<421.0,252.0>> = 6.776822369089007

	* uni227B (U+227B): B<<179.0,252.0>-<272.0,326.0>-<424.0,336.0>>/B<<424.0,336.0>-<272.0,344.0>-<179.0,413.5>> = 6.776822369089007

	* uni227C (U+227C): B<<421.0,538.5>-<328.0,469.0>-<176.0,461.0>>/B<<176.0,461.0>-<328.0,451.0>-<421.0,377.0>> = 6.776822369089007

	* uni22CE (U+22CE): B<<218.5,448.5>-<290.0,355.0>-<298.0,201.0>>/B<<298.0,201.0>-<308.0,355.0>-<380.0,448.5>> = 6.689020187908829

	* uni234B (U+234B): L<<277.0,109.0>--<277.0,505.0>>/L<<277.0,505.0>--<187.0,109.0>> = 12.80426606528674

	* uni234B (U+234B): L<<412.0,109.0>--<322.0,504.0>>/L<<322.0,504.0>--<322.0,109.0>> = 12.835609486401424

	* uni2352 (U+2352): L<<189.0,621.0>--<281.0,226.0>>/L<<281.0,226.0>--<280.0,621.0>> = 12.966040693270955

	* uni2352 (U+2352): L<<324.0,621.0>--<324.0,226.0>>/L<<324.0,226.0>--<413.0,621.0>> = 12.697640216649821

	* uni236C (U+236C): L<<197.0,524.0>--<197.0,383.0>>/B<<197.0,383.0>-<210.0,457.0>-<257.0,457.0>> = 9.963804189907158

	* uni236C (U+236C): L<<403.0,206.0>--<403.0,361.0>>/B<<403.0,361.0>-<390.0,287.0>-<343.0,287.0>> = 9.963804189907158

	* uni2375 (U+2375): B<<338.5,20.5>-<306.0,51.0>-<300.0,104.0>>/B<<300.0,104.0>-<293.0,51.0>-<260.5,20.5>> = 13.982636817357287

	* uni2379 (U+2379): B<<338.5,20.5>-<306.0,51.0>-<300.0,104.0>>/B<<300.0,104.0>-<293.0,51.0>-<260.5,20.5>> = 13.982636817357287

	* uni26A1 (U+26A1): L<<579.0,440.0>--<49.0,-110.0>>/L<<49.0,-110.0>--<294.0,310.0>> = 13.68265114620652

	* w (U+0077): B<<171.0,146.0>-<174.0,110.0>-<176.0,86.0>>/B<<176.0,86.0>-<177.0,110.0>-<180.0,146.0>> = 7.149585721114954

	* w (U+0077): B<<306.0,403.5>-<302.0,440.0>-<300.0,463.0>>/B<<300.0,463.0>-<299.0,440.0>-<294.0,403.5>> = 7.459293650109428

	* w (U+0077): B<<420.5,145.5>-<424.0,109.0>-<426.0,85.0>>/B<<426.0,85.0>-<428.0,109.0>-<430.5,145.5>> = 9.527283381452328

	* wacute (U+1E83): B<<171.0,146.0>-<174.0,110.0>-<176.0,86.0>>/B<<176.0,86.0>-<177.0,110.0>-<180.0,146.0>> = 7.149585721114954

	* wacute (U+1E83): B<<306.0,403.5>-<302.0,440.0>-<300.0,463.0>>/B<<300.0,463.0>-<299.0,440.0>-<294.0,403.5>> = 7.459293650109428

	* wacute (U+1E83): B<<420.5,145.5>-<424.0,109.0>-<426.0,85.0>>/B<<426.0,85.0>-<428.0,109.0>-<430.5,145.5>> = 9.527283381452328

	* wcircumflex (U+0175): B<<171.0,146.0>-<174.0,110.0>-<176.0,86.0>>/B<<176.0,86.0>-<177.0,110.0>-<180.0,146.0>> = 7.149585721114954

	* wcircumflex (U+0175): B<<306.0,403.5>-<302.0,440.0>-<300.0,463.0>>/B<<300.0,463.0>-<299.0,440.0>-<294.0,403.5>> = 7.459293650109428

	* wcircumflex (U+0175): B<<420.5,145.5>-<424.0,109.0>-<426.0,85.0>>/B<<426.0,85.0>-<428.0,109.0>-<430.5,145.5>> = 9.527283381452328

	* wdieresis (U+1E85): B<<171.0,146.0>-<174.0,110.0>-<176.0,86.0>>/B<<176.0,86.0>-<177.0,110.0>-<180.0,146.0>> = 7.149585721114954

	* wdieresis (U+1E85): B<<306.0,403.5>-<302.0,440.0>-<300.0,463.0>>/B<<300.0,463.0>-<299.0,440.0>-<294.0,403.5>> = 7.459293650109428

	* wdieresis (U+1E85): B<<420.5,145.5>-<424.0,109.0>-<426.0,85.0>>/B<<426.0,85.0>-<428.0,109.0>-<430.5,145.5>> = 9.527283381452328

	* wgrave (U+1E81): B<<171.0,146.0>-<174.0,110.0>-<176.0,86.0>>/B<<176.0,86.0>-<177.0,110.0>-<180.0,146.0>> = 7.149585721114954

	* wgrave (U+1E81): B<<306.0,403.5>-<302.0,440.0>-<300.0,463.0>>/B<<300.0,463.0>-<299.0,440.0>-<294.0,403.5>> = 7.459293650109428 

	* wgrave (U+1E81): B<<420.5,145.5>-<424.0,109.0>-<426.0,85.0>>/B<<426.0,85.0>-<428.0,109.0>-<430.5,145.5>> = 9.527283381452328 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* e (U+0065): L<<190.0,325.0>--<410.0,326.0>>

	* eacute (U+00E9): L<<190.0,325.0>--<410.0,326.0>>

	* ebreve (U+0115): L<<190.0,325.0>--<410.0,326.0>>

	* ecaron (U+011B): L<<190.0,325.0>--<410.0,326.0>>

	* ecircumflex (U+00EA): L<<190.0,325.0>--<410.0,326.0>>

	* edieresis (U+00EB): L<<190.0,325.0>--<410.0,326.0>>

	* edotaccent (U+0117): L<<190.0,325.0>--<410.0,326.0>>

	* egrave (U+00E8): L<<190.0,325.0>--<410.0,326.0>>

	* emacron (U+0113): L<<190.0,325.0>--<410.0,326.0>>

	* eogonek (U+0119): L<<192.0,323.0>--<408.0,324.0>>

	* phi (U+03C6): L<<151.0,345.0>--<150.0,205.0>>

	* uni0428 (U+0428): L<<48.0,0.0>--<47.0,730.0>>

	* uni0435 (U+0435): L<<190.0,325.0>--<410.0,326.0>>

	* uni0448 (U+0448): L<<48.0,0.0>--<47.0,550.0>>

	* uni0451 (U+0451): L<<190.0,325.0>--<410.0,326.0>>

	* uni04D9 (U+04D9): L<<410.0,225.0>--<190.0,224.0>>

	* uni1EB9 (U+1EB9): L<<190.0,325.0>--<410.0,326.0>>

	* uni1EBB (U+1EBB): L<<190.0,325.0>--<410.0,326.0>>

	* uni1EBD (U+1EBD): L<<190.0,325.0>--<410.0,326.0>>

	* uni1EBF (U+1EBF): L<<190.0,325.0>--<410.0,326.0>>

	* uni1EC1 (U+1EC1): L<<190.0,325.0>--<410.0,326.0>>

	* uni1EC3 (U+1EC3): L<<190.0,325.0>--<410.0,326.0>>

	* uni1EC5 (U+1EC5): L<<190.0,325.0>--<410.0,326.0>>

	* uni1EC7 (U+1EC7): L<<190.0,325.0>--<410.0,326.0>>

	* uni2352 (U+2352): L<<281.0,226.0>--<280.0,621.0>> 

	* uniE0A2 (U+E0A2): L<<345.0,50.0>--<344.0,210.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[18] PitagonSansMono-SemiBoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Pitagon Sans Mono SemiBold' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, exclam_equal_equal.liga.ss19.001, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- dollar.cv14

	- eight.dnom

	- eight.numr

	- exclam_equal.liga.ss19.001

	- exclam_equal_equal.liga.ss19.001

	- five.dnom

	- five.numr

	- four.dnom

	- four.numr

	- nine.dnom

	- nine.numr

	- one.dnom

	- one.numr

	- seven.dnom

	- seven.numr

	- six.dnom

	- six.numr

	- three.dnom

	- three.numr

	- two.dnom

	- two.numr

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- zero.dnom 

	- zero.numr
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1697 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 2 glyphs (0.11%) have a different width. You should check the widths of: ['periodcentered.loclCAT', 'periodcentered.loclCAT.case'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): B<<491.0,577.0>-<505.0,641.0>-<518.0,693.0>>/L<<518.0,693.0>--<357.0,338.0>> = 10.35905248808368

	* M (U+004D): L<<256.0,342.0>--<210.0,684.0>>/B<<210.0,684.0>-<208.0,613.0>-<198.5,521.0>> = 9.27401426734746

	* Mu (U+039C): B<<491.0,577.0>-<505.0,641.0>-<518.0,693.0>>/L<<518.0,693.0>--<357.0,338.0>> = 10.35905248808368

	* Mu (U+039C): L<<256.0,342.0>--<210.0,684.0>>/B<<210.0,684.0>-<208.0,613.0>-<198.5,521.0>> = 9.27401426734746

	* Uogonek (U+0172): B<<213.0,-58.5>-<237.0,-30.0>-<272.0,-6.0>>/B<<272.0,-6.0>-<263.0,-10.0>-<254.0,-10.0>> = 10.476500334225372

	* W (U+0057): B<<142.0,138.0>-<138.0,100.0>-<135.0,76.0>>/B<<135.0,76.0>-<142.0,100.0>-<151.0,138.0>> = 9.135188359410144

	* W (U+0057): B<<357.0,599.0>-<360.0,636.0>-<362.0,659.0>>/B<<362.0,659.0>-<356.0,636.0>-<347.5,599.0>> = 9.651133260521348

	* W (U+0057): B<<398.5,138.0>-<397.0,100.0>-<395.0,76.0>>/B<<395.0,76.0>-<401.0,100.0>-<409.5,138.0>> = 9.272601777200244

	* Wacute (U+1E82): B<<142.0,138.0>-<138.0,100.0>-<135.0,76.0>>/B<<135.0,76.0>-<142.0,100.0>-<151.0,138.0>> = 9.135188359410144

	* Wacute (U+1E82): B<<357.0,599.0>-<360.0,636.0>-<362.0,659.0>>/B<<362.0,659.0>-<356.0,636.0>-<347.5,599.0>> = 9.651133260521348

	* Wacute (U+1E82): B<<398.5,138.0>-<397.0,100.0>-<395.0,76.0>>/B<<395.0,76.0>-<401.0,100.0>-<409.5,138.0>> = 9.272601777200244

	* Wcircumflex (U+0174): B<<142.0,138.0>-<138.0,100.0>-<135.0,76.0>>/B<<135.0,76.0>-<142.0,100.0>-<151.0,138.0>> = 9.135188359410144

	* Wcircumflex (U+0174): B<<357.0,599.0>-<360.0,636.0>-<362.0,659.0>>/B<<362.0,659.0>-<356.0,636.0>-<347.5,599.0>> = 9.651133260521348

	* Wcircumflex (U+0174): B<<398.5,138.0>-<397.0,100.0>-<395.0,76.0>>/B<<395.0,76.0>-<401.0,100.0>-<409.5,138.0>> = 9.272601777200244

	* Wdieresis (U+1E84): B<<142.0,138.0>-<138.0,100.0>-<135.0,76.0>>/B<<135.0,76.0>-<142.0,100.0>-<151.0,138.0>> = 9.135188359410144

	* Wdieresis (U+1E84): B<<357.0,599.0>-<360.0,636.0>-<362.0,659.0>>/B<<362.0,659.0>-<356.0,636.0>-<347.5,599.0>> = 9.651133260521348

	* Wdieresis (U+1E84): B<<398.5,138.0>-<397.0,100.0>-<395.0,76.0>>/B<<395.0,76.0>-<401.0,100.0>-<409.5,138.0>> = 9.272601777200244

	* Wgrave (U+1E80): B<<142.0,138.0>-<138.0,100.0>-<135.0,76.0>>/B<<135.0,76.0>-<142.0,100.0>-<151.0,138.0>> = 9.135188359410144

	* Wgrave (U+1E80): B<<357.0,599.0>-<360.0,636.0>-<362.0,659.0>>/B<<362.0,659.0>-<356.0,636.0>-<347.5,599.0>> = 9.651133260521348

	* Wgrave (U+1E80): B<<398.5,138.0>-<397.0,100.0>-<395.0,76.0>>/B<<395.0,76.0>-<401.0,100.0>-<409.5,138.0>> = 9.272601777200244

	* ae (U+00E6): B<<305.0,535.5>-<335.0,511.0>-<334.0,470.0>>/B<<334.0,470.0>-<345.0,511.0>-<382.0,535.5>> = 13.621179603854264

	* aeacute (U+01FD): B<<305.0,535.5>-<335.0,511.0>-<334.0,470.0>>/B<<334.0,470.0>-<345.0,511.0>-<382.0,535.5>> = 13.621179603854264

	* b (U+0062): B<<200.5,20.0>-<166.0,50.0>-<163.0,103.0>>/L<<163.0,103.0>--<147.0,0.0>> = 12.069444964011174

	* b (U+0062): L<<239.0,573.0>--<216.0,448.0>>/B<<216.0,448.0>-<236.0,502.0>-<279.5,531.0>> = 9.89732830377812

	* braceleft (U+007B): B<<383.5,404.5>-<346.0,370.0>-<276.0,363.0>>/B<<276.0,363.0>-<343.0,354.0>-<369.5,317.0>> = 13.361244092859051

	* d (U+0064): B<<398.5,530.0>-<434.0,500.0>-<437.0,447.0>>/L<<437.0,447.0>--<454.0,573.0>> = 10.923682125836095

	* d (U+0064): L<<365.0,0.0>--<382.0,104.0>>/B<<382.0,104.0>-<363.0,49.0>-<319.5,19.5>> = 9.774151704866913

	* dcaron (U+010F): L<<309.0,0.0>--<325.0,102.0>>/B<<325.0,102.0>-<310.0,49.0>-<271.0,19.5>> = 6.887586996787647

	* endOfMediumcontrol (U+2419): B<<530.0,210.0>-<539.0,257.0>-<554.0,295.0>>/L<<554.0,295.0>--<443.0,96.0>> = 7.611319099534627

	* endOfMediumcontrol (U+2419): L<<370.0,96.0>--<320.0,292.0>>/B<<320.0,292.0>-<321.0,267.0>-<320.0,241.0>> = 12.020431219967877

	* eogonek (U+0119): B<<183.0,-111.0>-<190.0,-62.0>-<266.0,-8.0>>/B<<266.0,-8.0>-<261.0,-10.0>-<254.0,-10.0>> = 13.593386358635234

	* epsilon (U+03B5): B<<106.5,250.0>-<151.0,287.0>-<216.0,290.0>>/B<<216.0,290.0>-<155.0,293.0>-<124.5,325.5>> = 5.458101978275948

	* epsilontonos (U+03AD): B<<106.5,250.0>-<151.0,287.0>-<216.0,290.0>>/B<<216.0,290.0>-<155.0,293.0>-<124.5,325.5>> = 5.458101978275948

	* g (U+0067): L<<371.0,47.0>--<388.0,138.0>>/B<<388.0,138.0>-<367.0,89.0>-<324.5,62.5>> = 12.616954992704343

	* gbreve (U+011F): L<<371.0,47.0>--<388.0,138.0>>/B<<388.0,138.0>-<367.0,89.0>-<324.5,62.5>> = 12.616954992704343

	* gcaron (U+01E7): L<<371.0,47.0>--<388.0,138.0>>/B<<388.0,138.0>-<367.0,89.0>-<324.5,62.5>> = 12.616954992704343

	* gcircumflex (U+011D): L<<371.0,47.0>--<388.0,138.0>>/B<<388.0,138.0>-<367.0,89.0>-<324.5,62.5>> = 12.616954992704343

	* gdotaccent (U+0121): L<<371.0,47.0>--<388.0,138.0>>/B<<388.0,138.0>-<367.0,89.0>-<324.5,62.5>> = 12.616954992704343

	* nu (U+03BD): B<<264.5,136.5>-<268.0,106.0>-<267.0,86.0>>/B<<267.0,86.0>-<272.0,106.0>-<285.0,136.5>> = 11.173838241814705

	* p (U+0070): L<<230.0,526.0>--<217.0,448.0>>/B<<217.0,448.0>-<237.0,502.0>-<280.5,531.0>> = 10.860814621637298

	* perthousand (U+2030): B<<394.0,271.5>-<415.0,253.0>-<413.0,222.0>>/B<<413.0,222.0>-<422.0,253.0>-<449.0,271.5>> = 12.49782027057565

	* perthousand (U+2030): B<<407.5,13.5>-<387.0,32.0>-<389.0,63.0>>/B<<389.0,63.0>-<380.0,32.0>-<353.0,13.5>> = 12.49782027057565

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<365.0,279.0>-<368.0,276.0>-<370.0,275.0>>/L<<370.0,275.0>--<365.0,279.0>> = 12.094757077012058

	* petapp.minimal (U+E007): B<<402.0,358.0>-<402.0,357.0>-<401.0,355.0>>/L<<401.0,355.0>--<402.0,358.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>>/L<<437.0,404.0>--<440.0,406.0>> = 7.125016348901757

	* petapp.minimal (U+E007): B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>>/L<<442.0,407.0>--<447.0,409.0>> = 4.763641690726143

	* petapp.minimal (U+E007): B<<468.0,415.0>-<467.0,415.0>-<465.0,414.0>>/L<<465.0,414.0>--<468.0,415.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>>/L<<467.0,106.0>--<469.0,103.0>> = 11.309932474020195

	* petapp.minimal (U+E007): B<<484.5,8.5>-<484.0,4.0>-<483.0,0.0>>/B<<483.0,0.0>-<483.0,3.0>-<483.0,6.5>> = 14.036243467926484

	* petapp.minimal (U+E007): L<<408.0,166.0>--<411.0,165.0>>/B<<411.0,165.0>-<409.0,166.0>-<408.0,166.5>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<413.0,298.0>--<412.0,301.0>>/B<<412.0,301.0>-<413.0,299.0>-<413.0,298.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<417.0,160.0>--<420.0,159.0>>/B<<420.0,159.0>-<418.0,160.0>-<417.0,160.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<437.0,404.0>--<440.0,406.0>>/B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>> = 11.309932474020227

	* petapp.minimal (U+E007): L<<442.0,407.0>--<447.0,409.0>>/B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>> = 3.3664606634297236

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<467.0,106.0>--<469.0,103.0>>/B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>> = 7.125016348901757

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<90.0,577.0>-<99.0,557.0>> = 4.969740728110289

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* q (U+0071): B<<397.0,529.5>-<432.0,499.0>-<436.0,447.0>>/L<<436.0,447.0>--<452.0,550.0>> = 13.228450022904594

	* radical (U+221A): L<<247.0,550.0>--<289.0,79.0>>/B<<289.0,79.0>-<291.0,93.0>-<298.0,120.0>> = 13.225802273714564

	* thorn (U+00FE): B<<197.5,20.0>-<163.0,50.0>-<160.0,103.0>>/L<<160.0,103.0>--<143.0,0.0>> = 12.611793004681205

	* thorn (U+00FE): L<<235.0,573.0>--<213.0,448.0>>/B<<213.0,448.0>-<232.0,502.0>-<276.0,531.0>> = 9.402686391624673

	* trademark (U+2122): B<<428.5,652.5>-<426.0,679.0>-<423.0,699.0>>/B<<423.0,699.0>-<422.0,675.0>-<419.5,638.0>> = 10.916709640336949

	* trademark (U+2122): B<<567.0,637.0>-<576.0,675.0>-<583.0,700.0>>/B<<583.0,700.0>-<575.0,680.0>-<563.0,652.5>> = 6.159163029142964

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni0123 (U+0123): L<<371.0,47.0>--<388.0,138.0>>/B<<388.0,138.0>-<367.0,89.0>-<324.5,62.5>> = 12.616954992704343

	* uni01EA (U+01EA): B<<213.0,-58.5>-<237.0,-30.0>-<272.0,-6.0>>/B<<272.0,-6.0>-<264.0,-10.0>-<254.0,-10.0>> = 7.873938131725601

	* uni01EB (U+01EB): B<<205.5,-61.5>-<225.0,-36.0>-<268.0,-6.0>>/B<<268.0,-6.0>-<260.0,-10.0>-<254.0,-10.0>> = 8.337444438846678

	* uni01F5 (U+01F5): L<<371.0,47.0>--<388.0,138.0>>/B<<388.0,138.0>-<367.0,89.0>-<324.5,62.5>> = 12.616954992704343

	* uni03D6 (U+03D6): B<<298.0,19.5>-<271.0,49.0>-<272.0,101.0>>/B<<272.0,101.0>-<258.0,49.0>-<221.0,19.5>> = 13.96678204428583

	* uni03D7 (U+03D7): B<<156.0,138.5>-<148.0,107.0>-<141.0,85.0>>/L<<141.0,85.0>--<422.0,550.0>> = 13.494489601340437

	* uni03D7 (U+03D7): B<<442.5,408.5>-<450.0,439.0>-<457.0,460.0>>/L<<457.0,460.0>--<177.0,0.0>> = 12.893744044882132

	* uni0418 (U+0418): B<<161.5,189.0>-<153.0,150.0>-<147.0,123.0>>/L<<147.0,123.0>--<454.0,730.0>> = 14.29993026936884

	* uni0418 (U+0418): B<<466.0,539.0>-<475.0,579.0>-<482.0,607.0>>/L<<482.0,607.0>--<174.0,0.0>> = 12.867609289569407

	* uni0419 (U+0419): B<<161.5,189.0>-<153.0,150.0>-<147.0,123.0>>/L<<147.0,123.0>--<454.0,730.0>> = 14.29993026936884

	* uni0419 (U+0419): B<<466.0,539.0>-<475.0,579.0>-<482.0,607.0>>/L<<482.0,607.0>--<174.0,0.0>> = 12.867609289569407

	* uni041C (U+041C): B<<491.0,577.0>-<505.0,641.0>-<518.0,693.0>>/L<<518.0,693.0>--<357.0,338.0>> = 10.35905248808368

	* uni041C (U+041C): L<<256.0,342.0>--<210.0,684.0>>/B<<210.0,684.0>-<208.0,613.0>-<198.5,521.0>> = 9.27401426734746

	* uni0431 (U+0431): L<<197.0,459.0>--<190.0,413.0>>/B<<190.0,413.0>-<210.0,463.0>-<254.0,489.5>> = 13.148867695237074

	* uni0434 (U+0434): B<<413.5,487.0>-<450.0,458.0>-<452.0,406.0>>/L<<452.0,406.0>--<461.0,459.0>> = 11.840136274696714

	* uni0437 (U+0437): B<<488.5,322.0>-<449.0,290.0>-<389.0,288.0>>/B<<389.0,288.0>-<459.0,284.0>-<489.0,249.5>> = 5.179640356179886

	* uni043C (U+043C): B<<456.0,378.5>-<466.0,425.0>-<473.0,461.0>>/L<<473.0,461.0>--<335.0,162.0>> = 13.771599717082417

	* uni0440 (U+0440): L<<230.0,526.0>--<217.0,448.0>>/B<<217.0,448.0>-<237.0,502.0>-<280.5,531.0>> = 10.860814621637298

	* uni04DF (U+04DF): B<<488.5,322.0>-<449.0,290.0>-<389.0,288.0>>/B<<389.0,288.0>-<459.0,284.0>-<489.0,249.5>> = 5.179640356179886

	* uni04E4 (U+04E4): B<<161.5,189.0>-<153.0,150.0>-<147.0,123.0>>/L<<147.0,123.0>--<454.0,730.0>> = 14.29993026936884

	* uni04E4 (U+04E4): B<<466.0,539.0>-<475.0,579.0>-<482.0,607.0>>/L<<482.0,607.0>--<174.0,0.0>> = 12.867609289569407

	* uni2116 (U+2116): B<<153.5,572.5>-<151.0,611.0>-<149.0,641.0>>/B<<149.0,641.0>-<147.0,600.0>-<143.5,546.5>> = 6.606777200003615

	* uni2116 (U+2116): B<<254.5,160.5>-<257.0,121.0>-<259.0,90.0>>/B<<259.0,90.0>-<261.0,132.0>-<264.5,186.0>> = 6.417696980357485

	* uni2196 (U+2196): B<<243.0,639.0>-<225.0,640.0>-<215.0,646.0>>/L<<215.0,646.0>--<562.0,300.0>> = 13.953565632796554

	* uni2197 (U+2197): L<<40.0,300.0>--<387.0,646.0>>/B<<387.0,646.0>-<377.0,640.0>-<359.5,639.0>> = 13.953565632796554

	* uni2198 (U+2198): B<<359.5,91.5>-<377.0,90.0>-<387.0,84.0>>/L<<387.0,84.0>--<40.0,430.0>> = 13.953565632796579

	* uni2199 (U+2199): L<<560.0,430.0>--<213.0,84.0>>/B<<213.0,84.0>-<223.0,90.0>-<240.5,91.5>> = 13.953565632796579

	* uni227A (U+227A): B<<378.0,368.5>-<299.0,333.0>-<201.0,328.0>>/B<<201.0,328.0>-<345.0,318.0>-<424.5,247.0>> = 6.893217461751019

	* uni227B (U+227B): B<<249.0,293.0>-<328.0,329.0>-<427.0,335.0>>/B<<427.0,335.0>-<331.0,341.0>-<262.5,374.5>> = 7.0445636339144215

	* uni227C (U+227C): B<<401.0,493.5>-<322.0,458.0>-<224.0,453.0>>/B<<224.0,453.0>-<368.0,443.0>-<447.5,372.0>> = 6.893217461751019

	* uni22CE (U+22CE): B<<274.5,383.0>-<297.0,309.0>-<287.0,212.0>>/B<<287.0,212.0>-<309.0,310.0>-<356.0,384.0>> = 6.766568667529695

	* uni234B (U+234B): L<<276.0,95.0>--<276.0,525.0>>/L<<276.0,525.0>--<175.0,95.0>> = 13.2182373989993

	* uni234B (U+234B): L<<425.0,95.0>--<323.0,525.0>>/L<<323.0,525.0>--<323.0,95.0>> = 13.344450989740325

	* uni2352 (U+2352): L<<176.0,635.0>--<281.0,203.0>>/L<<281.0,203.0>--<278.0,635.0>> = 13.263272745070877

	* uni2352 (U+2352): L<<324.0,635.0>--<324.0,203.0>>/L<<324.0,203.0>--<425.0,635.0>> = 13.159175935941423

	* uni236C (U+236C): L<<227.0,527.0>--<205.0,387.0>>/B<<205.0,387.0>-<230.0,457.0>-<279.0,457.0>> = 10.723233957634339

	* uni236C (U+236C): L<<401.0,203.0>--<425.0,359.0>>/B<<425.0,359.0>-<400.0,287.0>-<350.0,287.0>> = 10.401975195384372

	* uni2375 (U+2375): B<<297.0,19.5>-<270.0,49.0>-<272.0,100.0>>/B<<272.0,100.0>-<257.0,49.0>-<220.0,19.5>> = 14.14379776813967

	* uni2377 (U+2377): B<<103.0,252.5>-<145.0,289.0>-<215.0,292.0>>/B<<215.0,292.0>-<156.0,296.0>-<128.0,326.0>> = 6.332556177374743

	* uni2379 (U+2379): B<<297.0,19.5>-<270.0,49.0>-<272.0,100.0>>/B<<272.0,100.0>-<257.0,49.0>-<220.0,19.5>> = 14.14379776813967

	* uni26A1 (U+26A1): L<<580.0,440.0>--<50.0,-110.0>>/L<<50.0,-110.0>--<295.0,310.0>> = 13.68265114620652

	* uniFF5B (U+FF5B): B<<383.5,404.5>-<346.0,370.0>-<276.0,363.0>>/B<<276.0,363.0>-<343.0,354.0>-<369.5,317.0>> = 13.361244092859051

	* uogonek (U+0173): B<<205.5,-61.5>-<225.0,-36.0>-<268.0,-6.0>>/B<<268.0,-6.0>-<260.0,-10.0>-<254.0,-10.0>> = 8.337444438846678

	* v (U+0076): B<<264.5,136.5>-<268.0,106.0>-<267.0,86.0>>/B<<267.0,86.0>-<272.0,106.0>-<285.0,136.5>> = 11.173838241814705

	* w (U+0077): B<<145.5,129.5>-<143.0,98.0>-<141.0,78.0>>/B<<141.0,78.0>-<146.0,98.0>-<154.0,129.5>> = 8.325650330426848

	* w (U+0077): B<<328.5,421.0>-<330.0,455.0>-<331.0,475.0>>/B<<331.0,475.0>-<327.0,455.0>-<317.0,421.0>> = 8.447527247908404

	* w (U+0077): B<<395.5,129.5>-<394.0,98.0>-<392.0,78.0>>/B<<392.0,78.0>-<397.0,98.0>-<405.0,129.5>> = 8.325650330426848

	* wacute (U+1E83): B<<145.5,129.5>-<143.0,98.0>-<141.0,78.0>>/B<<141.0,78.0>-<146.0,98.0>-<154.0,129.5>> = 8.325650330426848

	* wacute (U+1E83): B<<328.5,421.0>-<330.0,455.0>-<331.0,475.0>>/B<<331.0,475.0>-<327.0,455.0>-<317.0,421.0>> = 8.447527247908404

	* wacute (U+1E83): B<<395.5,129.5>-<394.0,98.0>-<392.0,78.0>>/B<<392.0,78.0>-<397.0,98.0>-<405.0,129.5>> = 8.325650330426848

	* wcircumflex (U+0175): B<<145.5,129.5>-<143.0,98.0>-<141.0,78.0>>/B<<141.0,78.0>-<146.0,98.0>-<154.0,129.5>> = 8.325650330426848

	* wcircumflex (U+0175): B<<328.5,421.0>-<330.0,455.0>-<331.0,475.0>>/B<<331.0,475.0>-<327.0,455.0>-<317.0,421.0>> = 8.447527247908404

	* wcircumflex (U+0175): B<<395.5,129.5>-<394.0,98.0>-<392.0,78.0>>/B<<392.0,78.0>-<397.0,98.0>-<405.0,129.5>> = 8.325650330426848

	* wdieresis (U+1E85): B<<145.5,129.5>-<143.0,98.0>-<141.0,78.0>>/B<<141.0,78.0>-<146.0,98.0>-<154.0,129.5>> = 8.325650330426848

	* wdieresis (U+1E85): B<<328.5,421.0>-<330.0,455.0>-<331.0,475.0>>/B<<331.0,475.0>-<327.0,455.0>-<317.0,421.0>> = 8.447527247908404

	* wdieresis (U+1E85): B<<395.5,129.5>-<394.0,98.0>-<392.0,78.0>>/B<<392.0,78.0>-<397.0,98.0>-<405.0,129.5>> = 8.325650330426848

	* wgrave (U+1E81): B<<145.5,129.5>-<143.0,98.0>-<141.0,78.0>>/B<<141.0,78.0>-<146.0,98.0>-<154.0,129.5>> = 8.325650330426848

	* wgrave (U+1E81): B<<328.5,421.0>-<330.0,455.0>-<331.0,475.0>>/B<<331.0,475.0>-<327.0,455.0>-<317.0,421.0>> = 8.447527247908404 

	* wgrave (U+1E81): B<<395.5,129.5>-<394.0,98.0>-<392.0,78.0>>/B<<392.0,78.0>-<397.0,98.0>-<405.0,129.5>> = 8.325650330426848 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[20] PitagonSansMono-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Pitagon Sans Mono Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- uni2070.zero

	- uni2080.zero

	- zero.dnom.zero 

	- zero.numr.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1710 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* Oslash (U+00D8): X=549.0,Y=729.0 (should be at cap-height 730?)

	* Aogonek (U+0104): X=530.0,Y=1.0 (should be at baseline 0?)

	* Aogonek (U+0104): X=530.0,Y=1.0 (should be at baseline 0?)

	* aogonek (U+0105): X=493.0,Y=-1.0 (should be at baseline 0?)

	* eogonek (U+0119): X=399.0,Y=1.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=398.0,Y=1.0 (should be at baseline 0?)

	* uogonek (U+0173): X=397.0,Y=1.0 (should be at baseline 0?)

	* uni019B (U+019B): X=449.0,Y=729.0 (should be at cap-height 730?)

	* uni019B (U+019B): X=464.0,Y=730.5 (should be at cap-height 730?)

	* uni01EA (U+01EA): X=398.0,Y=1.0 (should be at baseline 0?)

	* uni01EB (U+01EB): X=397.0,Y=1.0 (should be at baseline 0?)

	* Oslashacute (U+01FE): X=549.0,Y=729.0 (should be at cap-height 730?)

	* ogonek (U+02DB): X=331.0,Y=1.0 (should be at baseline 0?)

	* uni0328 (U+0328): X=-269.0,Y=1.0 (should be at baseline 0?)

	* Alphatonos (U+0386): X=95.0,Y=729.0 (should be at cap-height 730?)

	* Alphatonos (U+0386): X=141.0,Y=729.0 (should be at cap-height 730?)

	* Epsilontonos (U+0388): X=-28.0,Y=729.0 (should be at cap-height 730?)

	* Epsilontonos (U+0388): X=18.0,Y=729.0 (should be at cap-height 730?)

	* Etatonos (U+0389): X=-28.0,Y=729.0 (should be at cap-height 730?)

	* Etatonos (U+0389): X=18.0,Y=729.0 (should be at cap-height 730?)

	* Iotatonos (U+038A): X=-28.0,Y=729.0 (should be at cap-height 730?)

	* Iotatonos (U+038A): X=18.0,Y=729.0 (should be at cap-height 730?)

	* Omicrontonos (U+038C): X=5.0,Y=729.0 (should be at cap-height 730?)

	* Omicrontonos (U+038C): X=51.0,Y=729.0 (should be at cap-height 730?)

	* Upsilontonos (U+038E): X=-41.0,Y=729.0 (should be at cap-height 730?)

	* Upsilontonos (U+038E): X=5.0,Y=729.0 (should be at cap-height 730?)

	* Omegatonos (U+038F): X=5.0,Y=729.0 (should be at cap-height 730?)

	* Omegatonos (U+038F): X=51.0,Y=729.0 (should be at cap-height 730?)

	* zeta (U+03B6): X=442.0,Y=-2.0 (should be at baseline 0?)

	* xi (U+03BE): X=525.0,Y=-1.5 (should be at baseline 0?)

	* uni03C2 (U+03C2): X=478.0,Y=-1.5 (should be at baseline 0?)

	* uni21DE (U+21DE): X=338.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=262.0,Y=-1.0 (should be at baseline 0?)

	* uni21DF (U+21DF): X=262.0,Y=731.0 (should be at cap-height 730?)

	* uni21DF (U+21DF): X=338.0,Y=731.0 (should be at cap-height 730?)

	* uni21E7 (U+21E7): X=301.0,Y=729.0 (should be at cap-height 730?)

	* uni21EA (U+21EA): X=300.0,Y=728.0 (should be at cap-height 730?)

	* uni27C5 (U+27C5): X=263.5,Y=-2.0 (should be at baseline 0?)

	* uni27C6 (U+27C6): X=346.5,Y=-2.0 (should be at baseline 0?)

	* piads (U+E001): X=158.0,Y=2.0 (should be at baseline 0?)

	* pioffice (U+E002): X=158.0,Y=2.0 (should be at baseline 0?)

	* pitagram (U+E003): X=158.0,Y=2.0 (should be at baseline 0?)

	* piweb (U+E004): X=158.0,Y=2.0 (should be at baseline 0?)

	* pisign (U+E005): X=158.0,Y=2.0 (should be at baseline 0?)

	* petapp (U+E006): X=534.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=303.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=293.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=318.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=336.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=331.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=328.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=326.0,Y=1.5 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=278.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=274.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=272.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?) 

	* picall (U+E009): X=158.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): L<<257.0,341.0>--<141.0,697.0>>/B<<141.0,697.0>-<148.0,632.0>-<151.0,547.5>> = 11.90119540912436

	* Mu (U+039C): L<<257.0,341.0>--<141.0,697.0>>/B<<141.0,697.0>-<148.0,632.0>-<151.0,547.5>> = 11.90119540912436

	* W (U+0057): B<<165.0,120.0>-<168.0,81.0>-<170.0,57.0>>/B<<170.0,57.0>-<172.0,81.0>-<176.0,120.0>> = 9.527283381452328

	* W (U+0057): B<<307.5,616.0>-<304.0,652.0>-<302.0,673.0>>/B<<302.0,673.0>-<299.0,652.0>-<296.5,616.0>> = 13.570434385161475

	* W (U+0057): B<<423.5,120.0>-<428.0,81.0>-<431.0,57.0>>/B<<431.0,57.0>-<433.0,81.0>-<437.0,120.0>> = 11.888658039627936

	* Wacute (U+1E82): B<<165.0,120.0>-<168.0,81.0>-<170.0,57.0>>/B<<170.0,57.0>-<172.0,81.0>-<176.0,120.0>> = 9.527283381452328

	* Wacute (U+1E82): B<<307.5,616.0>-<304.0,652.0>-<302.0,673.0>>/B<<302.0,673.0>-<299.0,652.0>-<296.5,616.0>> = 13.570434385161475

	* Wacute (U+1E82): B<<423.5,120.0>-<428.0,81.0>-<431.0,57.0>>/B<<431.0,57.0>-<433.0,81.0>-<437.0,120.0>> = 11.888658039627936

	* Wcircumflex (U+0174): B<<165.0,120.0>-<168.0,81.0>-<170.0,57.0>>/B<<170.0,57.0>-<172.0,81.0>-<176.0,120.0>> = 9.527283381452328

	* Wcircumflex (U+0174): B<<307.5,616.0>-<304.0,652.0>-<302.0,673.0>>/B<<302.0,673.0>-<299.0,652.0>-<296.5,616.0>> = 13.570434385161475

	* Wcircumflex (U+0174): B<<423.5,120.0>-<428.0,81.0>-<431.0,57.0>>/B<<431.0,57.0>-<433.0,81.0>-<437.0,120.0>> = 11.888658039627936

	* Wdieresis (U+1E84): B<<165.0,120.0>-<168.0,81.0>-<170.0,57.0>>/B<<170.0,57.0>-<172.0,81.0>-<176.0,120.0>> = 9.527283381452328

	* Wdieresis (U+1E84): B<<307.5,616.0>-<304.0,652.0>-<302.0,673.0>>/B<<302.0,673.0>-<299.0,652.0>-<296.5,616.0>> = 13.570434385161475

	* Wdieresis (U+1E84): B<<423.5,120.0>-<428.0,81.0>-<431.0,57.0>>/B<<431.0,57.0>-<433.0,81.0>-<437.0,120.0>> = 11.888658039627936

	* Wgrave (U+1E80): B<<165.0,120.0>-<168.0,81.0>-<170.0,57.0>>/B<<170.0,57.0>-<172.0,81.0>-<176.0,120.0>> = 9.527283381452328

	* Wgrave (U+1E80): B<<307.5,616.0>-<304.0,652.0>-<302.0,673.0>>/B<<302.0,673.0>-<299.0,652.0>-<296.5,616.0>> = 13.570434385161475

	* Wgrave (U+1E80): B<<423.5,120.0>-<428.0,81.0>-<431.0,57.0>>/B<<431.0,57.0>-<433.0,81.0>-<437.0,120.0>> = 11.888658039627936

	* arrowboth (U+2194): L<<578.0,295.0>--<21.0,295.0>>/B<<21.0,295.0>-<45.0,289.0>-<69.0,257.0>> = 14.036243467926457

	* arrowleft (U+2190): L<<580.0,295.0>--<111.0,295.0>>/B<<111.0,295.0>-<135.0,289.0>-<159.0,257.0>> = 14.036243467926457

	* arrowright (U+2192): B<<441.0,257.0>-<465.0,289.0>-<489.0,295.0>>/L<<489.0,295.0>--<20.0,295.0>> = 14.036243467926457

	* b (U+0062): B<<226.0,19.5>-<186.0,49.0>-<176.0,100.0>>/L<<176.0,100.0>--<176.0,0.0>> = 11.09372301155785

	* b (U+0062): L<<176.0,573.0>--<175.0,450.0>>/B<<175.0,450.0>-<184.0,501.0>-<225.0,530.5>> = 9.54217071867635

	* braceleft (U+007B): B<<353.5,404.5>-<324.0,370.0>-<259.0,363.0>>/B<<259.0,363.0>-<323.0,354.0>-<353.0,317.0>> = 14.151354516939499

	* d (U+0064): B<<375.0,530.5>-<416.0,501.0>-<425.0,450.0>>/L<<425.0,450.0>--<424.0,573.0>> = 9.54217071867635

	* d (U+0064): L<<424.0,0.0>--<424.0,100.0>>/B<<424.0,100.0>-<414.0,49.0>-<374.0,19.5>> = 11.09372301155785

	* endOfMediumcontrol (U+2419): B<<510.5,212.5>-<512.0,262.0>-<522.0,300.0>>/L<<522.0,300.0>--<436.0,109.0>> = 9.49665435318734

	* endOfMediumcontrol (U+2419): L<<364.0,109.0>--<278.0,297.0>>/B<<278.0,297.0>-<283.0,272.0>-<286.0,245.0>> = 13.27164200854843

	* omega (U+03C9): B<<334.5,22.0>-<303.0,54.0>-<299.0,108.0>>/B<<299.0,108.0>-<296.0,53.0>-<264.5,21.5>> = 7.3585252611745515

	* omegatonos (U+03CE): B<<334.5,22.0>-<303.0,54.0>-<299.0,108.0>>/B<<299.0,108.0>-<296.0,53.0>-<264.5,21.5>> = 7.3585252611745515

	* p (U+0070): L<<176.0,550.0>--<176.0,450.0>>/B<<176.0,450.0>-<186.0,501.0>-<226.0,530.5>> = 11.09372301155785

	* perthousand (U+2030): B<<406.0,271.0>-<429.0,252.0>-<431.0,220.0>>/B<<431.0,220.0>-<434.0,252.0>-<457.5,271.0>> = 8.932159417852464

	* perthousand (U+2030): B<<457.0,14.0>-<434.0,33.0>-<432.0,65.0>>/B<<432.0,65.0>-<429.0,33.0>-<405.0,14.0>> = 8.932159417852464

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<365.0,279.0>-<368.0,276.0>-<370.0,275.0>>/L<<370.0,275.0>--<365.0,279.0>> = 12.094757077012058

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>>/L<<437.0,404.0>--<440.0,406.0>> = 7.125016348901757

	* petapp.minimal (U+E007): B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>>/L<<442.0,407.0>--<447.0,409.0>> = 4.763641690726143

	* petapp.minimal (U+E007): B<<468.0,415.0>-<467.0,415.0>-<465.0,414.0>>/L<<465.0,414.0>--<468.0,415.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<486.0,17.0>-<484.0,7.0>-<483.0,0.0>>/B<<483.0,0.0>-<483.0,3.0>-<483.0,6.5>> = 8.13010235415596

	* petapp.minimal (U+E007): L<<404.0,317.0>--<403.0,320.0>>/B<<403.0,320.0>-<404.0,318.0>-<404.0,317.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<437.0,404.0>--<440.0,406.0>>/B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>> = 11.309932474020227

	* petapp.minimal (U+E007): L<<442.0,407.0>--<447.0,409.0>>/B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>> = 3.3664606634297236

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<475.0,91.0>--<476.0,88.0>>/B<<476.0,88.0>-<475.0,90.0>-<474.5,91.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<89.0,577.0>-<98.5,557.0>> = 2.4895529219991284

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* r (U+0072): L<<197.0,532.0>--<197.0,448.0>>/B<<197.0,448.0>-<206.0,500.0>-<244.5,530.0>> = 9.819300638757893

	* racute (U+0155): L<<197.0,532.0>--<197.0,448.0>>/B<<197.0,448.0>-<206.0,500.0>-<244.5,530.0>> = 9.819300638757893

	* rcaron (U+0159): L<<197.0,532.0>--<197.0,448.0>>/B<<197.0,448.0>-<206.0,500.0>-<244.5,530.0>> = 9.819300638757893

	* thorn (U+00FE): B<<222.0,19.5>-<182.0,49.0>-<172.0,100.0>>/L<<172.0,100.0>--<172.0,-173.0>> = 11.09372301155785

	* thorn (U+00FE): L<<172.0,573.0>--<171.0,450.0>>/B<<171.0,450.0>-<181.0,501.0>-<222.0,530.5>> = 10.627913928792863

	* trademark (U+2122): B<<368.0,658.0>-<360.0,683.0>-<354.0,703.0>>/B<<354.0,703.0>-<356.0,683.0>-<358.5,651.0>> = 10.988651096493946

	* trademark (U+2122): B<<514.5,651.0>-<517.0,683.0>-<519.0,703.0>>/B<<519.0,703.0>-<512.0,683.0>-<504.5,657.0>> = 13.57945308168909

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni0157 (U+0157): L<<197.0,532.0>--<197.0,448.0>>/B<<197.0,448.0>-<206.0,500.0>-<244.5,530.0>> = 9.819300638757893

	* uni03D7 (U+03D7): B<<172.0,152.5>-<171.0,107.0>-<164.0,78.0>>/L<<164.0,78.0>--<403.0,550.0>> = 13.285209969776162

	* uni03D7 (U+03D7): B<<428.0,399.0>-<429.0,445.0>-<436.0,473.0>>/L<<436.0,473.0>--<197.0,0.0>> = 12.770560618419598

	* uni041C (U+041C): L<<257.0,341.0>--<141.0,697.0>>/B<<141.0,697.0>-<148.0,632.0>-<151.0,547.5>> = 11.90119540912436

	* uni0431 (U+0431): L<<158.0,463.0>--<158.0,406.0>>/B<<158.0,406.0>-<169.0,456.0>-<210.0,484.5>> = 12.407418527400745

	* uni0438 (U+0438): B<<172.0,152.5>-<171.0,107.0>-<164.0,78.0>>/L<<164.0,78.0>--<403.0,550.0>> = 13.285209969776162

	* uni0438 (U+0438): B<<428.0,399.0>-<429.0,445.0>-<436.0,473.0>>/L<<436.0,473.0>--<197.0,0.0>> = 12.770560618419598

	* uni0439 (U+0439): B<<172.0,152.5>-<171.0,107.0>-<164.0,78.0>>/L<<164.0,78.0>--<403.0,550.0>> = 13.285209969776162

	* uni0439 (U+0439): B<<428.0,399.0>-<429.0,445.0>-<436.0,473.0>>/L<<436.0,473.0>--<197.0,0.0>> = 12.770560618419598

	* uni0440 (U+0440): L<<176.0,550.0>--<176.0,450.0>>/B<<176.0,450.0>-<186.0,501.0>-<226.0,530.5>> = 11.09372301155785

	* uni04E5 (U+04E5): B<<172.0,152.5>-<171.0,107.0>-<164.0,78.0>>/L<<164.0,78.0>--<403.0,550.0>> = 13.285209969776162

	* uni04E5 (U+04E5): B<<428.0,399.0>-<429.0,445.0>-<436.0,473.0>>/L<<436.0,473.0>--<197.0,0.0>> = 12.770560618419598

	* uni2116 (U+2116): B<<103.0,594.0>-<95.0,627.0>-<89.0,652.0>>/B<<89.0,652.0>-<90.0,628.0>-<92.0,595.5>> = 11.109789250406987

	* uni2116 (U+2116): B<<274.5,136.5>-<282.0,103.0>-<288.0,78.0>>/B<<288.0,78.0>-<286.0,103.0>-<283.5,136.5>> = 8.921812020894938

	* uni227A (U+227A): B<<350.0,374.0>-<278.0,340.0>-<186.0,334.0>>/B<<186.0,334.0>-<278.0,327.0>-<350.0,291.0>> = 8.082474950734255

	* uni227B (U+227B): B<<250.0,291.0>-<322.0,327.0>-<414.0,334.0>>/B<<414.0,334.0>-<322.0,340.0>-<250.0,374.0>> = 8.082474950734255

	* uni227C (U+227C): B<<350.0,499.0>-<278.0,465.0>-<186.0,459.0>>/B<<186.0,459.0>-<278.0,452.0>-<350.0,416.0>> = 8.082474950734255

	* uni22CE (U+22CE): B<<256.5,385.5>-<291.0,314.0>-<297.0,221.0>>/B<<297.0,221.0>-<304.0,314.0>-<339.5,385.5>> = 7.9958549469592395

	* uni234B (U+234B): L<<276.0,71.0>--<276.0,557.0>>/L<<276.0,557.0>--<153.0,71.0>> = 14.202558761363669

	* uni234B (U+234B): L<<447.0,71.0>--<324.0,556.0>>/L<<324.0,556.0>--<324.0,71.0>> = 14.230653995020582

	* uni2352 (U+2352): L<<154.0,659.0>--<280.0,169.0>>/L<<280.0,169.0>--<276.0,659.0>> = 13.95306286747249

	* uni2352 (U+2352): L<<324.0,659.0>--<324.0,169.0>>/L<<324.0,169.0>--<447.0,659.0>> = 14.091256201393758

	* uni236C (U+236C): L<<172.0,533.0>--<172.0,395.0>>/B<<172.0,395.0>-<186.0,457.0>-<238.0,457.0>> = 12.724355685422363

	* uni236C (U+236C): L<<428.0,197.0>--<428.0,349.0>>/B<<428.0,349.0>-<414.0,287.0>-<362.0,287.0>> = 12.724355685422363

	* uni26A1 (U+26A1): L<<580.0,440.0>--<50.0,-110.0>>/L<<50.0,-110.0>--<295.0,310.0>> = 13.68265114620652

	* uniFF5B (U+FF5B): B<<353.5,404.5>-<324.0,370.0>-<259.0,363.0>>/B<<259.0,363.0>-<323.0,354.0>-<353.0,317.0>> = 14.151354516939499

	* w (U+0077): B<<171.5,104.0>-<174.0,78.0>-<176.0,61.0>>/B<<176.0,61.0>-<177.0,78.0>-<180.5,104.0>> = 10.076297471186699

	* w (U+0077): B<<306.5,442.5>-<302.0,475.0>-<300.0,493.0>>/B<<300.0,493.0>-<299.0,475.0>-<294.0,442.5>> = 9.520021865774117

	* w (U+0077): B<<420.5,105.0>-<424.0,79.0>-<426.0,61.0>>/B<<426.0,61.0>-<427.0,79.0>-<430.0,105.0>> = 9.520021865774117

	* wacute (U+1E83): B<<171.5,104.0>-<174.0,78.0>-<176.0,61.0>>/B<<176.0,61.0>-<177.0,78.0>-<180.5,104.0>> = 10.076297471186699

	* wacute (U+1E83): B<<306.5,442.5>-<302.0,475.0>-<300.0,493.0>>/B<<300.0,493.0>-<299.0,475.0>-<294.0,442.5>> = 9.520021865774117

	* wacute (U+1E83): B<<420.5,105.0>-<424.0,79.0>-<426.0,61.0>>/B<<426.0,61.0>-<427.0,79.0>-<430.0,105.0>> = 9.520021865774117

	* wcircumflex (U+0175): B<<171.5,104.0>-<174.0,78.0>-<176.0,61.0>>/B<<176.0,61.0>-<177.0,78.0>-<180.5,104.0>> = 10.076297471186699

	* wcircumflex (U+0175): B<<306.5,442.5>-<302.0,475.0>-<300.0,493.0>>/B<<300.0,493.0>-<299.0,475.0>-<294.0,442.5>> = 9.520021865774117

	* wcircumflex (U+0175): B<<420.5,105.0>-<424.0,79.0>-<426.0,61.0>>/B<<426.0,61.0>-<427.0,79.0>-<430.0,105.0>> = 9.520021865774117

	* wdieresis (U+1E85): B<<171.5,104.0>-<174.0,78.0>-<176.0,61.0>>/B<<176.0,61.0>-<177.0,78.0>-<180.5,104.0>> = 10.076297471186699

	* wdieresis (U+1E85): B<<306.5,442.5>-<302.0,475.0>-<300.0,493.0>>/B<<300.0,493.0>-<299.0,475.0>-<294.0,442.5>> = 9.520021865774117

	* wdieresis (U+1E85): B<<420.5,105.0>-<424.0,79.0>-<426.0,61.0>>/B<<426.0,61.0>-<427.0,79.0>-<430.0,105.0>> = 9.520021865774117

	* wgrave (U+1E81): B<<171.5,104.0>-<174.0,78.0>-<176.0,61.0>>/B<<176.0,61.0>-<177.0,78.0>-<180.5,104.0>> = 10.076297471186699

	* wgrave (U+1E81): B<<306.5,442.5>-<302.0,475.0>-<300.0,493.0>>/B<<300.0,493.0>-<299.0,475.0>-<294.0,442.5>> = 9.520021865774117 

	* wgrave (U+1E81): B<<420.5,105.0>-<424.0,79.0>-<426.0,61.0>>/B<<426.0,61.0>-<427.0,79.0>-<430.0,105.0>> = 9.520021865774117 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* b (U+0062): L<<176.0,573.0>--<175.0,450.0>>

	* d (U+0064): L<<425.0,450.0>--<424.0,573.0>>

	* p (U+0070): L<<175.0,102.0>--<176.0,-15.0>>

	* phi (U+03C6): L<<132.0,358.0>--<131.0,199.0>>

	* q (U+0071): L<<424.0,-23.0>--<425.0,97.0>>

	* thorn (U+00FE): L<<172.0,573.0>--<171.0,450.0>>

	* uni0428 (U+0428): L<<65.0,0.0>--<64.0,730.0>>

	* uni0440 (U+0440): L<<175.0,102.0>--<176.0,-15.0>>

	* uni0448 (U+0448): L<<65.0,0.0>--<64.0,550.0>>

	* uni04B7 (U+04B7): L<<412.0,0.0>--<413.0,194.0>> 

	* uni2352 (U+2352): L<<280.0,169.0>--<276.0,659.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] PitagonSansMono-ThinItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Pitagon Sans Mono Thin' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, exclam_equal_equal.liga.ss19.001, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- dollar.cv14

	- eight.dnom

	- eight.numr

	- exclam_equal.liga.ss19.001

	- exclam_equal_equal.liga.ss19.001

	- five.dnom

	- five.numr

	- four.dnom

	- four.numr

	- nine.dnom

	- nine.numr

	- one.dnom

	- one.numr

	- seven.dnom

	- seven.numr

	- six.dnom

	- six.numr

	- three.dnom

	- three.numr

	- two.dnom

	- two.numr

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- zero.dnom 

	- zero.numr
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: uni2288	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: uni2288	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1697 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.06%) have a different width. You should check the widths of: ['uniFF5D'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* four (U+0034): X=442.0,Y=729.0 (should be at cap-height 730?)

	* four (U+0034): X=499.0,Y=729.0 (should be at cap-height 730?)

	* section (U+00A7): X=463.0,Y=2.0 (should be at baseline 0?)

	* uni0162 (U+0162): X=276.0,Y=1.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=344.0,Y=2.0 (should be at baseline 0?)

	* uni01EA (U+01EA): X=344.0,Y=2.0 (should be at baseline 0?)

	* zeta (U+03B6): X=414.0,Y=2.0 (should be at baseline 0?)

	* uni04A2 (U+04A2): X=441.0,Y=2.0 (should be at baseline 0?)

	* quotesinglbase (U+201A): X=259.0,Y=0.5 (should be at baseline 0?)

	* quotedblbase (U+201E): X=154.0,Y=0.5 (should be at baseline 0?)

	* quotedblbase (U+201E): X=384.0,Y=0.5 (should be at baseline 0?)

	* uni21DE (U+21DE): X=323.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=277.0,Y=-1.0 (should be at baseline 0?)

	* uni21DF (U+21DF): X=277.0,Y=731.0 (should be at cap-height 730?)

	* uni21DF (U+21DF): X=323.0,Y=731.0 (should be at cap-height 730?)

	* uni21E7 (U+21E7): X=301.0,Y=729.0 (should be at cap-height 730?)

	* uni21EA (U+21EA): X=300.0,Y=728.0 (should be at cap-height 730?)

	* uni22BC (U+22BC): X=132.0,Y=732.0 (should be at cap-height 730?)

	* uni22BC (U+22BC): X=612.0,Y=732.0 (should be at cap-height 730?)

	* uni22BD (U+22BD): X=132.0,Y=732.0 (should be at cap-height 730?)

	* uni22BD (U+22BD): X=612.0,Y=732.0 (should be at cap-height 730?)

	* uni27C6 (U+27C6): X=212.0,Y=732.0 (should be at cap-height 730?)

	* uni27C6 (U+27C6): X=261.0,Y=729.0 (should be at cap-height 730?)

	* pitagon (U+E000): X=158.0,Y=2.0 (should be at baseline 0?)

	* piads (U+E001): X=158.0,Y=2.0 (should be at baseline 0?)

	* pioffice (U+E002): X=158.0,Y=2.0 (should be at baseline 0?)

	* pitagram (U+E003): X=158.0,Y=2.0 (should be at baseline 0?)

	* piweb (U+E004): X=158.0,Y=2.0 (should be at baseline 0?)

	* pisign (U+E005): X=158.0,Y=2.0 (should be at baseline 0?)

	* petapp (U+E006): X=534.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=303.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=293.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=318.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=336.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=331.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=328.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=326.0,Y=1.5 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=278.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=274.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=272.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?) 

	* picall (U+E009): X=158.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* perthousand (U+2030): B<<396.0,271.5>-<416.0,253.0>-<413.0,221.0>>/B<<413.0,221.0>-<421.0,253.0>-<447.0,271.5>> = 8.680418425071275

	* perthousand (U+2030): B<<406.0,14.0>-<386.0,33.0>-<389.0,64.0>>/B<<389.0,64.0>-<381.0,33.0>-<354.5,14.0>> = 8.942753948409665

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<364.0,279.0>-<367.0,276.0>-<370.0,274.0>>/L<<370.0,274.0>--<364.0,279.0>> = 6.115503566285384

	* petapp.minimal (U+E007): B<<402.0,326.0>-<402.0,324.0>-<403.0,322.0>>/L<<403.0,322.0>--<402.0,326.0>> = 12.528807709151492

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<403.0,322.0>--<402.0,326.0>>/B<<402.0,326.0>-<402.0,324.0>-<403.0,322.0>> = 14.036243467926484

	* petapp.minimal (U+E007): L<<404.0,317.0>--<403.0,320.0>>/B<<403.0,320.0>-<404.0,318.0>-<404.0,317.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<485.0,44.0>--<486.0,41.0>>/B<<486.0,41.0>-<485.0,43.0>-<485.0,44.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,238.0>--<88.0,326.0>>/B<<88.0,326.0>-<93.0,305.0>-<107.0,292.0>> = 13.392497753751098

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<89.0,577.0>-<98.5,557.0>> = 2.4895529219991284

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni0431 (U+0431): L<<179.0,475.0>--<165.0,386.0>>/B<<165.0,386.0>-<183.0,443.0>-<229.0,474.0>> = 8.586003370571321

	* uni0434 (U+0434): B<<433.0,472.5>-<470.0,440.0>-<469.0,384.0>>/L<<469.0,384.0>--<483.0,475.0>> = 7.723132073887334

	* uni2116 (U+2116): B<<153.0,602.0>-<149.0,643.0>-<147.0,670.0>>/B<<147.0,670.0>-<145.0,651.0>-<140.0,617.0>> = 10.245400756553341

	* uni2116 (U+2116): B<<251.0,120.5>-<255.0,82.0>-<256.0,59.0>>/B<<256.0,59.0>-<258.0,79.0>-<262.5,113.0>> = 8.200146059498772

	* uni227A (U+227A): B<<371.0,370.5>-<293.0,335.0>-<199.0,329.0>>/B<<199.0,329.0>-<291.0,323.0>-<358.0,287.5>> = 7.38361977946671

	* uni227B (U+227B): B<<261.0,289.0>-<339.0,325.0>-<433.0,332.0>>/B<<433.0,332.0>-<341.0,337.0>-<274.0,372.0>> = 7.369686775661075

	* uni227C (U+227C): B<<391.0,495.5>-<313.0,460.0>-<219.0,454.0>>/B<<219.0,454.0>-<311.0,448.0>-<378.0,412.5>> = 7.38361977946671

	* uni22CE (U+22CE): B<<273.5,381.0>-<297.0,309.0>-<288.0,215.0>>/B<<288.0,215.0>-<309.0,309.0>-<356.5,381.0>> = 7.124234985991051

	* uni26A1 (U+26A1): L<<580.0,440.0>--<50.0,-110.0>>/L<<50.0,-110.0>--<295.0,310.0>> = 13.68265114620652

	* w (U+0077): B<<142.0,80.0>-<141.0,56.0>-<139.0,35.0>>/B<<139.0,35.0>-<144.0,56.0>-<152.0,79.5>> = 7.952165722745561

	* w (U+0077): B<<337.5,451.5>-<336.0,485.0>-<337.0,507.0>>/B<<337.0,507.0>-<333.0,485.0>-<321.0,451.5>> = 7.702284266266219

	* w (U+0077): B<<388.0,82.0>-<389.0,58.0>-<387.0,35.0>>/B<<387.0,35.0>-<392.0,57.0>-<397.5,82.0>> = 7.834525337176437

	* wacute (U+1E83): B<<142.0,80.0>-<141.0,56.0>-<139.0,35.0>>/B<<139.0,35.0>-<144.0,56.0>-<152.0,79.5>> = 7.952165722745561

	* wacute (U+1E83): B<<337.5,451.5>-<336.0,485.0>-<337.0,507.0>>/B<<337.0,507.0>-<333.0,485.0>-<321.0,451.5>> = 7.702284266266219

	* wacute (U+1E83): B<<388.0,82.0>-<389.0,58.0>-<387.0,35.0>>/B<<387.0,35.0>-<392.0,57.0>-<397.5,82.0>> = 7.834525337176437

	* wcircumflex (U+0175): B<<142.0,80.0>-<141.0,56.0>-<139.0,35.0>>/B<<139.0,35.0>-<144.0,56.0>-<152.0,79.5>> = 7.952165722745561

	* wcircumflex (U+0175): B<<337.5,451.5>-<336.0,485.0>-<337.0,507.0>>/B<<337.0,507.0>-<333.0,485.0>-<321.0,451.5>> = 7.702284266266219

	* wcircumflex (U+0175): B<<388.0,82.0>-<389.0,58.0>-<387.0,35.0>>/B<<387.0,35.0>-<392.0,57.0>-<397.5,82.0>> = 7.834525337176437

	* wdieresis (U+1E85): B<<142.0,80.0>-<141.0,56.0>-<139.0,35.0>>/B<<139.0,35.0>-<144.0,56.0>-<152.0,79.5>> = 7.952165722745561

	* wdieresis (U+1E85): B<<337.5,451.5>-<336.0,485.0>-<337.0,507.0>>/B<<337.0,507.0>-<333.0,485.0>-<321.0,451.5>> = 7.702284266266219

	* wdieresis (U+1E85): B<<388.0,82.0>-<389.0,58.0>-<387.0,35.0>>/B<<387.0,35.0>-<392.0,57.0>-<397.5,82.0>> = 7.834525337176437

	* wgrave (U+1E81): B<<142.0,80.0>-<141.0,56.0>-<139.0,35.0>>/B<<139.0,35.0>-<144.0,56.0>-<152.0,79.5>> = 7.952165722745561

	* wgrave (U+1E81): B<<337.5,451.5>-<336.0,485.0>-<337.0,507.0>>/B<<337.0,507.0>-<333.0,485.0>-<321.0,451.5>> = 7.702284266266219 

	* wgrave (U+1E81): B<<388.0,82.0>-<389.0,58.0>-<387.0,35.0>>/B<<387.0,35.0>-<392.0,57.0>-<397.5,82.0>> = 7.834525337176437 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[20] PitagonSansMono-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Pitagon Sans Mono Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- uni2070.zero

	- uni2080.zero

	- zero.dnom.zero 

	- zero.numr.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1710 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 2 glyphs (0.11%) have a different width. You should check the widths of: ['periodcentered.loclCAT', 'periodcentered.loclCAT.case'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* g (U+0067): X=511.0,Y=2.0 (should be at baseline 0?)

	* cedilla (U+00B8): X=304.0,Y=2.0 (should be at baseline 0?)

	* Aogonek (U+0104): X=529.0,Y=-2.0 (should be at baseline 0?)

	* aogonek (U+0105): X=500.0,Y=-1.0 (should be at baseline 0?)

	* Eogonek (U+0118): X=472.0,Y=-2.0 (should be at baseline 0?)

	* eogonek (U+0119): X=399.0,Y=-2.0 (should be at baseline 0?)

	* gcircumflex (U+011D): X=511.0,Y=2.0 (should be at baseline 0?)

	* gbreve (U+011F): X=511.0,Y=2.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=511.0,Y=2.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=511.0,Y=2.0 (should be at baseline 0?)

	* Iogonek (U+012E): X=333.0,Y=-2.0 (should be at baseline 0?)

	* iogonek (U+012F): X=349.0,Y=-2.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=399.0,Y=-2.0 (should be at baseline 0?)

	* uogonek (U+0173): X=398.0,Y=-2.0 (should be at baseline 0?)

	* uni019B (U+019B): X=446.0,Y=728.0 (should be at cap-height 730?)

	* uni019B (U+019B): X=463.5,Y=729.0 (should be at cap-height 730?)

	* Ohorn (U+01A0): X=538.0,Y=731.0 (should be at cap-height 730?)

	* gcaron (U+01E7): X=511.0,Y=2.0 (should be at baseline 0?)

	* uni01EA (U+01EA): X=399.0,Y=-2.0 (should be at baseline 0?)

	* uni01EB (U+01EB): X=398.0,Y=-2.0 (should be at baseline 0?)

	* uni01F5 (U+01F5): X=511.0,Y=2.0 (should be at baseline 0?)

	* ogonek (U+02DB): X=333.0,Y=-2.0 (should be at baseline 0?)

	* uni0327 (U+0327): X=-296.0,Y=2.0 (should be at baseline 0?)

	* uni0328 (U+0328): X=-267.0,Y=-2.0 (should be at baseline 0?)

	* uni03CF (U+03CF): X=580.0,Y=-1.0 (should be at baseline 0?)

	* uni03D7 (U+03D7): X=555.0,Y=-1.0 (should be at baseline 0?)

	* uni1EDA (U+1EDA): X=538.0,Y=731.0 (should be at cap-height 730?)

	* uni1EDC (U+1EDC): X=538.0,Y=731.0 (should be at cap-height 730?)

	* uni1EDE (U+1EDE): X=538.0,Y=731.0 (should be at cap-height 730?)

	* uni1EE0 (U+1EE0): X=538.0,Y=731.0 (should be at cap-height 730?)

	* uni1EE2 (U+1EE2): X=538.0,Y=731.0 (should be at cap-height 730?)

	* uni2113 (U+2113): X=338.0,Y=-1.0 (should be at baseline 0?)

	* uni2113 (U+2113): X=338.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=346.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=254.0,Y=-1.0 (should be at baseline 0?)

	* uni21DF (U+21DF): X=254.0,Y=731.0 (should be at cap-height 730?)

	* uni21DF (U+21DF): X=346.0,Y=731.0 (should be at cap-height 730?)

	* uni21E7 (U+21E7): X=301.0,Y=729.0 (should be at cap-height 730?)

	* uni21EA (U+21EA): X=300.0,Y=728.0 (should be at cap-height 730?)

	* uni2272 (U+2272): X=401.0,Y=-1.0 (should be at baseline 0?)

	* uni27C5 (U+27C5): X=382.5,Y=732.0 (should be at cap-height 730?)

	* uni27C6 (U+27C6): X=227.5,Y=732.0 (should be at cap-height 730?)

	* piads (U+E001): X=158.0,Y=2.0 (should be at baseline 0?)

	* pioffice (U+E002): X=158.0,Y=2.0 (should be at baseline 0?)

	* pitagram (U+E003): X=158.0,Y=2.0 (should be at baseline 0?)

	* piweb (U+E004): X=158.0,Y=2.0 (should be at baseline 0?)

	* pisign (U+E005): X=158.0,Y=2.0 (should be at baseline 0?)

	* petapp (U+E006): X=534.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=303.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=293.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=318.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=336.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=331.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=328.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=326.0,Y=1.5 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=278.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=274.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=272.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?) 

	* picall (U+E009): X=158.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): B<<445.5,581.5>-<449.0,646.0>-<453.0,698.0>>/L<<453.0,698.0>--<344.0,342.0>> = 12.624823337370273

	* M (U+004D): L<<250.0,342.0>--<145.0,689.0>>/B<<145.0,689.0>-<154.0,616.0>-<158.0,526.5>> = 9.807086051523703

	* Mu (U+039C): B<<445.5,581.5>-<449.0,646.0>-<453.0,698.0>>/L<<453.0,698.0>--<344.0,342.0>> = 12.624823337370273

	* Mu (U+039C): L<<250.0,342.0>--<145.0,689.0>>/B<<145.0,689.0>-<154.0,616.0>-<158.0,526.5>> = 9.807086051523703

	* N (U+004E): L<<220.0,713.0>--<432.0,114.0>>/B<<432.0,114.0>-<429.0,140.0>-<426.5,178.5>> = 12.908108300416911

	* Nacute (U+0143): L<<220.0,713.0>--<432.0,114.0>>/B<<432.0,114.0>-<429.0,140.0>-<426.5,178.5>> = 12.908108300416911

	* Ncaron (U+0147): L<<220.0,713.0>--<432.0,114.0>>/B<<432.0,114.0>-<429.0,140.0>-<426.5,178.5>> = 12.908108300416911

	* Ntilde (U+00D1): L<<220.0,713.0>--<432.0,114.0>>/B<<432.0,114.0>-<429.0,140.0>-<426.5,178.5>> = 12.908108300416911

	* Nu (U+039D): L<<220.0,713.0>--<432.0,114.0>>/B<<432.0,114.0>-<429.0,140.0>-<426.5,178.5>> = 12.908108300416911

	* W (U+0057): B<<166.5,129.5>-<169.0,93.0>-<170.0,70.0>>/B<<170.0,70.0>-<172.0,93.0>-<175.0,129.5>> = 7.459293650109428

	* W (U+0057): B<<305.5,607.5>-<303.0,642.0>-<302.0,663.0>>/B<<302.0,663.0>-<299.0,642.0>-<297.0,607.5>> = 10.8564133480622

	* W (U+0057): B<<424.0,129.5>-<428.0,93.0>-<431.0,70.0>>/B<<431.0,70.0>-<432.0,93.0>-<435.0,129.5>> = 9.920960893171678

	* Wacute (U+1E82): B<<166.5,129.5>-<169.0,93.0>-<170.0,70.0>>/B<<170.0,70.0>-<172.0,93.0>-<175.0,129.5>> = 7.459293650109428

	* Wacute (U+1E82): B<<305.5,607.5>-<303.0,642.0>-<302.0,663.0>>/B<<302.0,663.0>-<299.0,642.0>-<297.0,607.5>> = 10.8564133480622

	* Wacute (U+1E82): B<<424.0,129.5>-<428.0,93.0>-<431.0,70.0>>/B<<431.0,70.0>-<432.0,93.0>-<435.0,129.5>> = 9.920960893171678

	* Wcircumflex (U+0174): B<<166.5,129.5>-<169.0,93.0>-<170.0,70.0>>/B<<170.0,70.0>-<172.0,93.0>-<175.0,129.5>> = 7.459293650109428

	* Wcircumflex (U+0174): B<<305.5,607.5>-<303.0,642.0>-<302.0,663.0>>/B<<302.0,663.0>-<299.0,642.0>-<297.0,607.5>> = 10.8564133480622

	* Wcircumflex (U+0174): B<<424.0,129.5>-<428.0,93.0>-<431.0,70.0>>/B<<431.0,70.0>-<432.0,93.0>-<435.0,129.5>> = 9.920960893171678

	* Wdieresis (U+1E84): B<<166.5,129.5>-<169.0,93.0>-<170.0,70.0>>/B<<170.0,70.0>-<172.0,93.0>-<175.0,129.5>> = 7.459293650109428

	* Wdieresis (U+1E84): B<<305.5,607.5>-<303.0,642.0>-<302.0,663.0>>/B<<302.0,663.0>-<299.0,642.0>-<297.0,607.5>> = 10.8564133480622

	* Wdieresis (U+1E84): B<<424.0,129.5>-<428.0,93.0>-<431.0,70.0>>/B<<431.0,70.0>-<432.0,93.0>-<435.0,129.5>> = 9.920960893171678

	* Wgrave (U+1E80): B<<166.5,129.5>-<169.0,93.0>-<170.0,70.0>>/B<<170.0,70.0>-<172.0,93.0>-<175.0,129.5>> = 7.459293650109428

	* Wgrave (U+1E80): B<<305.5,607.5>-<303.0,642.0>-<302.0,663.0>>/B<<302.0,663.0>-<299.0,642.0>-<297.0,607.5>> = 10.8564133480622

	* Wgrave (U+1E80): B<<424.0,129.5>-<428.0,93.0>-<431.0,70.0>>/B<<431.0,70.0>-<432.0,93.0>-<435.0,129.5>> = 9.920960893171678

	* arrowboth (U+2194): B<<506.0,247.0>-<532.0,281.0>-<558.0,286.0>>/L<<558.0,286.0>--<42.0,286.0>> = 10.885527054658743

	* arrowboth (U+2194): L<<558.0,286.0>--<42.0,286.0>>/B<<42.0,286.0>-<68.0,281.0>-<94.0,247.0>> = 10.885527054658743

	* arrowleft (U+2190): L<<580.0,286.0>--<135.0,286.0>>/B<<135.0,286.0>-<161.0,281.0>-<187.0,247.0>> = 10.885527054658743

	* arrowright (U+2192): B<<413.0,247.0>-<439.0,281.0>-<465.0,286.0>>/L<<465.0,286.0>--<20.0,286.0>> = 10.885527054658743

	* braceleft (U+007B): B<<358.0,405.0>-<325.0,370.0>-<254.0,363.0>>/B<<254.0,363.0>-<325.0,355.0>-<358.0,317.0>> = 12.059430506465072

	* dollar (U+0024): L<<335.0,308.0>--<334.0,321.0>>/L<<334.0,321.0>--<334.0,80.0>> = 4.398705354995508

	* endOfMediumcontrol (U+2419): B<<506.5,210.5>-<508.0,258.0>-<518.0,297.0>>/L<<518.0,297.0>--<443.0,112.0>> = 7.686504971319614

	* endOfMediumcontrol (U+2419): L<<359.0,112.0>--<281.0,294.0>>/B<<281.0,294.0>-<286.0,268.0>-<289.0,242.0>> = 12.313063458989452

	* eogonek (U+0119): B<<248.0,-111.0>-<248.0,-60.0>-<315.0,-6.0>>/B<<315.0,-6.0>-<309.0,-10.0>-<300.0,-10.0>> = 5.177709976340867

	* perthousand (U+2030): B<<405.5,271.5>-<429.0,253.0>-<431.0,221.0>>/B<<431.0,221.0>-<435.0,253.0>-<458.5,271.5>> = 10.701350723899111

	* perthousand (U+2030): B<<457.5,13.5>-<434.0,32.0>-<432.0,64.0>>/B<<432.0,64.0>-<428.0,32.0>-<404.5,13.5>> = 10.701350723899111

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<365.0,279.0>-<368.0,276.0>-<370.0,275.0>>/L<<370.0,275.0>--<365.0,279.0>> = 12.094757077012058

	* petapp.minimal (U+E007): B<<402.0,358.0>-<402.0,357.0>-<401.0,355.0>>/L<<401.0,355.0>--<402.0,358.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>>/L<<437.0,404.0>--<440.0,406.0>> = 7.125016348901757

	* petapp.minimal (U+E007): B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>>/L<<442.0,407.0>--<447.0,409.0>> = 4.763641690726143

	* petapp.minimal (U+E007): B<<468.0,415.0>-<467.0,415.0>-<465.0,414.0>>/L<<465.0,414.0>--<468.0,415.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>>/L<<467.0,106.0>--<469.0,103.0>> = 11.309932474020195

	* petapp.minimal (U+E007): B<<484.5,8.5>-<484.0,4.0>-<483.0,0.0>>/B<<483.0,0.0>-<483.0,3.0>-<483.0,6.5>> = 14.036243467926484

	* petapp.minimal (U+E007): L<<408.0,166.0>--<411.0,165.0>>/B<<411.0,165.0>-<409.0,166.0>-<408.0,166.5>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<413.0,298.0>--<412.0,301.0>>/B<<412.0,301.0>-<413.0,299.0>-<413.0,298.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<417.0,160.0>--<420.0,159.0>>/B<<420.0,159.0>-<418.0,160.0>-<417.0,160.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<437.0,404.0>--<440.0,406.0>>/B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>> = 11.309932474020227

	* petapp.minimal (U+E007): L<<442.0,407.0>--<447.0,409.0>>/B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>> = 3.3664606634297236

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<467.0,106.0>--<469.0,103.0>>/B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>> = 7.125016348901757

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<90.0,577.0>-<99.0,557.0>> = 4.969740728110289

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* trademark (U+2122): B<<369.5,653.5>-<362.0,679.0>-<357.0,699.0>>/B<<357.0,699.0>-<359.0,678.0>-<362.5,644.0>> = 8.595911436920954

	* trademark (U+2122): B<<511.5,643.5>-<514.0,678.0>-<517.0,700.0>>/B<<517.0,700.0>-<511.0,680.0>-<504.0,653.5>> = 8.934078215568242

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni0145 (U+0145): L<<220.0,713.0>--<432.0,114.0>>/B<<432.0,114.0>-<429.0,140.0>-<426.5,178.5>> = 12.908108300416911

	* uni01EB (U+01EB): B<<262.0,-61.5>-<277.0,-36.0>-<315.0,-5.0>>/B<<315.0,-5.0>-<308.0,-10.0>-<300.0,-10.0>> = 3.6695257129933005

	* uni03D7 (U+03D7): B<<179.5,171.0>-<178.0,124.0>-<169.0,93.0>>/L<<169.0,93.0>--<390.0,550.0>> = 9.618676054992475

	* uni03D7 (U+03D7): B<<420.5,379.5>-<422.0,426.0>-<430.0,456.0>>/L<<430.0,456.0>--<210.0,0.0>> = 10.823853582029543

	* uni0418 (U+0418): B<<426.5,551.5>-<429.0,590.0>-<432.0,616.0>>/L<<432.0,616.0>--<214.0,0.0>> = 12.906728344263213

	* uni0419 (U+0419): B<<426.5,551.5>-<429.0,590.0>-<432.0,616.0>>/L<<432.0,616.0>--<214.0,0.0>> = 12.906728344263213

	* uni041C (U+041C): B<<445.5,581.5>-<449.0,646.0>-<453.0,698.0>>/L<<453.0,698.0>--<344.0,342.0>> = 12.624823337370273

	* uni041C (U+041C): L<<250.0,342.0>--<145.0,689.0>>/B<<145.0,689.0>-<154.0,616.0>-<158.0,526.5>> = 9.807086051523703

	* uni0431 (U+0431): L<<165.0,458.0>--<165.0,411.0>>/B<<165.0,411.0>-<177.0,460.0>-<217.5,488.0>> = 13.760785111791225

	* uni0438 (U+0438): B<<179.5,171.0>-<178.0,124.0>-<169.0,93.0>>/L<<169.0,93.0>--<390.0,550.0>> = 9.618676054992475

	* uni0438 (U+0438): B<<420.5,379.5>-<422.0,426.0>-<430.0,456.0>>/L<<430.0,456.0>--<210.0,0.0>> = 10.823853582029543

	* uni0439 (U+0439): B<<179.5,171.0>-<178.0,124.0>-<169.0,93.0>>/L<<169.0,93.0>--<390.0,550.0>> = 9.618676054992475

	* uni0439 (U+0439): B<<420.5,379.5>-<422.0,426.0>-<430.0,456.0>>/L<<430.0,456.0>--<210.0,0.0>> = 10.823853582029543

	* uni043C (U+043C): B<<440.5,325.5>-<442.0,433.0>-<452.0,502.0>>/L<<452.0,502.0>--<341.0,211.0>> = 12.632696066088867

	* uni043C (U+043C): L<<254.0,211.0>--<148.0,486.0>>/B<<148.0,486.0>-<158.0,424.0>-<159.5,325.0>> = 11.91703664911254

	* uni04E4 (U+04E4): B<<426.5,551.5>-<429.0,590.0>-<432.0,616.0>>/L<<432.0,616.0>--<214.0,0.0>> = 12.906728344263213

	* uni04E5 (U+04E5): B<<179.5,171.0>-<178.0,124.0>-<169.0,93.0>>/L<<169.0,93.0>--<390.0,550.0>> = 9.618676054992475

	* uni04E5 (U+04E5): B<<420.5,379.5>-<422.0,426.0>-<430.0,456.0>>/L<<430.0,456.0>--<210.0,0.0>> = 10.823853582029543

	* uni2116 (U+2116): B<<106.0,577.5>-<97.0,615.0>-<91.0,644.0>>/B<<91.0,644.0>-<94.0,609.0>-<97.5,563.5>> = 6.7902767216514475

	* uni2116 (U+2116): B<<272.5,155.5>-<281.0,117.0>-<288.0,87.0>>/B<<288.0,87.0>-<284.0,123.0>-<280.0,169.0>> = 6.793830560486441

	* uni2196 (U+2196): B<<229.0,645.5>-<211.0,647.0>-<201.0,653.0>>/L<<201.0,653.0>--<557.0,297.0>> = 14.036243467926484

	* uni2197 (U+2197): L<<43.0,297.0>--<400.0,653.0>>/B<<400.0,653.0>-<390.0,647.0>-<372.0,645.5>> = 13.95588478357194

	* uni2198 (U+2198): B<<372.0,84.5>-<390.0,83.0>-<400.0,77.0>>/L<<400.0,77.0>--<43.0,433.0>> = 13.95588478357194

	* uni2199 (U+2199): L<<557.0,433.0>--<200.0,77.0>>/B<<200.0,77.0>-<210.0,83.0>-<228.0,84.5>> = 13.95588478357194

	* uni227A (U+227A): B<<353.5,374.5>-<281.0,341.0>-<186.0,335.0>>/B<<186.0,335.0>-<281.0,329.0>-<353.5,292.5>> = 7.227761504007194

	* uni227B (U+227B): B<<246.5,292.5>-<319.0,329.0>-<414.0,335.0>>/B<<414.0,335.0>-<319.0,341.0>-<246.5,374.5>> = 7.227761504007194

	* uni227C (U+227C): B<<353.5,499.5>-<281.0,466.0>-<186.0,460.0>>/B<<186.0,460.0>-<281.0,454.0>-<353.5,417.5>> = 7.227761504007194

	* uni22CE (U+22CE): B<<257.0,385.5>-<292.0,313.0>-<297.0,218.0>>/B<<297.0,218.0>-<304.0,313.0>-<339.5,385.5>> = 7.226966026917322

	* uni234B (U+234B): L<<276.0,88.0>--<276.0,536.0>>/L<<276.0,536.0>--<168.0,88.0>> = 13.55376409773164

	* uni234B (U+234B): L<<432.0,88.0>--<323.0,535.0>>/L<<323.0,535.0>--<323.0,88.0>> = 13.704010199142768

	* uni2352 (U+2352): L<<169.0,643.0>--<280.0,191.0>>/L<<280.0,191.0>--<277.0,643.0>> = 13.417111893872454

	* uni2352 (U+2352): L<<324.0,643.0>--<324.0,191.0>>/L<<324.0,191.0>--<432.0,643.0>> = 13.438188158350638

	* uni236C (U+236C): L<<183.0,529.0>--<183.0,388.0>>/B<<183.0,388.0>-<197.0,457.0>-<247.0,457.0>> = 11.469530332866904

	* uni236C (U+236C): L<<417.0,202.0>--<417.0,356.0>>/B<<417.0,356.0>-<403.0,287.0>-<353.0,287.0>> = 11.469530332866904

	* uni26A1 (U+26A1): L<<580.0,440.0>--<50.0,-110.0>>/L<<50.0,-110.0>--<295.0,310.0>> = 13.68265114620652

	* uniFF5B (U+FF5B): B<<358.0,405.0>-<325.0,370.0>-<254.0,363.0>>/B<<254.0,363.0>-<325.0,355.0>-<358.0,317.0>> = 12.059430506465072

	* uogonek (U+0173): B<<262.0,-61.5>-<277.0,-36.0>-<315.0,-5.0>>/B<<315.0,-5.0>-<308.0,-10.0>-<300.0,-10.0>> = 3.6695257129933005

	* w (U+0077): B<<171.0,121.0>-<174.0,92.0>-<175.0,74.0>>/B<<175.0,74.0>-<177.0,92.0>-<180.0,121.0>> = 9.520021865774117

	* w (U+0077): B<<305.5,430.0>-<302.0,463.0>-<300.0,482.0>>/B<<300.0,482.0>-<299.0,463.0>-<294.5,430.0>> = 9.021793461677795

	* w (U+0077): B<<420.5,121.5>-<424.0,93.0>-<426.0,74.0>>/B<<426.0,74.0>-<428.0,93.0>-<431.0,121.5>> = 12.018011914988996

	* wacute (U+1E83): B<<171.0,121.0>-<174.0,92.0>-<175.0,74.0>>/B<<175.0,74.0>-<177.0,92.0>-<180.0,121.0>> = 9.520021865774117

	* wacute (U+1E83): B<<305.5,430.0>-<302.0,463.0>-<300.0,482.0>>/B<<300.0,482.0>-<299.0,463.0>-<294.5,430.0>> = 9.021793461677795

	* wacute (U+1E83): B<<420.5,121.5>-<424.0,93.0>-<426.0,74.0>>/B<<426.0,74.0>-<428.0,93.0>-<431.0,121.5>> = 12.018011914988996

	* wcircumflex (U+0175): B<<171.0,121.0>-<174.0,92.0>-<175.0,74.0>>/B<<175.0,74.0>-<177.0,92.0>-<180.0,121.0>> = 9.520021865774117

	* wcircumflex (U+0175): B<<305.5,430.0>-<302.0,463.0>-<300.0,482.0>>/B<<300.0,482.0>-<299.0,463.0>-<294.5,430.0>> = 9.021793461677795

	* wcircumflex (U+0175): B<<420.5,121.5>-<424.0,93.0>-<426.0,74.0>>/B<<426.0,74.0>-<428.0,93.0>-<431.0,121.5>> = 12.018011914988996

	* wdieresis (U+1E85): B<<171.0,121.0>-<174.0,92.0>-<175.0,74.0>>/B<<175.0,74.0>-<177.0,92.0>-<180.0,121.0>> = 9.520021865774117

	* wdieresis (U+1E85): B<<305.5,430.0>-<302.0,463.0>-<300.0,482.0>>/B<<300.0,482.0>-<299.0,463.0>-<294.5,430.0>> = 9.021793461677795

	* wdieresis (U+1E85): B<<420.5,121.5>-<424.0,93.0>-<426.0,74.0>>/B<<426.0,74.0>-<428.0,93.0>-<431.0,121.5>> = 12.018011914988996

	* wgrave (U+1E81): B<<171.0,121.0>-<174.0,92.0>-<175.0,74.0>>/B<<175.0,74.0>-<177.0,92.0>-<180.0,121.0>> = 9.520021865774117

	* wgrave (U+1E81): B<<305.5,430.0>-<302.0,463.0>-<300.0,482.0>>/B<<300.0,482.0>-<299.0,463.0>-<294.5,430.0>> = 9.021793461677795 

	* wgrave (U+1E81): B<<420.5,121.5>-<424.0,93.0>-<426.0,74.0>>/B<<426.0,74.0>-<428.0,93.0>-<431.0,121.5>> = 12.018011914988996 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* phi (U+03C6): L<<142.0,355.0>--<141.0,203.0>>

	* question (U+003F): L<<202.0,218.0>--<201.0,393.0>>

	* uni0416 (U+0416): L<<261.0,0.0>--<260.0,340.0>>

	* uni0428 (U+0428): L<<58.0,0.0>--<57.0,730.0>>

	* uni0448 (U+0448): L<<58.0,0.0>--<57.0,550.0>>

	* uni04DC (U+04DC): L<<261.0,0.0>--<260.0,340.0>>

	* uni2352 (U+2352): L<<280.0,191.0>--<277.0,643.0>> 

	* uni23A8 (U+23A8): L<<350.0,1020.0>--<349.0,497.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] PitagonSansMono-MediumItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Pitagon Sans Mono Medium' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, exclam_equal_equal.liga.ss19.001, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- dollar.cv14

	- eight.dnom

	- eight.numr

	- exclam_equal.liga.ss19.001

	- exclam_equal_equal.liga.ss19.001

	- five.dnom

	- five.numr

	- four.dnom

	- four.numr

	- nine.dnom

	- nine.numr

	- one.dnom

	- one.numr

	- seven.dnom

	- seven.numr

	- six.dnom

	- six.numr

	- three.dnom

	- three.numr

	- two.dnom

	- two.numr

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- zero.dnom 

	- zero.numr
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1697 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 2 glyphs (0.11%) have a different width. You should check the widths of: ['periodcentered.loclCAT', 'periodcentered.loclCAT.case'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* g (U+0067): X=467.0,Y=2.0 (should be at baseline 0?)

	* macron (U+00AF): X=208.0,Y=729.0 (should be at cap-height 730?)

	* amacron (U+0101): X=213.0,Y=729.0 (should be at cap-height 730?)

	* Aogonek (U+0104): X=484.0,Y=-2.0 (should be at baseline 0?)

	* emacron (U+0113): X=208.0,Y=729.0 (should be at cap-height 730?)

	* Eogonek (U+0118): X=427.0,Y=-2.0 (should be at baseline 0?)

	* eogonek (U+0119): X=355.0,Y=-2.0 (should be at baseline 0?)

	* gcircumflex (U+011D): X=467.0,Y=2.0 (should be at baseline 0?)

	* gbreve (U+011F): X=467.0,Y=2.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=467.0,Y=2.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=467.0,Y=2.0 (should be at baseline 0?)

	* imacron (U+012B): X=224.0,Y=729.0 (should be at cap-height 730?)

	* Iogonek (U+012E): X=289.0,Y=-2.0 (should be at baseline 0?)

	* iogonek (U+012F): X=305.0,Y=-2.0 (should be at baseline 0?)

	* omacron (U+014D): X=208.0,Y=729.0 (should be at cap-height 730?)

	* uni0162 (U+0162): X=295.0,Y=2.0 (should be at baseline 0?)

	* umacron (U+016B): X=208.0,Y=729.0 (should be at cap-height 730?)

	* Uogonek (U+0172): X=354.0,Y=-2.0 (should be at baseline 0?)

	* uogonek (U+0173): X=354.0,Y=-2.0 (should be at baseline 0?)

	* Ohorn (U+01A0): X=610.0,Y=731.0 (should be at cap-height 730?)

	* gcaron (U+01E7): X=467.0,Y=2.0 (should be at baseline 0?)

	* uni01EA (U+01EA): X=354.0,Y=-2.0 (should be at baseline 0?)

	* uni01EB (U+01EB): X=354.0,Y=-2.0 (should be at baseline 0?)

	* uni01F5 (U+01F5): X=467.0,Y=2.0 (should be at baseline 0?)

	* uni0233 (U+0233): X=208.0,Y=729.0 (should be at cap-height 730?)

	* uni02C9 (U+02C9): X=208.0,Y=729.0 (should be at cap-height 730?)

	* ogonek (U+02DB): X=289.0,Y=-2.0 (should be at baseline 0?)

	* uni0304 (U+0304): X=-392.0,Y=729.0 (should be at cap-height 730?)

	* uni0328 (U+0328): X=-311.0,Y=-2.0 (should be at baseline 0?)

	* uni03CF (U+03CF): X=536.0,Y=-1.0 (should be at baseline 0?)

	* uni03D7 (U+03D7): X=418.0,Y=-2.0 (should be at baseline 0?)

	* uni03D7 (U+03D7): X=510.0,Y=-1.0 (should be at baseline 0?)

	* uni1EDA (U+1EDA): X=610.0,Y=731.0 (should be at cap-height 730?)

	* uni1EDC (U+1EDC): X=610.0,Y=731.0 (should be at cap-height 730?)

	* uni1EDE (U+1EDE): X=610.0,Y=731.0 (should be at cap-height 730?)

	* uni1EE0 (U+1EE0): X=610.0,Y=731.0 (should be at cap-height 730?)

	* uni1EE2 (U+1EE2): X=610.0,Y=731.0 (should be at cap-height 730?)

	* uni2113 (U+2113): X=294.0,Y=-1.0 (should be at baseline 0?)

	* uni2113 (U+2113): X=294.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=346.0,Y=-1.0 (should be at baseline 0?)

	* uni21DE (U+21DE): X=254.0,Y=-1.0 (should be at baseline 0?)

	* uni21DF (U+21DF): X=254.0,Y=731.0 (should be at cap-height 730?)

	* uni21DF (U+21DF): X=346.0,Y=731.0 (should be at cap-height 730?)

	* uni21E7 (U+21E7): X=301.0,Y=729.0 (should be at cap-height 730?)

	* uni21EA (U+21EA): X=300.0,Y=728.0 (should be at cap-height 730?)

	* uni2272 (U+2272): X=358.0,Y=-1.0 (should be at baseline 0?)

	* uni27C5 (U+27C5): X=454.0,Y=732.0 (should be at cap-height 730?)

	* uni27C6 (U+27C6): X=300.0,Y=732.0 (should be at cap-height 730?)

	* piads (U+E001): X=158.0,Y=2.0 (should be at baseline 0?)

	* pioffice (U+E002): X=158.0,Y=2.0 (should be at baseline 0?)

	* pitagram (U+E003): X=158.0,Y=2.0 (should be at baseline 0?)

	* piweb (U+E004): X=158.0,Y=2.0 (should be at baseline 0?)

	* pisign (U+E005): X=158.0,Y=2.0 (should be at baseline 0?)

	* petapp (U+E006): X=534.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=303.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=293.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=318.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=336.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=331.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=328.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=326.0,Y=1.5 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=323.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=278.0,Y=1.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=274.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=272.0,Y=2.0 (should be at baseline 0?)

	* petapp.wpda (U+E008): X=266.0,Y=2.0 (should be at baseline 0?) 

	* picall (U+E009): X=158.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): B<<493.5,581.5>-<507.0,646.0>-<520.0,698.0>>/L<<520.0,698.0>--<354.0,340.0>> = 10.840305454330533

	* M (U+004D): L<<260.0,343.0>--<211.0,689.0>>/B<<211.0,689.0>-<204.0,541.0>-<171.0,335.0>> = 10.768458021290737

	* Mu (U+039C): B<<493.5,581.5>-<507.0,646.0>-<520.0,698.0>>/L<<520.0,698.0>--<354.0,340.0>> = 10.840305454330533

	* Mu (U+039C): L<<260.0,343.0>--<211.0,689.0>>/B<<211.0,689.0>-<204.0,541.0>-<171.0,335.0>> = 10.768458021290737

	* W (U+0057): B<<140.5,129.5>-<137.0,93.0>-<134.0,70.0>>/B<<134.0,70.0>-<140.0,93.0>-<149.0,129.5>> = 7.1894660174590985

	* W (U+0057): B<<358.0,607.5>-<361.0,642.0>-<363.0,663.0>>/B<<363.0,663.0>-<357.0,642.0>-<349.5,607.5>> = 10.505063869917334

	* W (U+0057): B<<397.5,129.5>-<396.0,93.0>-<395.0,70.0>>/B<<395.0,70.0>-<400.0,93.0>-<408.5,129.5>> = 9.775220805893223

	* Wacute (U+1E82): B<<140.5,129.5>-<137.0,93.0>-<134.0,70.0>>/B<<134.0,70.0>-<140.0,93.0>-<149.0,129.5>> = 7.1894660174590985

	* Wacute (U+1E82): B<<358.0,607.5>-<361.0,642.0>-<363.0,663.0>>/B<<363.0,663.0>-<357.0,642.0>-<349.5,607.5>> = 10.505063869917334

	* Wacute (U+1E82): B<<397.5,129.5>-<396.0,93.0>-<395.0,70.0>>/B<<395.0,70.0>-<400.0,93.0>-<408.5,129.5>> = 9.775220805893223

	* Wcircumflex (U+0174): B<<140.5,129.5>-<137.0,93.0>-<134.0,70.0>>/B<<134.0,70.0>-<140.0,93.0>-<149.0,129.5>> = 7.1894660174590985

	* Wcircumflex (U+0174): B<<358.0,607.5>-<361.0,642.0>-<363.0,663.0>>/B<<363.0,663.0>-<357.0,642.0>-<349.5,607.5>> = 10.505063869917334

	* Wcircumflex (U+0174): B<<397.5,129.5>-<396.0,93.0>-<395.0,70.0>>/B<<395.0,70.0>-<400.0,93.0>-<408.5,129.5>> = 9.775220805893223

	* Wdieresis (U+1E84): B<<140.5,129.5>-<137.0,93.0>-<134.0,70.0>>/B<<134.0,70.0>-<140.0,93.0>-<149.0,129.5>> = 7.1894660174590985

	* Wdieresis (U+1E84): B<<358.0,607.5>-<361.0,642.0>-<363.0,663.0>>/B<<363.0,663.0>-<357.0,642.0>-<349.5,607.5>> = 10.505063869917334

	* Wdieresis (U+1E84): B<<397.5,129.5>-<396.0,93.0>-<395.0,70.0>>/B<<395.0,70.0>-<400.0,93.0>-<408.5,129.5>> = 9.775220805893223

	* Wgrave (U+1E80): B<<140.5,129.5>-<137.0,93.0>-<134.0,70.0>>/B<<134.0,70.0>-<140.0,93.0>-<149.0,129.5>> = 7.1894660174590985

	* Wgrave (U+1E80): B<<358.0,607.5>-<361.0,642.0>-<363.0,663.0>>/B<<363.0,663.0>-<357.0,642.0>-<349.5,607.5>> = 10.505063869917334

	* Wgrave (U+1E80): B<<397.5,129.5>-<396.0,93.0>-<395.0,70.0>>/B<<395.0,70.0>-<400.0,93.0>-<408.5,129.5>> = 9.775220805893223

	* a (U+0061): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* aacute (U+00E1): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* abreve (U+0103): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* acircumflex (U+00E2): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* adieresis (U+00E4): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* agrave (U+00E0): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* alpha (U+03B1): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* alphatonos (U+03AC): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* amacron (U+0101): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* aogonek (U+0105): B<<385.5,51.0>-<372.0,79.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 8.972626614896358

	* aring (U+00E5): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* arrowboth (U+2194): B<<506.0,247.0>-<532.0,281.0>-<558.0,286.0>>/L<<558.0,286.0>--<42.0,286.0>> = 10.885527054658743

	* arrowboth (U+2194): L<<558.0,286.0>--<42.0,286.0>>/B<<42.0,286.0>-<68.0,281.0>-<94.0,247.0>> = 10.885527054658743

	* arrowleft (U+2190): L<<580.0,286.0>--<135.0,286.0>>/B<<135.0,286.0>-<161.0,281.0>-<187.0,247.0>> = 10.885527054658743

	* arrowright (U+2192): B<<413.0,247.0>-<439.0,281.0>-<465.0,286.0>>/L<<465.0,286.0>--<20.0,286.0>> = 10.885527054658743

	* atilde (U+00E3): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* b (U+0062): B<<194.5,20.5>-<160.0,51.0>-<159.0,106.0>>/L<<159.0,106.0>--<142.0,0.0>> = 10.152983720793959

	* braceleft (U+007B): B<<378.0,405.0>-<340.0,370.0>-<267.0,363.0>>/B<<267.0,363.0>-<337.0,355.0>-<364.0,317.0>> = 11.997170480485789

	* dcaron (U+010F): L<<314.0,0.0>--<330.0,100.0>>/B<<330.0,100.0>-<315.0,48.0>-<276.0,19.0>> = 7.000539428029851

	* dollar (U+0024): L<<340.0,308.0>--<341.0,321.0>>/L<<341.0,321.0>--<302.0,79.0>> = 4.75619778021684

	* endOfMediumcontrol (U+2419): B<<531.0,210.5>-<540.0,258.0>-<556.0,297.0>>/L<<556.0,297.0>--<442.0,96.0>> = 7.254149409773001

	* endOfMediumcontrol (U+2419): L<<372.0,96.0>--<318.0,294.0>>/B<<318.0,294.0>-<319.0,268.0>-<318.5,242.0>> = 13.052520541291988

	* eogonek (U+0119): B<<187.0,-111.0>-<193.0,-61.0>-<270.0,-6.0>>/B<<270.0,-6.0>-<263.0,-10.0>-<254.0,-10.0>> = 5.792796495032087

	* perthousand (U+2030): B<<394.5,271.5>-<415.0,253.0>-<413.0,221.0>>/B<<413.0,221.0>-<421.0,253.0>-<447.5,271.5>> = 10.459909092929111

	* perthousand (U+2030): B<<406.5,13.5>-<386.0,32.0>-<388.0,64.0>>/B<<388.0,64.0>-<380.0,32.0>-<353.0,13.5>> = 10.459909092929111

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<365.0,279.0>-<368.0,276.0>-<370.0,275.0>>/L<<370.0,275.0>--<365.0,279.0>> = 12.094757077012058

	* petapp.minimal (U+E007): B<<402.0,358.0>-<402.0,357.0>-<401.0,355.0>>/L<<401.0,355.0>--<402.0,358.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>>/L<<437.0,404.0>--<440.0,406.0>> = 7.125016348901757

	* petapp.minimal (U+E007): B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>>/L<<442.0,407.0>--<447.0,409.0>> = 4.763641690726143

	* petapp.minimal (U+E007): B<<468.0,415.0>-<467.0,415.0>-<465.0,414.0>>/L<<465.0,414.0>--<468.0,415.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>>/L<<467.0,106.0>--<469.0,103.0>> = 11.309932474020195

	* petapp.minimal (U+E007): B<<484.5,8.5>-<484.0,4.0>-<483.0,0.0>>/B<<483.0,0.0>-<483.0,3.0>-<483.0,6.5>> = 14.036243467926484

	* petapp.minimal (U+E007): L<<408.0,166.0>--<411.0,165.0>>/B<<411.0,165.0>-<409.0,166.0>-<408.0,166.5>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<413.0,298.0>--<412.0,301.0>>/B<<412.0,301.0>-<413.0,299.0>-<413.0,298.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<417.0,160.0>--<420.0,159.0>>/B<<420.0,159.0>-<418.0,160.0>-<417.0,160.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<437.0,404.0>--<440.0,406.0>>/B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>> = 11.309932474020227

	* petapp.minimal (U+E007): L<<442.0,407.0>--<447.0,409.0>>/B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>> = 3.3664606634297236

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<467.0,106.0>--<469.0,103.0>>/B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>> = 7.125016348901757

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<90.0,577.0>-<99.0,557.0>> = 4.969740728110289

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* q (U+0071): B<<403.5,528.5>-<439.0,497.0>-<440.0,444.0>>/L<<440.0,444.0>--<457.0,550.0>> = 10.192281231444655

	* thorn (U+00FE): B<<190.5,20.5>-<156.0,51.0>-<155.0,106.0>>/L<<155.0,106.0>--<138.0,0.0>> = 10.152983720793959

	* trademark (U+2122): B<<429.0,653.5>-<426.0,679.0>-<424.0,699.0>>/B<<424.0,699.0>-<423.0,678.0>-<420.5,644.0>> = 8.436904131405898

	* trademark (U+2122): B<<569.0,643.5>-<577.0,678.0>-<584.0,700.0>>/B<<584.0,700.0>-<575.0,680.0>-<563.5,653.5>> = 6.57762109802406

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni01CE (U+01CE): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni01EB (U+01EB): B<<208.5,-61.5>-<228.0,-36.0>-<272.0,-4.0>>/B<<272.0,-4.0>-<266.0,-10.0>-<254.0,-10.0>> = 8.972626614896358

	* uni0418 (U+0418): B<<158.0,177.5>-<150.0,140.0>-<144.0,114.0>>/L<<144.0,114.0>--<458.0,730.0>> = 14.015153367570079

	* uni0418 (U+0418): B<<470.0,551.5>-<479.0,590.0>-<485.0,616.0>>/L<<485.0,616.0>--<170.0,0.0>> = 14.088934072452139

	* uni0419 (U+0419): B<<158.0,177.5>-<150.0,140.0>-<144.0,114.0>>/L<<144.0,114.0>--<458.0,730.0>> = 14.015153367570079

	* uni0419 (U+0419): B<<470.0,551.5>-<479.0,590.0>-<485.0,616.0>>/L<<485.0,616.0>--<170.0,0.0>> = 14.088934072452139

	* uni041C (U+041C): B<<493.5,581.5>-<507.0,646.0>-<520.0,698.0>>/L<<520.0,698.0>--<354.0,340.0>> = 10.840305454330533

	* uni041C (U+041C): L<<260.0,343.0>--<211.0,689.0>>/B<<211.0,689.0>-<204.0,541.0>-<171.0,335.0>> = 10.768458021290737

	* uni0430 (U+0430): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni0431 (U+0431): L<<194.0,458.0>--<187.0,415.0>>/B<<187.0,415.0>-<207.0,464.0>-<251.0,490.0>> = 12.957365786494123

	* uni0434 (U+0434): B<<417.0,487.5>-<453.0,459.0>-<456.0,408.0>>/L<<456.0,408.0>--<464.0,458.0>> = 12.456737584252124

	* uni043C (U+043C): B<<459.0,385.5>-<469.0,433.0>-<476.0,469.0>>/L<<476.0,469.0>--<333.0,164.0>> = 14.116106783607867

	* uni04E4 (U+04E4): B<<158.0,177.5>-<150.0,140.0>-<144.0,114.0>>/L<<144.0,114.0>--<458.0,730.0>> = 14.015153367570079

	* uni04E4 (U+04E4): B<<470.0,551.5>-<479.0,590.0>-<485.0,616.0>>/L<<485.0,616.0>--<170.0,0.0>> = 14.088934072452139

	* uni1EA1 (U+1EA1): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni1EA3 (U+1EA3): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni1EA5 (U+1EA5): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni1EA7 (U+1EA7): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni1EA9 (U+1EA9): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni1EAB (U+1EAB): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni1EAD (U+1EAD): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni1EAF (U+1EAF): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni1EB1 (U+1EB1): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni1EB3 (U+1EB3): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni1EB5 (U+1EB5): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni1EB7 (U+1EB7): B<<397.5,32.5>-<370.0,65.0>-<378.0,115.0>>/B<<378.0,115.0>-<359.0,58.0>-<311.5,24.0>> = 9.344671902099657

	* uni2116 (U+2116): B<<153.0,577.5>-<150.0,615.0>-<149.0,644.0>>/B<<149.0,644.0>-<146.0,609.0>-<142.5,563.5>> = 6.874026464669735

	* uni2116 (U+2116): B<<253.5,155.5>-<256.0,117.0>-<258.0,87.0>>/B<<258.0,87.0>-<260.0,123.0>-<263.5,169.0>> = 6.993904954154567

	* uni2196 (U+2196): B<<229.0,645.5>-<211.0,647.0>-<201.0,653.0>>/L<<201.0,653.0>--<557.0,297.0>> = 14.036243467926484

	* uni2197 (U+2197): L<<43.0,297.0>--<400.0,653.0>>/B<<400.0,653.0>-<390.0,647.0>-<372.0,645.5>> = 13.95588478357194

	* uni2198 (U+2198): B<<372.0,84.5>-<390.0,83.0>-<400.0,77.0>>/L<<400.0,77.0>--<43.0,433.0>> = 13.95588478357194

	* uni2199 (U+2199): L<<557.0,433.0>--<200.0,77.0>>/B<<200.0,77.0>-<210.0,83.0>-<228.0,84.5>> = 13.95588478357194

	* uni227A (U+227A): B<<379.5,369.0>-<302.0,333.0>-<206.0,327.0>>/B<<206.0,327.0>-<347.0,318.0>-<425.5,246.5>> = 7.22855715530358

	* uni227B (U+227B): B<<249.0,292.5>-<327.0,329.0>-<423.0,335.0>>/B<<423.0,335.0>-<329.0,341.0>-<262.0,374.5>> = 7.22855715530358

	* uni227C (U+227C): B<<401.5,494.0>-<324.0,458.0>-<228.0,452.0>>/B<<228.0,452.0>-<368.0,443.0>-<446.5,371.5>> = 7.254573096990706

	* uni22CE (U+22CE): B<<274.0,385.5>-<297.0,313.0>-<288.0,218.0>>/B<<288.0,218.0>-<309.0,313.0>-<356.5,385.5>> = 7.053063689747983

	* uni234B (U+234B): L<<276.0,88.0>--<276.0,536.0>>/L<<276.0,536.0>--<168.0,88.0>> = 13.55376409773164

	* uni234B (U+234B): L<<432.0,88.0>--<323.0,535.0>>/L<<323.0,535.0>--<323.0,88.0>> = 13.704010199142768

	* uni2352 (U+2352): L<<169.0,643.0>--<280.0,191.0>>/L<<280.0,191.0>--<277.0,643.0>> = 13.417111893872454

	* uni2352 (U+2352): L<<324.0,643.0>--<324.0,191.0>>/L<<324.0,191.0>--<432.0,643.0>> = 13.438188158350638

	* uni236C (U+236C): L<<223.0,529.0>--<201.0,389.0>>/B<<201.0,389.0>-<226.0,457.0>-<275.0,457.0>> = 11.255212909045852

	* uni236C (U+236C): L<<405.0,202.0>--<430.0,358.0>>/B<<430.0,358.0>-<405.0,287.0>-<354.0,287.0>> = 10.293211583155978

	* uni2375 (U+2375): B<<297.0,19.0>-<270.0,48.0>-<272.0,99.0>>/B<<272.0,99.0>-<257.0,48.0>-<220.5,19.0>> = 14.14379776813967

	* uni2379 (U+2379): B<<297.0,19.0>-<270.0,48.0>-<272.0,99.0>>/B<<272.0,99.0>-<257.0,48.0>-<220.5,19.0>> = 14.14379776813967

	* uni26A1 (U+26A1): L<<580.0,440.0>--<50.0,-110.0>>/L<<50.0,-110.0>--<295.0,310.0>> = 13.68265114620652

	* uniFF5B (U+FF5B): B<<378.0,405.0>-<340.0,370.0>-<267.0,363.0>>/B<<267.0,363.0>-<337.0,355.0>-<364.0,317.0>> = 11.997170480485789

	* uogonek (U+0173): B<<208.5,-61.5>-<228.0,-36.0>-<272.0,-4.0>>/B<<272.0,-4.0>-<266.0,-10.0>-<254.0,-10.0>> = 8.972626614896358

	* w (U+0077): B<<144.0,121.0>-<142.0,92.0>-<141.0,74.0>>/B<<141.0,74.0>-<145.0,92.0>-<152.5,121.0>> = 9.348977589287225

	* w (U+0077): B<<329.5,430.0>-<331.0,463.0>-<332.0,482.0>>/B<<332.0,482.0>-<328.0,463.0>-<318.5,430.0>> = 8.875870535444639

	* w (U+0077): B<<394.0,121.5>-<393.0,93.0>-<392.0,74.0>>/B<<392.0,74.0>-<396.0,93.0>-<404.0,121.5>> = 8.875870535444639

	* wacute (U+1E83): B<<144.0,121.0>-<142.0,92.0>-<141.0,74.0>>/B<<141.0,74.0>-<145.0,92.0>-<152.5,121.0>> = 9.348977589287225

	* wacute (U+1E83): B<<329.5,430.0>-<331.0,463.0>-<332.0,482.0>>/B<<332.0,482.0>-<328.0,463.0>-<318.5,430.0>> = 8.875870535444639

	* wacute (U+1E83): B<<394.0,121.5>-<393.0,93.0>-<392.0,74.0>>/B<<392.0,74.0>-<396.0,93.0>-<404.0,121.5>> = 8.875870535444639

	* wcircumflex (U+0175): B<<144.0,121.0>-<142.0,92.0>-<141.0,74.0>>/B<<141.0,74.0>-<145.0,92.0>-<152.5,121.0>> = 9.348977589287225

	* wcircumflex (U+0175): B<<329.5,430.0>-<331.0,463.0>-<332.0,482.0>>/B<<332.0,482.0>-<328.0,463.0>-<318.5,430.0>> = 8.875870535444639

	* wcircumflex (U+0175): B<<394.0,121.5>-<393.0,93.0>-<392.0,74.0>>/B<<392.0,74.0>-<396.0,93.0>-<404.0,121.5>> = 8.875870535444639

	* wdieresis (U+1E85): B<<144.0,121.0>-<142.0,92.0>-<141.0,74.0>>/B<<141.0,74.0>-<145.0,92.0>-<152.5,121.0>> = 9.348977589287225

	* wdieresis (U+1E85): B<<329.5,430.0>-<331.0,463.0>-<332.0,482.0>>/B<<332.0,482.0>-<328.0,463.0>-<318.5,430.0>> = 8.875870535444639

	* wdieresis (U+1E85): B<<394.0,121.5>-<393.0,93.0>-<392.0,74.0>>/B<<392.0,74.0>-<396.0,93.0>-<404.0,121.5>> = 8.875870535444639

	* wgrave (U+1E81): B<<144.0,121.0>-<142.0,92.0>-<141.0,74.0>>/B<<141.0,74.0>-<145.0,92.0>-<152.5,121.0>> = 9.348977589287225

	* wgrave (U+1E81): B<<329.5,430.0>-<331.0,463.0>-<332.0,482.0>>/B<<332.0,482.0>-<328.0,463.0>-<318.5,430.0>> = 8.875870535444639 

	* wgrave (U+1E81): B<<394.0,121.5>-<393.0,93.0>-<392.0,74.0>>/B<<392.0,74.0>-<396.0,93.0>-<404.0,121.5>> = 8.875870535444639 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[19] PitagonSansMono-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ
at: https://scripts.sil.org/OFL." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry TRADEMARK on platform WINDOWS contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1120, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 400, but got 300 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.8.13 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0336

	- uni0337 

	- uni0338 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Pita' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x0400 (CYRILLIC CAPITAL LETTER IE WITH GRAVE)


	- 0x040D (CYRILLIC CAPITAL LETTER I WITH GRAVE)


	- 0x0450 (CYRILLIC SMALL LETTER IE WITH GRAVE)
 

	- 0x045D (CYRILLIC SMALL LETTER I WITH GRAVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Plus is almost fulfilled. Missing codepoints:

	- 0x20B8 (TENGE SIGN)


	- 0x20AD (KIP SIGN)


	- 0x2153 (VULGAR FRACTION ONE THIRD)


	- 0x2154 (VULGAR FRACTION TWO THIRDS)


	- 0x0E3F (THAI CURRENCY SYMBOL BAHT)


	- 0x20B5 (CEDI SIGN)


	- 0x20A1 (COLON SIGN)


	- 0x20B2 (GUARANI SIGN)


	- 0x20BE (LARI SIGN)


	- 0x20BA (TURKISH LIRA SIGN)


	- 0x20BC (MANAT SIGN)


	- 0x20A6 (NAIRA SIGN)


	- 0x20B1 (PESO SIGN)


	- 0x20A8 (RUPEE SIGN)


	- 0x20B9 (INDIAN RUPEE SIGN)


	- 0x20AA (NEW SHEQEL SIGN)


	- 0x20A9 (WON SIGN)
 

	- 0x2126 (OHM SIGN)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Pitagon Sans Mono SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
hyphen_hyphen_braceright_braceright.liga, braceleft_braceleft_hyphen_hyphen.liga, braceleft_exclam_hyphen_hyphen.liga, semicolon_semicolon_semicolon.liga, numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga, numbersign_underscore_parenleft.liga, ampersand_ampersand_ampersand.liga, less_numbersign_hyphen_hyphen.liga, asciitilde_asciitilde_greater.liga and ampersand_ampersand_ampersand.liga.cv15 [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- bar_bar_bar.liga

	- brevecombcy

	- uni0311.case

	- uni0324.case

	- uni0326.alt

	- uni032E.case

	- uni0331.case

	- uni2070.zero

	- uni2080.zero

	- zero.dnom.zero 

	- zero.numr.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: circleplus	Contours detected: 5	Expected: 3

	- Glyph name: dkshade	Contours detected: 41	Expected: 73

	- Glyph name: ltshade	Contours detected: 55	Expected: 46

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

	- Glyph name: shade	Contours detected: 110	Expected: 85

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni210D	Contours detected: 3	Expected: 2

	- Glyph name: uni2119	Contours detected: 4	Expected: 2

	- Glyph name: uni211A	Contours detected: 4	Expected: 3

	- Glyph name: uni211D	Contours detected: 5	Expected: 3

	- Glyph name: uni2213	Contours detected: 1	Expected: 2 

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: 𝕚̀ 𝕚́ 𝕚̂ 𝕚̃ 𝕚̄ 𝕚̆ 𝕚̇ 𝕚̈ 𝕚̉ 𝕚̊ 𝕚̋ 𝕚̌ 𝕚̏ 𝕚̒ 𝕚̥̀ 𝕚̥́ 𝕚̥̂ 𝕚̥̃ 𝕚̥̄ 𝕚̥̆ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1710 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 2 glyphs (0.11%) have a different width. You should check the widths of: ['periodcentered.loclCAT', 'periodcentered.loclCAT.case'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* M (U+004D): B<<444.0,577.0>-<448.0,641.0>-<453.0,693.0>>/L<<453.0,693.0>--<348.0,340.0>> = 11.07280756402622

	* M (U+004D): L<<247.0,340.0>--<146.0,684.0>>/B<<146.0,684.0>-<155.0,613.0>-<160.0,521.0>> = 9.138168552194179

	* Mu (U+039C): B<<444.0,577.0>-<448.0,641.0>-<453.0,693.0>>/L<<453.0,693.0>--<348.0,340.0>> = 11.07280756402622

	* Mu (U+039C): L<<247.0,340.0>--<146.0,684.0>>/B<<146.0,684.0>-<155.0,613.0>-<160.0,521.0>> = 9.138168552194179

	* Uogonek (U+0172): B<<266.5,-58.5>-<286.0,-30.0>-<317.0,-5.0>>/B<<317.0,-5.0>-<310.0,-10.0>-<300.0,-10.0>> = 3.346818641740188

	* W (U+0057): B<<167.0,138.0>-<169.0,100.0>-<170.0,76.0>>/B<<170.0,76.0>-<173.0,100.0>-<176.0,138.0>> = 9.510960379290568

	* W (U+0057): B<<306.0,599.0>-<303.0,636.0>-<301.0,659.0>>/B<<301.0,659.0>-<299.0,636.0>-<296.5,599.0>> = 9.939481456220602

	* W (U+0057): B<<423.5,138.0>-<428.0,100.0>-<430.0,76.0>>/B<<430.0,76.0>-<432.0,100.0>-<434.5,138.0>> = 9.527283381452328

	* Wacute (U+1E82): B<<167.0,138.0>-<169.0,100.0>-<170.0,76.0>>/B<<170.0,76.0>-<173.0,100.0>-<176.0,138.0>> = 9.510960379290568

	* Wacute (U+1E82): B<<306.0,599.0>-<303.0,636.0>-<301.0,659.0>>/B<<301.0,659.0>-<299.0,636.0>-<296.5,599.0>> = 9.939481456220602

	* Wacute (U+1E82): B<<423.5,138.0>-<428.0,100.0>-<430.0,76.0>>/B<<430.0,76.0>-<432.0,100.0>-<434.5,138.0>> = 9.527283381452328

	* Wcircumflex (U+0174): B<<167.0,138.0>-<169.0,100.0>-<170.0,76.0>>/B<<170.0,76.0>-<173.0,100.0>-<176.0,138.0>> = 9.510960379290568

	* Wcircumflex (U+0174): B<<306.0,599.0>-<303.0,636.0>-<301.0,659.0>>/B<<301.0,659.0>-<299.0,636.0>-<296.5,599.0>> = 9.939481456220602

	* Wcircumflex (U+0174): B<<423.5,138.0>-<428.0,100.0>-<430.0,76.0>>/B<<430.0,76.0>-<432.0,100.0>-<434.5,138.0>> = 9.527283381452328

	* Wdieresis (U+1E84): B<<167.0,138.0>-<169.0,100.0>-<170.0,76.0>>/B<<170.0,76.0>-<173.0,100.0>-<176.0,138.0>> = 9.510960379290568

	* Wdieresis (U+1E84): B<<306.0,599.0>-<303.0,636.0>-<301.0,659.0>>/B<<301.0,659.0>-<299.0,636.0>-<296.5,599.0>> = 9.939481456220602

	* Wdieresis (U+1E84): B<<423.5,138.0>-<428.0,100.0>-<430.0,76.0>>/B<<430.0,76.0>-<432.0,100.0>-<434.5,138.0>> = 9.527283381452328

	* Wgrave (U+1E80): B<<167.0,138.0>-<169.0,100.0>-<170.0,76.0>>/B<<170.0,76.0>-<173.0,100.0>-<176.0,138.0>> = 9.510960379290568

	* Wgrave (U+1E80): B<<306.0,599.0>-<303.0,636.0>-<301.0,659.0>>/B<<301.0,659.0>-<299.0,636.0>-<296.5,599.0>> = 9.939481456220602

	* Wgrave (U+1E80): B<<423.5,138.0>-<428.0,100.0>-<430.0,76.0>>/B<<430.0,76.0>-<432.0,100.0>-<434.5,138.0>> = 9.527283381452328

	* ae (U+00E6): B<<264.0,535.5>-<298.0,511.0>-<303.0,470.0>>/B<<303.0,470.0>-<308.0,511.0>-<341.0,535.5>> = 13.9059149363478

	* aeacute (U+01FD): B<<264.0,535.5>-<298.0,511.0>-<303.0,470.0>>/B<<303.0,470.0>-<308.0,511.0>-<341.0,535.5>> = 13.9059149363478

	* b (U+0062): B<<241.5,20.0>-<202.0,50.0>-<191.0,104.0>>/L<<191.0,104.0>--<191.0,0.0>> = 11.513831184487014

	* b (U+0062): L<<192.0,573.0>--<189.0,446.0>>/B<<189.0,446.0>-<201.0,499.0>-<241.5,529.5>> = 11.404340207096977

	* braceleft (U+007B): B<<363.5,404.5>-<331.0,370.0>-<263.0,362.0>>/B<<263.0,362.0>-<331.0,354.0>-<363.5,317.0>> = 13.41967361551383

	* d (U+0064): B<<358.5,530.0>-<399.0,500.0>-<411.0,446.0>>/L<<411.0,446.0>--<408.0,573.0>> = 11.17561575537178

	* d (U+0064): L<<409.0,0.0>--<409.0,104.0>>/B<<409.0,104.0>-<398.0,50.0>-<358.5,20.0>> = 11.513831184487014

	* endOfMediumcontrol (U+2419): B<<505.5,210.0>-<507.0,257.0>-<517.0,295.0>>/L<<517.0,295.0>--<444.0,113.0>> = 7.112104000625744

	* endOfMediumcontrol (U+2419): L<<357.0,113.0>--<282.0,292.0>>/B<<282.0,292.0>-<287.0,267.0>-<290.5,241.0>> = 11.423479252667413

	* g (U+0067): L<<408.0,47.0>--<410.0,139.0>>/B<<410.0,139.0>-<397.0,90.0>-<358.5,63.0>> = 13.61325018115632

	* gbreve (U+011F): L<<408.0,47.0>--<410.0,139.0>>/B<<410.0,139.0>-<397.0,90.0>-<358.5,63.0>> = 13.61325018115632

	* gcaron (U+01E7): L<<408.0,47.0>--<410.0,139.0>>/B<<410.0,139.0>-<397.0,90.0>-<358.5,63.0>> = 13.61325018115632

	* gcircumflex (U+011D): L<<408.0,47.0>--<410.0,139.0>>/B<<410.0,139.0>-<397.0,90.0>-<358.5,63.0>> = 13.61325018115632

	* gdotaccent (U+0121): L<<408.0,47.0>--<410.0,139.0>>/B<<410.0,139.0>-<397.0,90.0>-<358.5,63.0>> = 13.61325018115632

	* nine (U+0039): L<<199.0,24.0>--<363.0,309.0>>/L<<363.0,309.0>--<361.0,306.0>> = 3.7722836093798127

	* p (U+0070): L<<191.0,550.0>--<191.0,446.0>>/B<<191.0,446.0>-<202.0,500.0>-<241.5,530.0>> = 11.513831184487014

	* perthousand (U+2030): B<<405.0,271.5>-<429.0,253.0>-<432.0,222.0>>/B<<432.0,222.0>-<435.0,253.0>-<459.5,271.5>> = 11.055080303312293

	* perthousand (U+2030): B<<458.5,13.5>-<435.0,32.0>-<433.0,63.0>>/B<<433.0,63.0>-<428.0,32.0>-<404.0,13.5>> = 12.853733032172984

	* petapp (U+E006): B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>>/L<<129.0,397.0>--<127.0,400.0>> = 11.309932474020227

	* petapp (U+E006): B<<134.0,242.0>-<128.0,255.0>-<114.0,264.0>>/L<<114.0,264.0>--<141.0,249.0>> = 3.6806221730303044

	* petapp (U+E006): B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>>/L<<214.0,82.0>--<212.0,85.0>> = 11.309932474020227

	* petapp (U+E006): B<<262.0,54.0>-<263.0,54.0>-<265.0,53.0>>/L<<265.0,53.0>--<262.0,54.0>> = 8.130102354155916

	* petapp (U+E006): B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>>/L<<321.0,57.0>--<316.0,56.0>> = 7.125016348901757

	* petapp (U+E006): B<<318.0,63.0>-<319.0,63.0>-<321.0,64.0>>/L<<321.0,64.0>--<318.0,63.0>> = 8.130102354155916

	* petapp (U+E006): B<<336.0,60.0>-<334.0,60.0>-<331.0,59.0>>/L<<331.0,59.0>--<336.0,60.0>> = 7.125016348901705

	* petapp (U+E006): B<<338.0,162.0>-<338.0,163.0>-<337.0,165.0>>/L<<337.0,165.0>--<338.0,162.0>> = 8.13010235415587

	* petapp (U+E006): B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>>/L<<334.0,270.0>--<338.0,267.0>> = 10.304846468766009

	* petapp (U+E006): B<<343.0,379.0>-<342.0,379.0>-<340.0,380.0>>/L<<340.0,380.0>--<343.0,379.0>> = 8.13010235415587

	* petapp (U+E006): B<<347.0,132.0>-<347.0,133.0>-<346.0,135.0>>/L<<346.0,135.0>--<347.0,132.0>> = 8.13010235415587

	* petapp (U+E006): B<<380.0,331.0>-<380.0,332.0>-<379.0,334.0>>/L<<379.0,334.0>--<380.0,331.0>> = 8.13010235415587

	* petapp (U+E006): B<<386.0,311.0>-<386.0,312.0>-<385.0,314.0>>/L<<385.0,314.0>--<386.0,311.0>> = 8.13010235415587

	* petapp (U+E006): B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>>/L<<402.0,329.0>--<400.0,334.0>> = 3.366460663429615

	* petapp (U+E006): B<<413.0,303.0>-<413.0,302.0>-<414.0,300.0>>/L<<414.0,300.0>--<413.0,303.0>> = 8.130102354155916

	* petapp (U+E006): B<<413.0,318.0>-<413.0,317.0>-<414.0,315.0>>/L<<414.0,315.0>--<413.0,318.0>> = 8.130102354155916

	* petapp (U+E006): B<<418.0,294.0>-<418.0,293.0>-<419.0,291.0>>/L<<419.0,291.0>--<418.0,294.0>> = 8.130102354155916

	* petapp (U+E006): B<<419.0,309.0>-<419.0,308.0>-<420.0,306.0>>/L<<420.0,306.0>--<419.0,309.0>> = 8.130102354155916

	* petapp (U+E006): B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>>/L<<425.0,282.0>--<423.0,285.0>> = 7.125016348901705

	* petapp (U+E006): B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>>/L<<440.0,351.0>--<439.0,355.0>> = 12.528807709151492

	* petapp (U+E006): B<<451.0,275.0>-<453.0,274.0>-<454.0,273.0>>/L<<454.0,273.0>--<451.0,275.0>> = 11.309932474020195

	* petapp (U+E006): B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>>/L<<449.0,394.0>--<451.0,397.0>> = 7.125016348901757

	* petapp (U+E006): B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>>/L<<454.0,122.0>--<452.0,119.0>> = 7.125016348901705

	* petapp (U+E006): B<<462.0,132.0>-<462.0,133.0>-<463.0,135.0>>/L<<463.0,135.0>--<462.0,132.0>> = 8.130102354155916

	* petapp (U+E006): B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>>/L<<462.0,236.0>--<464.0,233.0>> = 11.309932474020195

	* petapp (U+E006): B<<470.0,219.0>-<470.0,220.0>-<469.0,222.0>>/L<<469.0,222.0>--<470.0,219.0>> = 8.13010235415587

	* petapp (U+E006): B<<472.0,214.0>-<472.0,215.0>-<471.0,217.0>>/L<<471.0,217.0>--<472.0,214.0>> = 8.13010235415587

	* petapp (U+E006): B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>>/L<<474.0,207.0>--<475.0,202.0>> = 7.125016348901705

	* petapp (U+E006): B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>>/L<<473.0,414.0>--<476.0,416.0>> = 11.309932474020227

	* petapp (U+E006): L<<112.0,428.0>--<111.0,431.0>>/B<<111.0,431.0>-<112.0,429.0>-<112.0,428.0>> = 8.130102354155916

	* petapp (U+E006): L<<129.0,397.0>--<127.0,400.0>>/B<<127.0,400.0>-<128.0,398.0>-<129.0,397.0>> = 7.125016348901705

	* petapp (U+E006): L<<157.0,372.0>--<153.0,375.0>>/B<<153.0,375.0>-<155.0,373.0>-<157.0,372.0>> = 8.13010235415596

	* petapp (U+E006): L<<214.0,82.0>--<212.0,85.0>>/B<<212.0,85.0>-<213.0,83.0>-<214.0,82.0>> = 7.125016348901705

	* petapp (U+E006): L<<310.0,60.0>--<307.0,59.0>>/B<<307.0,59.0>-<309.0,60.0>-<310.0,60.0>> = 8.130102354155916

	* petapp (U+E006): L<<321.0,57.0>--<316.0,56.0>>/B<<316.0,56.0>-<318.0,56.0>-<321.0,57.0>> = 11.309932474020195

	* petapp (U+E006): L<<334.0,270.0>--<338.0,267.0>>/B<<338.0,267.0>-<336.0,269.0>-<334.0,270.0>> = 8.13010235415596

	* petapp (U+E006): L<<356.0,65.0>--<352.0,64.0>>/B<<352.0,64.0>-<354.0,64.0>-<356.0,65.0>> = 14.036243467926484

	* petapp (U+E006): L<<363.0,244.0>--<364.0,241.0>>/B<<364.0,241.0>-<363.0,243.0>-<363.0,244.0>> = 8.13010235415587

	* petapp (U+E006): L<<384.0,203.0>--<385.0,200.0>>/B<<385.0,200.0>-<384.0,202.0>-<384.0,203.0>> = 8.13010235415587

	* petapp (U+E006): L<<387.0,303.0>--<388.0,300.0>>/B<<388.0,300.0>-<387.0,302.0>-<387.0,303.0>> = 8.13010235415587

	* petapp (U+E006): L<<402.0,329.0>--<400.0,334.0>>/B<<400.0,334.0>-<401.0,332.0>-<402.0,329.0>> = 4.763641690726066

	* petapp (U+E006): L<<425.0,282.0>--<423.0,285.0>>/B<<423.0,285.0>-<424.0,284.0>-<425.0,282.0>> = 11.309932474020227

	* petapp (U+E006): L<<440.0,351.0>--<439.0,355.0>>/B<<439.0,355.0>-<439.0,353.0>-<440.0,351.0>> = 14.036243467926484

	* petapp (U+E006): L<<442.0,340.0>--<441.0,343.0>>/B<<441.0,343.0>-<442.0,341.0>-<442.0,340.0>> = 8.130102354155916

	* petapp (U+E006): L<<444.0,335.0>--<443.0,338.0>>/B<<443.0,338.0>-<444.0,336.0>-<444.0,335.0>> = 8.130102354155916

	* petapp (U+E006): L<<446.0,330.0>--<445.0,333.0>>/B<<445.0,333.0>-<446.0,331.0>-<446.0,330.0>> = 8.130102354155916

	* petapp (U+E006): L<<449.0,394.0>--<451.0,397.0>>/B<<451.0,397.0>-<450.0,396.0>-<449.0,394.0>> = 11.309932474020195

	* petapp (U+E006): L<<454.0,122.0>--<452.0,119.0>>/B<<452.0,119.0>-<453.0,120.0>-<454.0,122.0>> = 11.309932474020227

	* petapp (U+E006): L<<462.0,236.0>--<464.0,233.0>>/B<<464.0,233.0>-<463.0,235.0>-<462.0,236.0>> = 7.125016348901757

	* petapp (U+E006): L<<473.0,414.0>--<476.0,416.0>>/B<<476.0,416.0>-<474.0,415.0>-<473.0,414.0>> = 7.125016348901757

	* petapp (U+E006): L<<474.0,207.0>--<475.0,202.0>>/B<<475.0,202.0>-<475.0,204.0>-<474.0,207.0>> = 11.309932474020195

	* petapp (U+E006): L<<480.0,418.0>--<483.0,419.0>>/B<<483.0,419.0>-<481.0,418.0>-<480.0,417.5>> = 8.13010235415587

	* petapp (U+E006): L<<491.0,252.0>--<488.0,253.0>>/B<<488.0,253.0>-<490.0,252.0>-<491.0,252.0>> = 8.130102354155916

	* petapp (U+E006): L<<496.0,250.0>--<493.0,251.0>>/B<<493.0,251.0>-<495.0,250.0>-<496.0,250.0>> = 8.130102354155916

	* petapp.minimal (U+E007): B<<365.0,279.0>-<368.0,276.0>-<370.0,275.0>>/L<<370.0,275.0>--<365.0,279.0>> = 12.094757077012058

	* petapp.minimal (U+E007): B<<402.0,358.0>-<402.0,357.0>-<401.0,355.0>>/L<<401.0,355.0>--<402.0,358.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<405.0,368.0>-<405.0,367.0>-<404.0,365.0>>/L<<404.0,365.0>--<405.0,368.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>>/L<<437.0,404.0>--<440.0,406.0>> = 7.125016348901757

	* petapp.minimal (U+E007): B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>>/L<<442.0,407.0>--<447.0,409.0>> = 4.763641690726143

	* petapp.minimal (U+E007): B<<468.0,415.0>-<467.0,415.0>-<465.0,414.0>>/L<<465.0,414.0>--<468.0,415.0>> = 8.13010235415587

	* petapp.minimal (U+E007): B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>>/L<<467.0,106.0>--<469.0,103.0>> = 11.309932474020195

	* petapp.minimal (U+E007): B<<484.5,8.5>-<484.0,4.0>-<483.0,0.0>>/B<<483.0,0.0>-<483.0,3.0>-<483.0,6.5>> = 14.036243467926484

	* petapp.minimal (U+E007): L<<408.0,166.0>--<411.0,165.0>>/B<<411.0,165.0>-<409.0,166.0>-<408.0,166.5>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<413.0,298.0>--<412.0,301.0>>/B<<412.0,301.0>-<413.0,299.0>-<413.0,298.0>> = 8.130102354155916

	* petapp.minimal (U+E007): L<<417.0,160.0>--<420.0,159.0>>/B<<420.0,159.0>-<418.0,160.0>-<417.0,160.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<437.0,404.0>--<440.0,406.0>>/B<<440.0,406.0>-<439.0,405.0>-<437.0,404.0>> = 11.309932474020227

	* petapp.minimal (U+E007): L<<442.0,407.0>--<447.0,409.0>>/B<<447.0,409.0>-<444.0,408.0>-<442.0,407.0>> = 3.3664606634297236

	* petapp.minimal (U+E007): L<<462.0,116.0>--<463.0,113.0>>/B<<463.0,113.0>-<462.0,115.0>-<462.0,116.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<467.0,106.0>--<469.0,103.0>>/B<<469.0,103.0>-<468.0,105.0>-<467.0,106.0>> = 7.125016348901757

	* petapp.minimal (U+E007): L<<471.0,157.0>--<472.0,154.0>>/B<<472.0,154.0>-<471.0,156.0>-<471.0,157.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<477.0,142.0>--<478.0,139.0>>/B<<478.0,139.0>-<477.0,141.0>-<477.0,142.0>> = 8.13010235415587

	* petapp.minimal (U+E007): L<<88.0,404.0>--<88.0,600.0>>/B<<88.0,600.0>-<90.0,577.0>-<99.0,557.0>> = 4.969740728110289

	* petapp.wpda (U+E008): B<<231.0,125.0>-<238.0,133.0>-<239.0,135.0>>/B<<239.0,135.0>-<238.0,132.0>-<236.0,113.5>> = 8.13010235415587

	* petapp.wpda (U+E008): L<<519.0,126.0>--<515.0,129.0>>/B<<515.0,129.0>-<517.0,127.0>-<517.0,125.0>> = 8.13010235415596

	* petapp.wpda (U+E008): L<<99.0,100.0>--<103.0,103.0>>/B<<103.0,103.0>-<101.0,101.0>-<99.0,103.0>> = 8.13010235415596

	* pisafe (U+E010): B<<54.0,449.0>-<54.0,448.0>-<53.0,446.0>>/L<<53.0,446.0>--<54.0,449.0>> = 8.13010235415587

	* pisafe (U+E010): B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>>/L<<538.0,461.0>--<540.0,458.0>> = 11.309932474020195

	* pisafe (U+E010): B<<547.0,444.0>-<547.0,445.0>-<546.0,447.0>>/L<<546.0,447.0>--<547.0,444.0>> = 8.13010235415587

	* pisafe (U+E010): B<<549.0,439.0>-<549.0,440.0>-<548.0,442.0>>/L<<548.0,442.0>--<549.0,439.0>> = 8.13010235415587

	* pisafe (U+E010): B<<551.0,434.0>-<551.0,435.0>-<550.0,437.0>>/L<<550.0,437.0>--<551.0,434.0>> = 8.13010235415587

	* pisafe (U+E010): B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>>/L<<554.0,424.0>--<555.0,420.0>> = 12.528807709151492

	* pisafe (U+E010): B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>>/L<<55.0,451.0>--<57.0,454.0>> = 11.309932474020195

	* pisafe (U+E010): B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>>/L<<72.0,475.0>--<74.0,478.0>> = 7.125016348901757

	* pisafe (U+E010): B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>>/L<<87.0,490.0>--<90.0,492.0>> = 7.125016348901757

	* pisafe (U+E010): L<<45.0,424.0>--<46.0,429.0>>/B<<46.0,429.0>-<46.0,426.0>-<45.0,424.0>> = 11.309932474020195

	* pisafe (U+E010): L<<502.0,497.0>--<505.0,495.0>>/B<<505.0,495.0>-<504.0,496.0>-<502.0,497.0>> = 11.309932474020227

	* pisafe (U+E010): L<<538.0,461.0>--<540.0,458.0>>/B<<540.0,458.0>-<539.0,460.0>-<538.0,461.0>> = 7.125016348901757

	* pisafe (U+E010): L<<55.0,451.0>--<57.0,454.0>>/B<<57.0,454.0>-<56.0,452.0>-<55.0,451.0>> = 7.125016348901757

	* pisafe (U+E010): L<<554.0,424.0>--<555.0,420.0>>/B<<555.0,420.0>-<555.0,422.0>-<554.0,424.0>> = 14.036243467926484

	* pisafe (U+E010): L<<559.0,402.0>--<560.0,399.0>>/B<<560.0,399.0>-<559.0,401.0>-<559.0,402.0>> = 8.13010235415587

	* pisafe (U+E010): L<<61.0,460.0>--<62.0,463.0>>/B<<62.0,463.0>-<61.0,461.0>-<61.0,460.0>> = 8.13010235415587

	* pisafe (U+E010): L<<72.0,475.0>--<74.0,478.0>>/B<<74.0,478.0>-<73.0,477.0>-<72.0,475.0>> = 11.309932474020195

	* pisafe (U+E010): L<<87.0,490.0>--<90.0,492.0>>/B<<90.0,492.0>-<89.0,491.0>-<87.0,490.0>> = 11.309932474020227

	* q (U+0071): B<<358.5,530.0>-<398.0,500.0>-<409.0,446.0>>/L<<409.0,446.0>--<409.0,550.0>> = 11.513831184487014

	* thorn (U+00FE): B<<238.5,20.0>-<199.0,50.0>-<187.0,104.0>>/L<<187.0,104.0>--<187.0,-170.0>> = 12.528807709151492

	* thorn (U+00FE): L<<189.0,573.0>--<186.0,446.0>>/B<<186.0,446.0>-<198.0,499.0>-<238.0,529.5>> = 11.404340207096977

	* trademark (U+2122): B<<369.0,652.5>-<362.0,679.0>-<356.0,699.0>>/B<<356.0,699.0>-<359.0,675.0>-<362.5,638.0>> = 9.574227885091789

	* trademark (U+2122): B<<510.0,637.0>-<513.0,675.0>-<516.0,700.0>>/B<<516.0,700.0>-<511.0,680.0>-<503.5,652.5>> = 7.193470055295488

	* u1D54A (U+1D54A): B<<168.5,651.5>-<188.0,682.0>-<220.0,693.0>>/B<<220.0,693.0>-<173.0,682.0>-<145.5,640.0>> = 5.797854385159548

	* u1D54A (U+1D54A): B<<436.5,94.0>-<419.0,57.0>-<388.0,37.0>>/B<<388.0,37.0>-<437.0,55.0>-<465.5,102.0>> = 12.657888379562115

	* u1D54D (U+1D54D): B<<345.0,102.0>-<352.0,69.0>-<353.0,52.0>>/B<<353.0,52.0>-<355.0,69.0>-<362.5,102.5>> = 10.076297471186699

	* u1D54E (U+1D54E): B<<219.5,144.5>-<220.0,126.0>-<223.0,92.0>>/B<<223.0,92.0>-<228.0,126.0>-<230.0,144.5>> = 13.408337193203469

	* u1D54E (U+1D54E): B<<480.0,144.5>-<482.0,126.0>-<485.0,92.0>>/B<<485.0,92.0>-<489.0,126.0>-<490.0,144.5>> = 11.752287876927799

	* u1D55E (U+1D55E): L<<155.0,550.0>--<155.0,484.0>>/B<<155.0,484.0>-<162.0,519.0>-<188.0,539.5>> = 11.309932474020195

	* u1D564 (U+1D564): B<<183.5,483.0>-<200.0,509.0>-<226.0,522.0>>/B<<226.0,522.0>-<180.0,512.0>-<151.5,478.0>> = 14.300277449185549

	* u1D568 (U+1D568): B<<225.5,112.5>-<228.0,96.0>-<230.0,75.0>>/B<<230.0,75.0>-<231.0,89.0>-<232.5,97.0>> = 9.52594881098034

	* u1D568 (U+1D568): B<<305.5,212.5>-<300.0,245.0>-<298.0,275.0>>/B<<298.0,275.0>-<297.0,253.0>-<292.5,219.5>> = 6.416637036790123

	* u1D568 (U+1D568): B<<475.0,112.0>-<478.0,96.0>-<480.0,75.0>>/B<<480.0,75.0>-<483.0,95.0>-<483.5,103.0>> = 13.97109764095363

	* uni0123 (U+0123): L<<408.0,47.0>--<410.0,139.0>>/B<<410.0,139.0>-<397.0,90.0>-<358.5,63.0>> = 13.61325018115632

	* uni01EA (U+01EA): B<<266.5,-58.5>-<286.0,-30.0>-<317.0,-5.0>>/B<<317.0,-5.0>-<310.0,-10.0>-<300.0,-10.0>> = 3.346818641740188

	* uni01EB (U+01EB): B<<259.0,-61.5>-<275.0,-36.0>-<313.0,-7.0>>/B<<313.0,-7.0>-<306.0,-10.0>-<300.0,-10.0>> = 14.15075853099239

	* uni01F5 (U+01F5): L<<408.0,47.0>--<410.0,139.0>>/B<<410.0,139.0>-<397.0,90.0>-<358.5,63.0>> = 13.61325018115632

	* uni03D7 (U+03D7): B<<182.0,177.0>-<180.0,129.0>-<172.0,96.0>>/L<<172.0,96.0>--<383.0,550.0>> = 11.300017536673845

	* uni03D7 (U+03D7): B<<417.5,372.0>-<419.0,418.0>-<428.0,449.0>>/L<<428.0,449.0>--<217.0,0.0>> = 8.981182609981499

	* uni040E (U+040E): B<<299.0,329.5>-<307.0,299.0>-<309.0,282.0>>/B<<309.0,282.0>-<311.0,299.0>-<317.5,329.5>> = 13.41967361551383

	* uni041C (U+041C): B<<444.0,577.0>-<448.0,641.0>-<453.0,693.0>>/L<<453.0,693.0>--<348.0,340.0>> = 11.07280756402622

	* uni041C (U+041C): L<<247.0,340.0>--<146.0,684.0>>/B<<146.0,684.0>-<155.0,613.0>-<160.0,521.0>> = 9.138168552194179

	* uni0423 (U+0423): B<<299.0,329.5>-<307.0,299.0>-<309.0,282.0>>/B<<309.0,282.0>-<311.0,299.0>-<317.5,329.5>> = 13.41967361551383

	* uni0431 (U+0431): L<<168.0,459.0>--<168.0,408.0>>/B<<168.0,408.0>-<180.0,459.0>-<220.5,487.5>> = 13.24051991518721

	* uni0438 (U+0438): B<<182.0,177.0>-<180.0,129.0>-<172.0,96.0>>/L<<172.0,96.0>--<383.0,550.0>> = 11.300017536673845

	* uni0438 (U+0438): B<<417.5,372.0>-<419.0,418.0>-<428.0,449.0>>/L<<428.0,449.0>--<217.0,0.0>> = 8.981182609981499

	* uni0439 (U+0439): B<<182.0,177.0>-<180.0,129.0>-<172.0,96.0>>/L<<172.0,96.0>--<383.0,550.0>> = 11.300017536673845

	* uni0439 (U+0439): B<<417.5,372.0>-<419.0,418.0>-<428.0,449.0>>/L<<428.0,449.0>--<217.0,0.0>> = 8.981182609981499

	* uni043C (U+043C): B<<439.5,387.5>-<442.0,453.0>-<449.0,499.0>>/L<<449.0,499.0>--<343.0,206.0>> = 11.23630249691612

	* uni043C (U+043C): L<<252.0,206.0>--<150.0,483.0>>/B<<150.0,483.0>-<161.0,421.0>-<162.5,318.5>> = 10.15458359285057

	* uni0440 (U+0440): L<<191.0,550.0>--<191.0,446.0>>/B<<191.0,446.0>-<202.0,500.0>-<241.5,530.0>> = 11.513831184487014

	* uni04E5 (U+04E5): B<<182.0,177.0>-<180.0,129.0>-<172.0,96.0>>/L<<172.0,96.0>--<383.0,550.0>> = 11.300017536673845

	* uni04E5 (U+04E5): B<<417.5,372.0>-<419.0,418.0>-<428.0,449.0>>/L<<428.0,449.0>--<217.0,0.0>> = 8.981182609981499

	* uni2116 (U+2116): B<<107.0,572.5>-<98.0,611.0>-<92.0,641.0>>/B<<92.0,641.0>-<96.0,600.0>-<100.5,546.5>> = 5.737734670056357

	* uni2116 (U+2116): B<<273.5,160.5>-<282.0,121.0>-<289.0,90.0>>/B<<289.0,90.0>-<284.0,132.0>-<279.0,186.0>> = 5.935381110983574

	* uni2196 (U+2196): B<<243.0,639.0>-<225.0,640.0>-<215.0,646.0>>/L<<215.0,646.0>--<562.0,300.0>> = 13.953565632796554

	* uni2197 (U+2197): L<<40.0,300.0>--<387.0,646.0>>/B<<387.0,646.0>-<377.0,640.0>-<359.5,639.0>> = 13.953565632796554

	* uni2198 (U+2198): B<<359.5,91.5>-<377.0,90.0>-<387.0,84.0>>/L<<387.0,84.0>--<40.0,430.0>> = 13.953565632796579

	* uni2199 (U+2199): L<<560.0,430.0>--<213.0,84.0>>/B<<213.0,84.0>-<223.0,90.0>-<240.5,91.5>> = 13.953565632796579

	* uni227A (U+227A): B<<353.5,374.5>-<280.0,341.0>-<183.0,335.0>>/B<<183.0,335.0>-<280.0,329.0>-<353.5,293.0>> = 7.0791183370998505

	* uni227B (U+227B): B<<246.5,293.0>-<320.0,329.0>-<417.0,335.0>>/B<<417.0,335.0>-<320.0,341.0>-<246.5,374.5>> = 7.0791183370998505

	* uni227C (U+227C): B<<353.5,499.5>-<280.0,466.0>-<183.0,460.0>>/B<<183.0,460.0>-<280.0,454.0>-<353.5,418.0>> = 7.0791183370998505

	* uni22CE (U+22CE): B<<257.5,383.0>-<292.0,309.0>-<298.0,212.0>>/B<<298.0,212.0>-<304.0,310.0>-<339.5,384.0>> = 7.043090813334337

	* uni234B (U+234B): L<<276.0,95.0>--<276.0,525.0>>/L<<276.0,525.0>--<175.0,95.0>> = 13.2182373989993

	* uni234B (U+234B): L<<425.0,95.0>--<323.0,525.0>>/L<<323.0,525.0>--<323.0,95.0>> = 13.344450989740325

	* uni2352 (U+2352): L<<176.0,635.0>--<281.0,203.0>>/L<<281.0,203.0>--<278.0,635.0>> = 13.263272745070877

	* uni2352 (U+2352): L<<324.0,635.0>--<324.0,203.0>>/L<<324.0,203.0>--<425.0,635.0>> = 13.159175935941423

	* uni236C (U+236C): L<<188.0,527.0>--<188.0,386.0>>/B<<188.0,386.0>-<202.0,457.0>-<251.0,457.0>> = 11.154659738928277

	* uni236C (U+236C): L<<412.0,203.0>--<412.0,358.0>>/B<<412.0,358.0>-<398.0,287.0>-<349.0,287.0>> = 11.154659738928277

	* uni2377 (U+2377): B<<107.0,252.5>-<143.0,289.0>-<213.0,292.0>>/B<<213.0,292.0>-<153.0,296.0>-<120.5,326.0>> = 6.268106508817428

	* uni26A1 (U+26A1): L<<580.0,440.0>--<50.0,-110.0>>/L<<50.0,-110.0>--<295.0,310.0>> = 13.68265114620652

	* uniFF5B (U+FF5B): B<<363.5,404.5>-<331.0,370.0>-<263.0,362.0>>/B<<263.0,362.0>-<331.0,354.0>-<363.5,317.0>> = 13.41967361551383

	* uogonek (U+0173): B<<259.0,-61.5>-<275.0,-36.0>-<313.0,-7.0>>/B<<313.0,-7.0>-<306.0,-10.0>-<300.0,-10.0>> = 14.15075853099239

	* w (U+0077): B<<171.0,129.5>-<174.0,98.0>-<175.0,78.0>>/B<<175.0,78.0>-<177.0,98.0>-<180.0,129.5>> = 8.57299836361137

	* w (U+0077): B<<305.5,421.0>-<302.0,455.0>-<300.0,475.0>>/B<<300.0,475.0>-<299.0,455.0>-<294.5,421.0>> = 8.57299836361137

	* w (U+0077): B<<420.5,129.5>-<424.0,98.0>-<426.0,78.0>>/B<<426.0,78.0>-<428.0,98.0>-<430.5,129.5>> = 11.42118627499929

	* wacute (U+1E83): B<<171.0,129.5>-<174.0,98.0>-<175.0,78.0>>/B<<175.0,78.0>-<177.0,98.0>-<180.0,129.5>> = 8.57299836361137

	* wacute (U+1E83): B<<305.5,421.0>-<302.0,455.0>-<300.0,475.0>>/B<<300.0,475.0>-<299.0,455.0>-<294.5,421.0>> = 8.57299836361137

	* wacute (U+1E83): B<<420.5,129.5>-<424.0,98.0>-<426.0,78.0>>/B<<426.0,78.0>-<428.0,98.0>-<430.5,129.5>> = 11.42118627499929

	* wcircumflex (U+0175): B<<171.0,129.5>-<174.0,98.0>-<175.0,78.0>>/B<<175.0,78.0>-<177.0,98.0>-<180.0,129.5>> = 8.57299836361137

	* wcircumflex (U+0175): B<<305.5,421.0>-<302.0,455.0>-<300.0,475.0>>/B<<300.0,475.0>-<299.0,455.0>-<294.5,421.0>> = 8.57299836361137

	* wcircumflex (U+0175): B<<420.5,129.5>-<424.0,98.0>-<426.0,78.0>>/B<<426.0,78.0>-<428.0,98.0>-<430.5,129.5>> = 11.42118627499929

	* wdieresis (U+1E85): B<<171.0,129.5>-<174.0,98.0>-<175.0,78.0>>/B<<175.0,78.0>-<177.0,98.0>-<180.0,129.5>> = 8.57299836361137

	* wdieresis (U+1E85): B<<305.5,421.0>-<302.0,455.0>-<300.0,475.0>>/B<<300.0,475.0>-<299.0,455.0>-<294.5,421.0>> = 8.57299836361137

	* wdieresis (U+1E85): B<<420.5,129.5>-<424.0,98.0>-<426.0,78.0>>/B<<426.0,78.0>-<428.0,98.0>-<430.5,129.5>> = 11.42118627499929

	* wgrave (U+1E81): B<<171.0,129.5>-<174.0,98.0>-<175.0,78.0>>/B<<175.0,78.0>-<177.0,98.0>-<180.0,129.5>> = 8.57299836361137

	* wgrave (U+1E81): B<<305.5,421.0>-<302.0,455.0>-<300.0,475.0>>/B<<300.0,475.0>-<299.0,455.0>-<294.5,421.0>> = 8.57299836361137 

	* wgrave (U+1E81): B<<420.5,129.5>-<424.0,98.0>-<426.0,78.0>>/B<<426.0,78.0>-<428.0,98.0>-<430.5,129.5>> = 11.42118627499929 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* asterisk (U+002A): L<<347.0,620.0>--<346.0,497.0>>

	* eogonek (U+0119): L<<184.0,322.0>--<416.0,323.0>>

	* five (U+0035): L<<195.0,612.0>--<196.0,481.0>>

	* phi (U+03C6): L<<145.0,351.0>--<144.0,204.0>>

	* question (U+003F): L<<197.0,221.0>--<196.0,402.0>>

	* uni0416 (U+0416): L<<259.0,0.0>--<258.0,338.0>>

	* uni0416 (U+0416): L<<341.0,338.0>--<343.0,0.0>>

	* uni0428 (U+0428): L<<55.0,0.0>--<53.0,730.0>>

	* uni0448 (U+0448): L<<55.0,0.0>--<53.0,550.0>>

	* uni04D9 (U+04D9): L<<419.0,227.0>--<181.0,226.0>>

	* uni04DC (U+04DC): L<<259.0,0.0>--<258.0,338.0>>

	* uni04DC (U+04DC): L<<341.0,338.0>--<343.0,0.0>>

	* uni2289 (U+2289): L<<29.0,685.0>--<332.0,684.0>> 

	* uni2352 (U+2352): L<<281.0,203.0>--<278.0,635.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 96 | 211 | 1882 | 97 | 1346 | 0 |
| 0% | 3% | 6% | 52% | 3% | 37% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
