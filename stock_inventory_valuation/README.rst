===========================
Stock Inventory - Valuation
===========================

.. !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-GRAP%2Fgrap--odoo--incubator-lightgray.png?logo=github
    :target: https://github.com/GRAP/grap-odoo-incubator/tree/8.0/stock_inventory_valuation
    :alt: GRAP/grap-odoo-incubator

|badge1| |badge2| |badge3| 

This module add simple valuation on stock inventories, based on standard_price
of each product.

A new computed field ``valuation`` is added on ``stock.inventory`` and
``stock.iventory.line`` models so as to be able to calculate the total
valuation of one inventory.

This module can be usefull when you don't use valuation by quants.

.. figure:: https://raw.githubusercontent.com/GRAP/grap-odoo-incubator/8.0/stock_inventory_valuation/static/description/stock_inventory_form.png

**Table of contents**

.. contents::
   :local:

Known issues / Roadmap
======================

the field ``valuation`` on ``stock.inventory.line`` is not designed
correctly for the time being : It is a computed field, and should be a
classical field with onchange. It is due to the dual API in odoo 8.0.
When porting this module in version 10.0, should be refactored in normal
field.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/GRAP/grap-odoo-incubator/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/GRAP/grap-odoo-incubator/issues/new?body=module:%20stock_inventory_valuation%0Aversion:%208.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* GRAP

Contributors
~~~~~~~~~~~~

* Sylvain LE GAL <https://twitter.com/legalsylvain>

Maintainers
~~~~~~~~~~~



This module is part of the `GRAP/grap-odoo-incubator <https://github.com/GRAP/grap-odoo-incubator/tree/8.0/stock_inventory_valuation>`_ project on GitHub.


You are welcome to contribute.
