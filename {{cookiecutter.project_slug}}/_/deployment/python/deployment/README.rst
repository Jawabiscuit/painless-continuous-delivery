Project Configuration
=====================

This folder contains configuration files for running the project as deployed
software, locally for development and on remote servers.

`application/ <application/>`__
    Web server to Python interface configuration
`webserver/ <webserver/>`__
    Web server configuration for the project

`base/ <base/>`__
    Kustomize base configuration
`overlays/ <overlays/>`__
    Kustomize target environment adaptions

See Also
--------

Application (framework) specific settings are located in the project's
``application`` module (e.g. ``application/settings.py`` for Django).
