# Mix - A Python Utility

Easily make files harder to read for transmission. Not a cryptographic tool, just useful when sending things like zip archives of code to people via email, as Google has now started blocking these kind of archives for security reasons.

*Requires Python 3, written and tested in Python 3.5.2*

Usage: python3 mix.py mix/unmix

Description:
  - Mixes a file up non-cryptographically
    so that it can pass cursory checks of filetype.
  - No bytemask will greatly aid speed, but
    a bytemask will disguise plaintext for you.
  - Currently only works with files that can
    fit in your computer's ram. Could (and will eventually)
    be modified to work on any size.

Options:
- ```-b/--bytemask: <xor byte mask 8 bits> #eg 10010100```
- ```-o/--dst: <file output path>```
- ```-h/--help: #this help```
- ```-i/--src: <file input path>```

