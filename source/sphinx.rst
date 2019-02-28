.. _Sphinx:

Sphinx
###################################

Sphinx is a tool for compiling sets of RST files into an HTML website. (You
can also use Sphinx to create many other document formats.)

We will use Sphinx to publish the RST content we created in the previous class
as HTML.

Goals
*********

* To understand the role of Sphinx in building documentation.

* To learn how to organize a Sphinx document and reuse content.

* To build a documentation set with Sphinx.

Readings
*********

* :xref:`Sphinx Overview`
* :xref:`First Steps with Sphinx`
* :xref:`Sphinx and Read the Docs for Technical Writers`

Videos
*******

This videos are very long and detailed.  You don't need to go through it
completely for the purposes of this course. But it's a great resources if
you need to complete real projects in Sphinx. You can also increase the
YouTube speed.

.. raw:: html

  <iframe width="560" height="315" src="https://www.youtube.com/embed/QNHM7q2hLh8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Install Sphinx
****************

.. note:: Installing Sphinx is optional. We can do everything needed online through GitHub and ReadTheDocs

To build your HTML document on your computer, you must install Sphinx.

#. If you are using Windows, you might need to :xref:`Python Install`.

   Depending on your Windows setup, after installation you might need to manually add the Python directory to your path. Try the :xref:`Python Windows Install` for help.

   If you are using a Mac, it's probably installed.

#. :xref:`PIP Install`.

   Depending on your Windows setup, after installation you might need to manually add the PIP directory to your path.

#. Use PIP to install Sphinx. On the command line, enter::

   $ pip install Sphinx

.. note:: If you are using Windows, this might be a frustrating task. If you get stuck, share the error messages and ask for help.

Assignment
*************

|Assignment|


#. Make a fork of :xref:`Get Started Sphinx Repo` in your own GitHub account.

#. Edit the following files for your resume:

   * index.rst 
   * profile.rst 
   * experience.rst
   * skills.rst
   * education.rst

To publish the document, continue with the :ref:`rtd` lesson.
