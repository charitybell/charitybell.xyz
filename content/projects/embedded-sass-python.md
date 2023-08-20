---
title: Embedded SASS host for Python
draft: true
---

The [embedded Sass protocol](https://github.com/sass/sass/blob/main/spec/embedded-protocol.md), implemented for python.

Existing Sass libraries for python use [libsass](https://sass-lang.com/libsass). Libsass is now
deprecated, and the only way to use newer Sass features is to either run the dart sass binary in a subprocess (subprocess
overhead every time the binary is executed), or to use the
embedded Sass protocol (which doesn't have many implementations).

embedded-sass-python is in extremely early in development, currently only supporting the VersionRequest command. The goal
is to eventually provide a not-quite-drop-in replacement for
[libsass-python](https://sass.github.io/libsass-python).

{{< githubstars "charitybell/embedded-sass-python" >}}
