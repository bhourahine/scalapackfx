**********
Change Log
**********

Notable project changes in various releases.


Unreleased
==========


1.0.1
=====

Fixed
-----

* ScaLAPACK interfaces use only assumed-size arrays (no fixed size ones) to
  avoid linking problems with NAG compiled applications


1.0
===

Added
-----

* Various improvements in the CMake-build system.

* CMake and PKG-Config export files when ScalapackFx is installed.


Changed
-------

* The Fypp-preprocessor is not shipped with ScalapackFx but is an external
  requirement.

* Name convention for processes (master -> lead, slave -> follow).
