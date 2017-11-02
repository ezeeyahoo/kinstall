# kinstall
A lightweight alternative to Kext Utility for macOS.

Since kinstall was made in bash it won't take more than a few bytes on your macOS install, but it will do absolutely the same as Kext Utility or Kext Wizard!

# Installing

To install kinstall, use the following code:

`cd /usr/bin && sudo curl https://raw.githubusercontent.com/ArtikusHG/kinstall/master/kinstall --output kinstall`

# Usage

Kinstall has only two simple options:

- Install kext

- Rebuild kext cache

To install a kext, simply run kinstall like that:

`kinstall /path/to/kext/file`

That will install a kext file to /System/Library/Extensions, fix its permissions and rebuild the kext cache.

To only rebuild kext cache, run kinstall like that:

`kinstall rebuild `

# Contributing

Feel free to fork, place a pull request or issue to that small piece of code.