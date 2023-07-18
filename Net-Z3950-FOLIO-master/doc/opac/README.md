This directory is about figuring out how to serve OPAC records. Files:

* `README` -- this file.
* [`z3950-opac-record-syntax.asn1`](z3950-opac-record-syntax.asn1) -- ASN.1 for the Z39.50 OPAC record format, copied from [the consolidated ASN.1 of the standard](https://www.loc.gov/z3950/agency/asn1.html#RecordSyntax-opac) and reformatted for clarity.
* [`sample-opac.xml`](sample-opac.xml) -- sample OPAC record built simply by following the XML Schema at [`yaz/etc/opacxml.xsd`](https://github.com/indexdata/yaz/blob/master/etc/opacxml.xsd)
* [`test-opac.xml`](test-opac.xml) -- a second sample OPAC record, extracted from the `tst_convert4` function in [`yaz/test/test_record_conv.c`](https://github.com/indexdata/yaz/blob/master/test/test_record_conv.c) and reformatted.
* [`Makefile`](Makefile) -- a simple controller for running the XSD validator on the sample XML files.
* [`supporting-opac-records.txt`](supporting-opac-records.txt) -- unstructured notes on how to build in the necessary support.

See also https://docs.google.com/document/d/1xwjrscPFfoCDG6u4efasYn0yjPRZphv-xRpIJneEq0U/edit#
