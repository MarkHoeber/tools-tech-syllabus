.. _Sphinx:

Sphinx
###################################

Sphinx is a tool for compiling sets of RST files into an HTML document. (You
can also use Sphinx to create many other document formats.)

We will use Sphinx to publish the RST content we created in the previous class
as HTML .

Goals
*********

* To understand the role of Sphinx in building documentation.

* To learn how to organize a Sphinx document and reuse content.

* To build a documentation set with Sphinx.

Readings
*********

* |Sphinx Overview|
* |First Steps with Sphinx|

Videos
*******

.. include:: video_refs/sphinx_intro.txt

.. include:: video_refs/sphinx_tutorial.txt

Install Sphinx
****************

To build your HTML document on your computer, you must install Sphinx.

#. If you are using Windows, you might need to |Python Install|.

   Depending on your Windows setup, after installation you might need to manually add the Python directory to your path. Try the |Python Windows Install| for help.

   If you are using a Mac, it's probably installed.

#. |PIP Install|.

   Depending on your Windows setup, after installation you might need to manually add the PIP directory to your path.

#. Use PIP to install Sphinx. On the command line, enter::

   $ pip install Sphinx

Assignment
*************

|Assignment|

Part 1
=========

#. Make a fork of |Get Started Sphinx Repo| in your own GitHub account.

#. Read the repository ReadMe.

#. Check out your repository on your computer.

#. Open a command prompt and change directories to the ``get_started_sphinx`` directory.

#. Run the command ``make html``.  Check if there are warnings or errors in the command window. There should not be.

#. Check for the HTML output in the ``get_started_sphinx/build/html`` directory.

#. Open the file ``index.html``.

   The page should look like the following image.

   .. image:: images/get_started_sphinx.png
     :width: 600

Make sure you complete these steps with no warnings or errors before proceeding.

Part 2
=========

Look back to the last class on :ref:`RST`. Review the files in |RST Templates Repository|, and the files your created as part of that assignment.

You can use the content of those files.  Add them into the your fork of the repository, or copy the content into the files that are already part of the Sphinx project. The same requirements apply.

When you have added content to RST files in the Sphinx project:

#. Run the command ``make html``.  Check if there are warnings or errors in the command window. Fix those issues.  Use Google, or :xref:`GitHub Issues` if you get stuck.

#. Check for the HTML output in the ``get_started_sphinx/build/html`` directory.

#. Open the file ``index.html``. Check that the content is what you expect.

#. Iterate over these steps until the document is what you intended.

.. include:: snippets/save_github.txt

Extra Credit
***************

* Change the Sphinx theme by changing the value of ``html_theme`` in the
  ``conf.py`` file. Search Sphinx documentation for more information.

* Checkout the |Tools and Technology Repo| (the source for this syllabus).
  Examine how the document is organized. Create a branch and make an
  improvement in this syllabus. Build it locally and ensure it comes out as
  you expect. Then submit a pull request.

Recommended if you intend to do your final project in Sphinx.

.. include:: includes.txt
