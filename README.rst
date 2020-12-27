poutils
=======

poutils is a metapackage to easily install usefull Python tools to use
with po files.


`powrap <https://pypi.org/project/powrap/>`_
--------------------------------------------

Script to fix indentation of given ``.po`` files.


`pospell <https://pypi.org/project/pospell/>`_
----------------------------------------------

Wrapper around hunspell to spell check ``.po`` files.


`pogrep <https://pypi.org/project/pogrep/>`_
--------------------------------------------

A side-by-side grep in ``.po`` files displaying `msgid` on the left
and `msgstr` on the right, usefull to find how a word has already been
translated.


`potodo <https://pypi.org/project/potodo/>`_
--------------------------------------------

A tool to find in which ``.po`` file work is needed (untranslated and
fuzzy are reported).

Can sync with github issues to tell which file have already an issue
opened, hint that the file may currently been translated by someone
else.


`pomerge <https://pypi.org/project/pomerge/>`_
----------------------------------------------

A "translation memory" CLI tool, usefull for example to backport
translation from a branch to another, or simply to replicate known
translations from a bunch of file to other files.


`padpo <https://pypi.org/project/padpo/>`_
------------------------------------------

Linter for gettext files (``*.po``) including Grammalecte,
non-breakable space checks, glossary checks etc ...
