webinspect
##########

Connects to a web target as many times as required as quickly as required. Has options to show:

* Request headers.
* Information on DNS records associated with the site's domain.
* A lookup on the details of the IP address associated with the site.

Installation
============

To install this software:

.. code-block:: bash

  $ pip install webinspect

Python Version
==============

This software only supports Python 3.5 and above.

Usage
=====

.. code-block:: bash

  $ webinspect www.domain.tld --loop --sleep 0 --limit 5 --headers --dnsinfo --ipinfo

License
=======

Licensed under the MIT license. See LICENSE.txt for details.
