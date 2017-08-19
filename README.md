NAME
====

Grammar::ErrorReporting - Error reporting infrastructure for Perl 6 grammars

SYNOPSIS
========

    grammar Parenthized does Grammar::ErrorReporting {
        token TOP { '(' ~ ')' \d+ }
    }
    Parenthized.parse('(123');


DESCRIPTION
===========

Please see the POD in `lib/Grammar/ErrorReporting.pm6` for more documentation.

AUTHOR
======

Moritz Lenz moritz.lenz@gmail.com 

COPYRIGHT AND LICENSE
=====================

Copyright © Moritz Lenz moritz.lenz@gmail.com

License GPLv3: The GNU General Public License, Version 3, 29 June 2007 <https://www.gnu.org/licenses/gpl-3.0.txt>

This is free software: you are free to change and redistribute it. There is NO WARRANTY, to the extent permitted by law.
