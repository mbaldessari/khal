khal
====

*Khal* is a standards based CLI (console) calendar program, able to synchronize
with CalDAV_ servers through vdirsyncer_.

.. image:: http://lostpackets.de/images/khal.png

Features
--------
(or rather: limitations)

- khal can read and write events/icalendars to vdir_, so vdirsyncer_ can be
  used to `synchronize calendars with a variety of other programs`__, for
  example CalDAV_ servers.
- fast and easy way to add new events
- ikhal (interactive khal) lets you browse and edit calendars and events
- support for recurring events is not complete yet, they cannot be deleted or
  edited and some recursion patterns are not understood
- you cannot edit the timezones of events
- khal should run on all major operating systems [1]_

.. [1] except for Microsoft Windows


.. _vdir: https://vdirsyncer.readthedocs.org/en/stable/vdir.html
.. _vdirsyncer: https://github.com/untitaker/vdirsyncer
.. _CalDAV: http://en.wikipedia.org/wiki/CalDAV
.. _github: https://github.com/geier/khal/
.. __: http://en.wikipedia.org/wiki/Comparison_of_CalDAV_and_CardDAV_implementations


Table of Contents
=================

.. toctree::
   :maxdepth: 1

   install
   configure
   usage
   standards
   timezones
   contributing
   changelog
   faq
   license
   news
