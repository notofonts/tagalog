## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[8] NotoSansTagalog-Regular.ttf</summary>
<div>
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
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansTagalog/googlefonts/ttf does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, tai-le, hebrew, tifinagh, todhri, canadian-aboriginal, old-permic, math, syriac, duployan, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>tagalog</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Teke-Ebo (Latn, 260,000 speakers), Mundani (Latn, 34,000 speakers), Ejagham (Latn, 120,000 speakers), Mango (Latn, 77,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Lugbara (Latn, 2,200,000 speakers), Cicipu (Latn, 44,000 speakers), Han (Latn, 6 speakers), Basaa (Latn, 332,940 speakers), Kom (Latn, 360,685 speakers), Fur (Latn, 1,230,163 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Ngbaka (Latn, 1,020,000 speakers), Yala (Latn, 200,000 speakers), Avokaya (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Bafut (Latn, 158,146 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), South Central Banda (Latn, 244,000 speakers), Dii (Latn, 71,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Zapotec (Latn, 490,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Gulay (Latn, 250,478 speakers), Nateni (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Mfumte (Latn, 79,000 speakers), Southern Kisi (Latn, 360,000 speakers), Makaa (Latn, 221,000 speakers), Vute (Latn, 21,000 speakers), Heiltsuk (Latn, 300 speakers), Kaska (Latn, 125 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Sar (Latn, 500,000 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* uni1700 (U+1700) contains a short segment L&lt;&lt;313.0,518.0&gt;--&lt;313.0,504.0&gt;&gt;

* uni1704 (U+1704) contains a short segment L&lt;&lt;811.0,0.0&gt;--&lt;801.0,0.0&gt;&gt;

* uni1705 (U+1705) contains a short segment B&lt;&lt;141.0,44.0&gt;-&lt;141.0,36.0&gt;-&lt;143.0,25.0&gt;&gt;

* uni1705 (U+1705) contains a short segment B&lt;&lt;143.0,25.0&gt;-&lt;145.0,14.0&gt;-&lt;150.0,0.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;426.0,75.0&gt;-&lt;437.0,83.0&gt;-&lt;439.5,87.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;439.5,87.0&gt;-&lt;442.0,91.0&gt;-&lt;442.0,94.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;442.0,94.0&gt;-&lt;442.0,102.0&gt;-&lt;424.0,109.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;391.5,234.0&gt;-&lt;406.0,243.0&gt;-&lt;412.0,246.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;412.0,246.0&gt;-&lt;423.0,253.0&gt;-&lt;432.5,257.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;432.5,257.0&gt;-&lt;442.0,261.0&gt;-&lt;442.0,264.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;442.0,264.0&gt;-&lt;442.0,269.0&gt;-&lt;424.0,276.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;412.0,413.0&gt;-&lt;422.0,419.0&gt;-&lt;432.0,424.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;432.0,424.0&gt;-&lt;442.0,429.0&gt;-&lt;442.0,432.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;442.0,432.0&gt;-&lt;442.0,434.0&gt;-&lt;440.5,436.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;440.5,436.0&gt;-&lt;439.0,438.0&gt;-&lt;432.0,442.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;449.0,357.0&gt;-&lt;434.0,349.0&gt;-&lt;434.0,346.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;434.0,346.0&gt;-&lt;434.0,344.0&gt;-&lt;442.0,340.5&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;442.0,340.5&gt;-&lt;450.0,337.0&gt;-&lt;460.0,332.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;466.0,200.0&gt;-&lt;454.0,193.0&gt;-&lt;444.0,187.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;444.0,187.0&gt;-&lt;434.0,181.0&gt;-&lt;434.0,179.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;434.0,179.0&gt;-&lt;434.0,177.0&gt;-&lt;443.0,174.0&gt;&gt;

* uni1708 (U+1708) contains a short segment B&lt;&lt;443.0,174.0&gt;-&lt;452.0,171.0&gt;-&lt;462.0,166.0&gt;&gt;

* uni170B (U+170B) contains a short segment B&lt;&lt;293.0,406.0&gt;-&lt;292.0,396.0&gt;-&lt;290.0,389.0&gt;&gt;

* uni170E (U+170E) contains a short segment B&lt;&lt;478.0,133.0&gt;-&lt;488.0,139.0&gt;-&lt;488.0,143.0&gt;&gt;

* uni170E (U+170E) contains a short segment B&lt;&lt;467.0,293.5&gt;-&lt;476.0,298.0&gt;-&lt;476.0,301.0&gt;&gt;

* uni170E (U+170E) contains a short segment B&lt;&lt;484.0,229.5&gt;-&lt;480.0,225.0&gt;-&lt;480.0,223.0&gt;&gt;

* uni170E (U+170E) contains a short segment B&lt;&lt;480.0,223.0&gt;-&lt;480.0,220.0&gt;-&lt;489.0,216.5&gt;&gt;

* uni1710 (U+1710) contains a short segment L&lt;&lt;250.0,151.0&gt;--&lt;252.0,151.0&gt;&gt;

* uni171F (U+171F) contains a short segment L&lt;&lt;397.0,308.0&gt;--&lt;408.0,308.0&gt;&gt;

* uni171F (U+171F) contains a short segment B&lt;&lt;161.0,174.0&gt;-&lt;166.0,174.0&gt;-&lt;183.0,177.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;177.0,626.0&gt;--&lt;173.0,626.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;450.0,129.0&gt;--&lt;454.0,129.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Ncaron (U+0147) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Ncaron (U+0147) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* uni0145 (U+0145) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* uni0145 (U+0145) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Q (U+0051) contains a short segment B&lt;&lt;416.0,-9.0&gt;-&lt;410.0,-9.0&gt;-&lt;403.5,-9.5&gt;&gt;

* Q (U+0051) contains a short segment B&lt;&lt;403.5,-9.5&gt;-&lt;397.0,-10.0&gt;-&lt;391.0,-10.0&gt;&gt;

* Uogonek (U+0172) contains a short segment B&lt;&lt;539.5,-158.5&gt;-&lt;551.0,-156.0&gt;-&lt;559.0,-155.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wacute (U+1E82) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wcircumflex (U+0174) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wdieresis (U+1E84) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wgrave (U+1E80) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* a (U+0061) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aacute (U+00E1) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* abreve (U+0103) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* acircumflex (U+00E2) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* adieresis (U+00E4) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* agrave (U+00E0) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* amacron (U+0101) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aogonek (U+0105) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aring (U+00E5) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;613.0,293.0&gt;-&lt;612.0,275.0&gt;-&lt;612.0,267.5&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;612.0,267.5&gt;-&lt;612.0,260.0&gt;-&lt;612.0,257.0&gt;&gt;

* atilde (U+00E3) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* d (U+0064) contains a short segment L&lt;&lt;446.0,72.0&gt;--&lt;442.0,72.0&gt;&gt;

* dcaron (U+010F) contains a short segment L&lt;&lt;446.0,72.0&gt;--&lt;442.0,72.0&gt;&gt;

* dcroat (U+0111) contains a short segment L&lt;&lt;445.0,72.0&gt;--&lt;441.0,72.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;184.0,390.0&gt;-&lt;183.0,380.0&gt;-&lt;183.0,371.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,371.0&gt;-&lt;183.0,362.0&gt;-&lt;183.0,352.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,352.0&gt;-&lt;183.0,343.0&gt;-&lt;183.0,332.5&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,332.5&gt;-&lt;183.0,322.0&gt;-&lt;184.0,311.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;95.0,311.0&gt;-&lt;94.0,323.0&gt;-&lt;94.0,331.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.0,331.0&gt;-&lt;94.0,339.0&gt;-&lt;94.0,352.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.0,352.0&gt;-&lt;94.0,363.0&gt;-&lt;94.5,373.5&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.5,373.5&gt;-&lt;95.0,384.0&gt;-&lt;95.0,390.0&gt;&gt;

* germandbls (U+00DF) contains a short segment B&lt;&lt;382.0,412.0&gt;-&lt;382.0,399.0&gt;-&lt;388.5,388.0&gt;&gt;

* m (U+006D) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* n (U+006E) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* nacute (U+0144) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* ncaron (U+0148) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* uni0146 (U+0146) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* ntilde (U+00F1) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* p (U+0070) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;173.0,463.0&gt;&gt;

* r (U+0072) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* racute (U+0155) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* rcaron (U+0159) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;386.0,633.0&gt;--&lt;382.0,633.0&gt;&gt;

* two (U+0032) contains a short segment L&lt;&lt;159.0,84.0&gt;--&lt;159.0,80.0&gt;&gt;

* u (U+0075) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uacute (U+00FA) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* ucircumflex (U+00FB) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* udieresis (U+00FC) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* ugrave (U+00F9) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uhungarumlaut (U+0171) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* umacron (U+016B) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uogonek (U+0173) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uring (U+016F) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* uni1710 (U+1710): L&lt;&lt;173.0,0.0&gt;--&lt;171.0,566.0&gt;&gt;

* uni1710 (U+1710): L&lt;&lt;248.0,550.0&gt;--&lt;250.0,151.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



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
| 0 | 0 | 1 | 7 | 116 | 6 | 121 | 0 | 
| 0% | 0% | 0% | 3% | 46% | 2% | 48% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
