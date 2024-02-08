# Colemak DE Keyboard Layouts for MacOS

This repository hosts modified versions of the Colemak and Colemak Mod-DH layouts. The adaptations were made to incorporate additional characters used in the German language and to make it possible to write German without switching between keyboard layouts.

Original layouts:
- [Colemak](https://en.wikipedia.org/wiki/Colemak)
- [Colemak Mod-DH](https://colemakmods.github.io/mod-dh/)

Note: I personally use mod-dh, but I also created a modification of the original Colemak layout for those who may need it.

## Modifications

- The following special characters have been added: ä, ö, ü, ß, Ä, Ö, Ü, ẞ
  - <kbd>Option</kbd> + <kbd>a</kbd> = ä
  - <kbd>Option</kbd> + <kbd>o</kbd> = ö
  - <kbd>Option</kbd> + <kbd>u</kbd> = ü
  - <kbd>Option</kbd> + <kbd>s</kbd> = ß
  - <kbd>Option</kbd> + <kbd>Shift</kbd> + <kbd>a</kbd> = Ä
  - <kbd>Option</kbd> + <kbd>Shift</kbd> + <kbd>o</kbd> = Ö
  - <kbd>Option</kbd> + <kbd>Shift</kbd> + <kbd>u</kbd> = Ü
  - <kbd>Option</kbd> + <kbd>Shift</kbd> + <kbd>s</kbd> = ẞ
- I also added a second combination for "@":
  - <kbd>Option</kbd> + <kbd>i</kbd> = @

## Installation

To install, simply copy the `Colemak-DE.bundle` file to your Keyboard Layouts directory. There are two possible Keyboard Layouts directories to choose from:

- `/Library/Keyboard Layouts`: Installing to this directory will install the keyboard layout system-wide for all users.
- `~/Library/Keyboard Layouts`: This is your personal user-local keyboard layouts directory.

After installation, you may need to log out of your system and log back in for the keyboard layout to become available in your System Preferences.
