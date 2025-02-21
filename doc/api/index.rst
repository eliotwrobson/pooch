.. _api:

List of functions and classes (API)
===================================

.. note::

    **All functions and classes should be accessed from the** :mod:`pooch`
    **top-level namespace.**

    Modules inside of the :mod:`pooch` package are meant mostly for internal
    organization. Please **avoid importing** directly from submodules since
    functions/classes may be moved around.

.. automodule:: pooch

Core
----

.. autosummary::
    :toctree: generated/

    pooch.create
    pooch.Pooch
    pooch.retrieve

Utilities
---------

.. autosummary::
    :toctree: generated/

    pooch.os_cache
    pooch.make_registry
    pooch.file_hash
    pooch.check_version
    pooch.get_logger

Downloaders
-----------

.. autosummary::
    :toctree: generated/

    pooch.HTTPDownloader
    pooch.FTPDownloader
    pooch.SFTPDownloader
    pooch.DOIDownloader

Processors
----------

.. autosummary::
    :toctree: generated/

    pooch.Unzip
    pooch.Untar
    pooch.Decompress

Miscellaneous
-------------

.. autosummary::
    :toctree: generated/

    pooch.test

Typing
------

Custom classes for type annotations.
This module provides additional `PEP 484 <https://peps.python.org/pep-0484/>`_
type aliases used in ``pooch``'s codebase.

.. autosummary::
   :toctree: generated/

    pooch.typing.Action
    pooch.typing.Downloader
    pooch.typing.PathType
    pooch.typing.PathInputType
    pooch.typing.ParsedURL
    pooch.typing.Processor
