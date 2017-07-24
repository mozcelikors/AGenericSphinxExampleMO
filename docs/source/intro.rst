.. toctree::
    :glob:

Introduction
============

*****
Title
*****

Sphinx is an amazing thing! Here is the code.. This is an `inline link <http://thewebblog.net>`_. See the figure from the reference here :ref:`reference-label`. See this table too: :ref:`reference-label2`. You can see that **this is bold text** while *this is italic* and this is ``verbatim, ergo the highlighted text``. This is from the citation [CITATION]_.

.. code-block:: C
    :linenos:

    #include <stdint.h>
    myFunction (void)
    {
        int x;
    }

.. _reference-label: 
.. figure:: https://thomas-cokelaer.info/tutorials/sphinx/_images/stars.jpg
   :width: 200px
   :align: center
   :height: 100px
   :alt: alternate text
   :figclass: align-center

   Figure text


.. here are some comments
   
Now, here is a table:

.. _reference-label2:
.. csv-table:: Table Title
   :header: "name", "firstname", "age"
   :widths: 20, 20, 10

   "Smith", "John", 40
   "Smith", "John Jr.", 20

Aaaand here is a note box:

.. note:: This is a **note** box.

And this is a warning box:

.. warning:: This is a warning box..

And this is a seealso box:

.. seealso:: This is a seealso box..

.. topic:: Your custom Topic Box
	   
   Lorem ipsum etc etc. 

Subtitle
########

subsubtitle
***********

Define citations at the bottom of the page

.. [CITATION] A citations
   (etc etc)
