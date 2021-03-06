Template
========

.. note::

   *INSTRUCTIONS*

   1. Use this file as a template to document API.
   2. Change the file name to the name of the header file that represents documented API.
   3. Include respective files with descriptions from the API folder using  ``..include::``

     * README.rst
     * example.rst

   4. Optionally provide description right in this file.
   5. Once done, remove all instructions like this one and any superfluous headers.

Overview
--------

.. note::

   *INSTRUCTIONS*

   1. Provide overview where and how this API may be used. 
   2. Where applicable include code snippets to illustrate functionality of particular functions.
   3. To distinguish between sections, use the following `heading levels <http://www.sphinx-doc.org/en/stable/rest.html#sections>`_:

     * ``#`` with overline, for parts
     * ``*`` with overline, for chapters
     * ``=``, for sections
     * ``-``, for subsections
     * ``^``, for subsubsections
     * ``"``, for paragraphs

Application Example
-------------------

.. note::

   *INSTRUCTIONS*

   1. Provide one or more practical examples to demonstrate functionality of this API.
   2. Break down the code into parts and describe functionality of each part.
   3. Provide screenshots if applicable.

API Reference
-------------

.. note::

   *INSTRUCTIONS*
 
   1. Specify the names of header files used to generate this reference. Each name should be linked to the source on `espressif/esp-idf <https://github.com/espressif/esp-idf>`_ repository.
   2. Provide list of API members divided into sections. 
   3. Use corresponding ``.. doxygen..`` directives, so member documentation is auto updated.

     * Data Structures -``.. doxygenstruct::`` together with ``:members:``
     * Macros - ``.. doxygendefine::``
     * Type Definitions - ``.. doxygentypedef::``
     * Enumerations - ``.. doxygenenum::``
     * Functions - ``.. doxygenfunction::``

     See `Breathe documentation <https://breathe.readthedocs.io/en/latest/directives.html>`_ for additional information. 

   4. Once done remove superfluous headers.
   5. When changes are committed and documentation is build, check how this section rendered. :doc:`Correct annotations <../documenting-code>` in respective header files, if required.

Header Files
^^^^^^^^^^^^

  * `path/header-file.h`

Data Structures
^^^^^^^^^^^^^^^

::

  .. doxygenstruct:: name_of_structure
     :members:

Macros
^^^^^^

::

  .. doxygendefine:: name_of_macro

Type Definitions
^^^^^^^^^^^^^^^^

::

  .. doxygentypedef:: name_of_type

Enumerations
^^^^^^^^^^^^

::

  .. doxygenenum:: name_of_enumeration

Functions
^^^^^^^^^

::

  .. doxygenfunction:: name_of_function


