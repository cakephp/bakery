CakePHP 5.0.0-beta2 Released
============================

The CakePHP core team is happy to announce the second beta release of CakePHP
5.0.0. Since the beta1 release the core team has continued to refine and
simplify the framework. Some of the highlights of this work include:

* Removing more code that was deprecated in 4.x.
* Adding namespaces to all the global functions that CakePHP provides. This
  enables application code to define their own global function names or use the
  global function shims provided by CakePHP.
* Added support for PSR-17 HTTP factories interfaces.
* Improved the runtime deprecation coverage to include all documentation only
  deprecations.
* Begun work on the rector rules for 4.5 and 5.0
* Added a Time only object to Chronos (will be added to CakePHP soon).

Finally, the scope for 5.x isn't locked down so if you'd like to see a feature
or breaking change made please `open an issue
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

Thank you to all the contributors that have helped since the beta1 release:

* ADmad
* Alejandro Ibarra
* Andrii Pukhalevych
* andrii-pukhalevych
* Brad McNaughton
* Brian French
* Chris Hallgren
* Edgaras Janušauskas
* Erwane Breton
* fabsn182
* Jamison Bryant
* Jaro Varga
* J.Brabec
* Jose Daian
* Kevin Pfeifer
* Marc Würth
* Mark Scherer
* Mark Story
* Matthias Wirtz
* Mikkel Bonde
* Nicos Panayides
* othercorey
* saeideng

As always, a huge thanks to all the community members that helped make this
release happen by reporting issues and sending pull requests.

Download a `packaged release on github
<https://github.com/cakephp/cakephp/releases>`_.

.. author:: markstory
.. categories:: news
.. tags:: release,news
