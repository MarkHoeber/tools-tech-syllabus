.. _XML:

XML
#############################


Goals
*********

* Understand what XML is and its role in writing and publishing content.
* Understand that XML brings *semantic meaning* to content.


Readings
*********

* |XML Tutorial|

* |XML - Wikipedia|

Videos
*******

.. youtube:: Q0k5ySZGPBc

.. youtube:: UqwGSo82cwU

Sublime for XML
***********************

Install the following packages to make it easier to edit XML in Atom.

* |XML-tools Atom|

* |XML Formatter Atom|


Assignment
************

|Assignment|

#. Create a new repository in Github.

#. Create a new branch.

#. Add an XMl file in the branch.

   Look at content you created in an earlier lesson.  Think about how it can be organized by semantic meaning.

   Here are a few examples:

   .. code-block:: XML
     :linenos:

     <page>
       <author>Your name</author>
       <title>The Title</title>
       <abstract>Two sentence abstract.</abstract>
       <body>
         <pargraph>First paragraph</paragraph>
         <pargraph>Second paragraph</pargraph>
       </body>
     </page>


   .. code-block:: XML
     :linenos:

     <people>
       <person>
         <age>3</age>
         <sex>M</sex>
         <name preferred="Joe">Joseph</name>
       </person>
     </people>

#. Add data in the file.

   Use at least 4 elements and one attribute.


.. include:: snippets/save_github.txt


.. include:: includes.txt
