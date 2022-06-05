# Nabatean Keyboard Layout
A basic Mac keyboard layout for typing Nabatean characters from the Unicode range 10880—108AF. This layout uses the preinstalled layout "Syriac – Arabic" as a starting point, so the placement of equivalent consonants should be familiar to those who type Arabic or Syriac.

**⚠️ This keyboard layout merely provides a method to insert the characters currently in the Unicode range for Nabatean.** It does not provide any additional characters or features. 

**⚠️ Specifically, connecting letters are a feature of the Nabatean script but typed characters cannot be connected.** This keyboard layout does not provide any way to connect letters, since (as far as I know), Unicode and font support for connecting letters in Nabatean is currently lacking.

This layout was created with the [Ukelele](https://software.sil.org/ukelele/) keyboard layout editor.

**Note:** Access final consonants and the numbers 20 and 100 by pressing the `Shift` key.
## Getting Started
**Mac OS:** 
 1. Download and unzip the latest release from https://github.com/nathangibson/nabatean-keyboard/releases. Copy the file `nabatean.bundle` to either `"~/Library/Keyboard Layouts"` or `"/Library/Keyboard Layouts"`.
 2. Go to System Preferences > Keyboards > Input Sources. Click the + button and select "Aramaic (Nabatean)" from the list. Click "Add". All done!

**Windows:** A Windows version is not yet available.
## Keyboard Layout
<img width="930" alt="keyboard-layout" src="https://raw.githubusercontent.com/nathangibson/nabatean-keyboard/main/images/keyboard-layout.png">

**Final Letters and Additional Numbers with the `Shift` Key**

<img width="930" alt="keyboard-layout-shift" src="https://raw.githubusercontent.com/nathangibson/nabatean-keyboard/main/images/keyboard-layout-shift.png">

## What is the Nabatean Aramaic alphabet?
Nabatean (or Nabataean) Aramaic was used by the ancient Nabatean people. It has survived in inscriptions, most famously at Petra, Jordan. See https://en.wikipedia.org/wiki/Nabataean_alphabet and https://en.wikipedia.org/wiki/Nabataean_Aramaic.

## Unicode & Fonts
The Unicode range for Nabatean is 10880—108AF. See https://en.wikipedia.org/wiki/Nabataean_(Unicode_block).

Fonts supporting the Nabatean range of characters include:
- [Noto Sans Nabatean](https://fonts.google.com/noto/specimen/Noto+Sans+Nabataean)
- [Everson Mono](https://evertype.com/emono/)

## Comparison of Typed Nabatean with Inscription
Here you can see an example of the difference between a real inscription with connected and typed Nabatean (currently without letter-connecting features).

**Umm al-Jimal Inscription**
| Tracing by [Sabulhab (Wikimedia Commons)](https://commons.wikimedia.org/wiki/File:Umm_al-Jimal_al-Awwal_commons.jpg) | Typed |
| -- | -- |
| <a title="Sabulhab, CC BY-SA 3.0 &lt;https://creativecommons.org/licenses/by-sa/3.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Umm_al-Jimal_al-Awwal_commons.jpg"><img width="256" alt="Umm al-Jimal al-Awwal commons" src="https://raw.githubusercontent.com/nathangibson/nabatean-keyboard/main/images/umm-al-jimal-al-awwal.jpg"></a> | <img width="256" alt="keyboard-layout-shift" src="https://raw.githubusercontent.com/nathangibson/nabatean-keyboard/main/images/umm-al-jimal-al-awwal-typed.jpg"> |

## Known Issues
Please feel free to contribute with a fork and pull request! Edits to the layout can be done in [Ukelele](https://software.sil.org/ukelele/).
- https://github.com/nathangibson/nabatean-keyboard/issues/3 Port for Windows
- https://github.com/nathangibson/nabatean-keyboard/issues/1 Add ligature support for final consonants
- https://github.com/nathangibson/nabatean-keyboard/issues/2 Add icon
