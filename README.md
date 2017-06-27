[![Build Status](https://travis-ci.org/zeroincombenze/stock-logistics-warehouse.svg?branch=9.0)](https://travis-ci.org/zeroincombenze/stock-logistics-warehouse)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/stock-logistics-warehouse/badge.svg?branch=9.0)](https://coveralls.io/github/zeroincombenze/stock-logistics-warehouse?branch=9.0)
[![codecov](https://codecov.io/gh/zeroincombenze/stock-logistics-warehouse/branch/9.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/stock-logistics-warehouse/branch/9.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-9.svg)](https://github.com/OCA/stock-logistics-warehouse/tree/9.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/dev/9.0)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/stock-)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-9.svg)](http://erp9.zeroincombenze.it)

Odoo Stock Logistic Warehouse
=============================


This project aim to deal with modules related to the management of warehouses. You'll find modules that:

 - Ease inventory by adding various possibilities
 - Move all product from one location to another
 - Manage the product catalog (merge them,..)

Please don't hesitate to suggest one of your module to this project. Also, you may want to have a look on those other projects here:

 - https://github.com/OCA/stock-logistics-tracking
 - https://github.com/OCA/stock-logistics-barcode
 - https://github.com/OCA/stock-logistics-workflow

[//]: # (addons)

Available addons
----------------
addon | version | summary
--- | --- | ---
[account_move_line_product](account_move_line_product/) | 9.0.1.0.0 | Displays the product in the journal entries and items
[account_move_line_stock_info](account_move_line_stock_info/) | 9.0.1.0.0 | Account Move Line Stock Move
[procurement_auto_create_group](procurement_auto_create_group/) | 9.0.1.0.0 | Procurement Auto Create Group
[stock_account_quant_merge](stock_account_quant_merge/) | 9.0.1.0.0 | Stock Account - Quant merge
[stock_available](stock_available/) | 9.0.1.1.0 | Stock available to promise
[stock_available_immediately](stock_available_immediately/) | 9.0.1.1.0 | Ignore planned receptions in quantity available to promise
[stock_available_mrp](stock_available_mrp/) | 9.0.1.0.0 | Consider the production potential is available to promise
[stock_available_unreserved](stock_available_unreserved/) | 9.0.1.0.0 | Quantity of stock available for inmediate use
[stock_cycle_count](stock_cycle_count/) | 9.0.1.1.0 | Adds the capability to schedule cycle counts in a warehouse through different rules defined by the user
[stock_inventory_discrepancy](stock_inventory_discrepancy/) | 9.0.1.0.0 | Adds the capability to show the discrepancy of every line in an inventory and to block the inventory validation when the discrepancy is over a user defined threshold.
[stock_inventory_exclude_sublocation](stock_inventory_exclude_sublocation/) | 9.0.1.0.0 | Allow to perform inventories of a location without including its child locations.
[stock_inventory_lockdown](stock_inventory_lockdown/) | 9.0.1.0.0 | Lock down stock locations during inventories.
[stock_inventory_revaluation](stock_inventory_revaluation/) | 9.0.1.0.0 | Introduces inventory revaluation as single point to change the valuation of products.
[stock_inventory_verification_request](stock_inventory_verification_request/) | 9.0.1.0.0 | Adds the capability to request a Slot Verification when a inventory is Pending to Approve
[stock_location_area_data](stock_location_area_data/) | 9.0.1.0.0 | Add surface units of measure
[stock_move_partner_info](stock_move_partner_info/) | 9.0.1.0.0 | Stock Move Partner Info
[stock_mts_mto_rule](stock_mts_mto_rule/) | 9.0.1.0.0 | Add a MTS+MTO route
[stock_orderpoint_generator](stock_orderpoint_generator/) | 9.0.1.1.0 | Mass configuration of stock order points
[stock_orderpoint_manual_procurement](stock_orderpoint_manual_procurement/) | 9.0.1.0.0 | Allows to create procurement orders from orderpoints instead of relying only on the scheduler
[stock_orderpoint_uom](stock_orderpoint_uom/) | 9.0.1.0.0 | Allows to create procurement orders in the UoM indicated in the orderpoint
[stock_partner_lot](stock_partner_lot/) | 9.0.1.0.0 | Show lots on the partners that own them
[stock_putaway_product](stock_putaway_product/) | 9.0.1.0.1 | Set a product location and put-away strategy per product
[stock_quant_manual_assign](stock_quant_manual_assign/) | 9.0.1.0.0 | Stock - Manual Quant Assignment
[stock_quant_merge](stock_quant_merge/) | 9.0.1.0.0 | Stock - Quant merge
[stock_quant_reserved_qty_uom](stock_quant_reserved_qty_uom/) | 9.0.1.0.0 | Stock Quant Reserved Qty UoM
[stock_removal_location_by_priority](stock_removal_location_by_priority/) | 9.0.1.0.0 | Establish a removal priority on stock locations.
[stock_reserve](stock_reserve/) | 9.0.1.0.0 | Stock reservations on products
[stock_valuation_account_manual_adjustment](stock_valuation_account_manual_adjustment/) | 9.0.1.0.0 | Shows in the product inventory stock value and the accounting value and allows to reconcile them
[stock_warehouse_orderpoint_stock_info](stock_warehouse_orderpoint_stock_info/) | 9.0.1.0.0 | Reordering rules stock info
[stock_warehouse_orderpoint_stock_info_unreserved](stock_warehouse_orderpoint_stock_info_unreserved/) | 9.0.1.0.0 | Reordering rules stock info unreserved


Unported addons
---------------
addon | version | summary
--- | --- | ---
[base_product_merge](base_product_merge/) | 1.0 (unported) | Base Products Merge
[configurable_stock_level](configurable_stock_level/) | 0.1 (unported) | name
[partner_location_auto_create](partner_location_auto_create/) | 0.1 (unported) | Partner Location Auto Create
[stock_available_sale](stock_available_sale/) | 2.0 (unported) | Quotations in quantity available to promise
[stock_inventory_preparation_filter](stock_inventory_preparation_filter/) | 8.0.1.0.0 (unported) | More filters for inventory adjustments
[stock_location_area_management](stock_location_area_management/) | 8.0.0.1.0 (unported) | Enter a location's area based on different units of measure
[stock_location_ownership](stock_location_ownership/) | 8.0.0.1.0 (unported) | Stock Location Ownership
[stock_lot_valuation](stock_lot_valuation/) | 0.1 (unported) | Lot Valuation
[stock_move_location](stock_move_location/) | 1.0 (unported) | Move Stock Location
[stock_optional_valuation](stock_optional_valuation/) | 0.1 (unported) | Stock optional valuation
[stock_reord_rule](stock_reord_rule/) | 0.2 (unported) | Improved reordering rules
[stock_reserve_sale](stock_reserve_sale/) | 8.0.1.0.0 (unported) | Stock Reserve Sales

[//]: # (end addons)

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

[![chat with us](https://www.shs-av.com/wp-content/chat_with_us.gif)](https://tawk.to/85d4f6e06e68dd4e358797643fe5ee67540e408b)
