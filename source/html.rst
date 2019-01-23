HTML
############

Most of the content we deliver on line is in HTML - the language of the World
Wide Web.  

In later lessons, we will use a variety of tools that make creating HTML much
easier. Thee other tools allow you to write content in a simpler format, then
*transform* the content into HTML for delivery to your users.

As we'll see, creating HTML directly can be tedious. Although other tools help
us avoid the verbosity of HTML, it is very helpful to know HTMl basics, which
is why we start the course working directly with HTML.


Goals
*********

* Understand the purpose and history of HTML 5.

* Become comfortable editing HTML 5.

* Learn to create a fork of a repository and make changes to your copy.

* Publish your own web page.


Readings
*********

* :xref:`HTML 5 - Wikipedia`

* :xref:`HTML Intro - W3`


Videos
*******

.. raw:: html

  <iframe width="560" height="315" src="https://www.youtube.com/embed/x4OKqZ2kIx4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

.. raw:: html

  <iframe width="560" height="315" src="https://www.youtube.com/embed/-USAeFpVf_A" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Assignment
************

|Assignment| 

Follow the GitHub flow, described in the :doc:`previous lesson <github>`, to
complete this assignment. You can complete the assignment through the browser,
or through GitHub Desktop and Sublime (or another text editor).

#. Make a fork of :xref:`Get Started HMTL Repo` in your own GitHub account.

#. In your new repository, edit the ``index.html`` file.

   .. include:: snippets/master_branch.txt

#. Give the page a title. Use an ``h1`` tag at the start of the ``body``.

   .. container:: toggle

     .. container:: header

       Hint

     .. code-block:: html
       :emphasize-lines: 2

        <body>
          <h1>Page Title</h1>
          <header>
            <nav>
              <ul>
                <li>Article 1</li>
                <li>Article 2</li>
              </ul>
            </nav>
          </header>

#. In the two ``article`` elements, add something about yourself, with a title
   and description.

   .. container:: toggle

     .. container:: header

       Hint

     .. code-block:: html
       :emphasize-lines: 4, 6, 11, 13

        <section> 
          <article>
            <header>
              <h2>First thing about you</h2>
            </header>
            <p>I love writing HTML.</p>
          </article>
          
          <article>
            <header>
              <h2>Second thing about you</h2>
            </header>
            <p>I love GitHub.</p>
          </article>
        </section>

#. Upload a photo to your GitHub repository.


#. In the first ``aside``, add a picture and description.

   .. container:: toggle

     .. container:: header

       Hint

     .. code-block:: html
       :emphasize-lines: 3

        <aside>
          <h2>My Photo</h2>
          <p><img src="photo.jpg"/></p>
          <p>My LinkedIn photo.</p>
        </aside>
   
#. In the second ``aside``, add your favorite quotation.

   .. container:: toggle

     .. container:: header

       Hint
   
     .. code-block:: html
       :emphasize-lines: 3

        <aside>
          <h2>Unknown</h2>
          <p><emphasis>"We overestimate what we can do in the short term, and underestimate what we can do in the long term."</emphasis></p>
        </aside>

#. Add an ``id`` attribute to each ``article`` element.

   .. container:: toggle

     .. container:: header

       Hint

     .. code-block:: html
       :emphasize-lines: 1

        <article id="article1">
          <header>
            <h2>First thing about you</h2>
          </header>
          <p>Add paragraphs and lists here.</p>
        </article>

#. In the ``nav`` element, change the text of the link to match the article
   titles, and add links to each ID. See :xref:`HMTL Links` for more information.

   .. container:: toggle

     .. container:: header

       Hint

     .. code-block:: html
       :emphasize-lines: 4

        <header>
          <nav>
            <ul>
              <li><a href="#article1">Article 1</a></li>
              <li>Article 2</li>
            </ul>
          </nav>
        </header>

#. Commit the file to the master branch in GitHub.

   Normally we would commit to a different branch, to review before merging to master. But in this lesson, as you own the repository, you can commit directly to master, so you can see the results in your GitHub page for the repository.

View Your Work
****************

You now have a web page that you, and your friends and family, can view.

#. In the repository, open the **Settings** tab.

#. Find the **GitHub Pages** section.

#. For the **Source**, select **master branch**.
   
#. Click **Save**.

   The URL of your new website is now listed. Open it.  If you don't like
   something in your web page, edit the ``index.html`` file again.

Extra
****************

:xref:`HTML 5 - edX`

Recommended if you intend to do your final project in HTML.

