## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoTraditionalNushu[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 944, but got 860 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[15] NotoTraditionalNushu[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 241, but got 118 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: OS/2]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (860) and hhea ascent (1055) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Noto Traditional Nushu Regular: hhea Ascender is 1055 when it should be 860</p>
 [code: bad-hhea-ascender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- u1B2B3.001

- uni3002.locl

- uni4494.locl
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoTraditionalNushu/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, old-permic, malayalam, todhri, tai-le, hebrew, syriac, tifinagh, duployan, coptic, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+2EDA CJK RADICAL C-SIMPLIFIED LEAF: not included in any glyphset definition</li>
<li>U+2F08 KANGXI RADICAL MAN: not included in any glyphset definition</li>
<li>U+2F25 KANGXI RADICAL WOMAN: not included in any glyphset definition</li>
<li>U+2FA5 KANGXI RADICAL VILLAGE: not included in any glyphset definition</li>
<li>U+2FAF KANGXI RADICAL FACE: not included in any glyphset definition</li>
<li>U+34B5 CJK UNIFIED IDEOGRAPH-34B5: not included in any glyphset definition</li>
<li>U+34C1 CJK UNIFIED IDEOGRAPH-34C1: not included in any glyphset definition</li>
<li>U+34C5 CJK UNIFIED IDEOGRAPH-34C5: not included in any glyphset definition</li>
<li>U+3539 CJK UNIFIED IDEOGRAPH-3539: not included in any glyphset definition</li>
<li>U+4352 CJK UNIFIED IDEOGRAPH-4352: not included in any glyphset definition</li>
<li>U+4491 CJK UNIFIED IDEOGRAPH-4491: not included in any glyphset definition</li>
<li>U+4E66 CJK UNIFIED IDEOGRAPH-4E66: try adding chinese-simplified</li>
<li>U+4EBA CJK UNIFIED IDEOGRAPH-4EBA: try adding one of: chinese-traditional, chinese-simplified, japanese, chinese-hongkong</li>
<li>U+51E1 CJK UNIFIED IDEOGRAPH-51E1: try adding one of: chinese-traditional, chinese-simplified, japanese, chinese-hongkong</li>
<li>U+53E9 CJK UNIFIED IDEOGRAPH-53E9: try adding one of: chinese-traditional, chinese-simplified, japanese, chinese-hongkong</li>
<li>U+5973 CJK UNIFIED IDEOGRAPH-5973: try adding one of: chinese-traditional, chinese-simplified, japanese, chinese-hongkong</li>
<li>U+662F CJK UNIFIED IDEOGRAPH-662F: try adding one of: chinese-traditional, chinese-simplified, japanese, chinese-hongkong</li>
<li>U+6C38 CJK UNIFIED IDEOGRAPH-6C38: try adding one of: chinese-traditional, chinese-simplified, japanese, chinese-hongkong</li>
<li>U+6D4B CJK UNIFIED IDEOGRAPH-6D4B: try adding chinese-simplified</li>
<li>U+7136 CJK UNIFIED IDEOGRAPH-7136: try adding one of: chinese-traditional, chinese-simplified, japanese, chinese-hongkong</li>
<li>U+7532 CJK UNIFIED IDEOGRAPH-7532: try adding one of: chinese-traditional, chinese-simplified, japanese, chinese-hongkong</li>
<li>U+7684 CJK UNIFIED IDEOGRAPH-7684: try adding one of: chinese-traditional, chinese-simplified, japanese, chinese-hongkong</li>
<li>U+8BD5 CJK UNIFIED IDEOGRAPH-8BD5: try adding chinese-simplified</li>
<li>U+8FD9 CJK UNIFIED IDEOGRAPH-8FD9: try adding chinese-simplified</li>
<li>U+91CC CJK UNIFIED IDEOGRAPH-91CC: try adding one of: chinese-traditional, chinese-simplified, japanese, chinese-hongkong</li>
<li>U+9762 CJK UNIFIED IDEOGRAPH-9762: try adding one of: chinese-traditional, chinese-simplified, japanese, chinese-hongkong</li>
<li>U+97E9 CJK UNIFIED IDEOGRAPH-97E9: try adding chinese-simplified</li>
<li>U+9875 CJK UNIFIED IDEOGRAPH-9875: try adding chinese-simplified</li>
<li>U+E000 : not included in any glyphset definition</li>
<li>U+E001 : not included in any glyphset definition</li>
<li>U+E002 : not included in any glyphset definition</li>
<li>U+E003 : not included in any glyphset definition</li>
<li>U+E004 : not included in any glyphset definition</li>
<li>U+E005 : not included in any glyphset definition</li>
<li>U+E006 : not included in any glyphset definition</li>
<li>U+E007 : not included in any glyphset definition</li>
<li>U+E008 : not included in any glyphset definition</li>
<li>U+E009 : not included in any glyphset definition</li>
<li>U+E010 : not included in any glyphset definition</li>
<li>U+E011 : not included in any glyphset definition</li>
<li>U+E012 : not included in any glyphset definition</li>
<li>U+F9E9 CJK COMPATIBILITY IDEOGRAPH-F9E9: not included in any glyphset definition</li>
<li>U+FF61 HALFWIDTH IDEOGRAPHIC FULL STOP: try adding yi</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>nushu</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Name ID 6 'NotoTraditionalNushu-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Makaa (Latn, 221,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kom (Latn, 360,685 speakers), Mfumte (Latn, 79,000 speakers), Zapotec (Latn, 490,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Nateni (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Igbo (Latn, 27,823,640 speakers), Kaska (Latn, 125 speakers), Yala (Latn, 200,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Cicipu (Latn, 44,000 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Bafut (Latn, 158,146 speakers), Sar (Latn, 500,000 speakers), Southern Kisi (Latn, 360,000 speakers), Han (Latn, 6 speakers), Ebira (Latn, 2,200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Vute (Latn, 21,000 speakers), Ma’di (Latn, 584,000 speakers), Dan (Latn, 1,099,244 speakers), Mundani (Latn, 34,000 speakers), Navajo (Latn, 166,319 speakers), Nzakara (Latn, 50,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), South Central Banda (Latn, 244,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ekpeye (Latn, 226,000 speakers), Mango (Latn, 77,000 speakers), Koonzime (Latn, 40,000 speakers), Heiltsuk (Latn, 300 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* uniE004 (U+E004) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain less than 150 CJK characters? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>There are only 29 CJK glyphs when there needs to be at least 150 in order to support the smallest CJK writing system, Kana.
The following CJK glyphs were found:
['uni2EDA', 'uni2F08', 'uni2F25', 'uni2FA5', 'uni2FAF', 'uni34B5', 'uni34C1', 'uni34C5', 'uni3539', 'uni4352', 'uni4491', 'uni4E66', 'uni2F08', 'uni51E1', 'uni53E9', 'uni2F25', 'uni662F', 'uni6C38', 'uni6D4B', 'uni7136', 'uni7532', 'uni7684', 'uni8BD5', 'uni8FD9', 'uni2FA5', 'uni2FAF', 'uni97E9', 'uni2EDA', 'uni2FA5']
Please check that these glyphs have the correct unicodes.</p>
 [code: cjk-not-enough-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 6 | 10 | 96 | 7 | 132 | 0 | 
| 0% | 0% | 2% | 4% | 38% | 3% | 53% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
