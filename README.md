ArchivesSpace EAD2PDF
--------------------
A customized version of [ead2pdf](https://github.com/archivesspace/ead2pdf) which includes [Rockefeller Archive Center's](https://github.com/RockefellerArchiveCenter) logo instead of the default [ArchivesSpace](https://github.com/archivesspace) one.

This is a basic little script to convert EAD files into PDFs.
It uses a slightly tweaked XSLT developed by Winona Salesky, using the Apache FO library
to convert XML into PDF.

It requires JRuby.

To run, simply use java -jar ead2pdf.jar EAD_INPUT_FILE PDF_OUTPUT_FILE [ XSLT_FILE ( option ) ]

To develop, make your edits, have warbler installed, and then "warble"
