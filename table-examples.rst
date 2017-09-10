.. table:: Cells do not span rows or columns

   +--------+---------------------------------------------------------+
   | Header | If this is 2 rows, it will show the same error          |
   +========+=========================================================+
   | single | All is still good                                       |
   +--------+---------------------------------------------------------+
   | double | Next one will break when changing text.                 |
   |        | Make sure breakage is not due to an empty line          |
   +--------+---------------------------------------------------------+
   | single | Will still show a wrong line                            |
   +--------+---------------------------------------------------------+
   | double | Lines are odd again, next one will be fine              |
   |        |                                                         |
   +--------+---------------------------------------------------------+
   | single | Everything ok                                           |
   +--------+---------------------------------------------------------+
   | double | DELETE ME to remove content as well (even line)         |
   |        | DELETE ME PLEASE to show errors in gridlines (odd line) |
   +--------+---------------------------------------------------------+
   | single | INSERT TEXT to remove content when a line is long       |
   +--------+---------------------------------------------------------+
   | single | Just to prove it is not due to being the bottom line    |
   +--------+---------------------------------------------------------+


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