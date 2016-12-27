.. _RST:

reStructuredText (RST)
###################################

RST is a text file format used for technical documentation. RST grew out of the Python programming community, but can be used for a wide variety of content (for example, this syllabus.)

Goals
*********

* Learn the basic syntax of RST.
* Edit a page in RST.
* Learn to use Atom packages to improve the RST editing experience.
* Be prepared to create documentation sets in Sphinx.


Readings
*********

* :xref:`RST Wikipedia`
* :xref:`Quick RST`
* :xref:`RST Documentation`

Video
*****************

.. youtube:: hM4I58TA72g


Practice
*************

:xref:`Online RST Writer`

.. note:: Indentation is important in RST. Lots of problems are caused by inconsistent indentation. The only way to learn is to practice and see the results.


Assignment
************

|Assignment|

You can edit RST directly in GitHub. You can also use the GitHub client to get
files on your local computer, and use Sublime or another program to edit.

Part 1 
=========

Lets get familiar with RST.

#. Use :xref:`Online RST Writer` to create a short version of your resume (or
   something else if your prefer). Save it with a unique link and share the link
   in :xref:`GitHub Issues`.

#. Examine the RST files in the ``source`` folder of the :xref:`GitHub Syllabus Repository`. View the **Raw** files. Compare the RST structure to this syllabus.


Part 2 
========

#. Fork the :xref:`RST Templates Repository`.

#. Read all the files in the repository and get familiar with the constructs.

#. In your repository, create a new branch. 

#. In that branch, use the templates to create a documentation set. Edit
   and rename files as needed.

   In those files, use at least:

   * 3 different pages (RST files).

   * 2 levels of headings on each page.

     .. container:: toggle

        .. container:: header

          Hint

        .. code-block:: rst
          
          ######################
          Level 1 - Main Title
          ######################

          Intro text

          ********
          Level 2
          ********

          Section text

          ********
          Level 2
          ********

          Section text

          =======
          Level 3
          =======

          Subsection text

          =======
          Level 3
          =======

          Subsection text

   * One table.

     .. container:: toggle

        .. container:: header

          Hint

        .. code-block:: rst
          
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

   * One ordered list.
   
     .. container:: toggle

        .. container:: header

          Hint

        .. code-block:: rst
          
          #. Step one.

             Text under step one.

          #. Step two.

          #. Step three.

   * One unordered list.

     .. container:: toggle

        .. container:: header

          Hint

        .. code-block:: rst
          
          * Item one.

            Text under item one.

          * Item two.

          * Item three.

   * One code block.

     .. container:: toggle

        .. container:: header

          Hint

        .. code-block:: rst
          
          .. code-block:: HTML

            <html>
               <head/>
               <body>

               </body>
            </html>

   * One external link.

     .. container:: toggle

        .. container:: header

          Hint

        .. code-block:: rst
          
          `CNN Website <http://cnn.com/>`_

        .. note:: There are other, better ways to do this in large projects.

   * One substitution.

     .. container:: toggle

        .. container:: header

          Hint

        .. code-block:: rst
          
           .. |TTTW| replace:: Tools and Technologies for Technical Writers

           "The name of this class is |TTTW|".

   * Two different conditions.

     .. container:: toggle

        .. container:: header

          Hint

        .. code-block:: rst
          
           .. only:: Administrators

             This paragraph will be shown only in the Administrator's Guide.

           .. only:: End Users

             This paragraph will be shown only in the User's Guide.

   * One note and one caution.

     .. container:: toggle

        .. container:: header

          Hint

        .. code-block:: rst
          
           .. note:: You might find this interesting.

           .. caution:: Don't do this.

   * One image.

     .. container:: toggle

        .. container:: header

          Hint

        .. code-block:: rst
          
           .. image:: path/file-name
             :width: 400
             :alt" Image description

.. include:: snippets/save_github.txt

These files will form the basis of your Sphinx project in the :ref:`next lesson <Sphinx>`.

.. include:: includes.txt
