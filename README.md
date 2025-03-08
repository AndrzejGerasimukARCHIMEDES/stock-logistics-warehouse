
[![Runboat](https://img.shields.io/badge/runboat-Try%20me-875A7B.png)](https://runboat.odoo-community.org/builds?repo=OCA/stock-logistics-warehouse&target_branch=18.0)
[![Pre-commit Status](https://github.com/OCA/stock-logistics-warehouse/actions/workflows/pre-commit.yml/badge.svg?branch=18.0)](https://github.com/OCA/stock-logistics-warehouse/actions/workflows/pre-commit.yml?query=branch%3A18.0)
[![Build Status](https://github.com/OCA/stock-logistics-warehouse/actions/workflows/test.yml/badge.svg?branch=18.0)](https://github.com/OCA/stock-logistics-warehouse/actions/workflows/test.yml?query=branch%3A18.0)
[![codecov](https://codecov.io/gh/OCA/stock-logistics-warehouse/branch/18.0/graph/badge.svg)](https://codecov.io/gh/OCA/stock-logistics-warehouse)
[![Translation Status](https://translation.odoo-community.org/widgets/stock-logistics-warehouse-18-0/-/svg-badge.svg)](https://translation.odoo-community.org/engage/stock-logistics-warehouse-18-0/?utm_source=widget)

<!-- /!\ do not modify above this line -->

# Stock Warehouse

Extend the stock related models (warehouse, location, picking, move...) but without impact flows and processes. It's mainly adding fields or buttons.

Are you looking for modules related to logistics? Or would like to contribute
to? There are many repositories with specific purposes. Have a look at this
[README](https://github.com/OCA/wms/blob/18.0/README.md).

<!-- /!\ do not modify below this line -->

<!-- prettier-ignore-start -->

[//]: # (addons)

Available addons
----------------
addon | version | maintainers | summary
--- | --- | --- | ---
[account_move_line_stock_info](account_move_line_stock_info/) | 18.0.1.0.0 |  | Account Move Line Stock Info
[stock_archive_constraint](stock_archive_constraint/) | 18.0.1.0.0 | [![victoralmau](https://github.com/victoralmau.png?size=30px)](https://github.com/victoralmau) | Stock archive constraint
[stock_demand_estimate](stock_demand_estimate/) | 18.0.1.0.0 |  | Allows to create demand estimates.
[stock_inventory](stock_inventory/) | 18.0.1.0.0 |  | Allows to do an easier follow up of the Inventory Adjustments
[stock_location_bin_name](stock_location_bin_name/) | 18.0.1.0.0 |  | Compute bin stock location name automatically
[stock_location_empty](stock_location_empty/) | 18.0.1.0.0 |  | Adds a filter for empty stock location
[stock_location_is_sublocation](stock_location_is_sublocation/) | 18.0.1.0.0 |  | Add method to check stock location is sublocation
[stock_location_position](stock_location_position/) | 18.0.1.0.0 |  | Add coordinate attributes on stock location.
[stock_location_zone](stock_location_zone/) | 18.0.1.0.0 |  | Classify locations with zones.
[stock_move_common_dest](stock_move_common_dest/) | 18.0.1.0.0 |  | Adds field for common destination moves
[stock_packaging_calculator](stock_packaging_calculator/) | 18.0.1.0.0 |  | Compute product quantity to pick by packaging
[stock_picking_volume](stock_picking_volume/) | 18.0.1.0.0 | [![lmignon](https://github.com/lmignon.png?size=30px)](https://github.com/lmignon) | Compute volume information on stock moves and pickings
[stock_putaway_product_template](stock_putaway_product_template/) | 18.0.1.0.0 | [![kevinkhao](https://github.com/kevinkhao.png?size=30px)](https://github.com/kevinkhao) [![sebastienbeau](https://github.com/sebastienbeau.png?size=30px)](https://github.com/sebastienbeau) | Add product template in putaway strategies from the product view
[stock_quant_cost_info](stock_quant_cost_info/) | 18.0.1.0.0 |  | Shows the cost of the quants
[stock_warehouse_calendar](stock_warehouse_calendar/) | 18.0.1.0.1 | [![JordiBForgeFlow](https://github.com/JordiBForgeFlow.png?size=30px)](https://github.com/JordiBForgeFlow) | Adds a calendar to the Warehouse

[//]: # (end addons)

<!-- prettier-ignore-end -->

## Licenses

This repository is licensed under [AGPL-3.0](LICENSE).

However, each module can have a totally different license, as long as they adhere to Odoo Community Association (OCA)
policy. Consult each module's `__manifest__.py` file, which contains a `license` key
that explains its license.

----
OCA, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit
organization whose mission is to support the collaborative development of Odoo features
and promote its widespread use.
