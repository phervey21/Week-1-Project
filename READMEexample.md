# README Example

============
Introduction
============

Twitter has published new version `Twitter API V2 <https://twitter.com/TwitterDev/status/1293593516040269825>`_ for developer at Aug 13, 2020.

This library provides a service to easily use this new version Twitter API.

=============
Documentation
=============

You can get all api description and update at `Twitter API v2: Early Access <https://developer.twitter.com/en/docs/twitter-api/early-access>`_.

Library docs site on `here <https://sns-sdks.github.io/python-twitter/>`_


==========
Installing
==========

You can install this library easily by `pypi`:

.. code-block:: shell

    $ pip install python-twitter-v2

Code is hosted at `https://github.com/sns-sdks/python-twitter <https://github.com/sns-sdks/python-twitter>`_.

Checkout latest development version with:

.. code-block:: shell

    $ git clone https://github.com/sns-sdks/python-twitter.git
    $ cd python-twitter

Install dependencies with:

.. code-block:: shell

    $ make env


Run tests with:

.. code-block:: shell

    $ make test

Run tests with coverage:

.. code-block:: shell

    $ make cov-term
    $ make cov-html

=====
Using
=====

The API is exposed via the ``pytwitter.Api`` class.

Now cover features:

- Tweets
    - Tweet lookup
    - Manage Tweets
    - Quote Tweets
    - Timelines
    - Search Tweets
    - Tweet counts
    - Filtered stream
    - Volume streams
    - Retweets
    - Likes
    - Bookmarks
    - Hide replies

- Users
    - User lookup
    - Follows
    - Blocks
    - Mutes

- Spaces
    - Spaces lookup
    - Search Spaces

- Compliance
    - Batch compliance

- Lists
    - List lookup
    - Manage lists
    - List Tweets lookup
    - List members
    - List follows
    - Pinned Lists
