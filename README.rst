..
    This file is part of SpatioTemporal Open Research Manager Web Service Specification.
    Copyright (C) 2021 INPE.

    SpatioTemporal Open Research Manager Web Service Specification is free software; you can redistribute it and/or modify it
    under the terms of the MIT License; see LICENSE file for more details.


================================================================
SpatioTemporal Open Research Manager Web Service - Specification
================================================================

.. image:: https://img.shields.io/badge/run-Insomnia-blueviolet
        :target: https://insomnia.rest/run/?label=Storm%20WS%20implementation%20example&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fstorm-platform%2Fstorm-ws-spec%2Fmaster%2Fexample%2Fstorm-ws-insomnia.json
        :alt: Run in Insomnia

.. image:: https://img.shields.io/badge/license-MIT-green
        :target: https://github.com/storm-platform/storm-ws-spec/blob/master/LICENSE
        :alt: Software License

.. image:: https://img.shields.io/badge/lifecycle-maturing-blue.svg
        :target: https://www.tidyverse.org/lifecycle/#maturing
        :alt: Software Life Cycle

.. image:: https://img.shields.io/github/tag/storm-platform/storm-ws-spec.svg
        :target: https://github.com/storm-platform/storm-ws-spec/releases
        :alt: Release

.. image:: https://img.shields.io/discord/689541907621085198?logo=discord&logoColor=ffffff&color=7389D8
        :target: https://discord.com/channels/689541907621085198#
        :alt: Join us at Discord

.. image:: https://cdn.rawgit.com/syl20bnr/spacemacs/442d025779da2f62fc86c2082703697714db6514/assets/spacemacs-badge.svg
        :target: https://github.com/syl20bnr/spacemacs
        :alt: Made with Spacemacs

About
=====

SpatioTemporal Open Research Manager Web Service `OpenAPI 3.0 specification <https://github.com/OAI/OpenAPI-Specification>`_.

Repository Organization
=======================

- `api <./api>`_: Storm WS Specification using `OpenAPI 3.0 <https://github.com/OAI/OpenAPI-Specification>`_;

- `example <./example>`_: `Insomnia <https://insomnia.rest/>`_-based example of using the implementation of the specification provided by the `Storm WS <https://github.com/storm-platform/storm-ws>`_ package.

Building the Documentation
==========================

Requirements
------------

The build system for the REST API documentation relies on the Node.js run-time environment:

  - `Node.js <https://nodejs.org/en/>`_ (Version 8+).

  - `ReDoc <https://github.com/Redocly/redoc>`_: generates HTML reference documentation from an OpenAPI specification file.


Build
-----

If you have Node.js installed, please, execute the following command to install the ReDoc dependency:

.. code-block:: shell

    $ npm install


After that, generate the documentation:

.. code-block:: shell

    $ npm run build


The above command will create a folder named ``dist`` with the bundled file index.html. You may open it in your web browser or may serve it with an HTTP Server.

For Python developers, you can serve the HTML with:

.. code-block:: shell

        python3.8 -m http.server 8080 --directory dist


License
=======

.. admonition::
    Copyright (C) 2021 INPE.

    SpatioTemporal Open Research Manager Web Service is free software; you can redistribute it and/or modify it
    under the terms of the MIT License; see LICENSE file for more details.
