# Phoenician Unicode Keyboard Layout (PHNX-UKL)

The **Phoenician Unicode Keyboard Layout** or **PHNX-UKL** is the first Unicode-compliant keyboard layout for the Phoenician Unicode block. Its main feature is the incorporation of the characters commonly used in various ancient Western Asian writing scripts.

- Ammonite
- Early Aramaic
- Old Hebrew dialects
- Palæo-Hebrew (1000 B.C.E.)
- Siloam Hebrew
- Hebrew seals
- Moabite
- Phoenician
- Archaic Phoenician
- Late Phoenician cursive
- Phoenician papyri
- Punic

In addition to the above, the Phoenician Unicode block is also compatible with a much earlier script than Palæo-Hebrew/Phoenician which is *Ancient Hebrew (a.k.a. Proto-Canaanite; Early Hebrew; Proto-Sinaitic)*, a pictograph script which was in used from 6000 B.C.E. to 1700 B.C.E. As the Ancient Hebrew script is still being deciphered and might have more glyphs, the Unicode Consortium in the future may assign a separate block for this.

There are also some exceptions. While the Samaritan script is similar and one of the closely related and surviving writing system to the Palæo-Hebrew/Phoenician family, the Unicode consortium assigned a separate block ([U+0800…U+083F](https://www.unicode.org/charts/PDF/U0800.pdf)) for the Samaritan script. As such, do not use the Phoenician Unicode block when creating a font for or typing in Samaritan.

Lastly, why "Phoenician" and not "Palœo-Hebrew"? Simply because the former was the name chosen by the Unicode Consortium to refer to this Unicode block. As this keyboard project is a Unicode-compliant layout, using the name assigned by the Unicode is part of it. If in the future they change the block name to the latter, then this project will implement the same.

### Project info

- Based on: [Unicode 8.0](https://blog.unicode.org/2015/06/announcing-unicode-standard-version-80.html) (2015-06-17)
- Unicode block: [U+10900…U+1091F](https://www.unicode.org/charts/PDF/U10900.pdf)
- Unicode name: Phoenician
- Latest version: 1.0.0
- First release: 2015-07-19
- Official website: [https://im.youronly.one/techmagus/projects/keyboard/paleo-hebrew-phoenician-unicode-keyboard-2015200/](https://im.youronly.one/techmagus/projects/keyboard/paleo-hebrew-phoenician-unicode-keyboard-2015200/)
- Git: [https://codeberg.org/yelosan/unicode-keyboard-layout-phoenician](https://codeberg.org/yelosan/unicode-keyboard-layout-phoenician)
- Project contact: [techmagus](https://im.youronly.one/p/contact-us/)

*A project of [Yelosan Publishing](https://yelosan.youronly.one).*

## Fonts

To see the glyphs that you are typing, you will need a Unicode-compliant or mixed-Unicode set of fonts. For more information and download links, visit our [wiki here](https://codeberg.org/yelosan/unicode-keyboard-layout-phoenician/wiki/Fonts).

## License

- Content License: Creative Commons-Attribution 4.0 International (CC BY-SA 4.0 International License)
- Code Copyright and License:
  - Copyright © 2015, 2016, 2018 JC John Sese Cuneta.
  - Copyleft 🄯 2015, 2016, 2018 JC John Sese Cuneta. [The MIT License](https://codeberg.org/yelosan/unicode-keyboard-layout-phoenician/src/branch/main/LICENSE)

## Keyboard Layout Images

### Neo-Paleo Layout

There were some keys which were left unassigned, what I did was assign a value. These are:

- Y = yod; so we have Y and I for yod/iod
- U = uau; so we have U and V for uau/vav
- F = pe; so we have F and P for pe
- K = kaf; so we have K and C for kaf/caf

If you would like to master the pure Neo-Paleo Layout, just remember not to use the keys Y; U; F; and K. These were only added in the keyboard layout to help in transitioning to the Neo-Paleo Layout (and eliminate the chance of getting a "missing key" bug report).

I also added 3 Unicode code points for inline directional use. These are:

- U+2067 (Shift+R): Right-to-Left isolate (invisible marker)
- U+2066 (Shift+L): Left-to-Right isolate (invisible marker)
- U+2069 (Shift+.): terminate RTL/LTR isolate markers

Examples:

- The title of the book is: ⁧𐤌𐤁𐤅𐤀 𐤋 ⁦C++⁩⁩ ("An Introduction to C++")
- My name in Hebrew is ⁧𐤉𐤅𐤇𐤍𐤍!⁩ (Yahuhanan)

Without these invisible markers, in the first example, the "C++" will become "++C"; in the second example, the exclamation point "!" will be on the right side not left. Also, you would have to cheat by first typing "C++" or the exclamation point "!" before typing Hebrew just to achieve the correct format (which is not advisable as far as semantics, relationships, and typing-flow are concerned). See [https://www.w3.org/International/articles/inline-bidi-markup/](https://www.w3.org/International/articles/inline-bidi-markup/).

#### Neo-Paleo layout in Ancient Hebrew 6000-1700 BCE font

![Neo-Paleo Layout in Ancient Hebrew 6000-1700 BCE font](https://codeberg.org/yelosan/unicode-keyboard-layout-phoenician/raw/branch/main/images/PHNX-Neo_in_Ancient_Hebrew_6000-1700BCE_font.png "Neo-Paleo Layout in Ancient Hebrew 6000-1700 BCE font")

#### Neo-Paleo Layout in Noto Sans Phoenician font

![Neo-Paleo Layout in Noto Sans Phoenician font](https://codeberg.org/yelosan/unicode-keyboard-layout-phoenician/raw/branch/main/images/PHNX-Neo_in_Noto_Sans_Phoenician_font.png "Neo-Paleo Layout in Noto Sans Phoenician font")

#### Neo-Paleo Layout in Paleo-Hebrew Gezer 1000-901 BCE font

![Neo-Paleo Layout in Paleo-Hebrew Gezer 1000-901 BCE font](https://codeberg.org/yelosan/unicode-keyboard-layout-phoenician/raw/branch/main/images/PHNX-Neo_in_Paleo-Hebrew_Gezer_1000-901BCE_font.png "Neo-Paleo Layout in Paleo-Hebrew Gezer 1000-901 BCE font")

## Attributions

### To 𐤉𐤄𐤅𐤄 (Yahuwah) and his son 𐤉𐤄𐤅𐤔𐤏 (Yahushua)

Thank you for the strength and support. You deserve all the glory, honour, praise, and worship, now and forevermore. AHMEIN! 𐤄𐤋𐤋𐤅𐤉𐤄 (HalleluYAH)

### Neo-Paleo Layout

This site, [Neo-Paleo Layout](https://loveandtruth.net/neopaleo.html), was shown to me by brother [Ted Walther](https://www.facebook.com/tederific), I am very grateful, blessings to you from 𐤉𐤄𐤅𐤄 (Yahuwah) and his son 𐤉𐤄𐤅𐤔𐤏 (Yahushua).

### To all the followers of Aluahim

This Unicode-compliant keyboard layout is for you. I hope it will help in spreading the Besorah of Yahushua and in learning the original Hebrew language.

### Blank Keyboard Layout

The keyboard layout shown in the images were:

- Based on: [KB United States-NoAltGr.svg](https://commons.wikimedia.org/wiki/File:KB_United_States-NoAltGr.svg)
- By: DaemonDice
- Source: [Blank BRSB Keyboard Layout.svg](https://commons.wikimedia.org/wiki/File%3ABlank_BRSB_Keyboard_Layout.svg)
