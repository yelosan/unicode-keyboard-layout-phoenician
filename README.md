# Phoenician Keyboard Layout (PHNKL)

The **Phoenician Keyboard Layout** or **PHNKL** is the first Unicode-compliant keyboard layout for the Phoenician Unicode block. Its main feature is the incorporation of the characters commonly used in the following scripts:

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

In addition to the above, the Phoenician Unicode block is currently compatible with a much earlier script than Palæo-Hebrew/Phoenician which is _Ancient Hebrew (a.k.a. Proto-Canaanite; Early Hebrew; Proto-Sinaitic)_, a pictograph script that was in used from 6000 B.C.E. to 1700 B.C.E. As the Ancient Hebrew script is still being deciphered and might have more glyphs the Unicode Consortium in the future may assign a separate block for this.

There are also some exceptions. While the Samaritan script is similar and one of the closely related and surviving writing system to the Palæo-Hebrew/Phoenician family, the Unicode consortium assigned a separate block ([U+0800 to U+083F]) for the Samaritan script. As such, do not use the Phoenician Unicode block when creating a font for or typing in Samaritan.

Lastly, why "Phoenician" and not "Palœo-Hebrew"? Simply because the former was the name chosen by the Unicode Consortium to refer to this Unicode block. As this keyboard project is claiming to be a Unicode-compliant layout, using the name assigned by the Unicode is part of it. If in the future they change the block name to the latter, then this project will implement the same.


### Project info
  * Based on: [Unicode 8.0 (2015-06-17)]
  * Unicode block: [U+10900 to U+1091F]
  * Unicode name: Phoenician
  * Latest version: 1.0.0
  * First release: 2015-07
  * Official website: [https://techmagus.ninja/Paleo-Hebrew-Phoenician-Keyboard-Layout/][0]
  * Git: [https://bitbucket.org/paninap/phnkl][1]
  * Project contact: JC John "Yuki" Sese Cuneta

_A project of [Paninap Services]._


## Layouts
  * [Neo-Paleo Layout]


## OS Compatibility
  * Supported:
    1. All GNU/Linux distribution and flavour with the latest XKB update.
    1. Microsoft® Windows 98 up to Windows 7
  * Not yet supported:
    * Microsoft Windows 8 and Windows 10 - the tool provided by Microsoft for developing keyboard layout still remains incompatible.
    * Apple OS - I do not have a Macintosh to study and convert the project into.
    * ChromeOS - no plans at the moment
  * Will never be supported:
    * Android, iOS, and any other mobile/tablet units
        1. Unicode-compliant keyboard layouts rely on Unicode-compliant fonts. Most fonts that comes with mobile phones/tablets only have the ASCII range and a select few Unicode characters (other than the Emoji Unicode block).
        1. Even if you install a compatible font, if your SMS recipient doesn't have a compatible font, it will not show correctly.
        1. SMS encoding differs from phone-to-phone and network-to-network, which usually leads to messed-up messages if it is beyond the ASCII range.
        1. I would advice looking for an app that provides a temporary typing space so you can copy and paste it in your local documents or browser. But again, it will never work correctly because of the 3 points raised above.


## Instructions
  * [GNU/Linux]
  * [Microsoft Windows]


## License
  * Content license: Creative Commons-Attribution 4.0 International (CC BY-SA 4.0 International License)
  * Code license: Apache 2.0


## Keyboard Layout Images
### Neo-Paleo Layout
![Neo-Paleo Layout in Ancient Hebrew 6000-1700 BCE font]
![Neo-Paleo Layout in Noto Sans Phoenician font]
![Neo-Paleo Layout in Paleo-Hebrew Gezer 1000-901 BCE font]



[U+0800 to U+083F]: http://www.unicode.org/charts/PDF/U0800.pdf "Official Unicode Consortium code chart for Samaritan (PDF)"
[Unicode 8.0 (2015-06-17)]: http://blog.unicode.org/2015/06/announcing-unicode-standard-version-80.html "Announcing The Unicode® Standard, Version 8.0"
[U+10900 to U+1091F]: http://www.unicode.org/charts/PDF/U10900.pdf "Official Unicode Consortium code chart for Phoenician (PDF)"
[0]: https://techmagus.ninja/Paleo-Hebrew-Phoenician-Keyboard-Layout/ "Official PHNKL Page"
[1]: https://bitbucket.org/paninap/phnkl "BitBucket Git Source"
[Paninap Services]: https://bitbucket.org/paninap "Paninap Services Git"
[Neo-Paleo Layout]: http://loveandtruth.net/neopaleo.html "Neo-Paleo Transliteration Scheme for a Neo-Paleo Hebrew Encoding Standard"
[GNU/Linux]: https://techmagus.ninja/Paleo-Hebrew-Phoenician-Keyboard-Layout-Linux/ "GNU/Linux Instructions"
[Microsoft Windows]: https://techmagus.ninja/Paleo-Hebrew-Phoenician-Keyboard-Layout-Windows/ "Microsoft Windows Guide"
[Neo-Paleo Layout in Ancient Hebrew 6000-1700 BCE font]: /images/PHN-Neo_in_Ancient_Hebrew_6000-1700BCE_font.png
[Neo-Paleo Layout in Noto Sans Phoenician font]: /images/PHN-Neo_in_Noto_Sans_Phoenician_font.png
[Neo-Paleo Layout in Paleo-Hebrew Gezer 1000-901 BCE font]: /images/PHN-Neo_in_Paleo-Hebrew_Gezer_1000-901BCE_font.png
