W3C CSS Test Suite Repository (forked by Vivliostyle)
-----------------------------------------------------

This is a fork of [W3C CSS Test Suite Repository](https://github.com/w3c/csswg-test).
See [the original README](https://github.com/w3c/csswg-test/blob/master/README.md) for general information.
 
Vivliostyle.js specific reftests
--------------------------------

[W3C's original repository](https://github.com/w3c/csswg-test) has only manual tests
for paged media specific features. Since [Vivliostyle.js](https://github.com/vivliostyle/vivliostyle.js)
renders pages on screen, these features can be tested by reftests.
We create reference files corresponding to the existing manual tests and
convert those to (Vivliostyle.js specific) reftests.
Those references are commited under vivliostyle/ directory under each spec's directory.
The mapping between the existing tests and the Vivliostyle.js specific references
are currently managed in [Vivliostyle.js repository](https://github.com/vivliostyle/vivliostyle.js).
