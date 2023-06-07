CakePHP 5.0.0-RC1 Released
============================

The CakePHP core team is happy to announce the first release candidate for CakePHP
5.0.0. Since the beta2 release the core team has continued to refine,
simplify, and prepare 5.0 for the upcoming future. Some of the highlights of this work include:

* Removing more code that will be deprecated in 4.5.
* Added ``Time`` extensions with translation integrations.
* Adding ``Time`` support to the ORM. Going forward ``time`` type columns will
  be mapped to this type. Additionally, ``date`` type columns will be mapped to
  immutable ``Date`` objects.
* Added support for typed finders. Typed finders allows you to call finders with
  named parameters and have those named parameters runtime typechecked. This
  allows for more expressive finders with no additional boilerplate for
  typechecking.
* Upgrade to PHPUnit 10. This was a challenging upgrade for us, and it may be
  challenging for some applications. If you identify ways that CakePHP
  could make the combined upgrade easier please `open an issue
  <https://github.com/cakephp/cakehp/issues/new>`__.
* Improved layout of development error pages.
* Continued work on the rector rules for 4.5 and 5.0

Finally, the scope for 5.x isn't locked down so if you'd like to see a feature
added please `open an issue
<https://github.com/cakephp/cakephp/issues/new>`__.

New Features
------------

The `migration guide
<https://book.cakephp.org/5/en/appendices/5-0-migration-guide.html>`_ has
a complete list of what's new in 5.0.0. We recommend you give that page a read
when upgrading as it notes the various breaking changes present in 5.0.

How you Can Help
----------------

You can help deliver 5.0 by contributing in one of many ways:

#. Check the `documentation <https://book.cakephp.org/5.0/en/>`_ for mistakes,
   outdated, unclear or broken examples. We've been trying to update the
   documentation as we go, but there are likely examples or sections we've
   missed.
#. Try it out! Give CakePHP 5.0 a test drive in a non-production application.
   We'd love to hear how converting a small application went and what was harder
   than it should have been.
#. File issues for regressions in existing features, or suggest new features.
   Even if those features don't make it into 5.0, we would appreciate community
   input on what should be part of 5.1 and 5.2

Contributors to 5.0.0-beta1
---------------------------

Thank you to all the contributors that have helped since the beta2 release:

* ADmad
* Kevin Pfeifer
* Marcelo Rocha
* Marc Würth
* Mark Scherer
* Mark Story
* mscherer
* ndm2
* othercorey
* Roland Waldner

As always, a huge thanks to all the community members that helped make this
release happen by reporting issues and sending pull requests.

Download a `packaged release on github
<https://github.com/cakephp/cakephp/releases>`_.

.. author:: markstory
.. categories:: news
.. tags:: release,news
