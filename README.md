# Excel-Metadata
Excel spreadsheet to easily compile simple metadata, according to INSPIRE Metadata Implemening Rules.
The spreadsheet file may be used to easily compile simple metadata according to INSPIRE Metadata Implemening Rules.

Two versions have been implemented:
*English version, conformant to INSPIRE Metadata Implementing Rules
*Italian version, conformant to national metadata specifications (RNDT)

The file is structured into the following sheets
a) Readme 	(this) sheet, containing brief instructions
b) Form	sheet to be used to compile metadata
c) XML	ISO19139 XML representation of the metadata
d) Codelist	codelist and values defined by ISO19115 and/or INSPIRE
e) CSW-T	configuration parameters for CSW endpoint
f) Credits	notes about the author of this file

In "Form" all elements defined by INSPIRE for "discovery" are listed.
The first column (A) is used to show/hide the rows of the form.
Rows where the value is "si" (yes) are shown and may be filled.
Where the value is "no", the correspondent rows are hidden: this is useful for constant values like "contacts" or "language", where the text can be written once and then hidden.

Some cells can be edited as free text: in this case it is sufficient to replace the string with the appropriate text.
In other cases, the cells shall contain values taken from dropdown list.

Cells with dark green background have been filled in with default values; you may leave them as they are (since requested by INSPIRE)

It is useful to start the editing of metadata with "constant" values, like the ones in cyan:
*organisation name
*telephone
*email
*web site
*bounding box (west, east, south, north)
For all these cells, once filled with appropriate values, it is sufficient to write "no" in the first column (A) and then click the "Show\Hide" functionality (Show\Hide).
