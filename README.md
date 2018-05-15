# GitHub Preamble

This is the GitHub version of the Defence-Force [Oric Software Development Kit](http://osdk.defence-force.org).

It mirrors the [original official version Subversion repository](http://miniserve.defence-force.org/svn/public/pc/tools/osdk/main/) and **does not intend to replace or supersede it** in any way.

Its purpose is to provide a Git interface to the OSDK for those who are more at ease with Git than with Subversion.

For any further information, please refer to the official documentation (cf first link).

Discussions regarding evolution of the OSDK take place on the [Defence-Force forums](http://forum.defence-force.org/index.php).

# Welcome to the OSDK!

The OSDK is a complete cross-development system allowing you to create software for the Oric range of computers<sup>[1](#footnote1)</sup>.

If you are interested in developing your programs for other 6502 based machines than the Oric, you should check cc65.
You are still reading, so I assume that you are still interested in the OSDK. Good.

## System requirements

The platform requirement for the OSDK are pretty minimalistic: It runs on anything that runs Windows, and it is compatible with Wine so you can also run it on Linux<sup>[2](#footnote2)</sup>.

## Licence model

Due to the composite nature of this SDK, it is difficult to give a clear statement such as 'the OSDK is using the ZLib/BSD/GPL/WTFPL licence'.

On the other hand, what you can or cannot do is relatively clear:
- You are free to use the SDK or any part of it to build anything you want, even if you plan to sell the resulting product.
- You are free to modify the source code, fork it, extend it, etc...
- Reselling the actual source code of the SDK or any part of it, is not allowed.

The spirit is simple: Some people have been working for free to provide you with all that, you are free to use it for your own projects (commercial or not), but don't resell other's people work or pretend it was yours.

<a name="footnote1"><sup>1</sup></a>: This includes the Oric 1, Oric Atmos, and Oric Telestrat. OSDK is not compatible with the first, original, machine in the Oric range (the Microtan 65). If you have never heard of Oric before, you can read about it on [Wikipedia](https://en.wikipedia.org/wiki/Oric).

<a name="footnote2"><sup>2</sup></a>: A real Linux port will be available at some point, in the meantime this Wine compatibility should be good enough.
