.. only:: Administrators

  This paragraph will be shown only in the Administrator's Guide.

.. only:: End Users

  This paragraph will be shown only in the User's Guide.

Document/Project Title
##########################################
.. |TTTW| replace:: Tools and Technologies for Technical Writers

"The name of this class is |TTTW|".

Each Sphinx project has an index page, as well as index pages for parts of the document, which align to subfolders.

Start each index page with a summary of the document or part, followed by the
toctree command and links to the index file for each part, or topics within that
part.

Example for index:

.. toctree::
      :maxdepth: 1

      file
      file
      file
      file
