0.2.3 (unreleased)
------------------

BUG FIXES:

* Fix project URL in ``setup.py``. [GH-49]
* Fix loss of precision during Java serialization. [GH-53]

0.2.2 (October 24, 2014)
------------------------

IMPROVEMENTS:

* Supplant ``--nimbus`` option with ``--nimbus-host`` and ``--nimbus-port``. [GH-35]
* Miscellaneous Python 3 compatibility improvements. [GH-37]
* Updates to ``README.rst`` and documentation.

BUG FIXES:

* Fix long integer serialization issue. [GH-48]

0.2.1 (October 17, 2014)
------------------------

IMPROVEMENTS:

* Rename ``--nimbus-ip`` option to ``--nimbus``. [GH-2]
* Improve Java code style. [GH-4]
* Add explicit dependency on ``virtualenv``. [GH-21]
* Updates to README.rst and documentation.

BUG FIXES:

* Fix ``pyleus build`` on case-insensitive filesystems. [GH-22]
* Fix installation of base JAR on some systems. [GH-24]

0.2 (October 15, 2014)
----------------------

* Initial open-source release