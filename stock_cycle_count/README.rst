[![Build Status](https://travis-ci.org/zeroincombenze/stock-logistics-warehouse.svg?branch=9.0)](https://travis-ci.org/zeroincombenze/stock-logistics-warehouse)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/stock-logistics-warehouse/badge.svg?branch=9.0)](https://coveralls.io/github/zeroincombenze/stock-logistics-warehouse?branch=9.0)
[![codecov](https://codecov.io/gh/zeroincombenze/stock-logistics-warehouse/branch/9.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/stock-logistics-warehouse/branch/9.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-9.svg)](https://github.com/OCA/stock-logistics-warehouse/tree/9.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/man/LO)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-9.svg)](http://erp9.zeroincombenze.it)




































[![en](http://www.shs-av.com/wp-content/en_US.png)](http://wiki.zeroincombenze.org/it/Odoo/7.0/man)

   :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
   :alt: License: AGPL-3

Stock Cycle Count
=================

This module provides the capability to execute a cycle count strategy in a
warehouse through different rules defined by the user. Cycle count is an
alternative to full wall-to-wall physical inventories in which little
portions (stock locations) of the stock are selected to count on a regular
basis.

The system propose locations in which to perform a inventory adjustment every
day based on a set of rules defined for the warehouse. In addition the system
can propose Zero-Confirmations which are simple and opportunistic counts to
check whether a locations has actually became empty or not.

With this strategy it is possible to:

* Remove the need to perform full physical inventories and to stop the
  production in the warehouse.
* Measure the accuracy of the inventory records and improve it.
* Correct inventory errors earlier and prevent them to become bigger.

Installation
------------






To install this module, you need to:

* Download this module to your addons path.
* Install the module in your database.

Recommendations

It is highly recommended to use this module in conjunction with:

* `stock_inventory_verification_request`: Adds the capability to request Slot
  Verifications.
* `stock_inventory_lockdown`: Lock down locations during inventories.

Configuration
-------------






You can configure the rules to compute the cycle count, acting as follow:

#. Go to *Inventory > Configuration > Cycle Count Rules*.
#. Create as much cycle count rules as you want.
#. Assign the rules to the Warehouse or zones where you want to apply the rules
   in.
#. Go to *Inventory > Configuration > Warehouse Management > Warehouses* and
   set a *Cycle Count Planning Horizon* for each warehouse.

Usage
-----






=====

Once you have some rules configured for your warehouses, you can proceed as
is described below.

#. Go to "Inventory > Configuration > Warehouse Management > Warehouses".
#. Select all the warehouses you want to compute the rules in.
#. Click on "Action" and then in "Compute Cycle Count Rules". (**note**: A
   cron job will do this for every warehouse daily.)
#. Go to "Inventory Control > Cycle Counts".
#. Select a planned Cycle Count and confirm it, this will create a draft
   Inventory Adjustment.
#. In the right top corner of the form view you can access to the generated
   Inventory Adjustment.
#. Proceed with the Inventory Adjustment as usual.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/153/9.0


Known issues / Roadmap
----------------------





Bug Tracker
-----------






Bugs are tracked on `GitHub Issues
<https://github.com/OCA/stock-logistics-warehouse/issues>`_. In case of
trouble, please check there if your issue has already been reported. If you
spotted it first, help us smash it by providing detailed and welcomed feedback.


Images

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.

Credits
-------










### Contributors






* Lois Rilo <lois.rilo@eficent.com>
* Jordi Ballester Alomar <jordi.ballester@eficent.com>


### Funders

### Maintainer










.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.

[//]: # (copyright)

----

**Odoo** is a trademark of [Odoo S.A.](https://www.odoo.com/) (formerly OpenERP, formerly TinyERP)

**OCA**, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

**zeroincombenze®** is a trademark of [SHS-AV s.r.l.](http://www.shs-av.com/)
which distributes and promotes **Odoo** ready-to-use on its own cloud infrastructure.
[Zeroincombenze® distribution](http://wiki.zeroincombenze.org/en/Odoo)
is mainly designed for Italian law and markeplace.
Everytime, every Odoo DB and customized code can be deployed on local server too.

[//]: # (end copyright)

[//]: # (addons)

[//]: # (end addons)

[![chat with us](https://www.shs-av.com/wp-content/chat_with_us.gif)](https://tawk.to/85d4f6e06e68dd4e358797643fe5ee67540e408b)
