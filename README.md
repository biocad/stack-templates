stack-templates
===============

This repository contains custom [stack](http://haskellstack.org) templates for Biocad.

Usage:

```console
$ stack new bio-something biocad/biocad-library # for libraries
$ stack new bio-something biocad/biocad-exe # for executables
```

This will create a sample project with `stack.yaml` pointing to our custom resolver and with
`package.yaml` filled with basic info and default GHC flags.
