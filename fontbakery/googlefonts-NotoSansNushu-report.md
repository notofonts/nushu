## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[5] NotoSansNushu-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* u1B1B9 (U+1B1B9): L<<206.0,45.0>--<206.0,45.0>>/L<<206.0,45.0>--<201.0,44.0>> = 11.309932474020195

	* u1B1BE (U+1B1BE): L<<206.0,45.0>--<206.0,45.0>>/L<<206.0,45.0>--<201.0,44.0>> = 11.309932474020195

	* u1B1DF (U+1B1DF): L<<206.0,45.0>--<206.0,45.0>>/L<<206.0,45.0>--<201.0,44.0>> = 11.309932474020195

	* u1B1E5 (U+1B1E5): L<<206.0,45.0>--<206.0,45.0>>/L<<206.0,45.0>--<201.0,44.0>> = 11.309932474020195

	* u1B200 (U+1B200): L<<206.0,45.0>--<206.0,45.0>>/L<<206.0,45.0>--<201.0,44.0>> = 11.309932474020195

	* u1B21C (U+1B21C): L<<206.0,45.0>--<206.0,45.0>>/L<<206.0,45.0>--<201.0,44.0>> = 11.309932474020195

	* u1B21F (U+1B21F): L<<206.0,45.0>--<206.0,45.0>>/L<<206.0,45.0>--<201.0,44.0>> = 11.309932474020195

	* u1B22A (U+1B22A): L<<206.0,45.0>--<206.0,45.0>>/L<<206.0,45.0>--<201.0,44.0>> = 11.309932474020195

	* u1B23A (U+1B23A): L<<206.0,45.0>--<206.0,45.0>>/L<<206.0,45.0>--<201.0,44.0>> = 11.309932474020195

	* u1B23B (U+1B23B): L<<206.0,45.0>--<206.0,45.0>>/L<<206.0,45.0>--<201.0,44.0>> = 11.309932474020195 

	* And 13 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 5 | 111 | 7 | 104 | 0 |
| 0% | 0% | 2% | 49% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
