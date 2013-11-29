===================
zconfig_watchedfile
===================

Provides a ZConfig statement to register a logging handler that uses a
`WatchedFileHandler`_::

    %import zconfig_watchedfile
    <accesslog>
      <watchedfile>
        path /path/to/logfile.log
      </watchedfile>
    </accesslog>


This package is compatible with Python version 2.7.
