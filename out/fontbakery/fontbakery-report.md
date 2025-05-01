## FontBakery report

fontbakery version: 0.13.2







## Check results



<details><summary>[16] Sedenion-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#alt-caron">alt_caron</a></summary>
    <div>









* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>Lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>tcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if uppercase glyphs are vertically centered. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#caps-vertically-centered">caps_vertically_centered</a></summary>
    <div>







* ⚠️ **WARN** <p>Uppercase glyphs are not vertically centered in the em box.</p>
 [code: vertical-metrics-not-centered]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: percent	Contours detected: 3	Expected: 4 or 5

- Glyph name: Igrave	Contours detected: 1	Expected: 2

- Glyph name: Iacute	Contours detected: 1	Expected: 2

- Glyph name: uni0122	Contours detected: 1	Expected: 2

- Glyph name: uni0123	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni013B	Contours detected: 1	Expected: 2

- Glyph name: uni013C	Contours detected: 1	Expected: 2

- Glyph name: Iacute	Contours detected: 1	Expected: 2

- Glyph name: Igrave	Contours detected: 1	Expected: 2

- Glyph name: percent	Contours detected: 3	Expected: 4 or 5

- Glyph name: uni0122	Contours detected: 1	Expected: 2

- Glyph name: uni0123	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni013B	Contours detected: 1	Expected: 2

- Glyph name: uni013C	Contours detected: 1	Expected: 2
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#gpos-kerning-info">gpos_kerning_info</a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 429 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 522:
plus</p>
<p>Width = 413:
equal</p>
<p>Width = 545:
multiply</p>
<p>Width = 530:
divide</p>
<p>Width = 410:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#typoascender-exceeds-Agrave">typoascender_exceeds_Agrave</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2.sTypoAscender value should be greater than 960, but got 800 instead</p>
 [code: typoAscender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- nonmarkingreturn
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, math, coptic, syriac, hebrew, old-permic, tai-le, duployan, canadian-aboriginal, malayalam, tifinagh</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_TransLatin_Arabic glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŀ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʻ</td>
<td align="left">en_Latn (English)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ĳ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ĳ</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ ĭ i̇ ǐ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* C (U+0043): L&lt;&lt;418.0,0.0&gt;--&lt;405.0,0.0&gt;&gt; -&gt; L&lt;&lt;405.0,0.0&gt;--&lt;165.0,0.0&gt;&gt;

* C (U+0043): L&lt;&lt;524.0,612.0&gt;--&lt;525.0,600.0&gt;&gt; -&gt; L&lt;&lt;525.0,600.0&gt;--&lt;525.0,540.0&gt;&gt;

* Cacute (U+0106): L&lt;&lt;418.0,0.0&gt;--&lt;405.0,0.0&gt;&gt; -&gt; L&lt;&lt;405.0,0.0&gt;--&lt;165.0,0.0&gt;&gt;

* Cacute (U+0106): L&lt;&lt;524.0,612.0&gt;--&lt;525.0,600.0&gt;&gt; -&gt; L&lt;&lt;525.0,600.0&gt;--&lt;525.0,540.0&gt;&gt;

* Ccaron (U+010C): L&lt;&lt;418.0,0.0&gt;--&lt;405.0,0.0&gt;&gt; -&gt; L&lt;&lt;405.0,0.0&gt;--&lt;165.0,0.0&gt;&gt;

* Ccaron (U+010C): L&lt;&lt;524.0,612.0&gt;--&lt;525.0,600.0&gt;&gt; -&gt; L&lt;&lt;525.0,600.0&gt;--&lt;525.0,540.0&gt;&gt;

* Ccedilla (U+00C7): L&lt;&lt;418.0,0.0&gt;--&lt;405.0,0.0&gt;&gt; -&gt; L&lt;&lt;405.0,0.0&gt;--&lt;333.0,0.0&gt;&gt;

* Ccedilla (U+00C7): L&lt;&lt;524.0,612.0&gt;--&lt;525.0,600.0&gt;&gt; -&gt; L&lt;&lt;525.0,600.0&gt;--&lt;525.0,540.0&gt;&gt;

* Cdotaccent (U+010A): L&lt;&lt;418.0,0.0&gt;--&lt;405.0,0.0&gt;&gt; -&gt; L&lt;&lt;405.0,0.0&gt;--&lt;165.0,0.0&gt;&gt;

* Cdotaccent (U+010A): L&lt;&lt;524.0,612.0&gt;--&lt;525.0,600.0&gt;&gt; -&gt; L&lt;&lt;525.0,600.0&gt;--&lt;525.0,540.0&gt;&gt;

* G (U+0047): L&lt;&lt;404.0,165.0&gt;--&lt;405.0,180.0&gt;&gt; -&gt; L&lt;&lt;405.0,180.0&gt;--&lt;405.0,240.0&gt;&gt;

* G (U+0047): L&lt;&lt;418.0,0.0&gt;--&lt;405.0,0.0&gt;&gt; -&gt; L&lt;&lt;405.0,0.0&gt;--&lt;165.0,0.0&gt;&gt;

* G (U+0047): L&lt;&lt;524.0,612.0&gt;--&lt;525.0,600.0&gt;&gt; -&gt; L&lt;&lt;525.0,600.0&gt;--&lt;525.0,540.0&gt;&gt;

* G (U+0047): L&lt;&lt;525.0,360.0&gt;--&lt;525.0,180.0&gt;&gt; -&gt; L&lt;&lt;525.0,180.0&gt;--&lt;525.0,120.0&gt;&gt;

* Gbreve (U+011E): L&lt;&lt;404.0,165.0&gt;--&lt;405.0,180.0&gt;&gt; -&gt; L&lt;&lt;405.0,180.0&gt;--&lt;405.0,240.0&gt;&gt;

* Gbreve (U+011E): L&lt;&lt;418.0,0.0&gt;--&lt;405.0,0.0&gt;&gt; -&gt; L&lt;&lt;405.0,0.0&gt;--&lt;165.0,0.0&gt;&gt;

* Gbreve (U+011E): L&lt;&lt;524.0,612.0&gt;--&lt;525.0,600.0&gt;&gt; -&gt; L&lt;&lt;525.0,600.0&gt;--&lt;525.0,540.0&gt;&gt;

* Gbreve (U+011E): L&lt;&lt;525.0,360.0&gt;--&lt;525.0,180.0&gt;&gt; -&gt; L&lt;&lt;525.0,180.0&gt;--&lt;525.0,120.0&gt;&gt;

* Gdotaccent (U+0120): L&lt;&lt;404.0,165.0&gt;--&lt;405.0,180.0&gt;&gt; -&gt; L&lt;&lt;405.0,180.0&gt;--&lt;405.0,240.0&gt;&gt;

* Gdotaccent (U+0120): L&lt;&lt;418.0,0.0&gt;--&lt;405.0,0.0&gt;&gt; -&gt; L&lt;&lt;405.0,0.0&gt;--&lt;165.0,0.0&gt;&gt;

* Gdotaccent (U+0120): L&lt;&lt;524.0,612.0&gt;--&lt;525.0,600.0&gt;&gt; -&gt; L&lt;&lt;525.0,600.0&gt;--&lt;525.0,540.0&gt;&gt;

* Gdotaccent (U+0120): L&lt;&lt;525.0,360.0&gt;--&lt;525.0,180.0&gt;&gt; -&gt; L&lt;&lt;525.0,180.0&gt;--&lt;525.0,120.0&gt;&gt;

* OE (U+0152): L&lt;&lt;165.0,720.0&gt;--&lt;345.0,720.0&gt;&gt; -&gt; L&lt;&lt;345.0,720.0&gt;--&lt;405.0,720.0&gt;&gt;

* OE (U+0152): L&lt;&lt;345.0,720.0&gt;--&lt;405.0,720.0&gt;&gt; -&gt; L&lt;&lt;405.0,720.0&gt;--&lt;765.0,720.0&gt;&gt;

* OE (U+0152): L&lt;&lt;405.0,0.0&gt;--&lt;345.0,0.0&gt;&gt; -&gt; L&lt;&lt;345.0,0.0&gt;--&lt;165.0,0.0&gt;&gt;

* OE (U+0152): L&lt;&lt;745.0,0.0&gt;--&lt;405.0,0.0&gt;&gt; -&gt; L&lt;&lt;405.0,0.0&gt;--&lt;345.0,0.0&gt;&gt;

* c (U+0063): L&lt;&lt;416.0,0.0&gt;--&lt;403.0,0.0&gt;&gt; -&gt; L&lt;&lt;403.0,0.0&gt;--&lt;163.0,0.0&gt;&gt;

* c (U+0063): L&lt;&lt;522.0,372.0&gt;--&lt;523.0,360.0&gt;&gt; -&gt; L&lt;&lt;523.0,360.0&gt;--&lt;523.0,300.0&gt;&gt;

* cacute (U+0107): L&lt;&lt;416.0,0.0&gt;--&lt;403.0,0.0&gt;&gt; -&gt; L&lt;&lt;403.0,0.0&gt;--&lt;163.0,0.0&gt;&gt;

* cacute (U+0107): L&lt;&lt;522.0,372.0&gt;--&lt;523.0,360.0&gt;&gt; -&gt; L&lt;&lt;523.0,360.0&gt;--&lt;523.0,300.0&gt;&gt;

* ccaron (U+010D): L&lt;&lt;416.0,0.0&gt;--&lt;403.0,0.0&gt;&gt; -&gt; L&lt;&lt;403.0,0.0&gt;--&lt;163.0,0.0&gt;&gt;

* ccaron (U+010D): L&lt;&lt;522.0,372.0&gt;--&lt;523.0,360.0&gt;&gt; -&gt; L&lt;&lt;523.0,360.0&gt;--&lt;523.0,300.0&gt;&gt;

* ccedilla (U+00E7): L&lt;&lt;416.0,0.0&gt;--&lt;403.0,0.0&gt;&gt; -&gt; L&lt;&lt;403.0,0.0&gt;--&lt;333.0,0.0&gt;&gt;

* ccedilla (U+00E7): L&lt;&lt;522.0,372.0&gt;--&lt;523.0,360.0&gt;&gt; -&gt; L&lt;&lt;523.0,360.0&gt;--&lt;523.0,300.0&gt;&gt;

* cdotaccent (U+010B): L&lt;&lt;416.0,0.0&gt;--&lt;403.0,0.0&gt;&gt; -&gt; L&lt;&lt;403.0,0.0&gt;--&lt;163.0,0.0&gt;&gt;

* cdotaccent (U+010B): L&lt;&lt;522.0,372.0&gt;--&lt;523.0,360.0&gt;&gt; -&gt; L&lt;&lt;523.0,360.0&gt;--&lt;523.0,300.0&gt;&gt;

* cent (U+00A2): L&lt;&lt;416.0,0.0&gt;--&lt;403.0,0.0&gt;&gt; -&gt; L&lt;&lt;403.0,0.0&gt;--&lt;287.0,0.0&gt;&gt;

* cent (U+00A2): L&lt;&lt;522.0,372.0&gt;--&lt;523.0,360.0&gt;&gt; -&gt; L&lt;&lt;523.0,360.0&gt;--&lt;523.0,300.0&gt;&gt;

* copyright (U+00A9): L&lt;&lt;596.0,60.0&gt;--&lt;583.0,60.0&gt;&gt; -&gt; L&lt;&lt;583.0,60.0&gt;--&lt;343.0,60.0&gt;&gt;

* copyright (U+00A9): L&lt;&lt;702.0,432.0&gt;--&lt;703.0,420.0&gt;&gt; -&gt; L&lt;&lt;703.0,420.0&gt;--&lt;703.0,360.0&gt;&gt;

* eth (U+00F0): L&lt;&lt;403.0,0.0&gt;--&lt;283.0,0.0&gt;&gt; -&gt; L&lt;&lt;283.0,0.0&gt;--&lt;163.0,0.0&gt;&gt;

* germandbls (U+00DF): L&lt;&lt;210.0,720.0&gt;--&lt;546.0,720.0&gt;&gt; -&gt; L&lt;&lt;546.0,720.0&gt;--&lt;548.0,720.0&gt;&gt;

* germandbls (U+00DF): L&lt;&lt;548.0,0.0&gt;--&lt;546.0,0.0&gt;&gt; -&gt; L&lt;&lt;546.0,0.0&gt;--&lt;300.0,0.0&gt;&gt;

* h (U+0068): L&lt;&lt;48.0,0.0&gt;--&lt;48.0,360.0&gt;&gt; -&gt; L&lt;&lt;48.0,360.0&gt;--&lt;48.0,720.0&gt;&gt;

* hbar (U+0127): L&lt;&lt;48.0,0.0&gt;--&lt;48.0,360.0&gt;&gt; -&gt; L&lt;&lt;48.0,360.0&gt;--&lt;48.0,540.0&gt;&gt;

* m (U+006D): L&lt;&lt;46.0,0.0&gt;--&lt;46.0,360.0&gt;&gt; -&gt; L&lt;&lt;46.0,360.0&gt;--&lt;46.0,480.0&gt;&gt;

* n (U+006E): L&lt;&lt;46.0,0.0&gt;--&lt;46.0,360.0&gt;&gt; -&gt; L&lt;&lt;46.0,360.0&gt;--&lt;46.0,480.0&gt;&gt;

* nacute (U+0144): L&lt;&lt;46.0,0.0&gt;--&lt;46.0,360.0&gt;&gt; -&gt; L&lt;&lt;46.0,360.0&gt;--&lt;46.0,480.0&gt;&gt;

* ncaron (U+0148): L&lt;&lt;46.0,0.0&gt;--&lt;46.0,360.0&gt;&gt; -&gt; L&lt;&lt;46.0,360.0&gt;--&lt;46.0,480.0&gt;&gt;

* nine (U+0039): L&lt;&lt;152.0,720.0&gt;--&lt;165.0,720.0&gt;&gt; -&gt; L&lt;&lt;165.0,720.0&gt;--&lt;405.0,720.0&gt;&gt;

* nine (U+0039): L&lt;&lt;166.0,555.0&gt;--&lt;165.0,540.0&gt;&gt; -&gt; L&lt;&lt;165.0,540.0&gt;--&lt;165.0,480.0&gt;&gt;

* nine (U+0039): L&lt;&lt;45.0,420.0&gt;--&lt;45.0,480.0&gt;&gt; -&gt; L&lt;&lt;45.0,480.0&gt;--&lt;45.0,540.0&gt;&gt;

* nine (U+0039): L&lt;&lt;45.0,480.0&gt;--&lt;45.0,540.0&gt;&gt; -&gt; L&lt;&lt;45.0,540.0&gt;--&lt;45.0,600.0&gt;&gt;

* nine (U+0039): L&lt;&lt;46.0,108.0&gt;--&lt;45.0,120.0&gt;&gt; -&gt; L&lt;&lt;45.0,120.0&gt;--&lt;45.0,180.0&gt;&gt;

* nine (U+0039): L&lt;&lt;46.0,408.0&gt;--&lt;45.0,420.0&gt;&gt; -&gt; L&lt;&lt;45.0,420.0&gt;--&lt;45.0,480.0&gt;&gt;

* ntilde (U+00F1): L&lt;&lt;46.0,0.0&gt;--&lt;46.0,360.0&gt;&gt; -&gt; L&lt;&lt;46.0,360.0&gt;--&lt;46.0,480.0&gt;&gt;

* question (U+003F): L&lt;&lt;141.0,720.0&gt;--&lt;201.0,720.0&gt;&gt; -&gt; L&lt;&lt;201.0,720.0&gt;--&lt;321.0,720.0&gt;&gt;

* questiondown (U+00BF): L&lt;&lt;341.0,0.0&gt;--&lt;281.0,0.0&gt;&gt; -&gt; L&lt;&lt;281.0,0.0&gt;--&lt;161.0,0.0&gt;&gt;

* r (U+0072): L&lt;&lt;46.0,0.0&gt;--&lt;46.0,360.0&gt;&gt; -&gt; L&lt;&lt;46.0,360.0&gt;--&lt;46.0,480.0&gt;&gt;

* racute (U+0155): L&lt;&lt;46.0,0.0&gt;--&lt;46.0,360.0&gt;&gt; -&gt; L&lt;&lt;46.0,360.0&gt;--&lt;46.0,480.0&gt;&gt;

* rcaron (U+0159): L&lt;&lt;46.0,0.0&gt;--&lt;46.0,360.0&gt;&gt; -&gt; L&lt;&lt;46.0,360.0&gt;--&lt;46.0,480.0&gt;&gt;

* six (U+0036): L&lt;&lt;420.0,0.0&gt;--&lt;408.0,0.0&gt;&gt; -&gt; L&lt;&lt;408.0,0.0&gt;--&lt;168.0,0.0&gt;&gt;

* six (U+0036): L&lt;&lt;528.0,240.0&gt;--&lt;528.0,180.0&gt;&gt; -&gt; L&lt;&lt;528.0,180.0&gt;--&lt;528.0,120.0&gt;&gt;

* six (U+0036): L&lt;&lt;528.0,300.0&gt;--&lt;528.0,240.0&gt;&gt; -&gt; L&lt;&lt;528.0,240.0&gt;--&lt;528.0,180.0&gt;&gt;

* six (U+0036): L&lt;&lt;528.0,312.0&gt;--&lt;528.0,300.0&gt;&gt; -&gt; L&lt;&lt;528.0,300.0&gt;--&lt;528.0,240.0&gt;&gt;

* six (U+0036): L&lt;&lt;528.0,612.0&gt;--&lt;528.0,600.0&gt;&gt; -&gt; L&lt;&lt;528.0,600.0&gt;--&lt;528.0,540.0&gt;&gt;

* u (U+0075): L&lt;&lt;524.0,480.0&gt;--&lt;524.0,120.0&gt;&gt; -&gt; L&lt;&lt;524.0,120.0&gt;--&lt;524.0,0.0&gt;&gt;

* uacute (U+00FA): L&lt;&lt;524.0,480.0&gt;--&lt;524.0,120.0&gt;&gt; -&gt; L&lt;&lt;524.0,120.0&gt;--&lt;524.0,0.0&gt;&gt;

* ucircumflex (U+00FB): L&lt;&lt;524.0,480.0&gt;--&lt;524.0,120.0&gt;&gt; -&gt; L&lt;&lt;524.0,120.0&gt;--&lt;524.0,0.0&gt;&gt;

* udieresis (U+00FC): L&lt;&lt;524.0,480.0&gt;--&lt;524.0,120.0&gt;&gt; -&gt; L&lt;&lt;524.0,120.0&gt;--&lt;524.0,0.0&gt;&gt;

* ugrave (U+00F9): L&lt;&lt;524.0,480.0&gt;--&lt;524.0,120.0&gt;&gt; -&gt; L&lt;&lt;524.0,120.0&gt;--&lt;524.0,0.0&gt;&gt;

* uhungarumlaut (U+0171): L&lt;&lt;524.0,480.0&gt;--&lt;524.0,120.0&gt;&gt; -&gt; L&lt;&lt;524.0,120.0&gt;--&lt;524.0,0.0&gt;&gt;

* umacron (U+016B): L&lt;&lt;524.0,480.0&gt;--&lt;524.0,120.0&gt;&gt; -&gt; L&lt;&lt;524.0,120.0&gt;--&lt;524.0,0.0&gt;&gt;

* uni0122 (U+0122): L&lt;&lt;404.0,165.0&gt;--&lt;405.0,180.0&gt;&gt; -&gt; L&lt;&lt;405.0,180.0&gt;--&lt;405.0,240.0&gt;&gt;

* uni0122 (U+0122): L&lt;&lt;418.0,0.0&gt;--&lt;405.0,0.0&gt;&gt; -&gt; L&lt;&lt;405.0,0.0&gt;--&lt;333.0,0.0&gt;&gt;

* uni0122 (U+0122): L&lt;&lt;524.0,612.0&gt;--&lt;525.0,600.0&gt;&gt; -&gt; L&lt;&lt;525.0,600.0&gt;--&lt;525.0,540.0&gt;&gt;

* uni0122 (U+0122): L&lt;&lt;525.0,360.0&gt;--&lt;525.0,180.0&gt;&gt; -&gt; L&lt;&lt;525.0,180.0&gt;--&lt;525.0,120.0&gt;&gt;

* uni0146 (U+0146): L&lt;&lt;46.0,0.0&gt;--&lt;46.0,360.0&gt;&gt; -&gt; L&lt;&lt;46.0,360.0&gt;--&lt;46.0,480.0&gt;&gt;

* uni1E9E (U+1E9E): L&lt;&lt;210.0,720.0&gt;--&lt;606.0,720.0&gt;&gt; -&gt; L&lt;&lt;606.0,720.0&gt;--&lt;608.0,720.0&gt;&gt;

* uni1E9E (U+1E9E): L&lt;&lt;608.0,0.0&gt;--&lt;606.0,0.0&gt;&gt; -&gt; L&lt;&lt;606.0,0.0&gt;--&lt;360.0,0.0&gt;&gt;

* uogonek (U+0173): L&lt;&lt;524.0,480.0&gt;--&lt;524.0,120.0&gt;&gt; -&gt; L&lt;&lt;524.0,120.0&gt;--&lt;524.0,0.0&gt;&gt;

* uring (U+016F): L&lt;&lt;524.0,480.0&gt;--&lt;524.0,120.0&gt;&gt; -&gt; L&lt;&lt;524.0,120.0&gt;--&lt;524.0,0.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* AE (U+00C6): L&lt;&lt;268.0,360.0&gt;--&lt;268.0,540.0&gt;&gt;/L&lt;&lt;268.0,540.0&gt;--&lt;228.0,360.0&gt;&gt; = 12.528807709151492
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-short-segments">outline_short_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* six (U+0036) contains a short segment B&lt;&lt;408.0,540.0&gt;-&lt;408.0,547.0&gt;-&lt;406.5,557.0&gt;&gt;

* nine (U+0039) contains a short segment B&lt;&lt;165.0,180.0&gt;-&lt;165.0,173.0&gt;-&lt;166.5,163.0&gt;&gt;

* C (U+0043) contains a short segment B&lt;&lt;405.0,540.0&gt;-&lt;405.0,547.0&gt;-&lt;403.5,557.0&gt;&gt;

* G (U+0047) contains a short segment B&lt;&lt;405.0,540.0&gt;-&lt;405.0,547.0&gt;-&lt;403.5,557.0&gt;&gt;

* S (U+0053) contains a short segment B&lt;&lt;226.0,600.0&gt;-&lt;219.0,600.0&gt;-&lt;209.0,598.5&gt;&gt;

* y (U+0079) contains a short segment B&lt;&lt;524.0,-60.0&gt;-&lt;522.0,-65.0&gt;-&lt;517.5,-73.0&gt;&gt;

* cent (U+00A2) contains a short segment L&lt;&lt;167.0,0.0&gt;--&lt;163.0,0.0&gt;&gt;

* section (U+00A7) contains a short segment B&lt;&lt;226.0,600.0&gt;-&lt;219.0,600.0&gt;-&lt;209.0,598.5&gt;&gt;

* Ccedilla (U+00C7) contains a short segment B&lt;&lt;405.0,540.0&gt;-&lt;405.0,547.0&gt;-&lt;403.5,557.0&gt;&gt;

* germandbls (U+00DF) contains a short segment L&lt;&lt;546.0,720.0&gt;--&lt;548.0,720.0&gt;&gt;

* ae (U+00E6) contains a short segment L&lt;&lt;283.0,300.0&gt;--&lt;283.0,314.0&gt;&gt;

* ae (U+00E6) contains a short segment L&lt;&lt;404.0,180.0&gt;--&lt;404.0,166.0&gt;&gt;

* ccedilla (U+00E7) contains a short segment B&lt;&lt;403.0,300.0&gt;-&lt;403.0,307.0&gt;-&lt;401.5,317.0&gt;&gt;

* eth (U+00F0) contains a short segment L&lt;&lt;313.0,630.0&gt;--&lt;325.0,636.0&gt;&gt;

* oslash (U+00F8) contains a short segment B&lt;&lt;582.0,371.0&gt;-&lt;583.0,367.0&gt;-&lt;583.0,360.0&gt;&gt;

* oslash (U+00F8) contains a short segment B&lt;&lt;104.0,108.0&gt;-&lt;103.0,112.0&gt;-&lt;103.0,120.0&gt;&gt;

* yacute (U+00FD) contains a short segment B&lt;&lt;524.0,-60.0&gt;-&lt;522.0,-65.0&gt;-&lt;517.5,-73.0&gt;&gt;

* ydieresis (U+00FF) contains a short segment B&lt;&lt;524.0,-60.0&gt;-&lt;522.0,-65.0&gt;-&lt;517.5,-73.0&gt;&gt;

* Cacute (U+0106) contains a short segment B&lt;&lt;405.0,540.0&gt;-&lt;405.0,547.0&gt;-&lt;403.5,557.0&gt;&gt;

* Cdotaccent (U+010A) contains a short segment B&lt;&lt;405.0,540.0&gt;-&lt;405.0,547.0&gt;-&lt;403.5,557.0&gt;&gt;

* Ccaron (U+010C) contains a short segment B&lt;&lt;405.0,540.0&gt;-&lt;405.0,547.0&gt;-&lt;403.5,557.0&gt;&gt;

* Gbreve (U+011E) contains a short segment B&lt;&lt;405.0,540.0&gt;-&lt;405.0,547.0&gt;-&lt;403.5,557.0&gt;&gt;

* Gdotaccent (U+0120) contains a short segment B&lt;&lt;405.0,540.0&gt;-&lt;405.0,547.0&gt;-&lt;403.5,557.0&gt;&gt;

* uni0122 (U+0122) contains a short segment B&lt;&lt;405.0,540.0&gt;-&lt;405.0,547.0&gt;-&lt;403.5,557.0&gt;&gt;

* Sacute (U+015A) contains a short segment B&lt;&lt;226.0,600.0&gt;-&lt;219.0,600.0&gt;-&lt;209.0,598.5&gt;&gt;

* Scedilla (U+015E) contains a short segment B&lt;&lt;226.0,600.0&gt;-&lt;219.0,600.0&gt;-&lt;209.0,598.5&gt;&gt;

* Scaron (U+0160) contains a short segment B&lt;&lt;226.0,600.0&gt;-&lt;219.0,600.0&gt;-&lt;209.0,598.5&gt;&gt;

* ycircumflex (U+0177) contains a short segment B&lt;&lt;524.0,-60.0&gt;-&lt;522.0,-65.0&gt;-&lt;517.5,-73.0&gt;&gt;

* uni0218 (U+0218) contains a short segment B&lt;&lt;226.0,600.0&gt;-&lt;219.0,600.0&gt;-&lt;209.0,598.5&gt;&gt;

* uni1E9E (U+1E9E) contains a short segment L&lt;&lt;606.0,720.0&gt;--&lt;608.0,720.0&gt;&gt;

* ygrave (U+1EF3) contains a short segment B&lt;&lt;524.0,-60.0&gt;-&lt;522.0,-65.0&gt;-&lt;517.5,-73.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value '4906' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 0 | 16 | 111 | 7 | 102 | 0 | 
| 0% | 0% | 0% | 7% | 47% | 3% | 43% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
