LwSHELL |version| documentation
===============================

Welcome to the documentation for version |version|.

LwSHELL is lightweight dynamic memory manager optimized for embedded systems.

.. image:: static/images/logo.svg
    :align: center

.. rst-class:: center
.. rst-class:: index_links

	:ref:`download_library` :ref:`getting_started` `Open Github <https://github.com/MaJerle/lwshell>`_ `Donate <https://paypal.me/tilz0R>`_

Features
^^^^^^^^

* Lightweight commands shell for embedded systems
* Platform independent and very easy to port

    * Development of library under Win32 platform
* Written in C language (C99)
* No dynamic allocation, maximum number of commands assigned at compile time
* Highly configurable
* Simple help-text with `cmd -v` option
* User friendly MIT license

Requirements
^^^^^^^^^^^^

* C compiler
* Less than ``5kB`` of non-volatile memory

Contribute
^^^^^^^^^^

Fresh contributions are always welcome. Simple instructions to proceed:

#. Fork Github repository
#. Respect `C style & coding rules <https://github.com/MaJerle/c-code-style>`_ used by the library
#. Create a pull request to ``develop`` branch with new features or bug fixes

Alternatively you may:

#. Report a bug
#. Ask for a feature request

License
^^^^^^^

.. literalinclude:: ../LICENSE

Table of contents
^^^^^^^^^^^^^^^^^

.. toctree::
    :maxdepth: 2

    self
    get-started/index
    user-manual/index
    api-reference/index
    examples/index
