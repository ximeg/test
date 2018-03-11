kableExtra 0.7.0
* Now HTML table will be previewed in Viewer panel
* Added HTML color code support to kableExtra
* Added footnote as a more flexible replacement for add_footnote. Add_footnote 
will be kept maintained for a while. 
* Fixed bug #105: bold/italic/monospace cannot accept T/F as vector
* Added extra_css to cell_spec, row_spec & column_spec
* Fixed bug #88: add_footnote doesn't support full width
* Added hline_after and extra_latex_after to row_spec #101
* Improved warning message for kables not in `html` or `latex`
* Added latex_hline to collapse_rows so users can choose from full, major or none
* Added strikeout and underline to column_spec, row_spec and cell_spec. 
* Added extra_css to column_spec, row_spec and cell_spec.
* Added a vignette about how to copy tables from HTML to Word. 
* Change some read_xml to read_html
* Added scale_from to some spec_tools
* Quite a few minor bug fixes




kableExtra 0.6.1
--------------------------------------------------------------------------------
* Fixed a bug in column_spec width introduced in ver 0.6.0

* Fixed a bug in add_header_above. #90
