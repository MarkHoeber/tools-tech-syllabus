.. _XML:

XML
####

XML is very much like HTML in that it consists of content within markup tags
(that is, ``<tag>content</tag>``).

In fact, HTML is an specific implementation of XML, meaning it has a set list
of defined tags and rules. In XML-speak, HTML has its own schema. A schema is
a set of rules for a specific type of XMl document.

XML itself allows you to create a schema for specific needs, so
people can create their own documents based on that schema.  HTML is one
example. DITA, which we'll learn about next, is another schema that is
commonly used in technical writing.

Goals
*********

* Understand what XML is and its role in writing and publishing content.

* Understand that XML brings *semantic meaning* to content.

Readings
*********

* :xref:`XML Tutorial`

* :xref:`XML Wikipedia`

Videos
*******

.. youtube:: Q0k5ySZGPBc

.. youtube:: UqwGSo82cwU



Assignment
************

|Assignment|

#. Create a new repository in Github.

#. Create a new branch.

#. Add an XMl file in the branch.

   Look at content you created in an earlier lesson.  Think about how it can be organized by semantic meaning.

   .. container:: toggle

     .. container:: header

       Examples

     .. code-block:: XML

       <page>
         <author>Your name</author>
         <title>The Title</title>
         <abstract>Two sentence abstract.</abstract>
         <body>
           <paragraph>First paragraph</paragraph>
           <paragraph>Second paragraph</paragraph>
         </body>
       </page>


     .. code-block:: XML

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


.. note:: 
  In this exercise, we did not use a schema.  That is, there were no rules the
  data had to follow (other than the basic XML syntax and rules such as
  closing tags.) So we did not *validate* the XML against rules.  In the next
  lesson, we will start using DITA, which will enforce certain rules on the
  structure of your content.
