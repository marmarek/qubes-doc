============================
Qubes OS 4.2.0 release notes
============================


**Please note:** *This page is still an unfinished draft in progress. It is being updated as Qubes 4.2 development and testing continues.*

New features and improvements since Qubes 4.1
---------------------------------------------


- Dom0 upgraded to Fedora 37
  (`#6982 <https://github.com/QubesOS/qubes-issues/issues/6982>`__)

- Xen upgraded to version 4.17

- Default Debian template upgraded to Debian 12

- Default Fedora and Debian templates use Xfce instead of GNOME
  (`#7784 <https://github.com/QubesOS/qubes-issues/issues/7784>`__)

- SELinux support in Fedora templates
  (`#4239 <https://github.com/QubesOS/qubes-issues/issues/4239>`__)

- Several GUI applications rewritten, including:

  - Applications Menu (also available as preview in R4.1)
    (`#6665 <https://github.com/QubesOS/qubes-issues/issues/6665>`__),
    (`#5677 <https://github.com/QubesOS/qubes-issues/issues/5677>`__)

  - Qubes Global Settings
    (`#6898 <https://github.com/QubesOS/qubes-issues/issues/6898>`__)

  - Create New Qube

  - Qubes Update
    (`#7443 <https://github.com/QubesOS/qubes-issues/issues/7443>`__)



- Unified ``grub.cfg`` location for both UEFI and legacy boot
  (`#7985 <https://github.com/QubesOS/qubes-issues/issues/7985>`__)

- PipeWire support
  (`#6358 <https://github.com/QubesOS/qubes-issues/issues/6358>`__)

- fwupd integration for firmware updates
  (`#4855 <https://github.com/QubesOS/qubes-issues/issues/4855>`__)

- Optional automatic clipboard clearing
  (`#3415 <https://github.com/QubesOS/qubes-issues/issues/3415>`__)

- Official packages built using Qubes Builder v2
  (`#6486 <https://github.com/QubesOS/qubes-issues/issues/6486>`__)

- Split GPG and Split SSH management in Qubes Global Settings

- Qrexec services use new qrexec policy format by default (but old
  format is still supported)
  (`#8000 <https://github.com/QubesOS/qubes-issues/issues/8000>`__)



For a full list, including more detailed descriptions, please see
`here <https://github.com/QubesOS/qubes-issues/issues?q=is%3Aissue+sort%3Aupdated-desc+milestone%3A%22Release+4.2%22+label%3A%22release+notes%22+is%3Aclosed>`__.

Known issues
------------


- DomU firewalls have completely switched to nftables. Users should add
  their custom rules to the ``custom-input`` and ``custom-forward``
  chains.
  (`#5031 <https://github.com/QubesOS/qubes-issues/issues/5031>`__,
  `#6062 <https://github.com/QubesOS/qubes-issues/issues/6062>`__)



For a full list of open bug reports affecting 4.2, please see
`here <https://github.com/QubesOS/qubes-issues/issues?q=is%3Aissue+label%3Aaffects-4.2+label%3A%22T%3A+bug%22+is%3Aopen>`__.
We strongly recommend :doc:`updating Qubes OS </user/how-to-guides/how-to-update>`
immediately after installation in order to apply any and all available
bug fixes.

Download
--------


All Qubes ISOs and associated :doc:`verification files </project-security/verifying-signatures>` are available on the
:doc:`downloads </user/downloading-installing-upgrading/downloads>` page.

Installation instructions
-------------------------


See the :doc:`installation guide </user/downloading-installing-upgrading/installation-guide>`.

Upgrading
---------


Please see :doc:`how to upgrade to Qubes 4.2 </user/downloading-installing-upgrading/upgrade/4_2>`.
