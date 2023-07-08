# EliIncludeDemo

This is a tiny parser definition to help track down problems with Include file processing.

The parser can be generated with:

```eli "nctable.specs:exe >test/nctable"```

and can be tested with:

```
$ cd test
$ ./nctable flat.tbl # to demonstrate operation without Include
$ ./nctable top.tbl # to demonstrate operating with Include
```

