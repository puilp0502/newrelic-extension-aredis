NOTE: THIS LIBRARY IS DEPRECATED
====
Starting from Newrelic Agent v7.6.0.173, `it supports aredis library natively <https://docs.newrelic.com/docs/release-notes/agent-release-notes/python-release-notes/python-agent-70600173/>`_. Upgrade your Newrelic Agent instead of using this library!

newrelic-extension-aredis
===========================================

New Relic Python Agent Extension For `aredis`_ asyncio Redis library

.. _aredis: https://github.com/NoneGG/aredis

Requirements
------------

- Python (3.7+)
- `aredis`_
- `New Relic Python Agent`_

.. _setuptools: https://setuptools.readthedocs.io/en/latest/pkg_resources.html#convenience-api
.. _New Relic Python Agent: https://docs.newrelic.com/docs/agents/python-agent/installation/standard-python-agent-install/

Testing
-------

All testing can be done through `tox <https://github.com/tox-dev/tox>`_.

.. code-block:: sh

   pip install tox
   tox


Usage
-----

Install the extension in the application:

.. code-block:: sh

    pip install newrelic-extension-aredis

No additional steps are required to enable this extension! Newrelic agent will now trace `aredis`_ calls.

License
-------

The contents of this repository are licensed under the terms of the
`Apache 2.0 License <https://www.apache.org/licenses/LICENSE-2.0>`_.
