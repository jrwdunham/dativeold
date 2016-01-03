================================================================================
  Dative-OLD
================================================================================

This project combines Dative and the OLD.

Dative (https://github.com/jrwdunham/dative) is a Backbone/CoffeeScript single
page application that runs in the browser.

The Online Linguistic Database, or OLD (https://github.com/jrwdunham/old), is a
Pylons/Python RESTful web service that sends and receives JSON.

Dative-OLD brings Dative and the OLD together in a nice bundle so that you can
have a fully operational linguistic fieldwork database and analysis tool in one
project.


Desiderata
================================================================================

1. This project should make it maximally easy for a non-technical user to get a
   fully functional linguistic fieldwork application up and running, either on
   their own computer or on a server.

2. Script that builds and serves both Dative and an OLD.

3. Pyinstaller script that bundles this all into platform-specific executables.

4. Add BuildOLD as a submodule: for installing the OLD's dependencies and
   building new OLDs.

