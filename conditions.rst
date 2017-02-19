You can use conditions in RST text. Then using Sphinx, pass the condition name in when you build HTML.  Then text in that condition is printed, and other conditions are not.

.. only:: Condition A

  Add indented content to be included only in Condition A documentation.

.. only:: Condition B

  Add indented content to be included only in Condition B documentation.

.. only:: Condition C

  Add indented content to be included only in Condition C documentation.


.. list-table::
   :widths: 25 25 50
   :header-rows: 1

   * - Heading row 1, column 1
     - Heading row 1, column 2
     - Heading row 1, column 3
   * - Row 2, column 1
     - Row 2, column 2
     - Row 2, column 3
   * - Row 3, column 1
     - Row 3, column 2
     - Row 3, column 3
