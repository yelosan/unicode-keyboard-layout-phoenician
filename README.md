# Phoenician Unicode Keyboard Layout (PHNX-UKL)
The **Phoenician Unicode Keyboard Layout** or **PHNX-UKL** is the first Unicode-compliant keyboard layout for the Phoenician Unicode block. Its main feature is the incorporation of the characters commonly used in the following scripts:

  * Ammonite
  * Early Aramaic
  * Old Hebrew dialects
  * Palæo-Hebrew (1000 B.C.E.)
  * Siloam Hebrew
  * Hebrew seals
  * Moabite
  * Phoenician
  * Archaic Phoenician
  * Late Phoenician cursive
  * Phoenician papyri
  * Punic

In addition to the above, the Phoenician Unicode block is currently compatible with a much earlier script than Palæo-Hebrew/Phoenician which is _Ancient Hebrew (a.k.a. Proto-Canaanite; Early Hebrew; Proto-Sinaitic)_, a pictograph script that was in used from 6000 B.C.E. to 1700 B.C.E. As the Ancient Hebrew script is still being deciphered and might have more glyphs, the Unicode Consortium in the future may assign a separate block for this.

There are also some exceptions. While the Samaritan script is similar and one of the closely related and surviving writing system to the Palæo-Hebrew/Phoenician family, the Unicode consortium assigned a separate block ([U+0800…U+083F]) for the Samaritan script. As such, do not use the Phoenician Unicode block when creating a font for or typing in Samaritan.

Lastly, why "Phoenician" and not "Palœo-Hebrew"? Simply because the former was the name chosen by the Unicode Consortium to refer to this Unicode block. As this keyboard project is claiming to be a Unicode-compliant layout, using the name assigned by the Unicode is part of it. If in the future they change the block name to the latter, then this project will implement the same.

### Project info
  * Based on: [Unicode 8.0 (2015-06-17)]
  * Unicode block: [U+10900…U+1091F]
  * Unicode name: Phoenician
  * Latest version: 1.0.0
  * First release: 2015-07
  * Official website: [https://techmagus.ninja/Paleo-Hebrew-Phoenician-Keyboard-Layout/](https://techmagus.ninja/Paleo-Hebrew-Phoenician-Keyboard-Layout/ "Official PHNKL Page")
  * Git: [https://bitbucket.org/paninap/phnx-ukl](https://bitbucket.org/paninap/phnx-ukl "BitBucket Git Source")
  * Project contact: Yahanan 'Yuki' Xie

_A project of [Paninap Services]._

## Fonts
To see the glyphs that you are typing, you will need a Unicode-compliant or mixed-Unicode set of fonts. For more information and download links, visit our [wiki here](https://bitbucket.org/paninap/pukbl/wiki/Fonts "Fonts").

## License
  * Content license: Creative Commons-Attribution 4.0 International (CC BY-SA 4.0 International License)
  * Code license:
      * Copyright © 2010, 2015 JC John Sese Cuneta; [The MIT License](https://bitbucket.org/paninap/pukbl/wiki/License "LICENSE")

## Keyboard Layout Images
### [Neo-Paleo Layout]
There were some keys that were left unassigned. In this, I took literary freedom and assigned a value. These are:

  * Y = yod; so we have Y and I for yod/iod
  * U = uau; so we have U and V for uau/vav
  * F = pe; so we have F and P for pe
  * K = kaf; so we have K and C for kaf/caf

If you would like to master the pure Neo-Paleo Layout, just remember not to use the keys Y; U; F; and K. These were only added in the keyboard layout to help in transitioning to the Neo-Paleo Layout (and eliminate the chance of getting a "missing key" bug report).

I also added 3 Unicode code points for inline directional use. These are:

  * U+2067 (Shift+R): Right-to-Left isolate (invisible marker)
  * U+2066 (Shift+L): Left-to-Right isolate (invisible marker)
  * U+2069 (Shift+.): terminate RTL/LTR isolate markers

Examples:

  1. The title of the book is "⁧𐤌𐤁𐤅𐤀 𐤋 ⁦C++⁩⁩". (n.b. only used an online translation for "An Introduction to C++")
  2. Brother Shaul released a new book entitled "His Name is ⁧𐤉𐤄𐤅𐤔𐤏!⁩".

Without these invisible markers, in the first example, the "C++" will become "++C"; in the second example, the exclamation point "!" will be on the right side not left. Also, you would have to cheat by first typing "C++" or the exclamation point "!" before typing Hebrew just to achieve the correct format (which is not advisable as far as semantics, relationships, and typing-flow are concerned). See http://www.w3.org/International/articles/inline-bidi-markup/.

#### Neo-Paleo layout in Ancient Hebrew 6000-1700 BCE font
![Neo-Paleo Layout in Ancient Hebrew 6000-1700 BCE font](https://bitbucket.org/repo/Kd9xpk/images/1830288730-PHN-Neo_in_Ancient_Hebrew_6000-1700BCE_font.png "Neo-Paleo Layout in Ancient Hebrew 6000-1700 BCE font")

#### Neo-Paleo Layout in Noto Sans Phoenician font
![Neo-Paleo Layout in Noto Sans Phoenician font](https://bitbucket.org/repo/Kd9xpk/images/105382865-PHN-Neo_in_Noto_Sans_Phoenician_font.png "Neo-Paleo Layout in Noto Sans Phoenician font")

#### Neo-Paleo Layout in Paleo-Hebrew Gezer 1000-901 BCE font
![Neo-Paleo Layout in Paleo-Hebrew Gezer 1000-901 BCE font](https://bitbucket.org/repo/Kd9xpk/images/64072058-PHN-Neo_in_Paleo-Hebrew_Gezer_1000-901BCE_font.png "Neo-Paleo Layout in Paleo-Hebrew Gezer 1000-901 BCE font")

## Attributions
### To 𐤉𐤄𐤅𐤄 (Yahuwah) and his son 𐤉𐤄𐤅𐤔𐤏 (Yahushua)
Thank you for the strength and support. You deserve all the glory, honour, praise, and worship, now and forevermore. AHMEIN! 𐤄𐤋𐤋𐤅𐤉𐤄 (HalleluYAH)

### [Neo-Paleo Layout]
This site was shown to me by brother [Ted Walther](https://www.facebook.com/tederific "Ted Walther"), I am very grateful, blessings to you from 𐤉𐤄𐤅𐤄 (Yahuwah) and his son 𐤉𐤄𐤅𐤔𐤏 (Yahushua).

### To all the followers of Aluahim
This Unicode-compliant keyboard layout is for you. I hope it will help in spreading the Besorah of Yahushua and in learning the original Hebrew language.

### Blank Keyboard Layout
By KB_United_States-NoAltGr.svg: [w:en:user:Deadcode]derivative work: DaemonDice (KB_United_States-NoAltGr.svg) [GFDL](http://www.gnu.org/copyleft/fdl.html), [via Wikimedia Commons](https://commons.wikimedia.org/wiki/File%3ABlank_BRSB_Keyboard_Layout.svg)

[U+0800…U+083F]: http://www.unicode.org/charts/PDF/U0800.pdf "Official Unicode Consortium code chart for Samaritan (PDF)"
[Unicode 8.0 (2015-06-17)]: http://blog.unicode.org/2015/06/announcing-unicode-standard-version-80.html "Announcing The Unicode® Standard, Version 8.0"
[U+10900…U+1091F]: http://www.unicode.org/charts/PDF/U10900.pdf "Official Unicode Consortium code chart for Phoenician (PDF)"
[Paninap Services]: https://bitbucket.org/paninap "Paninap Services Git"
[Neo-Paleo Layout]: http://loveandtruth.net/neopaleo.html "Neo-Paleo Transliteration Scheme for a Neo-Paleo Hebrew Encoding Standard"
