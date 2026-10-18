This module requires version 0.2.2 of the
[ofxparse2](https://pypi.org/project/ofxparse2/) Python distribution.

`ofxparse2` is a maintained fork selected because OFX statements issued by
Banco do Brasil are not compatible with the original `ofxparse` distribution.
The fork preserves the `ofxparse` Python import namespace, so the addon and its
Odoo external dependency check intentionally continue to import and declare
`ofxparse`.
