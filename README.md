MATSim Config v1 to v2 converter
================================

A very simple utility to convert the obsolete MATSim v1 config file format to
now-standard v2 format.

It will work with configs in v1 formats that are valid for release 0.10.x,
and will convert them to v2 configs that are valid for the same release.

This is a separate project in order to allow removing the v1 format from MATSim altogether.

Usage
-----

The project for the moment only contains one executable class `org.matsim.run.ConvertConfig`,
that takes two arguments: the path to the config to convert, and the path to the newly created
converted config.

TODO
----

* [ ] Simple GUI for those users that are not confident with the command line
* [ ] Tests
* [ ] More detailed instructions
