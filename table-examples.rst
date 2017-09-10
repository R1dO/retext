.. table:: Cells do not span rows or columns

   +-------------+------------------------------------------------------------------------+
   | Header      | If this is 2 rows, it will show the same error                         |
   +=============+========================================================================+
   | single line | All is still good                                                      |
   +-------------+------------------------------------------------------------------------+
   | 1st double  | Next one will break when changing text.                                |
   |             | This line makes sure breakage is not due to an empty line              |
   +-------------+------------------------------------------------------------------------+
   | single line | Will still show a wrong line                                           |
   +-------------+------------------------------------------------------------------------+
   | 2nd double  | Lines are odd again, everything will be fine for the next one          |
   |             |                                                                        |
   +-------------+------------------------------------------------------------------------+
   | single line | Everything ok                                                          |
   +-------------+------------------------------------------------------------------------+
   | double again| DELETE ME for demo of error which removes content as well (even line)  |
   |             | DELETE ME PLEASE To show errors in gridlines on longer lines (odd line)|
   +-------------+------------------------------------------------------------------------+
   | single line | INSERT TEXT to demonstrate content will be removed on really long lines|
   +-------------+------------------------------------------------------------------------+
   | single line | Just to prove it is not due to being the bottom line                   |
   +-------------+------------------------------------------------------------------------+


.. table:: Cells do span rows and columns

   +------------------------+------------+----------+----------+
   | Header row, column 1   | Header 2   | Header 3 | Header 4 |
   | (header rows optional) |            |          |          |
   +========================+============+==========+==========+
   | body row 1, column 1   | column 2   | column 3 | column 4 |
   +------------------------+------------+----------+----------+
   | body row 2             | Cells may span columns.          |
   +------------------------+------------+---------------------+
   | body row 3 {REMOVE ME} | Cells may  | - Table cells       |
   +------------------------+ span rows. | - contain           |
   | body row 4 {ADD TEXT}  |            | - body elements.    |
   +------------------------+------------+---------------------+
   | Row span               | col 2      | column 3 | column 4 |
   | Starting column        +------------+---------------------+
   |                        | col 2      | column 3 | column 4 |
   +------------------------+------------+---------------------+