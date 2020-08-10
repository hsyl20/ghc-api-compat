ghc-api-compat
==============

GHC-API isn't stable. Especially since we have been renaming every module to put
them in the ``GHC.*`` namespace (cf `#13009
<https://gitlab.haskell.org/ghc/ghc/issues/13009>`_).

This package aims to make GHC-API transitions easier by mapping old module names to
newer module names, by adding function aliases, etc. Pull requests are welcome!

Build with:

.. code::

   cabal new-build -w /path/to/ghc/HEAD/_build/stage1/bin/ghc
