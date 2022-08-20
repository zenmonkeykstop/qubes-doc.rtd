========================
Qubes R3.2 release notes
========================

New features since 3.1
======================

-  Management Stack extended to support in-VM configuration -
   `documentation </doc/salt/>`__
-  PV USB - `documentation </doc/usb/>`__
-  Dom0 update to Fedora 23 for better hardware support
-  Kernel 4.4.x
-  Default desktop environment switched to Xfce4
-  KDE 5 support (but it is no longer the default one)
-  Tiling window managers support: awesome, `i3 </doc/i3/>`__
-  More flexible Qubes RPC services - `related
   ticket <https://github.com/QubesOS/qubes-issues/issues/1876>`__,
   `documentation </doc/qrexec/#service-policies-with-arguments>`__

You can get detailed description in `completed github
issues <https://github.com/QubesOS/qubes-issues/issues?q=is%3Aissue+sort%3Aupdated-desc+milestone%3A%22Release+3.2%22+label%3Arelease-notes+is%3Aclosed>`__

Known issues
============

-  `Fedora 23 reached EOL in December
   2016 <https://fedoraproject.org/wiki/End_of_life>`__. There is a
   `manual procedure to upgrade your
   VMs </news/2018/01/06/fedora-26-upgrade/>`__.

-  Windows Tools: ``qvm-block`` does not work

-  Some icons in the Qubes Manager application might not be drawn
   correctly when using the Xfce4 environment in Dom0. If this bothers
   you, please use the KDE environment instead.

-  For other known issues take a look at `our
   tickets <https://github.com/QubesOS/qubes-issues/issues?q=is%3Aopen+is%3Aissue+milestone%3A%22Release+3.2%22+label%3Abug>`__

It is advised to install updates just after system installation to apply
bug fixes for (some of) the above problems.

Downloads
=========

See `Qubes Downloads </downloads/>`__.

Installation instructions
=========================

See `Installation Guide </doc/installation-guide/>`__. After
installation, `manually upgrade to Fedora
26 </news/2018/01/06/fedora-26-upgrade/>`__.

Upgrading
=========

From R3.1
---------

The easiest and safest way to upgrade to Qubes R3.2 is to install it
from scratch and use `qubes backup and restore
tools </doc/backup-restore/>`__ for migrating of all of the user VMs.

Users of Qubes R3.1 can also upgrade using `this
procedure </doc/upgrade-to-r3.2/>`__.

From R3.0 or earlier
--------------------

When upgrading from earlier versions the easiest and safest way is to
install it from scratch and use `qubes backup and restore
tools </doc/backup-restore/>`__ for migrating of all of the user VMs.

Alternatively you can `upgrade to R3.1
using </doc/releases/3.1/release-notes/#upgrading>`__ first, then follow
the instructions above. This will be time consuming process.
