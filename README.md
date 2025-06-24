[![Actions Status](https://github.com/Raku-L10N/JA/actions/workflows/linux.yml/badge.svg)](https://github.com/Raku-L10N/JA/actions) [![Actions Status](https://github.com/Raku-L10N/JA/actions/workflows/macos.yml/badge.svg)](https://github.com/Raku-L10N/JA/actions) [![Actions Status](https://github.com/Raku-L10N/JA/actions/workflows/windows.yml/badge.svg)](https://github.com/Raku-L10N/JA/actions)

NAME
====

L10N::JA - Japanese localization of Raku

SYNOPSIS
========

    $ ryuuu -e '言う "こんにちは世界"'
    こんにちは世界

```raku
use L10N::NL;
言う "こんにちは世界";
```

DESCRIPTION
===========

The `L10N::JA` distribution contains the logic to provide a Japanese localization of the Raku Programming Language. It installs a `ryuuu` executable that will automatically activate the Japanese localization. And it allows one to use the Japanese localization in selected programs with a `use L10N::JA` statement.

REFERENCES
==========

[Ryuuu - a Japanese dragon](https://dev.to/finanalyst/ryuu-a-japanese-dragon-2e7m)

AUTHORS
=======

Richard Hainsworth <rnhainsworth@gmail.com>

COPYRIGHT AND LICENSE
=====================

Copyright 2024, 2025 Raku Localization Team

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

