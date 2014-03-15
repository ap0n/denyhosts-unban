===============
denyhosts-unban
===============

Tool for unbanning people from DenyHosts.

Downloads
=========

- `.tar.gz <https://github.com/kura//tarball/master>`_
- `.zip <https://github.com/kura/denyhosts-unban/zipball/master>`_

Installation
============

apt.kura.io
-----------

Follow instructions on enabling `apt.kura.io <https://kura.io/apt.kura.io/>`__
repository and then run the following command to install the package.

.. code:: bash

    sudo apt-get install denyhosts-unban

Manual Installation
-------------------

Lazy way
~~~~~~~~

.. code:: bash

    sudo wget https://raw.github.com/kura/denyhosts-unban/master/usr/sbin/denyhosts-unban -O /usr/sbin/denyhosts-unban
    sudo chmod +x /usr/sbin/denyhosts-unban

From archive
~~~~~~~~~~~~

Download the tar.gz or zip archive from GitHub, extract etc.

.. code:: bash

    sudo make install

Usage
-----

    sudo denyhosts-unban [ADDRESS]

Thanks
------

- `Chris Gahan <https://github.com/epitron>`__ for starting the BASH version that spawned this SH version.

License
-------

MIT

