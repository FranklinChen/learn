.. advanced-ada documentation master file.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

:prev_state: False
:next_state: False

Advanced Journey With Ada: A Flight In Progress
===============================================

.. include:: ../global.txt

.. only:: builder_epub

    Release |release|

    |today|

.. only:: builder_latex or builder_epub

    .. container:: content-copyright

        Copyright © 2019 |ndash| 2022, AdaCore

        This book is published under a CC BY-SA license, which means that you
        can copy, redistribute, remix, transform, and build upon the content
        for any purpose, even commercially, as long as you give appropriate
        credit, provide a link to the license, and indicate if changes were
        made. If you remix, transform, or build upon the material, you must
        distribute your contributions under the same license as the original.
        You can find license details
        `on this page <http://creativecommons.org/licenses/by-sa/4.0>`_

        .. image:: ../../images/ccheart_black.png
            :width: 108pt

.. container:: content-description

    .. warning::

        **This is work in progress!**

        Information in this document is subject to change at any time without
        prior notification.  The editors/authors exclude all liability for the
        topicality, correctness, completeness or quality of the information
        provided in this course.

    This course will teach you advanced topics of the Ada programming language.
    The
    :doc:`Introduction to Ada </courses/intro-to-ada/index>`
    course is a prerequisite for this course.

    .. only:: not no_hidden_books

        This document was written by Gustavo A. Hoffmann and Robert A. Duff,
        with contributions from Franco Gasperoni, Gary Dismukes and
        Robert Dewar.

    .. only:: no_hidden_books

        This document was written by Gustavo A. Hoffmann and Robert A. Duff,
        with contributions from Arnaud Charlet, Emmanuel Briot,
        Franco Gasperoni, Gary Dismukes, Javier Miranda, Patrick Rogers,
        Quentin Ochem, Robert Dewar, and Yannick Moy.

    This document was reviewed by Patrick Rogers and Tucker Taft.

.. container:: content-changelog

    .. admonition:: CHANGELOG

        *Release 2023-04*

        - First draft release including following chapters:

            - Data Types
            - Control Flow
            - Modular Programming


.. only:: builder_html

    .. container:: ebook-download

        .. raw:: html

            <a class="ebook-download-button" href="/pdf_books/courses/advanced-ada.pdf">
                Download PDF
            </a>

            <a class="ebook-download-button" href="/epub_books/courses/advanced-ada.epub">
                Download EPUB
            </a>

.. toctree::
    :maxdepth: 4
    :caption: Contents:

    chapters/data_types
    chapters/control_flow
    chapters/modular_prog

.. only:: no_hidden_books

    .. toctree::
        :maxdepth: 4
        :caption: Contents:

        chapters/resource_management
        chapters/abstraction_oriented_prog
        chapters/design_by_contracts
        chapters/initialization
        chapters/multithreading
        chapters/interfacing_external
        chapters/appendices
