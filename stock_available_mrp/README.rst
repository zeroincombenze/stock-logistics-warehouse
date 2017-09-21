[![Build Status](https://travis-ci.org/zeroincombenze/stock-logistics-warehouse.svg?branch=7.0)](https://travis-ci.org/zeroincombenze/stock-logistics-warehouse)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/stock-logistics-warehouse/badge.svg?branch=7.0)](https://coveralls.io/github/zeroincombenze/stock-logistics-warehouse?branch=7.0)
[![codecov](https://codecov.io/gh/zeroincombenze/stock-logistics-warehouse/branch/7.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/stock-logistics-warehouse/branch/7.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-7.svg)](https://github.com/OCA/stock-logistics-warehouse/tree/7.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-7.svg)](http://wiki.zeroincombenze.org/en/Odoo/7.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-7.svg)](http://wiki.zeroincombenze.org/en/Odoo/7.0/man/LO)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-7.svg)](http://erp7.zeroincombenze.it)


[![en](https://github.com/zeroincombenze/grymb/blob/master/flags/en_US.png)](https://www.facebook.com/groups/openerp.italia/)

Consider the production potential is available to promise
=========================================================

This module takes the potential quantities available for Products in account in
the quantity available to promise, where the "Potential quantity" is the
quantity that can be manufactured with the components immediately at hand.

Known issues

The manufacturing delays are not taken into account : this module assumes that
if you have components in stock goods, you can manufacture finished goods
quickly enough.
To avoid overestimating, **only the first level** of Bill of Materials is
considered.

Roadmap

* include all levels of BoM, using `bom_explode`. @gdgellatly gave an example
  of how to do it here: https://github.com/OCA/stock-logistics-warehouse/pull/5#issuecomment-66902191
    Ideally, we will want to take manufacturing delays into account: we can't
    promiss goods to customers if they want them delivered earlier that we can
    make them
* add an option (probably as a sub-module) to consider all raw materials as
  available if they can be bought from the suppliers in time for the
  manufacturing.

Installation
------------




Configuration
-------------




Usage
-----

-----

-----

-----

Known issues / Roadmap
----------------------




Bug Tracker
-----------




Credits
-------





[![Odoo Italia Associazione]]




### Contributors




* Loïc Bellier (Numérigraphe) <lb@numerigraphe.com>
* Lionel Sausin (Numérigraphe) <ls@numerigraphe.com>

### Funders

### Maintainer








.. image:: http://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: http://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose mission is to support the collaborative development of Odoo features and promote its widespread use.

To contribute to this module, please visit http://odoo-community.org.

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
