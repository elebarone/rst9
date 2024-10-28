Section 1
========================================

Section 2
---------------------------------------------

------------------
Subsection 1.1
------------------

This is a *simple* reST document.

This is a bullet point
Another bullet point

1. Numbered list item
2. Another numbered list

.. code-block:: python 
  
  def greet():
  print("Hello, World!")

You can also write math:

.. math::
  
  E = mc^2

Add that to the bottom of your .rst file. Then, anywhere in that file, you can simply type `Python Docs`_ , and at render time, it will automatically be linked.

Paragraphs: Just type your text

Wrap text in single asterisks for italics text:: *italic*

Double asterisks to make it bold: **bold**

Double-backticks for inline “code” formatting: ``code``

Line Breaks: Leave a blank line

`Python Docs <https://docs.python.org>`_

.. note::
  Careful! Don't go overtime!

.. danger::
  This step is dangerous! Be real sure about it!

.. Error::
  Does not compute.

.. attention::
  This step is dangerous! Be real sure about it!

.. caution::
  This step is dangerous! Be real sure about it!
  
.. tip::
  This step is dangerous! Be real sure about it!

::

  Lorem ipsum dolor sit amet, consectetur adipiscing elit. In viverra convallis
  feugiat. Mauris facilisis dolor placerat massa porta vehicula. Vivamus quis
  posuere quam. Sed semper, libero vel tristique tincidunt, metus diam
  pellentesque dolor, congue dignissim nibh ipsum sed dui.

This text will be formatted as usual, meanwhile::

   This passage will become literal block. Lorem ipsum dolor sit amet,
   consectetur adipiscing elit. In viverra convallis
   feugiat. Mauris facilisis dolor placerat massa porta vehicula. Vivamus quis
   posuere quam. Sed semper, libero vel tristique tincidunt, metus diam
   pellentesque dolor, congue dignissim nibh ipsum sed dui.

.. code:: python

    from datetime import datetime
    print(datetime.now())

Add asterisks or numbers in front of each list item. 
Use #. to auto-number the list items.

* Bullet list item 1
* Bullet list item 2
  If the list item text is too long, it can go to the next lin If the list item text is too long, it can go to the next lin If the list item text is too long, it can go to the next lin If the list item text is too long, it can go to the next lin If the list item text is too long, it can go to the next line, like this.

1. Numbered list item 1
2. Numbered list item 2

   1. Nested list item 2
   2. Nested list item 2

#. Autonumbered list item
#. Autonumbered list item

.. This line will not be rendered.

..
   You can have multiline comments, by adding indented text blocks.
   This line will not be rendered.

   This is still a comment.

========  ========  ========
Column A  Column B  Column C
========  ========  ========
row 1A    row 1B    row 1C
row 2A    row 2B    row 2C
========  ========  ========

+----------+----------+----------+
| Column A | Column B | Column C |
+==========+==========+==========+
| row 1A   | row 1B   | row 1C   |
+----------+----------+----------+
| row 2A   | row 2B   | row 2C   |
+----------+----------+----------+

.. csv-table::
   :header: "Column A", "Column B", "Column C"

   "row 1A", "row 1B", "row 1C"
   "row 2A", "row 2B", "row 2C"

.. image:: https://github.com/allegheny-college-cmpsc-104-Fall-2024/classDocs/blob/main/lessons/week9_rst/src/image1.jpg



















  
.. _Python Docs: https://docs.python.org
