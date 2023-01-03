## Fontbakery report

Fontbakery version: 0.8.11a8

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoTraditionalNushu/googlefonts/ttf', 'fonts/NotoTraditionalNushu/googlefonts/variable-ttf'] [code: single-directory]
</div></details><br></div></details><details><summary><b>[10] NotoTraditionalNushu-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain less than 40 CJK characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_not_enough_glyphs">com.google.fonts/check/cjk_not_enough_glyphs</a>)</summary><div>


* ⚠ **WARN** There are only 29 CJK glyphs when there needs to be at least 40 in order to support the smallest CJK writing system, Hangul.
The following CJK glyphs were found:
['uni2EDA', 'uni2F08', 'uni2F25', 'uni2FA5', 'uni2FAF', 'uni34B5', 'uni34C1', 'uni34C5', 'uni3539', 'uni4352', 'uni4491', 'uni4E66', 'uni2F08', 'uni51E1', 'uni53E9', 'uni2F25', 'uni662F', 'uni6C38', 'uni6D4B', 'uni7136', 'uni7532', 'uni7684', 'uni8BD5', 'uni8FD9', 'uni2FA5', 'uni2FAF', 'uni97E9', 'uni2EDA', 'uni2FA5']
Please check that these glyphs have the correct unicodes. [code: cjk-not-enough-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- u1B2B3.001

	- uni3002.locl 

	- And uni4494.locl
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: hyphen	Contours detected: 0	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: minus	Contours detected: 0	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: hyphen	Contours detected: 0	Expected: 1

	- Glyph name: minus	Contours detected: 0	Expected: 1 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature">com.google.fonts/check/cjk_chws_feature</a>)</summary><div>


* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726 

	* And 13 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* u1B18F (U+1B18F): L<<505.0,1000.0>--<625.0,999.0>>

	* u1B195 (U+1B195): L<<407.0,1000.0>--<528.0,999.0>>

	* u1B19D (U+1B19D): L<<376.0,1000.0>--<497.0,999.0>>

	* u1B1A1 (U+1B1A1): L<<440.0,1000.0>--<563.0,999.0>>

	* u1B1D9 (U+1B1D9): L<<481.0,1000.0>--<610.0,999.0>>

	* u1B1DC (U+1B1DC): L<<749.0,241.0>--<626.0,240.0>>

	* u1B20B (U+1B20B): L<<427.0,-120.0>--<311.0,-119.0>>

	* u1B22D (U+1B22D): L<<407.0,1000.0>--<527.0,999.0>>

	* u1B231 (U+1B231): L<<217.0,346.0>--<336.0,345.0>>

	* u1B253 (U+1B253): L<<502.0,999.0>--<618.0,1000.0>> 

	* And u1B27E (U+1B27E): L<<389.0,999.0>--<506.0,1000.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[10] NotoTraditionalNushu-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Traditional Nushu Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain less than 40 CJK characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_not_enough_glyphs">com.google.fonts/check/cjk_not_enough_glyphs</a>)</summary><div>


* ⚠ **WARN** There are only 29 CJK glyphs when there needs to be at least 40 in order to support the smallest CJK writing system, Hangul.
The following CJK glyphs were found:
['uni2EDA', 'uni2F08', 'uni2F25', 'uni2FA5', 'uni2FAF', 'uni34B5', 'uni34C1', 'uni34C5', 'uni3539', 'uni4352', 'uni4491', 'uni4E66', 'uni2F08', 'uni51E1', 'uni53E9', 'uni2F25', 'uni662F', 'uni6C38', 'uni6D4B', 'uni7136', 'uni7532', 'uni7684', 'uni8BD5', 'uni8FD9', 'uni2FA5', 'uni2FAF', 'uni97E9', 'uni2EDA', 'uni2FA5']
Please check that these glyphs have the correct unicodes. [code: cjk-not-enough-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- u1B2B3.001

	- uni3002.locl 

	- And uni4494.locl
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: hyphen	Contours detected: 0	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: minus	Contours detected: 0	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: hyphen	Contours detected: 0	Expected: 1

	- Glyph name: minus	Contours detected: 0	Expected: 1 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature">com.google.fonts/check/cjk_chws_feature</a>)</summary><div>


* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u1B2B5 (U+1B2B5): L<<659.0,553.0>--<660.0,553.0>> -> L<<660.0,553.0>--<660.0,553.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[11] NotoTraditionalNushu-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* D
	* G
	* I
	* M
	* N
	* O
	* S
	* W
	* Z and 215 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Traditional Nushu' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain less than 40 CJK characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_not_enough_glyphs">com.google.fonts/check/cjk_not_enough_glyphs</a>)</summary><div>


* ⚠ **WARN** There are only 29 CJK glyphs when there needs to be at least 40 in order to support the smallest CJK writing system, Hangul.
The following CJK glyphs were found:
['uni2EDA', 'uni2F08', 'uni2F25', 'uni2FA5', 'uni2FAF', 'uni34B5', 'uni34C1', 'uni34C5', 'uni3539', 'uni4352', 'uni4491', 'uni4E66', 'uni2F08', 'uni51E1', 'uni53E9', 'uni2F25', 'uni662F', 'uni6C38', 'uni6D4B', 'uni7136', 'uni7532', 'uni7684', 'uni8BD5', 'uni8FD9', 'uni2FA5', 'uni2FAF', 'uni97E9', 'uni2EDA', 'uni2FA5']
Please check that these glyphs have the correct unicodes. [code: cjk-not-enough-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- u1B2B3.001

	- uni3002.locl 

	- And uni4494.locl
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: hyphen	Contours detected: 0	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: minus	Contours detected: 0	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: hyphen	Contours detected: 0	Expected: 1

	- Glyph name: minus	Contours detected: 0	Expected: 1 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature">com.google.fonts/check/cjk_chws_feature</a>)</summary><div>


* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u1B2B5 (U+1B2B5): L<<713.0,550.0>--<713.0,550.0>> -> L<<713.0,550.0>--<713.0,550.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] NotoTraditionalNushu[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Traditional Nushu' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain less than 40 CJK characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_not_enough_glyphs">com.google.fonts/check/cjk_not_enough_glyphs</a>)</summary><div>


* ⚠ **WARN** There are only 29 CJK glyphs when there needs to be at least 40 in order to support the smallest CJK writing system, Hangul.
The following CJK glyphs were found:
['uni2EDA', 'uni2F08', 'uni2F25', 'uni2FA5', 'uni2FAF', 'uni34B5', 'uni34C1', 'uni34C5', 'uni3539', 'uni4352', 'uni4491', 'uni4E66', 'uni2F08', 'uni51E1', 'uni53E9', 'uni2F25', 'uni662F', 'uni6C38', 'uni6D4B', 'uni7136', 'uni7532', 'uni7684', 'uni8BD5', 'uni8FD9', 'uni2FA5', 'uni2FAF', 'uni97E9', 'uni2EDA', 'uni2FA5']
Please check that these glyphs have the correct unicodes. [code: cjk-not-enough-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* ⚠ **WARN** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- u1B2B3.001

	- uni3002.locl 

	- And uni4494.locl
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature">com.google.fonts/check/cjk_chws_feature</a>)</summary><div>


* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Detect any interpolation issues in the font. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/interpolation_issues">com.google.fonts/check/interpolation_issues</a>)</summary><div>


* ⚠ **WARN** Interpolation issues were found in the font: 	- Contour 2 start point differs in glyph 'u1B1CE' between location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc12c7b1ed0> and location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc12c7b1f90>

	- Contour order differs in glyph 'u1B2F1': [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12] in <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc12c7b1ed0>, [0, 1, 2, 9, 10, 11, 12, 3, 4, 5, 6, 7, 8] in <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc12c7b1f90>.

	- Contour 3 start point differs in glyph 'u1B2F1' between location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc12c7b1ed0> and location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc12c7b1f90>

	- Contour 5 start point differs in glyph 'u1B2F1' between location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc12c7b1ed0> and location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc12c7b1f90>

	- Contour 9 start point differs in glyph 'u1B2F1' between location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc12c7b1ed0> and location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc12c7b1f90> 

	- And Contour 11 start point differs in glyph 'u1B2F1' between location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc12c7b1ed0> and location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc12c7b1f90> [code: interpolation-issues]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 5 | 37 | 445 | 26 | 371 | 0 |
| 0% | 1% | 4% | 50% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**