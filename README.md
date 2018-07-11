[![Build Status](https://travis-ci.org/zeroincombenze/stock-logistics-warehouse.svg?branch=8.0)](https://travis-ci.org/zeroincombenze/stock-logistics-warehouse)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/stock-logistics-warehouse/badge.svg?branch=8.0)](https://coveralls.io/github/zeroincombenze/stock-logistics-warehouse?branch=8.0)
[![codecov](https://codecov.io/gh/zeroincombenze/stock-logistics-warehouse/branch/8.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/stock-logistics-warehouse/branch/8.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-8.svg)](https://github.com/OCA/stock-logistics-warehouse/tree/8.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/man/LO)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-8.svg)](http://erp8.zeroincombenze.it)






























































[![en](http://www.shs-av.com/wp-content/en_US.png)](http://wiki.zeroincombenze.org/it/Odoo/7.0/man)

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
addon | version | OCA version | summary
--- | --- | --- | ---
[account_move_line_product](account_move_line_product/) | 8.0.1.0.0 | :repeat: | Account Move Line Product
[account_move_line_stock_info](account_move_line_stock_info/) | 8.0.1.0.0 | :repeat: | Account Move Line Stock Move
[business_product_location](business_product_location/) | 0.1 | 8.0.1.0.0 | Business Product Location
[partner_location_auto_create](partner_location_auto_create/) | 8.0.0.1.0 | :repeat: | Partner Location Auto Create
[stock_account_change_product_valuation](stock_account_change_product_valuation/) | 8.0.1.0.0 | :repeat: | Adjusts valuation of the products and quants when the cost method or type of a product changes
[stock_account_quant_merge](stock_account_quant_merge/) | 8.0.1.0.0 | :repeat: | Stock Account - Quant merge
[stock_available](stock_available/) | 8.0.3.1.0 | :repeat: | Stock available to promise
[stock_available_immediately](stock_available_immediately/) | 8.0.2.0.1 | :repeat: | Ignore planned receptions in quantity available to promise
[stock_available_mrp](stock_available_mrp/) | 8.0.3.1.1 | :repeat: | Consider the production potential is available to promise
[stock_available_sale](stock_available_sale/) | 8.0.3.0.0 | :repeat: | Quotations in quantity available to promise
[stock_available_unreserved](stock_available_unreserved/) | 8.0.1.0.0 | :repeat: | Quantity of stock available for inmediate use
[stock_change_qty_reason](stock_change_qty_reason/) | 8.0.1.0.0 | :repeat: | Stock Quantity Change Reason
[stock_inventory_hierarchical](stock_inventory_hierarchical/) | 8.0.2.0.0 | :repeat: | Group several Inventory adjustments in a master inventory
[stock_inventory_line_price](stock_inventory_line_price/) | 8.0.1.0.0 | :repeat: | Standard price at inventory level
[stock_inventory_lockdown](stock_inventory_lockdown/) | 8.0.1.0.0 | :repeat: | Lock down stock locations during inventories.
[stock_inventory_preparation_filter](stock_inventory_preparation_filter/) | 8.0.1.0.0 | :repeat: | More filters for inventory adjustments
[stock_inventory_revaluation](stock_inventory_revaluation/) | 8.0.1.1.0 | :repeat: | Introduces inventory revaluation as single point to change the valuation of products.
[stock_location_area_data](stock_location_area_data/) | 8.0.0.1.0 | :repeat: | Add surface units of measure
[stock_location_area_management](stock_location_area_management/) | 8.0.0.1.0 | :repeat: | Enter a location's area based on different units of measure
[stock_location_ownership](stock_location_ownership/) | 8.0.0.1.0 | :repeat: | Stock Location Ownership
[stock_lot_quantity](stock_lot_quantity/) | 8.0.1.0.0 | :repeat: | Stock quantity for serial number
[stock_mts_mto_rule](stock_mts_mto_rule/) | 8.0.1.0.0 | :repeat: | Add a MTS+MTO route
[stock_operation_type_location](stock_operation_type_location/) | 8.0.1.1.0 | :repeat: | Allows to filter locations on stock operations
[stock_orderpoint_generator](stock_orderpoint_generator/) | 8.0.1.0.0 | :repeat: | Mass configuration of stock order points
[stock_orderpoint_manual_procurement](stock_orderpoint_manual_procurement/) | 8.0.1.0.0 | :repeat: | Allows to create procurement orders from orderpoints instead of relying only on the scheduler
[stock_orderpoint_uom](stock_orderpoint_uom/) | 8.0.1.0.0 | :repeat: | Allows to create procurement orders in the UoM indicated in the orderpoint
[stock_product_location_sorted_by_qty](stock_product_location_sorted_by_qty/) | 8.0.1.0.0 | :repeat: | In the update wizard of quantities for a product, sort the stock location by quantity
[stock_putaway_product](stock_putaway_product/) | 8.0.1.0.1 | :repeat: | Set a product location and put-away strategy per product
[stock_quant_manual_assign](stock_quant_manual_assign/) | 8.0.1.1.0 | 8.0.1.2.1 | Stock - Manual assignment of quants
[stock_quant_merge](stock_quant_merge/) | 8.0.1.0.0 | :repeat: | Stock - Quant merge
[stock_quant_partner_info](stock_quant_partner_info/) | 8.0.1.1.0 | :repeat: | Stock - Quant partner info
[stock_reserve](stock_reserve/) | 8.0.0.2.0 | :repeat: | Stock reservations on products
[stock_reserve_sale](stock_reserve_sale/) | 8.0.1.0.1 | :repeat: | Stock Reserve Sales
[stock_traceability_operation](stock_traceability_operation/) | 8.0.1.1.0 | :repeat: | Adds operations in traceability and quant history
[stock_valuation_account_manual_adjustment](stock_valuation_account_manual_adjustment/) | 8.0.1.0.0 | :repeat: | Shows in the product inventory stock value and the accounting value and allows to reconcile them
[stock_warehouse_orderpoint_stock_info](stock_warehouse_orderpoint_stock_info/) | 8.0.1.0.0 | :repeat: | Reordering rules stock info


Unported addons
---------------
addon | version | OCA version | summary
--- | --- | --- | ---
[base_product_merge](base_product_merge/) | 1.0 (unported) | :repeat: | Base Products Merge
[configurable_stock_level](configurable_stock_level/) | 0.1 (unported) | :repeat: | name
[stock_inventory_hierarchical_location](stock_inventory_hierarchical_location/) | 7.0.1.1.0 (unported) | :x: | Extra consistency checks
[stock_inventory_location](stock_inventory_location/) | 7.0.1.1.0 (unported) | :x: | Remove from the stock what is not in the Physical Inventory.
[stock_lot_valuation](stock_lot_valuation/) | 0.1 (unported) | :repeat: | Lot Valuation
[stock_move_location](stock_move_location/) | 1.0 (unported) | :repeat: | Move Stock Location
[stock_optional_valuation](stock_optional_valuation/) | 0.1 (unported) | :repeat: | Stock optional valuation
[stock_orderpoint_creator](stock_orderpoint_creator/) | 1.0 (unported) | :repeat: | Configuration of order point in mass
[stock_reord_rule](stock_reord_rule/) | 0.2 (unported) | :repeat: | Improved reordering rules

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
