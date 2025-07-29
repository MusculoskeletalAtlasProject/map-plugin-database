===================
MAP Plugin Database
===================

.. _MAP Client: https://github.com/MusculoskeletalAtlasProject/mapclient
.. _MAP Plugin Database: https://github.com/MusculoskeletalAtlasProject/map-plugin-database
.. _MAP Plugin Database New Issue: https://github.com/MusculoskeletalAtlasProject/map-plugin-database/issues/new

Overview
--------

The `MAP Client`_ is a cross-platform, plugin-based framework for managing scientific workflows. Since plugins are central to the MAP Client's functionality, having a streamlined way to discover and share them is essential for usability.

The `MAP Plugin Database`_ is a centralised repository containing metadata about all known, published MAP Client plugins. Its primary purpose is to enable users to search for and install plugins directly from within the MAP Client, eliminating manual installation.

Accessing Plugins
-----------------

Users can access the *Plugin Finder* tool within the MAP Client application via the *Tools* menu. This tool allows users to browse and install available plugins from the database.

Submitting a Plugin
-------------------

MAP Client users are encouraged to contribute their plugins to the database. The recommended submission process is as follows:

1. Navigate to the `MAP Plugin Database New Issue`_ page.
2. Create a new issue and add the :code:`add-plugin` label.
3. In the issue body, include only the GitHub repository path of the plugin in the format::

   {organization}/{repository}

   Example: :code:`mapclient-plugins/pointsourcestep`

Maintaining the Database
------------------------

Editing database entries and triggering automated updates are **restricted** to repository maintainers.

