input
=====

Applies correct bindkeys for input events.

Without this module, you may experience oddities in how zsh interprets input.
For example, pressing LEFT and then the DELETE key may capitalize characters
rather than delete them.

Settings
--------

This module also provides double-dot parent directory expansion. It can be
enabled with:

    zstyle ':zim:input' double-dot-expand yes
