IOC updater
-----------

``make`` uses notepad configuration files generated by the parent directory's
``Makefile`` in ``../notepad/ioc-*-pcdsdevices.cfg`` to::

1. Check out the respective pvNotepad IOC for the given hutch from SVN.
2. Copies in the updated configuration file.
3. Adds it to the repository and shows the repository's status.