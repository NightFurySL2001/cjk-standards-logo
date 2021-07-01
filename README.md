# cjk-standards-logo

This is just a side project to remake the logos of the national standards involved in the decision-making of CJK Unified Ideographs/Unihan in Unicode, and also for me to try and use [AFDKO](https://github.com/adobe-type-tools/afdko/).

The logos are all hand drawn by me, which includes the following:

1. China (PRC), *Guojia Biaozhun* (GB, 国家标准)
2. Taiwan (ROC), Chinese National Standards (CNS, later renamed National Standards of the Republic of China)
3. Japan, Japanese Industrial Standards (JIS) (before 2005)
4. Japan, Japanese Industrial Standards (JIS) (after 2005)
5. South Korea, Korea Standard (KS X)

# Building the font

Please refer to [`build_commands.txt`](build_commands.txt) for the commands used to make the font from `src.otf`.

Be noted that the GB logo is too large to be hinted (mainy due to the greyscale dots) and thus is unhinted in the font file.

# Licensing

All files in this repository are hand-drawn and made by me (the only exception is mentioned below). Thus, I release all the files in this repository under CC0, i.e. public domain or No Rights Reserved.

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <span resource="[_:publisher]" rel="dct:publisher">
    <span property="dct:title">NightFurySL2001</span></span>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">CJK Standards logo</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="MY" about="[_:publisher]">
  Malaysia</span>.
</p>

However, be noted that some images——i.e. the logos of the standards——are still trademark of their owners.

# External sources

Images from Wikimedia Commons [[1]](https://commons.wikimedia.org/wiki/File:GB_logo.png) [[2]](https://commons.wikimedia.org/wiki/File:JIS_mark_old.png) [[3]](https://commons.wikimedia.org/wiki/File:JIS_mark.svg) are used as samples for drawing the logos. For KS, the original drawing guidelines are referred and thus no images are used as sample. For CNS, the logo on [official website](https://www.cnsonline.com.tw/) is screenshot and used as sample.

The letter "C", "N" and "S" in the font is copied from [Aileron](http://dotcolon.net/font/aileron), a CC0 font, which is then scaled 108% to match the size of the logos.

# Unicode assignments

1. China GB is mapped to U+3387 `㎇` SQUARE GB since it is……GB?
2. Taiwan CNS is mapped to U+2618 `☘` SHAMROCK since the CNS logo looks like it.
3. Japan JIS (before 2005) is mapped to U+3004 `〄` JAPANESE INDUSTRIAL STANDARD SYMBOL.
4. South Korea KS is mapped to U+327F `㉿` KOREAN STANDARD SYMBOL.

# OpenType features

1. Japan JIS (after 2005) is set as stylistic set 1 of Japan JIS (before 2005).
2. Taiwan CNS is also a ligature of the word `CNS` as CNS documents often substitute the logo in place of text.

# End note

Thanks are given to Dr. Ken Lunde for his generous help in figuring out how to use AFDKO. [This is the article that I had used when making the font](https://ccjktype.fonts.adobe.com/2011/12/leveraging-afdko-part-1.html) [[2]](https://ccjktype.fonts.adobe.com/2012/01/leveraging-afdko-part-2.html). More articles are available at https://ccjktype.fonts.adobe.com.

Have fun!
