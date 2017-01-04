.. _CSS:

CSS
#########

Most HTML content is formatted and styled with CSS code.

CSS is most heavily used by web designers.  However, because CSS has such a
high impact on how users experience content, it is essential for writers to
have a basic understanding of how it works.

Goals
*********

* Gain a basic understanding of CSS.

* Modify the look and style of your web page with CSS.

Readings
*********

* :xref:`CSS - Wikipedia`

* :xref:`CSS Intro - W3`

* :xref:`Chrome Inspector`

  .. note:: If you prefer to use a different browser, there are equivalent tools.

Videos
*******

.. youtube:: qKoajPPWpmo?list=PLr6-GrHUlVf8JIgLcu3sHigvQjTw_aC9C

.. note::  In the upper left of the video, you'll see a playlist icon.  This
  indicates the video is part of a series.  Click the icon to open the list of
  videos in the series.  View at least the first two.

.. youtube:: nV9PLPFTnkE

Assignment
************

|Assignment|

Find a partner for this assignment.  You should work together, though you only
need to complete these steps for one repository. The goal of this exercise is to learn the mechanics of editing styles in a web page.  It is not a design contest.

Follow the GitHub flow to complete this assignment. You can complete the
assignment through the browser, or through GitHub Desktop and Sublime (or another
text editor).



#. In your ``Get Started HMTL Repo`` edit the ``styles.css`` file.

   .. include:: snippets/master_branch.txt

   .. hint:: Edit the style sheet in one browser tabl, and open the webpage in a separate tab. Refresh the web page each time you commit a change to the style sheet.

#. For the ``nav`` element:

   * Apply a unique color.
   * Create a border around it.
   * Change the background color of the nav so it sticks out on the page.

   .. container:: toggle

     .. container:: header

       Hint

     .. code-block:: html

        nav {
          color: blue;
          border: 1px;
          border-style: solid;
          background-color: yellow;
        }

#. For the ``article`` element:

   * Create a blue border around the ``article``.
   * Change the style of the ``header`` however you see fit.
   * Indent the ``p`` element by 20pt.
   * Add 10pt margins around the article.
   * Add 10pt padding around the article.

   .. container:: toggle

     .. container:: header

       Hint

     .. code-block:: html
 
        nav {
          color: blue;
          border: 1px;
          border-style: solid;
          background-color: yellow;
        }

        article {
          border: 1px;
          border-style: solid;
          border-color: blue;
          padding: 10pt;
          margin: 10pt;
        }

        article header {
          font-style: italic;
        }

        article p {
          margin-left: 20pt;
        }
        

#. For the ``aside`` element:

   * Make the two  ``aside`` elements appear next to each other.
   * Add a 20pt margin on top of the aside elements.
   * Make the ``h2`` smaller than the ``h2`` for ``article``.
   * Indent the ``p`` element.
   * Make the top and left margins 20pt.

   .. container:: toggle

     .. container:: header

       Hint

     .. code-block:: html
 
        aside {
          display: inline-block;
          width: 40%;
          vertical-align: top;
          margin-top: 20pt;
          margin-left: 20pt;
        }

        aside h2 {
          font-size: 16pt;
        }
                

#. For the footer:

   * Add a 1pt solid top border.
   * Make the footer paragraph font 12pt.
   * Align the footer paragraph to the right.

   .. container:: toggle

     .. container:: header

       Hint

     .. code-block:: html
 
        footer {
          border-top: 1pt solid;
        }

        footer p {
          font-size: 12pt;
          text-align: right;
        }
          

#. Continue editing the styles and refreshing the web page until you are
   satisfied.

View Your Work
****************

You now have a styles to enhance your web page. To see the results *before* you merge the style changes to your master branch, follow these instructions..

#. In the repository, open the **Settings** tab.

#. Find the **GitHub Pages** section.

#. For the **Source**, select the branch you are working in.
   
#. Click **Save**.

   The URL of your new website is now listed. Open it.  If you don't like
   something in your web page, edit the ``styles.css`` file again.

   .. hint:: Use Chrome Inspector to experiment with changing styles.


Extra Credit
*************

:xref:`CSS - edX`

Recommended if you intend to do your final project in HTML.

.. include:: includes.txt
