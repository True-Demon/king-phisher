:mod:`letsencrypt`
==================

.. module:: king_phisher.server.letsencrypt
   :synopsis:

This module provides the functionality related to managing SSL certificates with
Let's Encrypt.

Data
----

.. autodata:: LETS_ENCRYPT_DEFAULT_DATA_PATH
   :annotation:

Functions
---------

.. autofunction:: certbot_issue

.. autofunction:: get_certbot_bin_path

.. autofunction:: get_sni_hostname_config

.. autofunction:: get_sni_hostnames

Classes
-------

.. autoclass:: SNIHostnameConfiguration
