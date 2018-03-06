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

Stock Inventory Verification Request
====================================

Adds the capability to request a Slot Verification when a inventory is
'Pending to Approve'. When asked from Inventory Adjustment, which have
discrepancies over the threshold for the location, a Slot Verification
Request will be created for each line that exceed the maximum discrepancy
allowed.

A SVR must be created when warehouse operation (e.g. an inventory adjustment,
a cycle count...) uncovers a count discrepancy within a slot (a small stock
location), and the discrepancy is greater than the pre-defined acceptable
variance threshold. A stock manager should accept the SVR and assign it to
someone to perform it.

The aim of SVR is to find and fix errors before they are transferred to
another location, so they will not be found again in similar stock operations.
In other words, a SVR helps to correct an already existing error in our stock
records the earliest possible. Many times, a SVR will likely lead to manual
actions (before being marked as solved) in order to fix the problems uncovered.

Installation
------------





Configuration
-------------





Usage
-----






=====

In order to use this module act as follow:

* From a Inventory Adjustment in state 'Pending to Approve' click in the
  button 'Request Verification'. This will create all the Slot Verification
  Request needed.
* Go to 'Inventory / Inventory Control / Slot Verification Request'
* Go to a Slot Verification Request 'Waiting Actions' and confirm it.
* You can now check the involved lines and moves to help you.
* Once you have found the problem and you have fixed it 'Mark as Solved' the
  Verification.


.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/153/9.0


Known issues / Roadmap
----------------------





Bug Tracker
-----------






Bugs are tracked on `GitHub Issues
<https://github.com/OCA/stock-logistics-warehouse/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smash it by providing detailed and welcomed feedback.


Images

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.

Credits
-------










### Contributors






* Lois Rilo Antelo <lois.rilo@eficent.com>


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
